# Parts list

**Note**: I am German (I know, tragic), so I will be using german sites and sellers. Sites like DigiKey, JLCPCB and 
Amazon of course ship (mostly?) world wide, while Motedis at least ships to the EU, UK and US from what I can tell.

If you are following this list, I would still recommend you to check with the [parts-list.txt](https://github.com/ReflexCreations/hardware-design/blob/master/part-lists.txt) 
from the hardware design repo and the `unpopulated.csv` files from both the [io-board](https://github.com/ReflexCreations/io-board) and [panel-board](https://github.com/ReflexCreations/panel-board) gerber zips, 
just to make sure you're getting everything.

## my list:
- DigiKey: https://www.digikey.de/short/zttw7nnq TH parts for 1 pad + ethernet and barrel jack cables. 
- Galoce Load Cells: https://www.galoce.com/products/micro-load-cell/GML670_Full_Bridge_Micro_Load_Cell_.html Sensors (16 pieces per pad), make sure it’s the full bridge ones (you need to contact them if you want to buy some)
- PCBs: bought them from JLCPCB, follow the instructions in the repos for those (need at least 1 populated IO board and 4 populated panel boards per pad)
- Aluminium panels: https://www.aluminium-online-shop.de/produkt-kategorie/aluminium-platten-aluminium-bleche/bleche-platten/ 6mm thick, 280x280mm, AIMg3 5 pieces per pad. You probably want to add anodizing ("Eloxierung" in german) to it (can only be done via adding it to the order note and paying the fee once they send it to you)
- PolyCarb panels: https://kunststoffplattenprofis.de/produkt/polycarbonat-farblos-innen/ 12mm thick 28x28cm, 4 pieces per pad. Don’t bother with the deburring service for that price, you might as well just do it yourself.
	- "but the original guide tells you to get acrylic pads!" yeah but acrylic pads will pretty quickly break on you as well, so you might as well not bother with them and go straight to PC
- Motedis parts:
	- https://www.motedis.com/shop/create_offers_kit.php?oID=30739 base pad set
	- https://www.motedis.co.uk/shop/create_offers_kit.php?oID=30830 bar assembly (incomplete)
	- https://www.motedis.com/shop/create_offers_kit.php?oID=30741 doubles connector if you’re building 2 pads
	- not all parts seem to be available anymore and one part was out of stock for me:
		- https://www.motedis.com/en/Connector-plate-double-156x78x5-lasercut if the regular 5mm aluminium version is sold out, the 3mm steel one works just fine too
		- ~~https://www.motedis.com/en/Connection-Plate-40x80-black I bought this instead of the `Connector plate 74x34x5, Laser cut, series 40` (which is out of production as far as I can tell) for the bar~~
		  actually this plate sucks, just use a 40x40 bracket like this https://www.motedis.com/en/Bracket-40-I-Type-slot-8
		- https://www.item24.com/de-de/profil-8-d40-3no-natur-49345?length=849 The bars are out of production at motedis apparently, so I switched to this seller. Sadly they don’t sell to private buyers, so I’m getting my workplace to buy it for me.
		- alternatively, you can get an extra 40-series extrusion and print these: https://github.com/joshhead/reflex-extrusion-bar
- Amazon parts:
	- https://amzn.eu/d/3SlqP1G PSU
	- https://amzn.eu/d/bTP2xQI JST plugs (ignore these if you could order them from DigiKey)
	- https://amzn.eu/d/1zSG3ks Programmer for the STM32s
	- https://amzn.eu/d/2jiJ9OI Velcro discs
- What is missing here:
	- 3D printed parts: I have a 3D printer on the way, so I will just print them myself. Alternatively you can ask a friend with a 3D printer or order them from e.g. JLCPCB
	- USB B to A cable (I should still have enough of those lying around)
	- cable ties (same with these)

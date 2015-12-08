###Kossel Minimax

Based on Johan's Kossel Mini @ github.com/jcrocholl/kossel/

Completely remodeled in Solidworks for Misumi 2020 and 2040 extrusions and a much bigger print area (300mm diameter print plate, ~470mm cylindrical print height, ~500mm tower print height, 1000mm overall height)

**Basic BOM:**

For belts, thid design uses 2020mm GT2 belts for each axis, 6060mm total, get a bit more to be safe.

* Aluminum Extrusion 2020 (length 420mm qty3 and length 1000mm qty3) (http://us.misumi-ec.com/vona2/detail/110302368740/ Choose Carefully!)
* Aluminum Extrusion 2040 (length 420mm qty3)  (http://us.misumi-ec.com/vona2/detail/110302368830/ - Choose Carefully!)
* Bag of extrusion nuts (qty1) HNKK5-3 (http://us.misumi-ec.com/vona2/detail/110302246940/)
* 300mm diameter round glass plate (such as http://www.amazon.com/Clear-Borosilicate-Glass-Printers-Round/dp/B00GRHFIC0)


Kossel Mini fasteners BOM, bearings BOM, 3x Nema  17 motors for motion, bowden extruder of your choice with enough bowden tube


**The design has 3 different types of vertical movement types available:**

1. *Steel Linear bearing:* MGN 12H rails and bearing cartridges, 600mm (like http://www.ebay.com/itm/161304571537)
  - Pros: superior rigidity, longevity, and backlash tolerances. Not a lot of material to print. 
  - Cons: expensive (over 150$USD for three 800mm long rails with bearings)
 
2. *Printed linear bearing:* Uses 5/16th delrin balls found on amazon (http://www.amazon.com/gp/product/B000FMWFXI/ 2 packs). 
  - Pros: Bearings are cheap, about $10 for plenty of balls, decent longevity, nearly fully 3d printed solution
  - Cons: Can be noisy, and requires a good printer to make bearings with smooth channels to facilitate smooth travel. 
	
3. *Printed linear bushings:* PLA bushings that slide over the extrusions.
  - Pros: Fully 3d-printed solution, lightweight solution, can be assembled and tightened with zip-ties
  - Cons: May wear over time requiring replacement or tightening to eliminate backlash and wobble.



Kossel mini assembly instructions apply, with a slight difference on the upper vertex:

  There is an embedded nut trap on the inside of the bearing area. On top of that is a single washer followed by the two flanged bearings, and then another washer.
  
  The tensioner could use a larger washer than the Kossel mini's instruction, or perhaps some printed solution. I use an additional set of m4 washers under the m3 washers.
		

*TODO:*

Design effector plate, extruder fan shroud, auto level probe mount.
  
  You can use regular Kossel mini parts for these if you want to print it now.	

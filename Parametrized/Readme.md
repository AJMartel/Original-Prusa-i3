# Modified Prusa i3 MK3
https://github.com/puddnig/Prusa-i3-Parametrized
https://www.thingiverse.com/thing:2793649

Original Prusa i3 MK3 OpenScad files are hard to modify, because dimensions are hardcoded and often used redundantly. I am going to rewrite all parts parametrized with parameters stored in a single file.

List of rewritten parts:

* x-end-idler
* x-end-motor
* y-belt-holder
* z-axis-bottom
* z-axis-top

Added parts:

* x-tensioner

**Links**

 * Prusa Research website : http://prusa3d.com
 
 Originally I just wanted to change the position of the x axis idler, but the original Prusa OpenSCAD code makes it hard to change things because most dimensions are used directly. That's why I've decided to rewrite all parts, but driven by parameters stored in a single file.

OpenSCAD code here

Currently rewritten the following parts:

z-rod-bottom*
The Stepper is centered as in R2 of the original part. I also cut the front to make it easier to access the bolts behind the stepper. The chamfer on the outside ends flush with the frame.

z-rod-top*
The original part is a bit flexible left to right because of the cutout in the top and the narrow connections. Also the chamfer on the corner should end flush with the frame.

x-end-idler*
The idler is mounted 2 mm further upwards to make the belt parallel with the x axis.
The cutout the idler is mounted in looks less "patchy". There are integrated bearing spacers in the bearing housing.

x-end-motor and x-tensioner*
I've added a tensioning mechanism with a bit more range and control.

y-motor-holder*
The stepper mount is adjustable, so you can move the stepper directly against the frame.

y-belt-idler*
Changed height of idler to make belt parallel with the y axis. Also there are added bridges to prevent the side mounted to the plate from getting convex when tightening the idler.

y-belt-holder*
Changed height of the belt slots to make the belt parallel with the y axis.

y-rod-holder*
No zip ties anymore. The part also employs a new technology called rounded corners.

einsy-base*
No needed changes, but it is fully parametric now and the code is a lot shorter.

einsy-doors*
The same as with einsy-base.

I haven't gotten around to rewrite the x-carriage but I've fixed the original stl's for a parallel x belt.

There might be some errors in the parts as they are mostly written from scratch. If you find some please let me know.
Parts marked with * have not been tested yet, but might work.
 

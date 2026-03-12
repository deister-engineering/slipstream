# Assembly Notes

#### This document is meant to be for use by beta testers and not a long-term solution. It contains information and "gotchas" that we've run into during assembly. Eventually, this document will inform as we create an assembly manual.

### Recommended Order
There isn't really a _right_ order, but there are definitely wrong orders to assemble the printer in.
We'd recommend building the frame (SQUARE IT BEFORE CONTINUING FURTHER), sideskirts, Z drive assembly, bed assembly, then the electronics.

Gantry should be assembled and tensioned (120hz at 150mm) outside of the printer, then can be moved into the printer. Ensure all 4 corners of the Z axis are the same tension (recommended this is tensioned to ~140hz at 150mm) around the same height (this can be done with a ruler). Moving the gantry into the printer can be finnicky and is best done with an extra pair of hands.

It's recommended to add the EVA foam tape, panels, and locking clips after the gantry is in. 

### Z Drive Assembly
The rails are set to index against the bottom of the Z axis belt tensioners. It's recommended to install the tensioners, then the Z rail stop blocks, then the rails, then the lower Z drive assembly. For the lower Z drive assembly, PAY CLOSE ATTENTION to which parts are mirrored and which parts are not. They are _not_ interchangeable as the motors are not mounted a direct 45 degrees off of the frame. Failure to follow this will result in the drive pulley being out of alignment with the top pulley, causing the belt to rub against the Z carriage.

### XY Pulley Stacks
The bearing/washer/pulley stack order should be as follows, starting from the side closest to the motor and ending on the bottom of the stack.

Top-driven:
- 625zz bearing
- 0.5mm washer
- Drive pulley (grub screws below)
- 0.5mm washer
- 1mm washer
- Idler pulley
- 1mm washer
- 625zz bearing

Bottom-driven:
- 625zz bearing
- 0.5mm washer
- Idler pulley
- 0.5mm washer
- 1mm washer
- Drive pulley (grub screws above)
- 1mm washer
- 625zz bearing

### XY Tensioners
The belts are routed in a similar manner to how Annex Engineering tensions the XY belts on the K3. Ensure the belt loop that the M3 screw goes through has at least 10 teeth on each side meshing with itself (so, fold over ~1in of belt). 

On the side that interfaces with the moving tensioner block, ensure that ALL teeth mesh. The more contact, the better, so that the belt doesn't slip out of the tensioner block.
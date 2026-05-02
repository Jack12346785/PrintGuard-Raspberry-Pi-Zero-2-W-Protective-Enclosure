Installation Guide — Raspberry Pi Zero 2 W Enclosure
Note: The Raspberry Pi Zero 2 W does not have a built-in OLED. If you are not adding a separate OLED module, skip the OLED steps and use the lid as a plain vented/display-window lid.

1. Required Parts
Printed parts
1× printed base
1× printed snap-fit lid
Electronics
1× Raspberry Pi Zero 2 W
1× microSD card
Optional: separate OLED display module, if you decide to use the display window
Hardware
4× M2.5 heat-set inserts
4× M2.5 screws, about 4–6 mm long
Optional: thin plastic or nylon washers
Tools
Soldering iron or heat-set insert tool
Small Phillips screwdriver
Deburring tool, hobby knife, or small file
2. Recommended Print Settings
Material:

PETG recommended
PLA also works for indoor/light-duty use
Suggested settings:

Layer height: 0.16–0.24 mm
Walls/perimeters: 3
Top/bottom layers: 4–5
Infill: 20–35%
Supports: on
Brim: optional, useful for PETG
Print orientation:

Base: flat bottom on the build plate
Lid: top surface facing upward, with fins printing vertically
After printing, lightly clean:

Snap clips
Pi port openings
microSD slot
Heat-set insert pockets
Lid-to-base mating edges
3. Install the Heat-Set Inserts
Place one M2.5 heat-set insert into each standoff pocket in the base.
Heat the insert with a soldering iron.
PLA: roughly 180–200°C
PETG: roughly 220–250°C
Press the insert straight down until it sits flush with the top of the standoff.
Let the plastic fully cool before installing the Pi.
Check that all four inserts are vertical and clear of melted plastic.
Do not overtighten or overheat; the standoffs can deform if too much heat is applied.

4. Prepare the Raspberry Pi Zero 2 W
Install the microSD card before placing the board in the enclosure.
If a GPIO header is already soldered, confirm it clears the GPIO access slot.
If no header is installed, no extra preparation is needed.
Confirm the stock connectors are facing the correct side:
Mini-HDMI
Micro-USB OTG
Micro-USB power
microSD at the end opening
5. Install the Pi in the Base
Lower the Pi Zero 2 W into the base.
Align the four mounting holes with the standoffs.
Make sure the ports line up with the cutouts:
Mini-HDMI cutout
Micro-USB OTG cutout
Micro-USB power cutout
microSD slot
Insert the four M2.5 screws.
Tighten gently until the board is secure.
Do not overtighten. The PCB should be held firmly without bending.

6. Optional OLED Installation
Only do this if you are adding a separate OLED display module.

Place the OLED module into the underside recess of the lid.
Confirm the screen aligns with the top window.
If it is a friction fit, press it in gently.
If needed, secure it with a small amount of removable adhesive or thin double-sided tape.
Route the wires so they do not interfere with the snap clips or Pi components.
Connect the OLED to the Pi GPIO header according to the display module pinout.
Common I2C OLED wiring is usually:

VCC to 3.3 V or 5 V, depending on module
GND to GND
SDA to GPIO SDA
SCL to GPIO SCL
Verify your specific OLED module before powering on.

7. Test Cable Fit Before Closing
Before snapping the lid on:

Plug in the micro-USB power cable.
Test the micro-USB OTG port.
Test the mini-HDMI cable.
Check microSD access.
Make sure no cable or connector pushes the Pi out of position.
If any connector rubs, lightly file the edge of the port opening.

8. Attach the Snap-Fit Lid
Place the lid over the base.
Align the snap clips with the base catch openings.
Press down evenly on both sides.
Listen or feel for the clips engaging.
Check that the lid sits flush all the way around.
To remove the lid:

Gently flex one side of the base near the clip area.
Lift that side of the lid slightly.
Repeat on the opposite side.
Avoid prying aggressively, especially if printed in PLA.
9. Final Checks
After assembly:

Pi is secure on all four standoffs
Ports are accessible
microSD card can be inserted/removed
Lid snaps on and off without cracking
Cooling fins are unobstructed
No wires are pinched
No screws touch components on the Pi
10. Usage Notes
PETG is preferred because the snap clips are more flexible than PLA.
PLA works, but clips may become brittle over repeated removals.
If the lid fit is too tight, lightly sand the mating edges or snap hooks.
If the lid fit is too loose, add a thin strip of tape inside the lid edge as a temporary tolerance shim.
Installation Guide Raspberry Pi Zero 2 W Enclosure
Just so you know, the Raspberry Pi Zero 2 W doesn't come with an OLED screen. If you're not planning to add one yourself, you can just skip the parts about the OLED. Your lid will then just be a simple one with vents or a window.

1. First, what you'll need:
The parts you print:
One base you've printed
One lid you've printed that snaps on
Electronics:
A Raspberry Pi Zero 2 W
A microSD card
You might also want: a separate OLED display, if you're going to use the window on the lid.
Hardware bits:
Four M2.5 heat set inserts
Four M2.5 screws, roughly 4 to 6 mm long
You could also use: thin plastic or nylon washers.
Tools you'll need:
A soldering iron or a tool for heat set inserts
A small Phillips head screwdriver
Something to clean up edges, like a deburring tool, a hobby knife, or a small file.

2. What to use for printing:
Material:
PETG is your best bet.
PLA is fine too, especially if it's just for inside or not getting much rough handling.
Some settings that usually work well:
Layer height: somewhere between 0.16 and 0.24 mm
Walls/perimeters: 3 layers
Top/bottom layers: 4 to 5 layers
Infill: 20 to 35%
Supports: definitely turn these on
Brim: you can use this if you want, it helps with PETG prints.
How to place your parts for printing:
For the base: lay its flat bottom right on the build plate.
For the lid: have its top side facing up, so the fins print straight up.
Once your prints are done, do a quick clean up on these spots:
The snap clips
The openings for the Pi's ports
The microSD slot
The little pockets where the heat set inserts go
The edges where the lid and base meet

3. Time to put in the heat set inserts.
Pop an M2.5 heat set insert into each of those little standoff pockets on the base.
Then, heat up the insert with your soldering iron.
If you're using PLA, aim for about 180–200°C.
For PETG, you'll want it a bit hotter, around 220–250°C.
Gently push the insert straight down until it's level with the top of the standoff.
Make sure the plastic is completely cool before you put the Pi in.
Just double check that all four inserts are straight and don't have any melted plastic messing them up.
Don't screw them in too tight or use too much heat; those standoffs can get warped if you're not careful.

4. Getting your Raspberry Pi Zero 2 W ready.
First thing, put your microSD card in before you drop the board into its case.
If you've already soldered on a GPIO header, just make sure it's not blocking the access slot for the GPIO.
No header? Great, you don't need to do anything extra here.
Just check that all the standard connectors are facing the right way:
The Mini HDMI port
The Micro USB OTG port
The Micro USB power port
And the microSD card should line up with the opening at the end.

5. Now, put the Pi into its base.
Carefully place your Pi Zero 2 W down into the base.
Line up the four holes on the Pi with the standoffs.
Double check that all the ports fit perfectly into their cutouts:
The Mini HDMI cutout
The Micro USB OTG cutout
The Micro- SB power cutout
And the microSD slot.
Screw in the four M2.5 screws.
Tighten them softly until the board feels snug.
Don't crank them too hard. You want the board to be held firmly, but not bent.

6. Putting in the optional OLED screen.
Only do these steps if you're actually adding an OLED display.
Slide the OLED module into the little space under the lid.
Make sure the screen sits right in line with the window on top.
If it just holds by friction, a gentle push should do it.
If it feels loose, you can use a tiny bit of removable glue or some thin doubles ided tape to hold it.
Arrange the wires so they don't get in the way of the snap clips or any parts on the Pi.
Hook up the OLED to the Pi's GPIO header. Just follow the pinout diagram for your display.
For most I2C OLEDs, the wiring generally goes like this:
VCC connects to either 3.3 V or 5 V, depending on your module.
GND goes to GND.
SDA connects to GPIO SDA.
SCL connects to GPIO SCL.
Always check the specific instructions for your OLED module before turning anything on.

7. Before you snap it shut, test your cables.
Before you put the lid on:
Plug in your micro USB power cable.
Try out the micro USB OTG port.
Give the mini HDMI cable a test.
See if you can easily get to the microSD card.
Just confirm that none of the cables or connectors are nudging the Pi out of place.
If a connector seems to rub against the edge, just gently file that opening a bit.

8. Putting on the snapfit lid.
Lay the lid over the base.
Line up those snap clips with the slots on the base.
Press down at the same time on both sides.
You should hear or feel the clips click into place.
Make sure the lid looks flat and even all the way around.
To take the lid off:
Carefully bend one side of the base a little, right by where the clip is.
Then, lift that side of the lid up a tiny bit.
Do the same thing on the other side.
Try not to force it open too hard, especially if your case is made of PLA.

9. Last check up once it's all together:
Is the Pi held firmly by all four standoffs?
Can you easily get to all the ports?
Can you put in and take out the microSD card without trouble?
Does the lid snap on and off without any cracks?
Are the cooling fins clear?
Are any wires getting squeezed?
Are any screws touching parts on the Pi board?

10. A few extra tips for using it:
We like PETG more because its snap clips are bendier than PLA's.
PLA does work, but those clips might break off if you take the lid on and off a lot.
If the lid feels too snug, just gently sand down the edges where it meets the base, or the little snap hooks.
If the lid feels a bit too loose, you can stick a thin piece of tape inside the lid's edge. It helps fill the gap temporarily.

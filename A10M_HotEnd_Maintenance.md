## Geeetech A10M HotEnd Maintenance
A minimal invasive way to maintain (clean) your A10M HotEnd.
*REMARK:* I added the full size pictures in order to be able to zoom into all the details!

**Disclaimer:**
*This tutorial is showing steps which worked for my installation. If you follow the steps, you are doing it at your own risk! Different installations might require a different approach. The minimal invasive approach requires additional care since the initial wiring will not be disassembled. Also using the blow torch to heat up the parts for cleaning introduced a fire hazard and might cause injuries due to the handling with hot metal parts. It is also not a bad idea to take step by step pictures while you are disassembling your own installation.*

**ATTENTION:**
Every time your are doing something with the hotend it is recommended to check if the heater cartridge or the thermistor is touching the metal parts of the hotend. 
REASON: If both the cartridge wire an the thermistor wire it touching the metal, you instantly fry the mainboard!

*HOW TO CHECK:*
Just unplug the cartridge and thermsitor plugs on the extension board, use a multimeter in diode mode and check the metal hotend vs. every line of the wiring.

*HOTEND IMPROVEMENT:*
Heater cartridge: The heater cartridge wires need to be bent 90 degree so make sure your heater cartridge is at least even or about 1mm outside the heatend. Best is if you also turn the cartridge vertically, so the little piece of wire exposed has enough clearance to the hotend. Advanced: you can also get yourself some hight temp silicone (+350°C e.g. K2 bond black silicone) or even exhaust assembly paste (+1000°C e.g. holts firegum but this will not be flexible) to seal the bare wires. this stuff might also help you with some hotend sealing...

*THERMISTOR IMPROVEMENT:*
Use a PTFE washer for the screw pushing the thermistor into the hotend. You might get the same result with a PTFE plumbing tape wrapper around the screw and the thermistor wires. Also possible is to use the high temp silicon, to just glue the thermistor into place, but this is somehow permanent.

### HotEnd schematics
![](pics/IMG_0872.JPG)

### Before you start:
Make sure you have all the required tools. You will need following mandatory thing:
-	Allen key 1.5mm and 2mm
-	Tweezers
-	Tongs small
-	Tongs big (to hold the heat block while hot)
-	Wrench 10mm and 11mm
-	Screwdriver PH2
-	Measuring stick
-	Plunger (came with the original A10M tools)
-	Teflon tube 4mm outer diameter
-	Blow torch or small heat gun (I prefer the blow torch since its heating the parts very fast, but it is more dangerous since you have an open fire and the filament might start to burn)
- Thread seal (temperature resistant) to stop the throats heatblock connection from oozing
![](pics/IMG_0946.JPG)

### Step by step disassembling
#### 1. Undo the front fan
![](pics/IMG_0906.JPG)
#### 2. Unplug the bed leveling sensor
![](pics/IMG_0908.JPG)
#### 3. Undo the 4 top screws holding the HotEnd in the cage
![](pics/IMG_0913.JPG)
### 4. Undo the 2 front and 2 back screws holding the cage into the place
![](pics/IMG_0911.JPG)
![](pics/IMG_0912.JPG)
#### 5. Disassemble the cage from the carriage and take out the HotEnd
![](pics/IMG_0914.JPG)
#### 6. Undo the allen screws locking cartridge heater and pull it out
![](pics/IMG_0916.JPG)
#### 7. Undo the screw locking thermistor and pull it out
![](pics/IMG_0917.JPG)
#### 8. Undo the allen screw locking the throat (you can do this between the fan blades) on both sides
![](pics/IMG_0915.JPG)
#### 9. Undo the 2 screws pushing the heat block against the throats
![](pics/IMG_0918.JPG)
#### 10. Pull the throats out of the cooling blocks
![](pics/IMG_0919.JPG)
#### 11. Undo the throats out of the heat block
![](pics/IMG_0922.JPG)
#### 12. Take out the screen from the throat (you will have to heat the throat until the filament is melting)
![](pics/IMG_0931.JPG)

### Cleaning the parts (you will have to heat up all the parts until the filament is melting)
![](pics/IMG_0942.JPG)
- Clean the screen (you might be able to burn off the filament)
![](pics/IMG_0927.JPG)
- Clean the thread of the throats
![](pics/IMG_0924.JPG)
- Clean the innper part of the throat using the plunger and to a piece of 4mm Teflon tube
![](pics/IMG_0940.JPG)
![](pics/IMG_0939.JPG)
![](pics/IMG_0937.JPG)

### Re-assembling the HotEnd
*In general just the other opposite sequence. I added the steps you have to take additional care:*
- when putting the screen back into the throat, make sure its alligned with the cone part facing the throat
left is correct, right is wrong
![](pics/IMG_0883.JPG)
- Apply seal or hight temp silicon on the thread of the throat before screwing it into the heating block
![](pics/IMG_0935.JPG)
![](pics/IMG_0936.JPG)
- Make sure that the tube is standing out of the lower part of the cooling block min 5mm, but not too much otherwise you will be unable to assemble the throats
![](pics/IMG_0949.JPG)
- Push the throat back into the cooling block and use the screws in the heatblock to push the throat against the tube the last millimetre
![](pics/IMG_0953.JPG)
- Make sure the groove of the throat is aligned with the holes in the cooling block, which should give you a distance between the cooling and the heat block of 3.5mm before redo the allen screw locking the throat
![](pics/IMG_0950.JPG)
![](pics/IMG_0951.JPG)
![](pics/IMG_0952.JPG)
- Make sure the front fan calbe is between the heat shield and the side fan before pushing the HotEnd back into the cage
![](pics/IMG_0956.JPG)
- Redo all the screws, plug in the sensor (BLtouch or 3Dtouch wire sequence looking from the front, left to right: white, black, yellow, red, brown) and check the z-offset in the printer menu

### Finding the right nozzle for the A10M (nozzelmania)
**ATTENTION:** *The A10M is using a very special nozzle!*

- The outer diameter is M7 (unlike the A10, which is M6 most common nozzles with other printers).
- The inner diameter of the nozzle is 2mm (not like the common M7 nozzles used in e.g. MK10 setup)

So best is when you are buying an original geeetech A10M nozzle (hard to get directly in US or Europe, so you might have by it directly from geeetech.com or ali)

I heard of a possible workaround for retrofitting a M7 MK10 nozzle by putting in a short piece of Teflon tube, but this might cause some thermic problems.

Using a off the shelf MK10 might work as well, but when you are doing multi colour print, you have to use a bigger prime tower due to the additional volume of the 4mm inner diameter of the nozzle.

![](pics/IMG_0818.JPG)

**I hope this helps you maintaining your A10M HotEnd.**
**If you find any errors in the tutorial, let me know**

**Regards**
***Caesar***

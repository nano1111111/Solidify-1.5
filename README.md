# Solidify SlimeVR  Flat Tracker


There are 2 cases available, take the one you prefer




## Parts list
- Lolin D1 mini 4.0
- commercially available TP4056 boards
- 180K Resistors
- 1N5817 diode
- 12D00 switch
- takes BMI160 pin compatible and SlimeVR BNO085 pin compatible boards
- 503450 Li-Po Polymer battery
- Case (3D printed)


## Assembly
A step by step guide on how to assemble the tracker

* **Step 1**
---------- 
    Prepare all your components
    Soldering Iron
    Solder
    Lolin D1 mini 4.0
    TP4056 Boards
    BMI160 pin compatible and SlimeVR BNO085 pin compatible boards
    12D00 Switches
    503450 Li-Po Battery
    the PCB's
------------
- **Step 2**
Place the Lolin D1 Mini onto the PCB. To help with positioning, use a strand of solder by threading it through the holes on both the Lolin D1 Mini and the PCB. This will help align the board as accurately as possible. Once you've done this, add solder to all the holes, Incase there are problems, add solder to the backside of the main PCB to ensure the electrical connections



---
- **Step 3**

	Repeat the same process for the IMU board and the TP4056 charging board, ensuring proper alignment and secure soldering.
 ---
- **Step 4**
If you have a multimeter, check the switch's continuity to determine which pins are electrically connected. Once confirmed, insert the switch into the PCB and push it forward towards the cutout. It should sit flush against your workbench before soldering.

	If you're unsure about positioning, refer to the provided image for guidance.

 ---
 - **Step 5**

	If your battery comes with a JST connector, cut it off and strip the insulation to expose the
	copper wires. Tin the exposed strands with solder to make assembly easier.

	On the PCB, locate the two copper pads labeled **+** and **-** to indicate polarity. Solder the
	wires to the corresponding pads, ensuring correct polarity.

**Note:** The following image shows an earlier version of my PCB, which included a JST 2.0 connector in the eCAD design and copper pads for the official SlimeVR BNO085 module (which is to my knowledge discontinued). In that version, I soldered the battery directly to the TP4056 charging module. However, your PCB should resemble this once the soldering is complete.
![enter image description here](https://cdn.discordapp.com/attachments/635870829619707905/1348265709331026051/IMG_20250309_130142985_HDR.jpg?ex=67ced5ca&is=67cd844a&hm=3b663daeb26def1367c31b6fa8cca3dd19d9f3f39d1503056956e1ffed2acb0e&)

a JST 2.0 connector will not fit due to space constraints, and you shouldn't solder the battery wires to that, it will just break off eventually

 --- 
- **Step 6** 


The case consists of two parts: the main body and the lid.

1.  Place the battery at the bottom of the case.
2.  Position the PCB on top of it. Due to the switch, you’ll need to insert the PCB at a slight angle before pressing it down into place.
3.  Press the lid onto the case. The design features a press-fit mechanism, so no additional fasteners are required.

  
## Flashing

You may need to change the I²C address in the firmware. Use the web firmware flasher available here "https://slimevr-firmware.bscotch.ca/". The tool is straightforward to use. However, avoid clicking on any video links on the page as they will lead to a rickroll (seriously).


## Strap
You can use 50mm elastic fabric band for the straps, I suggest you use buckles for the hip and chest tracker but this comes down to personal preference.

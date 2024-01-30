# **3D Printer Smart Board**  <img src="https://github.com/MrPresident2/3D-Printer-Smart-Board/blob/main/Pictures/PCB.png?raw=true" width="90" height="70" /> ✨

Hey guys! and thank you for buying our PCB kit, here you can find our official instructions and more information about our PCBs and products. The 3D Printer Smart Board will make your printer smart! and will integrate seamlessly with Home 
Assistant and Octoprint.

<img src="https://github.com/MrPresident2/3D-Printer-Smart-Board/blob/main/Pictures/GEN2%20Power%20Smart%20Switch%20Thumbnail%20B-Close%20up%202.png?raw=true" width="300" height="200" /> 


## **Join Our Discord Server**
---
To discuss everything about our custom made PCBs or everything 3D printed!

[<img src="https://discordapp.com/api/guilds/763458034440863814/widget.png?style=banner2" alt="Discord Banner 2"/>](https://discord.gg/cdHPTxnrM8)

---
## 🖳 **Parts:**  
• 3D Printer Smart Board [Link](http://a.com) 

• 3D Printer Smart Board power adapter [Link](https://amzn.to/49feKC9) 

• RGBW light strip - addressable [Link](https://amzn.to/3ShPnJe) 

• Extra AC Power Cable [Link](https://amzn.to/495xfce) 

• 22 Gauge Wire [Link](https://amzn.to/3U8urXJ) 

• XH2.54 Connector Kit [Link](https://amzn.to/47nJfo6) 

• XH2.54mm Crimper [Link](https://amzn.to/48hjnM3) 

• Qty 2 - Cherry MX Switches (Blues the best ) [Link](https://amzn.to/3SCHvTJ) 

---

## ⚙️ **Bulid Instructions:**

1. Install the unit under your table, I recommend the back middle area. Screw in place using 4
wood screws. Orientation does not matter but I found it easiest to face the power in input back
towards the wall.

<img src="https://github.com/MrPresident2/3D-Printer-Smart-Board/blob/main/Pictures/A.png?raw=true" width="310" height="200" /> 

2. Plug the printer into the outlet on the front of the unit.

<img src="https://github.com/MrPresident2/3D-Printer-Smart-Board/blob/main/Pictures/B.png?raw=true" width="310" height="200" /> 

3. **Buttons:**

There are 3 part types to this print, the GEN2 button case, button container, and the buttons
themselves. Let's tackle the button caps first, These can be printed facedown with a color change
on
after the first or second layer, this will create the contrast for the icons to become visible on the
buttons.

<img src="https://github.com/MrPresident2/3D-Printer-Smart-Board/blob/main/Pictures/C.png?raw=true" width="310" height="200" /> 

Press the two printed button caps onto the pegs of of the Cherry MX switches.
 Insert both the assembled buttons into the button case like shown.
 Now is a good time to solder the cable wires to the 2 pins sticking out the back side of the buttons (the orientation of the cables are not importent).

<img src="https://github.com/MrPresident2/3D-Printer-Smart-Board/blob/main/Pictures/D.png?raw=true" width="310" height="200" /> 

Slide the button container, with the installed buttons inserted, into the GEN2 button case. Route
the cables from the buttons through the cable holders on the inner sides of the GEN2 button case
and out the back opening.

<img src="https://github.com/MrPresident2/3D-Printer-Smart-Board/blob/main/Pictures/E.png?raw=true" width="310" height="200" /> 
<img src="https://github.com/MrPresident2/3D-Printer-Smart-Board/blob/main/Pictures/G.png?raw=true" width="310" height="200" /> 

Crimp the other end of each button cable using the 2 pin [XH2.54 Connector](https://amzn.to/47nJfo6) and the [XH2.54mm Crimper](https://amzn.to/48hjnM3). Insert the crimped pins into the connector as shown here: (the orientation of the cables are not importent).
<img src="https://github.com/MrPresident2/3D-Printer-Smart-Board/blob/main/Pictures/H.png?raw=true" width="310" height="200" /> 

Slide the Button case into place on the GEN2 rails under the table.
after mounting to the GEN2 rails we can connect the cable for the PWR into the connector
labeled PWR and the LED cable into the connector labeled LED
<img src="https://github.com/MrPresident2/3D-Printer-Smart-Board/blob/main/Pictures/I.png?raw=true" width="310" height="200" /> 

4. **LED's:**

Strip the wires back slightly and solder to the LED strips quick disconnect wire. If connecting more than one LED strips, pay close attention to the direction of the LEDs (marked with an arrow) and make sure you are soldering the wires to the right terminals on the LEDs. The right oreontation are marked on the board and on the enclosure. or do it as follow: From left to right GND Data VCC.

<img src="https://github.com/MrPresident2/3D-Printer-Smart-Board/blob/main/Pictures/L.png?raw=true" width="310" height="200" /> 

Crimp the other end of the LED cable using the 3
Crimper. Insert the crimped pins into the connector as shown here

<img src="https://github.com/MrPresident2/3D-Printer-Smart-Board/blob/main/Pictures/M.png?raw=true" width="310" height="200" /> 


**• Double check the LED wires, The Smart Control Board box will have the labels “VCC”,
“DATA” and “GND” which will match up with the text on the LED strip.**

5. **POWER⚡**

• plug in both the 3 prong AC power cord to back of the Smart Power box as well as the 5V 10A DC adapter

• To toggle on the lights single press the lights button on the button panel. Single press to turn off the lights.

• Turn on the printer by quickly double pressing the power button of the button panel. Double
press again to turn off your printer. If pressed too slow the printer will not turn on or off, this is a
safety feature to help prevent accidently turning the printer off by simply bumping the button. 

6. **3D Printer Smart Board**

 PCB is controlled by a preprogrammed ESP32, this allows you 
to do the following:

• Toggle printer or LED power

• Fine tune any RGBW value for the LED strips

• Connect to OctoPi, Home Assistant, for advanced controls and triggers

---
## 🖳 **Useage:**  
after powering the 3D Printer Smart Board for the first time, the board will broadcast an AP "smart-printer-board". Connect to it via your phone.

<img src="https://github.com/MrPresident2/3D-Printer-Smart-Board/blob/main/Pictures/3.png?raw=true" width="310" height="500" /> 

after connection to the AP, a windows will open, if not just go 192.168.4.1.
add your wifi network SSID and Password and that's it!

<img src="https://github.com/MrPresident2/3D-Printer-Smart-Board/blob/main/Pictures/2.png?raw=true" width="310" height="500" /> 

now you can go to your board ip to have some basic webserver controls, or connect to Home Assitant via ESPHome integration.

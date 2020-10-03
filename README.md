# Kicad-STM32


STM32 library for Kicad : BluePill and BlackPill

- symbols : 4 for each ; with and without SWD port breakout ; four are is KLC compliant (let me know if it isn't !), four are "part like", and usefull when capturing schematics while playing with breadboards

- footprints : 3 for each. They are of three kinds ; one is eye candy with a nice silkscreen. The two other ones consider that the "Pill" is on pin headers +- socket headers, and that there is room underneath for components : courtyards are limited to the headers. One of them adds a breakout to the PCB for the SWD port : this can be usefull (for example if the project has a remote connector for flashing/debugging). Footprints are oriented the same way that the pinout drawings that can be found all over the web : USB socket downside for the BlackPill, upside for the BluePill. In my opinion, this makes things easier.

- STEP models : 9 models for every *Pill. Total = 18. All combinations : pin headers, pin headers + socket headers, vertical SWD connector, horizontal SWD connector, and SWD breakout to the PCB using pin headers +- socket headers.

**The step files are too large for GitHub. They are available on GrabCad :** 

BlackPill STEP models : https://grabcad.com/library/stm32-blackpill-1

BluePill STEP models : https://grabcad.com/library/stm32-bluepill-2

- WRL models : they are there.

All 3D models and parts are 100% original.

**All 3D models should align properly with the KiCad and FreeCad coordinates systems. It wasn't the case with the previous version. The problem is now solved.**


![](https://github.com/yet-another-average-joe/Kicad-STM32/blob/master/images/BlackPill.JPG)
![](https://github.com/yet-another-average-joe/Kicad-STM32/blob/master/images/BluePill.JPG)


Symbols

![](https://github.com/yet-another-average-joe/Kicad-STM32/blob/master/images/YAAJ_BlackPill_Sym.png)
![](https://github.com/yet-another-average-joe/Kicad-STM32/blob/master/images/YAAJ_BlackPill_SWD_Breakout_Sym.png)
![](https://github.com/yet-another-average-joe/Kicad-STM32/blob/master/images/YAAJ_BluePill_Part_Like_Sym.png)
![](https://github.com/yet-another-average-joe/Kicad-STM32/blob/master/images/YAAJ_BlackPill_Part_Like_SWD_Breakout_Sym.png)
![](https://github.com/yet-another-average-joe/Kicad-STM32/blob/master/images/YAAJ_BluePill_Sym.png)
![](https://github.com/yet-another-average-joe/Kicad-STM32/blob/master/images/YAAJ_BluePill_SWD_Breakout_Sym.png)
![](https://github.com/yet-another-average-joe/Kicad-STM32/blob/master/images/YAAJ_BluePill_Part_Like_Sym.png)
![](https://github.com/yet-another-average-joe/Kicad-STM32/blob/master/images/YAAJ_BluePill_Part_Like_SWD_Breakout_Sym.png)

Footprints

![](https://github.com/yet-another-average-joe/Kicad-STM32/blob/master/images/YAAJ_BlackPill_No_SWD_Breakout_1_Footprint.png)
![](https://github.com/yet-another-average-joe/Kicad-STM32/blob/master/images/YAAJ_BlackPill_No_SWD_Breakout_2_Footprint.png)
![](https://github.com/yet-another-average-joe/Kicad-STM32/blob/master/images/YAAJ_BlackPill_SWD_Breakout_1_Footprint.png)
![](https://github.com/yet-another-average-joe/Kicad-STM32/blob/master/images/YAAJ_BlackPill_SWD_Breakout_2_Footprint.png)

![](https://github.com/yet-another-average-joe/Kicad-STM32/blob/master/images/YAAJ_BluePill_1.PNG)
![](https://github.com/yet-another-average-joe/Kicad-STM32/blob/master/images/YAAJ_BluePill_2.PNG)
![](https://github.com/yet-another-average-joe/Kicad-STM32/blob/master/images/YAAJ_BluePill_2_SWD_Breakout.PNG)

Naming for 3Dpackage files is probably not the best. English is not my first language...

**YAAJ_Module_STM32_BlackPill_No_Headers_cp** :

bare module, no headers

**YAAJ_Module_STM32_BlackPill_PinHeaders_B_SWD_Header_cp** :

pin headers, SWD header broken out on bottom

**YAAJ_Module_STM32_BlackPill_PinHeaders_H_SWD_Header_cp** :

pin headers, SWD port on top with horizontal pin header

**YAAJ_Module_STM32_BlackPill_PinHeaders_No_SWD_Header_cp** :

pin headers, no SWD port

**YAAJ_Module_STM32_BlackPill_PinHeaders_V_SWD_Header_cp** :

pin headers, SWD port on top with vertical pin header

**YAAJ_Module_STM32_BlackPill_PinSockets_B_SWD_Header_cp** :

pin headers on pin sockets, SWD header broken out on bottom

**YAAJ_Module_STM32_BlackPill_PinSockets_H_SWD_Header_cp** :

pin headers on pin sockets, SWD port on top with horizontal pin header

**YAAJ_Module_STM32_BlackPill_PinSockets_No_SWD_Header_cp** :

pin headers on pin sockets, no SWD port

**YAAJ_Module_STM32_BlackPill_PinSockets_V_SWD_Header_cp** :

pin headers on pin sockets, SWD port on top with vertical pin header

**YAAJ_Module_STM32_BluePill_No_Headers_cp** :

bare module, no headers

**YAAJ_Module_STM32_BluePill_PinHeaders_B_SWD_Header_cp** :

pin headers, SWD header broken out on bottom

**YAAJ_Module_STM32_BluePill_PinHeaders_H_SWD_Header_cp** :

pin headers, SWD port on top with horizontal pin header

**YAAJ_Module_STM32_BluePill_PinHeaders_No_SWD_Header_cp** :

pin headers, no SWD port

**YAAJ_Module_STM32_BluePill_PinHeaders_V_SWD_Header_cp** :

pin headers, SWD port on top with vertical pin header

**YAAJ_Module_STM32_BluePill_PinSockets_B_SWD_Header_cp** :

pin headers on pin sockets, SWD header broken out on bottom

**YAAJ_Module_STM32_BluePill_PinSockets_H_SWD_Header_cp** :

pin headers on pin sockets, SWD port on top with horizontal pin header

**YAAJ_Module_STM32_BluePill_PinSockets_No_SWD_Header_cp** :

pin headers on pin sockets, no SWD port

**YAAJ_Module_STM32_BluePill_PinSockets_V_SWD_Header_cp** :

pin headers on pin sockets, SWD port on top with vertical pin header

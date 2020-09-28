# Kicad-STM32

STM32 library for Kicad : BluePill and BlackPill

- symbols : 2 for each ; one is KLC compliant (let me know if it isn't !), the other is "part like", and usefull when capturing schematics while playing with breadboards

- footprints : 3 for each. They are of three kinds ; one is eye candy with a nice silkscreen. The two other ones consider that the "Pill" is on pin headers +- socket headers, and that there is room underneath for components : courtyards are limited to the headers. One of them adds a breakout to the PCB for the SWD port : this can be usefull (for example if the project has a remote connector for flashing/debugging)

- STEP models : 9 models for every Pill. Total = 18. All combinations : pin headers, pin headers + socket headers, vertical SWD connector, horizontal SWD connector, and SWD breakout to the PCB using pin headers +- socket headers. The files are too large for GitHub. They will be uploaded elsewhere, and a link will be provided. Maybe GrabCad as it was before...

- WRL models : they are the most important ones, and they are there. .wrl is the format to use with KiCad !

All 3D models and parts are 100% original.

**All 3D models should align properly with the KiCad and FreeCad coordinates systems. It wasn't the case with the previous version. The problem is now solved.**


![](https://github.com/yet-another-average-joe/Kicad-STM32/blob/master/images/BlackPill.JPG)
![](https://github.com/yet-another-average-joe/Kicad-STM32/blob/master/images/BluePill.JPG)


Symbols

![](https://github.com/yet-another-average-joe/Kicad-STM32/blob/master/images/YAAJ_BlackPill_Sym.png)
![](https://github.com/yet-another-average-joe/Kicad-STM32/blob/master/images/YAAJ_BlackPill_Part_Like_Sym.png)

![](https://github.com/yet-another-average-joe/Kicad-STM32/blob/master/images/YAAJ_BluePill_Sym.png)
![](https://github.com/yet-another-average-joe/Kicad-STM32/blob/master/images/YAAJ_BluePill_Part_Like_Sym.png)

Footprints

![](https://github.com/yet-another-average-joe/Kicad-STM32/blob/master/images/YAAJ_BlackPill_1.PNG)
![](https://github.com/yet-another-average-joe/Kicad-STM32/blob/master/images/YAAJ_BlackPill_2.PNG)
![](https://github.com/yet-another-average-joe/Kicad-STM32/blob/master/images/YAAJ_BlackPill_2_SWD_Breakout.PNG)

![](https://github.com/yet-another-average-joe/Kicad-STM32/blob/master/images/YAAJ_BluePill_1.PNG)
![](https://github.com/yet-another-average-joe/Kicad-STM32/blob/master/images/YAAJ_BluePill_2.PNG)
![](https://github.com/yet-another-average-joe/Kicad-STM32/blob/master/images/YAAJ_BluePill_2_SWD_Breakout.PNG)

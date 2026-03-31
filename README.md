# Water Cooled MacBookPro (WCMBP)
> _this is part of a submission to Blueprint Hack Club._

**Hello!** I'm aiming to DIY the First True* Liquid Cooled Macbook utilising a sub-2.5mm Liquid Cooling Block, as well as creating the first Active Same-Level Hybrid Air-Liquid Cooling System In Consumer Electronics.
The first part of this readme will be a short introduction before this project is explained in more depth.
![Stock Cooler](/images/stockcooler.png)
_render of the stock cooler of the Macbook Pro A2442._

## Function / Use
Similar to a traditional Desktop PC AIO, it features a pump, two fans (one blower one exhaust) and a modified refrigerator heatsink for a small size. 
<br>To use this project, simply plug in the quick disconnect tubing and plug the usbc line into a Macbook that has been prefitted with the heatsink and watch temps drop. 

## Why did I start this project?
I've always wanted to start making something but never found the determination to. 
My first attempt happened last year with me challenging myself to build the smallest drone i could, though those plans were cut short by my lack of experience and shipping problems (negotiating 4 months for the pcb) that destroyed my motivation. 
I wanted to push for a pioneer and revolutionary idea that improves technology, and had an idea at the end of last year to create the world's first true liquid cooled Macbook. 

I hope to make a high quality video out of this project too!
<br> **Thank you for reviewing this project.**

note: this repository is placed under CC BY-NC-ND.

## Hardware (Cooler)
The concept is simple, just pull water over the processor ...
![Concept Sketch](/images/conceptidea.png)
The first design used parallel channels running from a supply manifold to a drain manifold, shortening single channels to reduce pressure drop.
![First Block Design](/images/coolerv1.png)
To assist with water flow better, the second design smoothed out corners of the first.
![Second Block Design](/images/coolerv2.png)

## PCB
This project is powered using the STM32G431CBT6, as my friend also happen to be building a project of his using this chip.
The schematics are as follows.
![Alt text description](/images/pcbschematics.png)
There are a few errors in the schematic design, such as flashing components being forgotten T_T but I'm trying to find a workaround without buying another board.
The wiring is relatively straightforward, all the power supply is at the bottom and the main chip components to the centre, while peripherals are connected to the left.
![Current wiring](/images/pcbwiring.png)
I have finished soldering the board (only rich people can afford stencil T-T) and debugging USB data issues.
![PCB Board](/images/pcb.png)

## Case
Original case
![Original casing](/images/ver1.png)
Somehow, not a **single** dimension fit. A round of revision and rebuilding the entire project again, ver2 is born.
![Casing 2](/images/assembled.png)
The whole thing can be 3D printed in a few pieces.
![Casing 2](/images/disassembled.png)

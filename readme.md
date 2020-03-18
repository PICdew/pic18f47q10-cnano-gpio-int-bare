<div id="readme" class="Box-body readme blob js-code-block-container">
  <article class="markdown-body entry-content p-3 p-md-6" itemprop="text"><p><a href="https://www.microchip.com" rel="nofollow"><img src="https://camo.githubusercontent.com/5fb5505f69a28ff407841612dfe2b7004f210594/68747470733a2f2f636c6475702e636f6d2f553071684c7742696a462e706e67" alt="MCHP" style="max-width:100%;"></a></p>

# PIC18F47Q10 GPIO Interrupt 

## Objective:
The PIC18F47Q10 provides multiple PORT modules.
In this demo, a PORT pin is configured as input and connected to a button. The Interrupt-on-Change is enabled on the negative edge. Another pin is used as an output and connected to an LED. 

## Resources:
- Technical Brief Link [(linkTBD)](http://www.microchip.com/)
- MPLAB® X IDE 5.30 or newer [(microchip.com/mplab/mplab-x-ide)](http://www.microchip.com/mplab/mplab-x-ide)
- MPLAB® XC8 2.10 or newer compiler [(microchip.com/mplab/compilers)](http://www.microchip.com/mplab/compilers)
- MPLAB® Code Configurator (MCC) 3.95.0 or newer [(microchip.com/mplab/mplab-code-configurator)](https://www.microchip.com/mplab/mplab-code-configurator)
- PIC18F47Q10 Curiosity Nano [(DM182029)](https://www.microchip.com/Developmenttools/ProductDetails/DM182029)
- [PIC18F47Q10 datasheet](http://ww1.microchip.com/downloads/en/DeviceDoc/40002043D.pdf) for more information or specifications.

## Hardware Configuration:

The PIC18F47Q10 Curiosity Nano Development Board [(DM182029)](https://www.microchip.com/Developmenttools/ProductDetails/DM182029) is used as the test platform, along with the Curiosity Nano Base for Click Boards™ [(AC164162)](https://www.microchip.com/Developmenttools/ProductDetails/AC164162) and the POT click board™ [(MIKROE-3402)](https://www.mikroe.com/pot-click).

The following configurations must be made for this project:
- RA0 pin - Configured as digital input and connected through a wire to D2 (RE2, which is connected to the SW0 user button)
- RE0 (LED0) pin - Configured as output

## Demo:
Run the code. When pressing the button, an interrupt will be generated and the LED will be toggled. 

<img src="images/demo.gif" alt="Demo" width="500"/>

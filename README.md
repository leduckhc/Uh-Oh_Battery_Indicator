Uh-Oh Battery Level Indicator
==================

[![Uh-Oh Battery Level Kit](https://dlnmh9ip6v2uc.cloudfront.net//images/products/1/1/0/8/7/11087-03.jpg)  
*Uh-Oh Battery Level Indicator Kit (KIT-11087)*](https://www.sparkfun.com/products/11087)

A kit that turns on an LED (Uh-Oh!) when the voltage of a given system drops below a user settable target. Utilizes the TL431 programmable shunt regulator.

Description
-----------
Under-powering a digital device can sometimes have pretty nasty consequences. Brown-out conditions can cause memory to get written or overwritten in odd ways, can cause unexpected behavior in connected systems and just generally screw up your day. One way to avoid this is to keep an eye on your battery voltage and turn off the system before it gets too low (or plug it in). We’ve whipped up a little board to help you out with this situation: the “Uh-oh” battery level indicator.

At the heart of the “Uh-oh” board is the TL431ACLPG shunt regulator diode. The reference voltage can be adjusted by using the trimpot on board. When the battery connected to the board reaches that voltage, the shunt allows current to flow through the LED, alerting you to a low battery situation. In order to set the appropriate reference voltage, you can use the formula found in the schematic to calculate your desired resistance and set it using the trimpot and a multimeter measuring resistance across the provided test points.

This board comes as a “bag of parts” kit. All of the parts are through-hole and it shouldn’t take long to solder together. The footprint of each part is clearly marked on the PCB to help you throw it together.

**Kit Includes:**

  + ‘Uh-oh’ Through-hole PCB
  + 10mm Diffused Green LED
  + JST Wire Assembly
  + TL431ACLPG IC
  + JST Right-Angle Connector
  + 10K Trimpot
  + 330 Ohm Resistor

**Documents:**

  + [Schematic](http://cdn.sparkfun.com/datasheets/Kits/UhOh-v11_corrected.pdf)
  + [Eagle Files](http://cdn.sparkfun.com/datasheets/Kits/UhOh-v11.zip)
  + [Datasheet](http://cdn.sparkfun.com/datasheets/Kits/TL431-D.pdf) (TL431ACLPG)
  + [Hookup Guide](https://learn.sparkfun.com/tutorials/uh-oh-battery-level-indicator-hookup-guide?_ga=1.181556452.2131958465.1460852985)
  + [GitHub](https://github.com/sparkfun/Uh-Oh_Battery_Indicator)

Repository Contents
-------------------
* **/hardware** - All Eagle design files (.brd, .sch)

License Information
-------------------

The hardware is released under [Creative Commons Share-alike 3.0](http://creativecommons.org/licenses/by-sa/3.0/).  

All other code is open source so please feel free to do anything you want with it; you buy me a beer if you use this and we meet someday ([Beerware license](http://en.wikipedia.org/wiki/Beerware)).

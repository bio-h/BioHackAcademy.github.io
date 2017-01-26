---
layout: page
title: Class 9 - Bioinformatics
permalink: /bha4/class/9/
---

## Synopsys

Microbes can generate a lot of data. Especially 3D data is beautiful and essential to understand. We will give enzyme analysis a try. Next, spectroscopy is a great tool for monitoring the growth and production in your bioreactor. We will make our own light source and detector setup. The class is about other analytical techniques too.

## Schedule

* Bioinformatics
* Spectrometer Design
* Practicals
  * PyMol
  * [Iodine Clock Reaction](/bha4/class/9/iodine-clock-reaction/)

## Devices

This week you can build two types of pumps. As with the other projects, each of the devices has its own github repository.

### Some notes on the source files and designs
* Code: We have included the LiquidCrystal_I2C library. However, as there are multiple libraries named LiquidCrystal_I2C around on the web, if you have included one in your Arduino libraries directory it can result in a conflict (errors during compilation). Temporarily remove the library from your Arduino libraries directory.
* Peristaltic pump: the design of the pump depends on the diameter of the tube. In case you use a different type, you will need to adjust the diameters. In our design we used HelixMark™ tubes (internal diameter 6.35 mm; external diameter 9.55 mm)
* Syringe pump: the mounting interface between the pump and the syringe depends on the type of syringe you use. In our design we used a MediWare 60mL syringe (REF: I3 040800).

### Syringe pump

This pump is best for moving small volumes of liquids.

* [BHA_SyringePump repository](https://github.com/BioHackAcademy/BHA_SyringePump)

### Peristaltic pump

This pump is best for moving small volumes of liquids.

* [BHA_PeristalticPump repository](https://github.com/BioHackAcademy/BHA_PeristalticPump)
* [Building guide](/biofactory/class/8-pumps/peristaltic-pump-building-guide/) 

Finished peristaltic pump:
[![Peristaltic Pump in action](http://img.youtube.com/vi/rvNwhfQSCfg/0.jpg)](http://www.youtube.com/watch?v=rvNwhfQSCfg)

[Watch the pump in action on Youtube](http://www.youtube.com/watch?v=rvNwhfQSCfg)

## Bill of Materials

In order to take part in this class you will need the following materials:

* [Syringe Pump materials](https://github.com/BioHackAcademy/BHA_PeristalticPump/blob/master/BoM.md)
* [Peristaltic Pump materials](https://github.com/BioHackAcademy/BHA_SyringePump/blob/master/BoM.md)

## Additional reading and hacking

* DIY Syringe pumps
  * [OpenPump](https://www.wevolver.com/gerrit.niezen/openpump---an-open-source-hardware-syringe-pump/openpump)
* DIY Peristaltic pumps
  * [Instructable Peristaltic Pump](http://www.instructables.com/id/Inexpensive-easy-to-build-peristaltic-pump/)

## Feeling lazy?

Go ahead and buy some pumps:

* [Syringepump.com](http://www.syringepump.com/index.php)
* [LabX Peristaltic Pump](http://www.labx.com/pumps-peristaltic)

Back to [BHA4](/bha4/)
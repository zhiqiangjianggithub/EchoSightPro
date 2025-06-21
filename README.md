# EchoSightPro #

<p align="center">
  <img src="images/logo.jpg" />
</p>

## Overview ##
__EchoSight Pro__ is an ultrasound software engine, which I developed by myself for fun. Compared to exsiting ultrasound research platform for public usage, such as Field II, Focus, KWAVE, MUST and ect focusing on sound field simulation, __EchoSight Pro__ is of different goal. 

It is efficiency oriented, engineering based and product level architectured for handling raw ultrasound signal, no matter it is from simulation or real channel data. It can be used combining with those pure research platform for your study, acadamic research or advanced prototype machine evaluation in real time.

To know the existing research platform check the link below

-Field II https://field-ii.dk/

-Focus    https://www.egr.msu.edu/~fultras-web/

-MUST     https://www.biomecardio.com/MUST/

-KWave    http://www.k-wave.org/index.php

## Predecessor EchoSight History ##
Previously, I have developed its predecessor EchoSight, which has done already, but not opened for public usage. EchoSight is support real time software beam forming, including IQ beam forming, Recursive Transmit Beamforming, Synthetic beamforming, Multiple Line Acqusition beam forming already, and can work on CPU only and CPU + GPU case both, support linear and phase probes, supporting steering for compounding, all of them can be in real time, and easy ,flexible to extend different modes. Old EchoSight real time running screen shot, plz check the images below(if U see any grid artifact, plz zoom in/out.it is cause by your browser display scale)

<p align="center">
  <img src="images/echosight%20old%20linear%20steer.gif" />
</p>
<p align="center">
  <img src="images//echosight%20old%20phase.jpg" />
</p>

If you have any intesests on its predecessor, you check the link below for previous development log

https://blog.csdn.net/gamer_gerald/article/details/135611461?spm=1001.2014.3001.5501


## New EchoSight Pro Advantage ##
__EchoSight Pro__ is the complete upgrade, rebuild version of its predecessor, actually I rewrote all the codes from scratch again. The whole engineering architecture is refined for __EchoSight Pro__, it will surpass old EchoSight completely.

-Efficiency

-Flexibility

-Ease of use



## License ##

Attention, personalized license is on this software. Check license declare for details. But I make it brief here for guys. If it is for university study, academic research, lab research without any commercial purpose, no limits at all. For commercial purpose, prototype machine build, it can only be used for hardware evaluation and run independently. Trying to integrate to your product is strictly forbidden. 


## Functionality Guidance ##
__EchoSightPro__ provides many useful functions for research and evaluation.

1.Basic BF with MLA


2.RTB BF with MLA


3.RTB BF with MLA and Synthetic


4.Mutiple Angle Scanning


5.Probe type selection

6.SNR control for data

7.System Extreme Pressure Control


For more information, please check the __EchoSightPro User Guidance__ mannual.









## Performance Evaluation ##

__EchoSightPro__ actual performance can variant depends on your settings and relies on your hardware. The following evaluation is based on my testing hardware. 

| CPU    | MEMORY     | GPU   | OS |
|:------:|:------:|:------:|:------:|
|Intel 12th I5-12400|16GB|3060Ti,UHD730|WIN 10|

Latest testing cases


## Platform ##

The __EchoSightPro__ is aviable on windows platform only. 

PS: It is all written by C++ (mostly ISO20, partially ISO23) and plused a simple OpenGL display, which makes it completely possible to transplant to other OS. But that is not my intersts by now.





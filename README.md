# EchoSightPro #

<p align="center">
  <img src="images/logo.jpg" />
</p>

## Overview ##
__EchoSight Pro__ is an ultrasound software engine, which I developed by myself for fun, using my spare time. Compared to exsiting ultrasound research platform for public usage, such as Field II, Focus, KWAVE, MUST and ect focusing on sound field simulation, __EchoSight Pro__ is of different goal. 

It is an efficiency oriented, engineering based and product level architectured for handling raw ultrasound channel signal data, no matter those data is from simulation, real data captured from machine. It can be used by cooprating with those research platform for acadamic research or advanced prototype machine evaluation. 

To know the existing research platform check the link below

-Field II https://field-ii.dk/

-Focus    https://www.egr.msu.edu/~fultras-web/

-MUST     https://www.biomecardio.com/MUST/

-KWave    http://www.k-wave.org/index.php


What makes __EchoSight Pro__  unique is, it can work in __real time__. Due to the extrodinary engineering architecture and implementation, __EchoSight Pro__ can run on your normal computer __with GPU__ or even __without GPU__ both. 

More than that, __EchoSight Pro__ support __Recursive Transmit Beamformation__, __Synthetic Aperture__, __Multiple Line Aquisition__,  __Steering__ scanning, it can support all of those features, while working in real time. 

It achieves high quality commercial level, no matter from ultrasound theoritical perspective or from engineering design point of view.


## Predecessor EchoSight History ##
Previously, I have developed its predecessor EchoSight, which has done already, but not opened for public usage. EchoSight is support real time software beam forming, including IQ beam forming, Recursive Transmit Beamforming, Synthetic beamforming, Multiple Line Acqusition beam forming, Steering scan already, and can work on CPU mode,  and GPU mode. 

Old EchoSight real time running screen shot, plz check the images below(if U see any grid artifact, which caused by your browser display,  plz zoom in/out.)

<p align="center">
  <img src="images/echosight%20old%20linear%20steer.gif" />
</p>
<p align="center">
  <img src="images//echosight%20old%20phase.jpg" />
</p>

If you have any intesests on its predecessor, you check the link below for previous development log

https://blog.csdn.net/gamer_gerald/article/details/135611461?spm=1001.2014.3001.5501


##  EchoSight Pro Design Target ##
The brand new __EchoSight Pro__ is the complete upgrade, rebuild, redesigned version of its predecessor, actually I rewrote all the codes from scratch once again. The whole engineering architecture is refined for __EchoSight Pro__, it will surpass old EchoSight completely. Its design target is focus on

-__Efficiency__
Not targeting on working in real time only, it aims at working super fast and smooth; It releases the full computation of your exsiting hardware, no matter it is a powerful work station or a normal personal computer, by my redesigning on high level and lowe level. It will surpass old EchoSight  completely.(Sorry baby, U become my new baby's background benchmark)

-__Flexibility__
It can work and adjust easily beyond your imagination;

-__Super Hybride__
EchoSight Pro not only works on CPU only mode or GPU only mode(which I call it single power mode), but also can work on CPU plus GPU hybride mode(dual power mode). In hybride mode configuration, it cooperating CPU and GPU on beamformation simultaneously, dynamically and automatically adjust computation work load in real time in order to obtain the best performance on your computer, on which ultrasound images are formed by your CPU and GPU both.
What is even cooler, hybride mode is designed to privde CPU plus embed GPU plus independent GPU working all together(trinity power) for beamformation, 


-__Ease of use__



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
|Intel 12th i5-12400|16GB(2400MHz)|3060Ti(8GB)<br>UHD730|WIN 10|

Latest testing cases


## Platform ##

The __EchoSightPro__ is aviable on windows platform only. 

PS: It is written by C++ (mostly ISO 20) and plused a simple OpenGL display, which makes it completely possible to transplant to other OS. But that is not my intersts by now.





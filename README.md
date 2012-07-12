PHEVCU
======

Plug-In Hybrid Electric Vehicle Control Unit for [Gen 2 Prius](http://en.wikipedia.org/wiki/Toyota_Prius#Second_generation_.28XW20.3B_2003.E2.80.932009.29)

This GIT is an offshoot of several PriusChat.org forum discussions include:
* ["De"-nginer by BruceMe](http://priuschat.com/threads/de-nginer.111713/)
* [Yipep by JDH](http://priuschat.com/threads/yapip-recreating-peefs-approach.109724/)
* [Decoding 0x348-0x3c8 by LopezJM](http://priuschat.com/threads/decoding-can-messages-0x348-0x3c8-as-described-by-peef.110042/)

Background
==========

Open source project to build an ECU to convert generatio 2 Prius into extended range plug-in hybrid electric vehicles.  Poor man's volt!

The exact physical layout is not specified yet in this project.  but the controller board is currently focusing on the Duinomite Mega with a second CAN bus extension.


How to get started
==================

* [Purchase a Duinomite Mega](http://www.mouser.com/ProductDetail/Olimex-Ltd/DUINOMITE-MEGA/?qs=DUTFWDROaMYoHFvzFPsInPCHugNbTKzd)

* Upgrade firmware to DMBASIC 2.7b, 
   http://www.duinomite.com/duinomite-firmware-update-guide/   

* Run CANECHO.BAS


Areas of ongoing interest
=================

* continued CAN message evaluate

* build the second CAN adapter

* build a solution for filtering or spoofing engine start and extending range CAN messages

* determine performance

* instrument and reporting battery condition
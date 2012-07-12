PHEVCU
======

Plug-In Hybrid Electric Vehicle Control Unit or Gen 2 Prius


Background
==========

Open source project to build an ECU to convert generatio 2 Prius into extended range plug-in hybrid electric vehicles.  Poor man's volt!

The exact physical layout is not specified yet in this project.  but the controller board is currently focusing on the Duinomite Mega with with a second CAN bus extension.


How to get started
==================

* Purchase a Duinomite Mega

* Upgrade firmware to DMBASIC 2.7b, here;
   http://www.duinomite.com/duinomite-firmware-update-guide/   

* Run CANECHO.BAS


Areas of ongoing interest
=================

* continued CAN message evaluate

* build the second CAN adapter

* build a solution for filtering or spoofing engine start and extending range CAN messages

* determine performance

* instrument and reporting battery condition
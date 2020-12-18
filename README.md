---
title: "14D_MotorTest"
author: Nikolaos Chalikias
date: 18/12/2020
output: word_document
---

# FIRMWARE_14D_MotorTest

Nucleo F401 + [X-NUCLEO-IHM04A1](https://os.mbed.com/components/X-NUCLEO-IHM04A1/) version of [12D_MotorTest](https://github.com/nBlocksStudioApps/SCHEMATIC_12D_MotorTest)

This is a more compact H/W version due to smaller (Nucleo + X-Nucleo) PCBs. 
 
The nBlocksStudio Design is the same with [10D_MotorTest for mbed-LPC1768 + L298 ](https://github.com/nBlocksStudioApps/10D_MotorTest) and [12D_MotorTest for Nucleo-F401 + L298](https://github.com/nBlocksStudioApps/12D_MotorTest), only the paramaters that define the Pins to be used are different.


----

## nBlocksStudio Design
This is the Design of the [12D_MotorTest](https://github.com/nBlocksStudioApps/SCHEMATIC_12D_MotorTest) project. The I/O pins used in this project, are different and are modified in the main.cpp directly without using a Design Schematic.

<p align="center">
<img
src="img/05.PNG"
width = 800
/>
</p>

----

<!-- pagebreak -->


## Block Diagram

<p align="center">
<img
src="img/03.PNG"
width = 800
/>
</p>

----

<!-- pagebreak -->

## Switches connection

<p align="center">
<img
src="img/01.PNG"
width = 500
/>
</p>

----

## Motor connection and bridge

<p align="center">
<img
src="img/02.PNG"
width = 500
/>
</p>

----

<!-- pagebreak -->

## main.cpp

The lines with comment "X-NUCLEO" are updated directly in this file manually

<p align="center">
<img
src="img/04.PNG"
width = 800
/>
</p>

----


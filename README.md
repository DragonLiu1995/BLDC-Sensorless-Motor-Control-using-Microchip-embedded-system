# BLDC-Sensorless-Motor-Control-using-Microchip-embedded-system
The purpose of this project is to study sensorless motor control theory and algorithm using the sensorless motor control platform dsPICDEM 
MCLV-2 of Microchip company, including hardware and software modules, such as ADC for the back EMF sampling, PI algorithm control, and 
filter settings and adjustments. In this paper we firstly analyze sensorless algorithm theory comprehensively, including the theory of 
hardware design and software implementation, find the way of combination of hardware and software. In the software, the completion 
includes the initialization according to the hardware condition, the control algorithm compilation and the debugging work. At the same time,
because the sensorless control of motor is easily disturbed by noise, we take the majority function filter algorithm to the deep exploration
. Through the design and improvement of the algorithm, the stability of zero crossing detection was significantly improved, eliminating the
influence of noise, improving the operation stability of the motor sensorless control.

Some sample results are display below showing the mechanism of sensorless control strategy.

<p align="center">
<img width="500" height="300" src="https://github.com/DragonLiu1995/BLDC-Sensorless-Motor-Control-using-Microchip-embedded-system/blob/master/images/BEMF.png?raw=true"/>
</p>
<p align="center">
  <b>Back EMF data read from ocilloscope for three-phases</b>
</p>

<p align="center">
<img width="500" height="300" src="https://github.com/DragonLiu1995/BLDC-Sensorless-Motor-Control-using-Microchip-embedded-system/blob/master/images/ADC.png?raw=true"/>
</p>
<p align="center">
  <b>ADC samples on BEMF phases for the fisrt half of 120 degrees</b>
</p>


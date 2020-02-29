***********************************************
FIR filter implementation and simulation
***********************************************

Introduction
=======================
This project is for those who have already done the four labs

In this project you are required to design a FIR filter and simulate it in the Vivado. You have to finish the code in FIR.vhd and get the simulation running.

In stimuli.txt is a timedomain signal with 8 frequency components sampled at the frequency of 100kHz.

.. image:: ./image/timedomain.png
   :height: 100px
   :align: center

The following figure is the spectrum of the signal in stimuli.

.. image:: ./image/spectrum.png
   :height: 100px
   :align: center


There are 8 frequency components in the signal presented in the stimuli.txt, You have to design a low pass FIR filter to remove six frequency components with higher frequency.


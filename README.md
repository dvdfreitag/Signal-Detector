# Signal Detector

## Peripherals

![AD8319](https://cloud.githubusercontent.com/assets/4998806/17704613/97e20b04-63a3-11e6-824b-6fd6cc15da59.png)

The Signal Detector utilizes an Analog Devices [AD8319](http://www.analog.com/en/products/rf-microwave/rf-power-detectors/non-rms-responding-detector/ad8319.html) RF power detector. Power is supplied to the board through the USB Micro B connector. The RF signal input is J2, and the output voltage is J1. Above you see the minimal external passives required to use the AD8319, however this board includes some extra external components so that things like the temperature offset and the output voltage can be changed. This board is configured to use the AD8319 in measurement mode, not in control mode.

## Specs

The AD8319 has a massive input bandwidth of 1MHz to 10GHz, with a dynamic range of 45dB up to 8GHz ( the chip operates to 10GHz, but there is reduced accuracy and dynamic range above 8GHz). The AD8319 operates at a maximum quiescent current of 30mA, and includes automatic internal temperature adjustments with the use of an external resistor. 

![AD8319](https://cloud.githubusercontent.com/assets/4998806/17705070/100cb1e6-63a5-11e6-9e5a-8e4cdc08ce2d.PNG)

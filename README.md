# Hello-Alexa
200W Speaker with Alexa built-in 

The TDA7294 is a monolithic integrated circuit in Multiwatt15 package, intended for use as audio class AB amplifier in Hi-Fi field applications (Home Stereo, self powered loudspeakers, Topclass TV). Thanks to the wide voltage range and to the high out current capability it is able to supply the highest power into both 4Ω and 8Ω loads even in presence of poor supply regulation, with high Supply Voltage Rejection. The built in muting function with turn on delay simplifies the remote operation avoiding switching on-off noises.


<h4 align="center"><img src=https://github.com/Frankenstein-byte/Hello-Alexa/blob/main/TDA7294.png width ="500" height="350"></h4>

## Notes

* The supply voltage range is +/- 10V to =/-40V DC.
* Heat sink is required and its thermal resistance should be around 0.038 degree Celsius/Watt.
* Use an 8 Ohm 150W speaker as the load.
* For 100W output the supply voltage must be +/-38VDC.
* The power supply must be well filtered and free of ripples.
* If ripples are present in the power supply it may cause oscillations.
* VM = 1.5V is the mute ON threshold and VM=3.5V is the mute OFF threshold.
* Typical input resistance of TDA7294 is 100KiloOhm.
* Frequency response is 20Hz to 20KHz.
* 145 degree Celsius is the threshold for thermal shutdown. Slew rate of TDA7294 is 10V/microsecond and the open loop voltage gain is 80 dB.
* Quiescent current of TDA7294 is approximately 30mA and its maximum value is 65mA.


## Required components for working of Alexa:

The following are required to build this Raspberry pi Alexa project:

* Raspberry pi 3 or 2
* WiFi Dongle (If raspberry pi 2 is to be used)
* Microphone
* Line-in Speaker (with 3.5mm jack)
* 5V, 2A USB Power supply
* Ethernet cable

After the setup is complete you can upload the file (main.py) and run directly to test the output.

## Output

<h4 align="center"><img src=https://github.com/Frankenstein-byte/Hello-Alexa/blob/main/Demo.gif width ="600" height="350"></h4>

<h4 align="center"><img src=https://github.com/Frankenstein-byte/Hello-Alexa/blob/main/1.jpg width ="600" height="450"></h4>

## Progress

The project is still in devlopment phase .............

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.


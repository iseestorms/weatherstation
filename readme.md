# My Weather Observations Weather Station (v0.2)

This repo if for a Raspberry Pi weather statuon that uses a

BME280 I2C/SPI Temperature Humidity Barometric Digital Sensor, ADS1115 ADC 4 Channel 16Bit I2C PGA and a 8 MegaPixel Raspberry Pi webcam.


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them
Purchased:
1x $56 AUD Raspberry Pi 2 or Higher. (I have a Raspbery Pi 2 1.1)
1x $18 AUD TPi Link 300Mbps Wireless N USB Adapter (TL-WN821N) or otehr Raspberry Pi Compatible adalter
1x #39 AUD 8 Mega Pixel Raspberry Pi Camera (3280 x 2464 pixels or 1080p video)
1x $7 AUD 30cm Raspberry PI Camera Cable (15Pin FFC FPC Flexible Ribbon Flat)
1x $5 ADS1115 4 Channel 16 Bit I2C Analog to Digital Sensor
1x $13 AUD BME280 Temperature Humidity Barometric Pressure Digital Sensor (I2C/SPI)
2x waterproof metal buttons (one for shutdown and 1 to take an take image)
Breadboard +breadboard wires, or protoboard and wires 
Optional LEDS, Piezo speaker etc


## Hardware Schematics

todo..


## Raspberry Pi Setup

Connected to WiFi on Boot
I2S
SPI
Python 2.7
Boot to command line.
Change pi password.
RASPBIAN STRETCH WITH DESKTOP - Nov 2017


Wait for Network at boot.


### Installing

A pythoin setp script will be available soon (https://stackoverflow.com/questions/1471994/what-is-setup-py)
 

```
sudo python setup.py install
```

This will downlaod scripts that talk to the alalog sensor, tale imagfes ever 2 minutes and upload to the web. 




## Deployment

Add additional notes about how to deploy this on a live system

## Built With

Bash, Python

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.


## Authors

* **Simon Fearby** - *Initial work* - [ISeeStorms](https://github.com/iseestorms)

See also the list of [contributors](https://github.com/iseestorms?tab=contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

todo..

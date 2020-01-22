Opieramy się na starym projekcie zero bot'a FPV link poniżej...

Pinout
![pinout](https://github.com/kawaczek/pi0w/blob/master/images/zeropinout.png)


sudo apt-get install libjpeg62-turbo-dev

sudo apt-get install cmake

cd

git clone https://github.com/jacksonliam/mjpg-streamer.git ~/mjpg-streamer

cd mjpg-streamer/mjpg-streamer-experimental

make clean all

sudo mkdir /opt/mjpg-streamer

sudo mv * /opt/mjpg-streamer



























# ZeroBot Custom
Leveraging the ZeroBot - Raspberry Pi Zero FPV Robot project: https://hackaday.io/project/25092-zerobot-raspberry-pi-zero-fpv-robot

Modifications
* Added a package.json to incorporate the package dependencies
* Using Raspberry Pi's GPIO 23 as an enable pin for the motor driver module
Modifications2
* Change node-ads1x15 to raspi-kit-ads1x15

Add
Install mjpg-streamer.sh

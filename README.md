# weatherstation
Code for simple a weather station consisting of rs485 devices and sending updates over mqtt


Prepatartion for rpi:
```sudo apt-get install wiringpi```

An upgrade may be required for raspberry PI 4B:
```cd /tmp
wget https://project-downloads.drogon.net/wiringpi-latest.deb
sudo dpkg -i wiringpi-latest.deb
```
Running gpio-v to check if the version is 2.52, If it is not, you need to check the installation again.
```
gpio -v
```

Install python:
```
sudo apt-get update
sudo apt-get install python3-pip
sudo pip3 install RPi.GPIO
sudo apt-get install python3-serial
```

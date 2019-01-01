# temperatureController

## Contents: 
1.Introduction
2.Assembly
3.Installation
4.Interaction

## 1.Introduction
This is a project for temperature adjustment and subscribing to the Adafruit feed. Wemos board subscribes to the Adafruit feed and if the temperature value falls below 19 degrees the heater which is placed inside water container will start.

## 2.Assembly
Materials: Wemos board, , Micro USB cable, water heater, relay
Wiring: You need to connect three wires from the wemos board to the relay. Connect 5v to v5, Di to D2 on the board and G to G.


## 3.Installation

![49312006_225921761641990_532223005766451200_n](https://user-images.githubusercontent.com/6553481/50575233-be778600-0dfa-11e9-98a3-1b5ffa67c9c8.jpg)

You will need Arduino software which can be downloaded using this link: https://www.arduino.cc/en/main/software
After the install is complete you will need to install ESP8266 package.
To do it follow these steps : 
1. Open the Preferences window in the Arduino IDE
2. Enter http://arduino.esp8266.com/stable/package_esp8266com_index.json into Additional Board Manager URLs field.
3. Open the Boards Manager from Tools > Board menu and install the esp8266 platform

Last step is creating Adafruit account if you dont have one yet. It can be done here: http://io.adafruit.com/

## 4.Interaction
Wifi name, password as well as Adafruit feed name and key are hardcoded.
To interact with the code you have to change the wifi name and password to match your wifi name and password. Adafruit feed name and key has to be changed as well.

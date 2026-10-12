# STARBIE PROJECT

## What is this project?
This is my version of a Starbie by SharKingStudios: https://github.com/SharKingStudios/Starbie
Starbie is essentially a mini companion. The companion character lives on the display. It's able
to move around and such. It can react to the environment using data collected from its built-in
IMU and DHT sensors. This gives it a dynamic range of reactions.

## Why did I make this?
This project is a great way to get started learning about PCB design. Its simplicity and low-risk 
nature allow you to master the fundamentals of PCB design with little worry about other aspects of
a project. 

## How it works
The DHT11 and MPU6050 collect temperature and accelerometer data, respectively; the data gets graphed on the serial plotter. This data is sent to the ESP32-C3, which parses the data. This is then used to control the menu and determine the character state. Although capable of doing so, gyroscopic data is not recorded or used. The character and menu are drawn on the OLED screen and can be controlled using tilting.

### The Character
It is supposed to be a snow leopard, but it doesn't look like one :(
Here is what it looks like:
<img width="64" height="64" alt="Character" src="https://github.com/user-attachments/assets/1fb41036-d2d5-4199-9115-c43df14fd88d" />

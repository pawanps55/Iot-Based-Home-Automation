# Iot-Based-Home-Automation
Introduction - 
In this project we use IOT based home automation system which goal is to develop a home automation system that gives the user complete control over all remotely controllable aspects of his or her home.
The recent developments in technology which permit the use of wireless controlling environments like, Bluetooth and Wi-Fi that have enabled different devices to have capabilities of connecting with each other. IoTs technology is used to come in with innovative idea and great growth for smart homes to improve the living standards of life.The main and very basic need of using home systems like light, fan, air conditioner, air heater by using different switches in different places. Therefore people, especially adult people need to put a lot of afford to switch all those components separately and with enough power to press.Those switches are mostly made very unsafe way and it is also asking more energy to put. These problems could be solved if home automation system would be used. In recent years home automation is gaining much popularity. The trend is also in favor of using home automation technology. If we look around residences, malls, offices, use of home automation systems will draw attention.

Chapter 2 – Components Required :
     1.	ARDUINO UNO R3	
     2.	BLUETOOTH MODULE HC05	
     3.	12V RELAY MODULE	
     4.	JUMPER WIRE	
     5.	CONNECTING WIRE	
     6.	LAMP LOAD	
     7.	SMARTPHONE	
     8.	12V Relay – 4	
     9.	BC547 Transistor - 4	
    10.	470ohm Resistor - 4	
    11.	Diode IN 4007 - 4	
    12.	LEDs – 4	
    13.	PCB board	

Working - 
i.A simple home automation project using Arduino UNO, Bluetooth module and a smartphone. The aim of this project is to control different home appliances using a smartphone.
ii.When the power is turned on, the connection LED on the Bluetooth module starts blinking. We need to start the “Bluetooth Controller” app in our smartphone and get connected to the Bluetooth module. If the pairing is successful, the LED becomes stable.
iii.Now, in the app, we need to set different keys for different loads and their corresponding value that must be transmitted when that key is pressed. The following image shows a set of keys to control 4 loads and an additional key to turn off all the loads.
iv.Then we are ready to control the loads. When a key is pressed in the smartphone, the Bluetooth module receives the corresponding data and intern transmits that data to Arduino.
v.The android application is used to transmit the instruction, which carries the information about the operation to be performed. The transmitted instruction is received by the Bluetooth module which has been paired with the android smartphone beforehand.
vi.When the signal port is at low level, the signal light will light up and the optocoupler 817c (it transforms electrical signals by light and can isolate input and output electrical signals) will conduct, and then the transistor will conduct, the relay coil will be electrified, and the normally open contact of the relay will be closed. 
vii.When the signal port is at high level, the normally closed contact of the relay will be closed. So you can connect and disconnect the load by controlling the level of the control signal port.

Advantages - 
I.Home automation using Bluetooth and Arduino can prove to be very useful for Elderly/Handicapped people.
II.A single android smartphone can control multiple devices.
III.Any android phone can be used, no internet required once the app is downloaded.
IV.You can control all kind of appliances and devices.
V.There is no need for extra training of that person who is using it.
VI.All the control would be in your hands by using this home automation system.
VII.There is no time delay for turn on or turn off the connected device.
VIII.This circuit can be used in all conditions.

Disadvantages - 
I.Bluetooth is used in this home automation system, which have a range of 10 to 20 meters so the control cannot be achieved from outside this range.
II.Application is disconnected after disconnect of the Bluetooth.
III.When the new users want to connect, first download application software and then configuration must be done.
IV.High power consumption because of Bluetooth connectivity.

Conclusion - 
From the above discussion it can be concluded that Home Automation is a special device used for controlling and monitoring devices in our home in a centralized place and easily accessible with minimum effort. And in this paper, we discussed the components, working, application and future scope of home automation. We have created a device which is compact, easy to use, long life and low cost. The need of this paper is to create a device which is energy efficient and makes human life easier.
![actual project home automation](https://github.com/pawanps55/Iot-Based-Home-Automation/assets/156445826/f588df02-e1fa-4dcb-a3d2-48236b2323dc)

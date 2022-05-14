# M3_STM32-Based-Automatic-Rain-Sensing-Car-Wiper-System

## Introduction:-
### The proposed car wiper system is automatic and intelligent. Automatic in the sense that the system detects rainfall and starts itself. Intelligent in the sense that the system calculates the intensity of rainfall and adjusts the speed of wiper motor accordingly – higher speed of rotation for higher rain fall and vice versa.The proposed car wiper system is automatic and intelligent. Automatic in the sense that the system detects rainfall and starts itself. Intelligent in the sense that the system calculates the intensity of rainfall and adjusts the speed of wiper motor accordingly – higher speed of rotation for higher rain fall and vice versa. In the current scenario, only luxury vehicles employ intelligent rain sensing windshield wiper systems. Our system is modeled to demonstrate how useful is an automatic wiper system that adjusts speed itself based on rainfall intensity. Such a system improves the safety of a ride. There are many instances of accidents occurring during heavy rainfall due to lack of proper vision. In many cases, these accidents were due to manual errors (for example: not increasing speed of wiper) from the driver. An automatic, intelligent system like ours remove any manual errors. Our system adjusts wiper speed according to the intensity of rainfall and hence improves the safety. The intelligent wiper system is proposed to design using mc, Rain Sensor module, Servo motor and a 16x2 LCD module. The rain sensor module senses rain fall and sends the information to 8051 microcontroller – which is a Atemga8 based micro controller board. mc processes the information collected from rain sensor and controls the output motor (servo motor) based on the processed information. The 16x2 LCD module is to display status messages to the driver – like intensity of rain fall, speed of wiper etc. The rain sensor is placed outside the car/vehicle, ideally at the side corner of windshield. The servo motor is connected to the wiper blades. LCD module is kept inside the car nearby the driver’s vision. All these 3 devices are connected together via mc – which is kept inside the car near to dc power source.

![](https://s3.amazonaws.com/assets.knowyourparts.com/app/uploads/2013/07/926942wipersrai_00000046668.jpg)

## Block Diagram:-

![](https://nevonprojects.com/wp-content/uploads/2015/08/Rain-Sensing-Automatic-Car-Wiper-block.png)

## Objectives:-

### The main theme in this project is to develop an automatic rain sensing car wiper to automatically detect perciperation. The system has been designed in a way which ignites the wiper blades to push off the water falling over the glass in the event of rainfall. This system aims to give better visualization to driver without involving the efforts of driver. Thus limiting the distraction Arduino UNO board, a rain sensing module, a servo motor and a LCD are the main set of requirements used in the_"STM32 Based Automatic Rain Sensing Car Wiper System".

## Requirements:-
* ###  Rain Sensor
* ###  Servo Motor
* ###  Arduino Uno MicroController
* ###  STM32
* ### Single Switch

## Folder Structure:-
|S.NO|FILES UPLOADED|FILE NAME|
|----|--------------|---------|
|0|Abstrat|readme.md|
|1|Requirements|readme.md|
|2|Design|text.md|
|3|Implementation|main.c|
|4|Tsecases|readme.md|
|5|Report|text.md|
|6|Output|readme.md|

## Sdlc Activity:-
![prtscr car  wiper](https://user-images.githubusercontent.com/101544562/168419021-93cebdd9-d791-4f46-a761-27635c921739.png)
![Code Quality Score](https://api.codiga.io/project/33305/score/svg)
![Code Grade](https://api.codiga.io/project/33305/status/svg)
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/7e8e461f566f44cd8b3c0f999211fdbe)](https://www.codacy.com/gh/NagaveniGowthakatla/M3_Automatic-Rain-Sensing-Car-Wiper-System/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=NagaveniGowthakatla/M3_Automatic-Rain-Sensing-Car-Wiper-System&amp;utm_campaign=Badge_Grade)




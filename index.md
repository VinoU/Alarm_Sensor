
   # CENG 317 - Relay Modules and Buzzer
   
-------------
## Table of Contents
1. [September 6, 2017 - Week 0](#respository)
2. [September 18, 2017 - Week 1](#proposal)
2. [September 25, 2017 - Week 2](#gantt-chart-schedule)
3. [October 02, 2017 - Week 3](#budget-report)
4. [October 16, 2017 - Week 4](#proof-of-purchases)
5. [October 23, 2017 - Week 5](#pc-board)
6. [November 27, 2017 - Week 6](#connecting-pi3-first-time)
7. [December 04, 2017 - Week 7](#making-led-blink-works-with-raspberry-pi3)
8. [December 11, 2017 - Week 7](#pla-card)
9. [December 18, 2017 - Week 8](#video)

-------------
## December 18, 2017 - Week 8
## video

**I have made my 30 seconds of video and here is ths link for it

[30s of video](https://www.youtube.com/watch?v=jTI7DDi5JlM)


-------------
## December 11, 2017 - Week 7

## Pla Card
![image alt](https://raw.githubusercontent.com/VinoU/Bar-QR-code-scanners/master/Pla%20Card%20Image%20.jpg) <br>

## My  30 second Script 

Here is mt script :

![image alt](https://raw.githubusercontent.com/VinoU/Bar-QR-code-scanners/master/30%20Second%20Script%20Vinokkumar%20uthayakumar-1%202.jpg) <br>

This is my Wor file od scripting
[Click here for word file](https://github.com/VinoU/Bar-QR-code-scanners/blob/master/30%20Second%20Script%20Vinokkumar%20uthayakumar.docx) <br>

-------------
## December 04, 2017 - Week 7

**Moment of Truth**

### Making LED BLINK works with Raspberry Pi3
### Scoure:
 ```
 git clone https://github.com/six0four/StudentSenseHat.git
 cd StudentSenseHat/firmware
 gcc -Wall -o traffic2B traffic2B.c -lwiringPi
 sudo ./traffic2B
 ```

**Step 1:**
I have Connected my PC board to Rasbperry Pi3:
![image alt](https://raw.githubusercontent.com/VinoU/Bar-QR-code-scanners/master/pcb%20on%20ras.JPG)<br>

**Step 2:**
Run Those Following Socure Code:
```
 git clone https://github.com/six0four/StudentSenseHat.git
 cd StudentSenseHat/firmware
 gcc -Wall -o traffic2B traffic2B.c -lwiringPi
 sudo ./traffic2B
```

**Step 3:**
### Moment of Turth:
LED was Blinking order :
![Image alt](https://github.com/VinoU/Bar-QR-code-scanners/blob/master/Blinking%20LEB%20and%20Sensor/pcb%20led%201.JPG?raw=true "sensor pic")<br>
 ![Image alt](https://github.com/VinoU/Bar-QR-code-scanners/blob/master/Blinking%20LEB%20and%20Sensor/pcb%20led%202.JPG?raw=true "sensor pic")<br>
 
**Report:**
I Connected pc to my Rasbperry and then I ran **traffic2B**  program and then LED was started to blinking from PC baord. When program says Red, the PCB LED was blinking Red and When program says Greed, the PCB LED was blinking green and also OFF.

### Making sensor work with Rasbperry Pi3:
**Step 1:**
From the Start Menu->Preferences->Raspberry Pi Configuration->Interfaces set I2C to Enabled.
![image alt](https://github.com/VinoU/Bar-QR-code-scanners/blob/master/Blinking%20LEB%20and%20Sensor/Sensor.JPG?raw=true "sensor pic")
![image alt](https://github.com/VinoU/Bar-QR-code-scanners/blob/master/Blinking%20LEB%20and%20Sensor/sensor%20on%20pcb2.JPG?raw=true "sensor pic")

**Step 2:**
```
 Shell
 make
 sudo ./ghmain
```
On Termnial<br>
![image alt](https://github.com/VinoU/Bar-QR-code-scanners/blob/master/Blinking%20LEB%20and%20Sensor/sensors%20works.JPG?raw=true "pic")

**Report:**

On Terminal, I connected the seonsors which are (light, tempatue humidity) working fine expect humidity. I ran the program called **ghmain**. and then light sensor detecting the light, Tempeature sensor was detecting the tempeature, and lastly the humidity was not detecting probaly. I am having some issue with Connection on P board.


**Isues with Programming code:**
We have fixed the isue with new Programming code and now it is running very smoothly. All the sensors are detecting probably.<br>

![image alt](https://github.com/VinoU/Bar-QR-code-scanners/blob/master/Blinking%20LEB%20and%20Sensor/sensor%20output.JPG?raw=true "sensor pic")

**Isues with PC board**
I had an isue with pc boad layout and then Kelly could able to fixed to for me . It was great expernices

-------------
## November 27, 2017 - Week 6

### Connecting Pi3 first time

I have my PC Board Soldered and I made my Board working and now I need to connect to my Pc Board to Rapsiberry Pi.
I have tested with Vlad.<br>


Working With Raspberry pi3- Amazing Teachnology ever Built :O
1.
![Image alt](https://github.com/VinoU/Bar-QR-code-scanners/blob/master/Raspberry%20Pi3/IMG_3474.JPG?raw=true "sensor pic")
2. I have installed the opearting system.
![Image alt](https://github.com/VinoU/Bar-QR-code-scanners/blob/master/Raspberry%20Pi3/IMG_3473.JPG?raw=true "sensor pic")
3. I am activating the Wifi Setting Having some issues . Hope I fix it 
![alt text](https://github.com/VinoU/Bar-QR-code-scanners/blob/master/Raspberry%20Pi3/IMG_3481.JPG?raw=true "sensor pic")
-------------
## October 23, 2017 - Week 5

### PC Board

I had some issues while I was soldering. Then I got helped from Vlad and He was teaching my How to fix if the slodering is not in proper.

I had hard time putting resister on my PC board but after Vlad watching taching some trick then I was able to do it by myself. It was great!!!!

![alt text](https://github.com/VinoU/Bar-QR-code-scanners/blob/master/Pictures/IMG_3089.JPG?raw=true "sensor pic")
![Watch the video](https://github.com/VinoU/Bar-QR-code-scanners/blob/master/Pictures/PC%20Board%20video.MOV)
-------------
## October 16, 2017 - Week 4

### Proof of Purchases

**CanaKit Raspberry Pi 3 Complete Starter Kit - 32 GB Edition**
[Invoice](https://github.com/VinoU/Bar-QR-code-scanners/blob/master/Invoices/CanaKit%20Raspberry%20Pi3.pdf?raw=true "sensor pic").
![alt text](https://github.com/VinoU/Bar-QR-code-scanners/blob/master/Pictures/IMG_3112.JPG?raw=true "sensor pic")

**SunFounder Relay Module for Arduino 5V DC Trigger by Low**
[Invoice](https://github.com/VinoU/Bar-QR-code-scanners/blob/master/Invoices/Relay%20Moudle.pdf).
![alt text](https://github.com/VinoU/Bar-QR-code-scanners/blob/master/Pictures/IMG_3105.JPG?raw=true "sensor pic")

**SunFounder Active Buzzer Sensor Module for Arduino and Raspberry Pi**
[Invoice](https://github.com/VinoU/Bar-QR-code-scanners/blob/master/Invoices/Buzzer.pdf).
![alt text](https://github.com/VinoU/Bar-QR-code-scanners/blob/master/Pictures/IMG_3096.JPG?raw=true "sensor pic")
-------------
## October 02, 2017 - Week 3

#### Budget Report

I have created [my Budget Report](https://github.com/VinoU/Bar-QR-code-scanners/blob/master/Parts%20Budget%20Vino%20Uthayakumar%20-%20new.xlsx).
-------------
## September 25, 2017 - Week 2

### Gantt chart schedule

I have Created [Gantt Chart schedule](https://github.com/VinoU/Bar-QR-code-scanners/blob/master/Vino%20Uthayakumar_Project%20Schedule.mpp).  

-------------
## September 18, 2017 - Week 1

### Proposal

 I have Created [proposal](https://github.com/VinoU/Bar-QR-code-scanners/blob/master/vino_%20proposal.xlsx).
 
-------------
## September 6, 2017 - Week 0

### Respository

I have Created [repository](https://github.com/VinoU/Bar-QR-code-scanners).

-------------
## August 30, 2017 

# Welcome to my Blog!!!!!  
                                                 ## Repository created!

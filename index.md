
   # CENG 317 - Bar_QR_Code_Scanners
-------------
## Table of Contents
1. [September 6, 2017 - Week 0]()
2. [September 18, 2017 - Week 1]()
2. [September 25, 2017 - Week 2]()
3. [October 02, 2017 - Week 3]()
4. [October 16, 2017 - Week 4]()
5. [October 23, 2017 - Week 5]()
6. [November 27, 2017 - Week 6]()
7. [December 04, 2017 - Week 7]()

-------------
## December 04, 2017 - Week 7

**Moment of Truth:D**

### Making LED BLINK works with Raspberry Pi3 :
### Scoure:
 ```
 git clone https://github.com/six0four/StudentSenseHat.git
 cd StudentSenseHat/firmware
 gcc -Wall -o traffic2B traffic2B.c -lwiringPi
 sudo ./traffic2B
 ```

**Step 1:**
I have Connected my PC board to Rasbperry Pi3:
![image alt](https://github.com/VinoU/Bar-QR-code-scanners/blob/master/Blinking%20LEB%20and%20Sensor/pcb%20on%20ras.JPG)<br>

**Step 2:**
Run Those Following Socure Code:
![Image alt attribute](https://github.com/VinoU/Bar-QR-code-scanners/blob/master/Blinking%20LEB%20and%20Sensor/pcb1.JPG)

**Step 3:**
### Moment of Turth:
LED was Blinking order :
![Image alt attribute](https://github.com/VinoU/Bar-QR-code-scanners/blob/master/Blinking%20LEB%20and%20Sensor/pcb%20led%201.JPG)
 ![Image alt attribute](https://github.com/VinoU/Bar-QR-code-scanners/blob/master/Blinking%20LEB%20and%20Sensor/pcb%20led%202.JPG)
 
**Report:**
I Connected pc to my Rasbperry and then I ran **traffic2B**  program and then LED was started to blinking from PC baord. When program says Red, the PCB LED was blinking Red and When program says Greed, the PCB LED was blinking green and also OFF.
![image alt](https://github.com/VinoU/Bar-QR-code-scanners/blob/master/Blinking%20LEB%20and%20Sensor/IMG_3580.JPG)

### Making sensor work with Rasbperry Pi3:
**Step 1:**
From the Start Menu->Preferences->Raspberry Pi Configuration->Interfaces set I2C to Enabled.
![alt image](https://github.com/VinoU/Bar-QR-code-scanners/blob/master/Blinking%20LEB%20and%20Sensor/Sensor.JPG)
![alt image](https://github.com/VinoU/Bar-QR-code-scanners/blob/master/Blinking%20LEB%20and%20Sensor/sensor%20on%20pcb2.JPG)

**Step 2:**
```
 Shell
 make
 sudo ./ghmain
```
On Termnial
![alt image](https://github.com/VinoU/Bar-QR-code-scanners/blob/master/Blinking%20LEB%20and%20Sensor/sensors%20works.JPG)

Report:

On Terminal, I connected the seonsors which are (light, tempatue humidity) working fine expect humidity and Tempeatre. I ran the program called **ghmain**. and then light sensor deacting the light, Tempeature sensor was not deacting the tempeature, and lastly the humidity was not working probaly. I am having some issue with Connection on P board.
![image alt](https://github.com/VinoU/Bar-QR-code-scanners/blob/master/Blinking%20LEB%20and%20Sensor/sensor%20output.JPG)

-------------
## November 27, 2017 - Week 6
I have my PC Board Soldered and I made my Board working and now I need to connect to my Pc Board to Rapsiberry Pi.
I have tested with Vlad.


Working With Raspberry pi3- Amazing Teachnology ever Built :O
1.
![Image alt attribute]("https://github.com/VinoU/Bar-QR-code-scanners/blob/master/Raspberry%20Pi3/IMG_3474.JPG")
2. I have installed the opearting system.
![Image alt attribute](https://github.com/VinoU/Bar-QR-code-scanners/blob/master/Raspberry%20Pi3/IMG_3473.JPG)
3. I am activating the Wifi Setting Having some issues . Hope I fix it 
![alt text](https://github.com/VinoU/Bar-QR-code-scanners/blob/master/Raspberry%20Pi3/IMG_3481.JPG)
-------------
## October 23, 2017 - Week 5
PC Board:

I had some issues while I was soldering. Then I got helped from Vlad and He was teaching my How to fix if the slodering is not in proper.

I had hard time putting resister on my PC board but after Vlad watching taching some trick then I was able to do it by myself. It was great!!!!

![alt text](https://github.com/VinoU/Bar-QR-code-scanners/blob/master/Pictures/IMG_3089.JPG)
![Watch the video](https://github.com/VinoU/Bar-QR-code-scanners/blob/master/Pictures/PC%20Board%20video.MOV)
-------------
## October 16, 2017 - Week 4
Proof of Purchases -
**CanaKit Raspberry Pi 3 Complete Starter Kit - 32 GB Edition**
[Invoice](https://github.com/VinoU/Bar-QR-code-scanners/blob/master/Invoices/CanaKit%20Raspberry%20Pi3.pdf).
![alt text](https://github.com/VinoU/Bar-QR-code-scanners/blob/master/Pictures/IMG_3112.JPG)

**SunFounder Relay Module for Arduino 5V DC Trigger by Low**
[Invoice](https://github.com/VinoU/Bar-QR-code-scanners/blob/master/Invoices/Relay%20Moudle.pdf).
![alt text](https://github.com/VinoU/Bar-QR-code-scanners/blob/master/Pictures/IMG_3105.JPG)

**SunFounder Active Buzzer Sensor Module for Arduino and Raspberry Pi**
[Invoice](https://github.com/VinoU/Bar-QR-code-scanners/blob/master/Invoices/Buzzer.pdf).
![alt text](https://github.com/VinoU/Bar-QR-code-scanners/blob/master/Pictures/IMG_3096.JPG)
-------------
## October 02, 2017 - Week 3
I have created [my Budget Report](https://github.com/VinoU/Bar-QR-code-scanners/blob/master/Parts%20Budget%20Vino%20Uthayakumar%20-%20new.xlsx).
-------------
## September 25, 2017 - Week 2

I have Created [Gantt Chart schedule](https://github.com/VinoU/Bar-QR-code-scanners/blob/master/Vino%20Uthayakumar_Project%20Schedule.mpp).  

-------------
## September 18, 2017 - Week 1

 I have Created [proposal](https://github.com/VinoU/Bar-QR-code-scanners/blob/master/vino_%20proposal.xlsx).
-------------
## September 6, 2017 - Week 0

I have Created [repository](https://github.com/VinoU/Bar-QR-code-scanners).
-------------
## August 30, 2017 

# Welcome to my Blog!!!!!  
                                                 ## Repository created!

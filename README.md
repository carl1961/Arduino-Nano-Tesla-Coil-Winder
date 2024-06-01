# Arduino-Uno-Tesla-Coil-Winder
Tesla Coil Winder
Still Building this thing
Tested with fishing string .41mm and thread .15mm

https://rumble.com/v4y38a9-tesla-coil-winding-and-unwinding-machine.html

Software used is  Modified for Nextion enhanced 3.5 inch NX4832K035-011 screen I had
attached firmeware from Mr Innovative, I commented in the code from what I learned (I think)


Original code from Mr Innovative (for Nextion 2.8 TFT)

https://drive.google.com/file/d/1WY4mIK8XG3_ycVTErPh_xCwgQd9zHItr/view   Arduino

https://drive.google.com/file/d/1tuVQruj4Ivzi-zP1gk5Kpdj8jmSq7Bu4/view   HMI

Gsuite_v1.4_3.rar  Is programe to make coil to gcode, if you want to use 3dprinter software to run the Machine


![Tesla-Coil-Winder v1](https://github.com/carl1961/Arduino-Nano-Tesla-Coil-Winder/assets/3056821/7952a30b-9bc7-4718-9f06-ba07dac80ae2)

Shaft just slides into coupling, for easy removal to change cones.

![WIN_20240501_12_16_09_Pro](https://github.com/carl1961/Arduino-Nano-Tesla-Coil-Winder/assets/3056821/8800b027-e95f-400f-a28a-eb251b1f56a7)


![WIN_20240501_12_17_50_Pro](https://github.com/carl1961/Arduino-Nano-Tesla-Coil-Winder/assets/3056821/345c564f-b55a-48c3-8330-f9bcad520949)

For Fusion 360 
https://www.thingiverse.com/thing:6604070

I have tryed every software out there and they have issues. mainly they only work when tuned in to one setting, and they get bragged on real BIG for their video's

Then I found Found a Excellant Program for the  Arduino-Uno-Tesla-Coil-Winder, rduart, doing a Awesome work      https://github.com/rduart/TelsaCoilWinder
I did have to dial it in to work with the 2mm pitch leadscrew setup. and added some background pictures, and enlarged the font for my eye's.
Still so far only testing with .4mm nylon fishing string.

START


![Start](https://github.com/carl1961/Arduino-Uno-Tesla-Coil-Winder/assets/3056821/8107b871-5e3e-4198-af6a-a6146f2c71fd)

Machine Setup

![Machine Setup](https://github.com/carl1961/Arduino-Uno-Tesla-Coil-Winder/assets/3056821/8c159a38-25c6-4977-8cde-5c0ac30ff911)

Coil Setup

![Coil Setup](https://github.com/carl1961/Arduino-Uno-Tesla-Coil-Winder/assets/3056821/f5d5ab21-07d2-425c-92db-1cc7258c7cca)

Control

![Control](https://github.com/carl1961/Arduino-Uno-Tesla-Coil-Winder/assets/3056821/7b48db6d-91cd-4f84-bd72-b65752a4dd34)


![331854834-7b1ee994-3767-4d57-8e13-8b2f83012a42](https://github.com/carl1961/Arduino-Uno-Tesla-Coil-Winder/assets/3056821/0cdb0ec3-4359-4cac-94d1-3e2dca023736)

![331854813-9d2d7ce8-59d7-4b9d-a038-71b6939ca693](https://github.com/carl1961/Arduino-Uno-Tesla-Coil-Winder/assets/3056821/a4eec5c2-acf5-4f93-937c-e8667117181e)

![331854786-a8c9cd06-c252-4e9a-81ed-586bc999cc4b](https://github.com/carl1961/Arduino-Uno-Tesla-Coil-Winder/assets/3056821/c95f3893-0a6c-421b-ae97-a4a0ce4a612f)

Added Stepper controlled Spool Winder, can also be used a tenstioner, by appling varable control voltage of 0 - 2 Volts on one of the coil windings 2 Volts likly too much.

![Tesla-Coil-Winder v82](https://github.com/carl1961/Arduino-Uno-Tesla-Coil-Winder/assets/3056821/be5c8732-8e61-49ce-ab19-09241d2631bc)



# UnWinder

Software used to drive Stepper  polihedron przemu custom Program made for Unwinder
[https://github.com/polihedron/TM1637_Timer_RPM-stepper_motor](https://github.com/carl1961/TM1637_RPM-stepper_motor)

Schematic ( in   File on GitHub )

![image](https://github.com/carl1961/Arduino-Uno-Tesla-Coil-Winder/assets/3056821/b4ae8239-c6f6-4209-8ba8-ed9964261e0b)   




I used a Ardunio Nono Terminal shield, Stepper Driver Module, KY-040 Encoder Module, TM1637 Display  and a Stepdown 5V Module wired as in Schematic.
I did not use any capacitors as shown in Schematic, Just all modules.

![Screenshot 2024-05-22 152216](https://github.com/carl1961/Arduino-Uno-Tesla-Coil-Winder/assets/3056821/90fcdc0b-48b8-47a4-b5c4-055a612d1180) 

![Screenshot 2024-05-27 062302](https://github.com/carl1961/Arduino-Uno-Tesla-Coil-Winder/assets/3056821/60b07cd1-3177-441c-ab5c-0b2e625b008b)

![image](https://github.com/carl1961/Arduino-Uno-Tesla-Coil-Winder/assets/3056821/d31ee118-24e4-4c4b-be27-ac5a8ee6f0a7) 

![image](https://github.com/carl1961/Arduino-Uno-Tesla-Coil-Winder/assets/3056821/0083b597-abfe-46e4-b754-2c03d6a55c75)

![image](https://github.com/carl1961/Arduino-Uno-Tesla-Coil-Winder/assets/3056821/70576122-0e5a-41c0-8583-ad2850285f1b) 

![image](https://github.com/carl1961/Arduino-Uno-Tesla-Coil-Winder/assets/3056821/ca4c8117-bc4f-4e52-81d2-822669c833e8)




![WIN_20240528_12_57_33_Pro](https://github.com/carl1961/Arduino-Uno-Tesla-Coil-Winder/assets/3056821/77e91386-08f3-4136-b56a-a97a74eafa37)


![WIN_20240528_12_57_19_Pro](https://github.com/carl1961/Arduino-Uno-Tesla-Coil-Winder/assets/3056821/449cb2e7-67de-4ec1-a94c-9815c50f52a7)

![WIN_20240528_12_57_45_Pro](https://github.com/carl1961/Arduino-Uno-Tesla-Coil-Winder/assets/3056821/2386d210-55d8-4fb2-a7d0-33c5a70617b6)

![WIN_20240528_13_02_17_Pro](https://github.com/carl1961/Arduino-Uno-Tesla-Coil-Winder/assets/3056821/18d9d03c-125e-45b5-a782-1aac466026c9)


# Wire tensioner Parts

2 channel 12v relay To completly disconnect Stepper 2 wires from Stepper coil attached to Driver Module,(If you don't it feeds back to Ardunio Nano and does weird stuff (seems like a reset).
12V to trigger Relays attached on Arduino Switching Side, on driver module motor voltage terminals. (Schematic comming soon).

![image](https://github.com/carl1961/Arduino-Uno-Tesla-Coil-Winder/assets/3056821/2e6bf50b-72d3-4b36-84d2-f5284c3f9de9)

A DC motor Controller I already had.

![5149JcvP2oL _AC_SL1100_](https://github.com/carl1961/Arduino-Uno-Tesla-Coil-Winder/assets/3056821/b694d6c5-ab77-40e2-9838-9ea87d2e087f)


![WIN_20240528_13_50_57_Pro](https://github.com/carl1961/Arduino-Uno-Tesla-Coil-Winder/assets/3056821/96112b23-b7a0-4a2e-8323-bcb60300dc04)


![WIN_20240528_13_49_55_Pro](https://github.com/carl1961/Arduino-Uno-Tesla-Coil-Winder/assets/3056821/4adf3578-d98b-4245-8fcc-53f36682bf29)


First Coil, after many test runs and fine tuning the winding machine. Using rduart, Awesome Program. Already slaped one coat of varnishing.


![first coil](https://github.com/carl1961/Arduino-Uno-Tesla-Coil-Winder/assets/3056821/86059fae-5b82-40db-8f89-89f3abab0278)



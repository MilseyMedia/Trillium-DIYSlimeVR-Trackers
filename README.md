# Trillium DIY SlimeVR Tracker

After my experiences with the DIY Arctic SlimeVR trackers I wanted to build a version for my personal use case scenario

This pcb is designed to use female header pins on the ESP8266 and IMU so parts can we swap out those parts in event of Updated IMU's or defective ESP32's


## Trillium 18650 tracker with extension

![Trillium 18650 assembled](https://github.com/user-attachments/assets/225075f9-a52e-4d4f-893d-219cb48c5408)

![Trillium 18650 disasembled](https://github.com/user-attachments/assets/6cc425b1-5748-4a64-a43f-071cd29bdce4)

<img width="383" height="363" alt="Trillium 18650 PCB layout" src="https://github.com/user-attachments/assets/dc6067dd-3c03-409c-bdfd-2fdc8de107bc" />


## Full body set of 8 trillium 14500 trackers

![Trillium 8 tracker set](https://github.com/user-attachments/assets/9e0e6437-6b27-4b28-88cc-94182e61f8f9)

<img width="461" height="618" alt="Trillium 14500 PCB layout" src="https://github.com/user-attachments/assets/c6bec962-3b64-48e3-b9e3-108513fe3b75" />


### Trillium 14500 soldering livestream guide
https://www.youtube.com/live/_fhmWKOj-kA?si=LMQn1sJzI0ec3_Id

> Trillium 18650 soldering livestream guide (Coming soon!)


## Parts List
- ESP8266
- IMU (LSM6DSV, ICM45686, BNO085, BNO08X)
- 14500 or 18650 battery with pin through holder
- TP4056 usb C charging module 
- MSS22D18 2P2T 6Pin switch
- 2.54mm female and male header pins
- 2.54 Pre Crimped Male and Female Dupont cables + Connectors kit
- JST ZH 1.5MM 7 Pin connector
- 180k Resistor
- 1N5817 Diode
- 30mm x 400mm Stretchy Velcro straps

## Firmware Flashing guide
- in a Google Chrome, Edge or Opera browser go to https://slimevr-firmware.bscotch.ca
- Under firmware
> select SlimeVR 0.5.4
- Under board type
> Select Wemos D1 mini
- Select your main and extension IMU types depending on which chips you have connected
- Enter the wifi settings for your router
- Plug in your tracker via the esp32 micro controller and click "Flash to Device"

<img width="818" height="506" alt="Screenshot 2026-02-26 at 12 26 00 AM" src="https://github.com/user-attachments/assets/e4ef1a6a-ddaf-41c8-9116-90677243b895" />

<img width="655" height="452" alt="Butterscotch config marked up" src="https://github.com/user-attachments/assets/b9ec0113-eaf7-45c8-a4ca-45ed1e9c74f8" />

Be sure to set the INT imu extension pin to D7

<img width="672" height="426" alt="Butterscotch Flash to device button" src="https://github.com/user-attachments/assets/44d0cbb4-b6e0-40ae-b903-7ecb5d1f092e" />

<img width="715" height="549" alt="Butterscotch device connection menu" src="https://github.com/user-attachments/assets/22ee2291-d2cd-475d-b656-a49ddc278692" />

## Connection to the SlimeVR Server

Download The SlimeVR Server app (available on Github at: https://github.com/SlimeVR/SlimeVR-Server/releases)

When you connect your SlimeVR tracker via USB-C to the Esp32 USB port directly, the SlimeVR Server should be able to detect your tracker

<img width="952" height="595" alt="SlimeVR Server Device Connected" src="https://github.com/user-attachments/assets/a78aa28e-ff05-4b9b-9ef5-1208245694ab" />

If not, click the “Set up Wizard” icons on the left side of the window

<img width="778" height="485" alt="SlimeVR Set up wizard Red arrow" src="https://github.com/user-attachments/assets/d4798c7f-5d04-4ae3-a0bf-6c8e79a88795" />

Enter the wifi credentials for your 2.4Ghz wifi network (or your travel router if over 10 trackers are being used)

<img width="808" height="314" alt="SlimeVR Server Wifi info" src="https://github.com/user-attachments/assets/cf5687ca-5496-469c-b47b-7163e4ed140d" />

Make sure the DIYSlimeVR Tracker is powered on after it is plugged in, so it stays in the Slime VR server.

<img width="550" height="346" alt="SlimeVR connect trackers screen" src="https://github.com/user-attachments/assets/47e5ab46-1d0c-4b91-b5db-66207b83d856" />

*** An initial tracker reboot may be required if the connection doesn’t work on the first try ***

If you move your tracker, you should now see it highlighted in the SlimeVR Server when rotation is detected. 

<img width="960" height="604" alt="SlimeVR Server Trillium connected moving" src="https://github.com/user-attachments/assets/3d62ec5e-d312-4610-9de6-b0df22dbc4dc" />









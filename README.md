# Trillium DIY SlimeVR Tracker

After my experiences with the DIY Arctic SlimeVR trackers I wanted to build a version for my personal use case scenario

This pcb is designed to use female header pins on the ESP8266 and IMU so parts can we swap out those parts in event of Updated IMU's or defective ESP32's


## Trillium 18650 tracker with extension

![Trillium 18650 assembled](https://github.com/user-attachments/assets/225075f9-a52e-4d4f-893d-219cb48c5408)

![Trillium 18650 disasembled](https://github.com/user-attachments/assets/6cc425b1-5748-4a64-a43f-071cd29bdce4)

<img width="383" height="363" alt="Trillium 18650 PCB layout" src="https://github.com/user-attachments/assets/dc6067dd-3c03-409c-bdfd-2fdc8de107bc" />


## Full body set of 8 Trillium 14500 trackers

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


## Quest (2 or 3) Standalone Set up
Video Guide from Zrock35: https://www.youtube.com/watch?v=NSsoi9bfH0I

What you’ll need:
- Any Mac / Windows laptop or computer with a usb port (gaming PC not required)
- USB C cable for headset and wemos board
- Quest Headset of choice
- SlimeVR Tracker
- SideQuest: https://sidequestvr.com/setup-howto
- Amaze File Manager : https://github.com/TeamAmaze/AmazeFileManager/releases/tag/v3.10
- SlimeVR APK: https://github.com/SlimeVR/SlimeVR-Server/releases
- MobileVR Station: https://www.meta.com/experiences/mobile-vr-station/3887008398005125/?srsltid=AfmBOopr1JRcwfAU0Mtvg5ox1js5XmIhiaDPNUFCYCYtu7o5BD2dGJ66

***Before setting this up, it is assumed that you have already connected your Slime Trackers to your wifi router. Setting up wifi credentials on your headset is currently not possible***

## Meta Developer Account Registration
Video Guide Referenced: https://www.youtube.com/watch?v=K3p3P3fCeHo
Go to https://developers.meta.com/horizon/ and log in with the same account used on the Meta Quest headset

<img width="1022" height="541" alt="Meta developer account home page" src="https://github.com/user-attachments/assets/6534e0ea-d0c5-4cac-93d6-0aa580c9c129" />

There Maybe a pop up regarding 2FA. Please fill this out. 

On the top right of the window click the <img width="127" height="112" alt="Fork" src="https://github.com/user-attachments/assets/37990b27-6dac-4790-ba60-dd27d9e18195" /> to bring up "Create organization" <img width="394" height="107" alt="Create organization" src="https://github.com/user-attachments/assets/7b50d226-a587-4a7b-a3e7-d814390145e9" />

Fill out your organization name → Accept the Terms & Conditions → Submit

<img width="1338" height="662" alt="Meta quest create organization" src="https://github.com/user-attachments/assets/12d7d33d-15e0-48bf-bef1-82937c330837" />


Ok, accept, steal my data, harvest my kidneys /j

<img width="775" height="539" alt="Meta NDA agree window" src="https://github.com/user-attachments/assets/27bdc02a-5b10-411f-8dc6-1253c3285852" />

You should now be able to enable developer mode on your headset

## Enabling Developer Permissions on the Quest Headset

click the Meta Quest logo and then settings

<img width="660" height="303" alt="Meta quest navigator button" src="https://github.com/user-attachments/assets/025e9eff-b508-4e53-8f57-e2c96398cca5" />

<img width="1005" height="770" alt="Meta quest navigator menu" src="https://github.com/user-attachments/assets/8907a411-676d-4ccb-a374-19df02c17031" />

Use the joystick or trigger to scroll down to Advanced → Developer → Enable Developer Settings

<img width="815" height="700" alt="Enable developer settings menu headset" src="https://github.com/user-attachments/assets/581db261-dafb-4763-af09-2a081cb0adb8" />

## Desktop SideQuest & APK files Installation

Video Tutorial from Piepop101
https://www.youtube.com/watch?v=3PsYdVUpQdk.

- Download and install SideQuest on a MacBook or Windows computer

<img width="962" height="565" alt="Sidequest home page red arrow" src="https://github.com/user-attachments/assets/d9842020-e2cf-4857-829b-d90cfe67906a" />

- Connect your headset via USB-C.

- Click on the box with the arrow pointing down to install the Amaze and SlimeVR Apk’s.


## MobileVR Station APK installation

Now, you may be saying, “If we already have MobileVR Station, why do we need Amaze?” 

***Mobile VR Station is very sensitive to input button triggers and is generally a buggier / soon-to-be-outdated application compared to Amaze due to sanctions from Meta. As of V78.1028, this method is currently still functioning, but can quickly become broken with a future update. This is why I have also included desktop APK instructions as a failsafe.*** 

From the MetaQuest Store, install Mobile VR Station: https://www.meta.com/experiences/mobile-vr-station/3887008398005125/

<img width="832" height="735" alt="Mobile VR station app" src="https://github.com/user-attachments/assets/606b1474-b3b7-4941-be9b-40118fc63e85" />

Once inside of MobileVR Station go to 

Configuration Wizard → Show All Options → Configure Manage All Files → Open Files All

<img width="737" height="616" alt="Mobile VR station config wizard" src="https://github.com/user-attachments/assets/da28728a-66b3-4832-ba09-ff93a5ccc158" />

<img width="376" height="677" alt="MobileVR remaining windows" src="https://github.com/user-attachments/assets/b1a98d5a-08eb-4349-b97e-8b0be0983943" />

If you can not see your files click “Enable Manage All Files”

You should then be taken to a screen showing your device’s files and downloads

<img width="891" height="702" alt="Headset file viewer menu" src="https://github.com/user-attachments/assets/1f665fa1-a521-48d1-b51d-167d6e9d394d" />

Accept any necessary storage permissions that the headset requests. This will allow us to install files from GitHub / the internet. 

<img width="923" height="789" alt="Settings pop up file viewer" src="https://github.com/user-attachments/assets/6b5487b5-deb9-4136-b999-478346a24433" />

<img width="782" height="841" alt="install from unknown apps toggle" src="https://github.com/user-attachments/assets/7f153b1f-2fa5-441b-9dea-97950c1ce1d5" />

After this simply click on the app again with the controllers rear trigger and follow the on screen prompts to install it

<img width="418" height="691" alt="Amaze installing" src="https://github.com/user-attachments/assets/dd5046b6-3cca-4f83-be2d-091625fc7fbd" />

Amaze is an open-source file manager that will allow you to update the SlimeVR server app directly from the headset in the future. Click Done to exit the pop-up window. 

To install or update SlimeVR locally on the headset, open Amaze and scroll down to the APK file after downloading the latest version of SlimeVR and uninstalling the old one from the headset. 

<img width="1033" height="777" alt="Unknown sources button" src="https://github.com/user-attachments/assets/822db116-dea3-449b-861d-48b8ac10dd12" />

<img width="479" height="758" alt="Amaze install directions first two pannels" src="https://github.com/user-attachments/assets/4e6b1475-627e-4416-8fbe-204416866621" />

<img width="831" height="628" alt="Just once pop up amaze" src="https://github.com/user-attachments/assets/15b95ef8-405e-4a70-ac54-d5c3ebc11a3e" />

There will be an additional pop-up asking permission to download the SlimeVR application. Please accept them.

Launch the SlimeVR Server and enter your wifi or travel router credentials. 

<img width="774" height="695" alt="SlimeVR Server welcome screen" src="https://github.com/user-attachments/assets/93405733-73f0-4e92-8043-2edd8d9adee0" />

After this, you should be able to turn on your SlimeVR trackers and have them connect to the same wifi network as the VR headset running the Slime VR APK. Make sure that only one instance of the SlimeVR is running on your network at once (ex., not on laptop and headset at the same time)


## Blender Motion Capture 

What You’ll Need:
- Vroid Studio: https://vroid.com/en/studio
- Blender 5.0: https://www.blender.org/download/
- VMC4B ($9.44 CAD): https://booth.pm/ja/items/3432915
- SlimeVR Server: https://github.com/SlimeVR/SlimeVR-Server/releases

## VRM Model Export
Once your Avatar in Vroid Studio is created Click <img width="98" height="87" alt="Upload arrow" src="https://github.com/user-attachments/assets/b25ecbd1-ad43-4bcd-915a-d877aeb5d1ed" /> to pull up the export window for your character model

 Click Export as VRM
 <img width="405" height="323" alt="Export as VRM window" src="https://github.com/user-attachments/assets/ec16e72b-c0af-45fc-88c5-30ce16d41e4c" />

 <img width="971" height="549" alt="VRM avatar window arrow" src="https://github.com/user-attachments/assets/107e100b-a879-4a1b-9275-0a12cda26f80" />

<img width="620" height="360" alt="Vroid studio export window pt 2" src="https://github.com/user-attachments/assets/e8dc22b2-76b2-4dd7-9d19-53dbba6df8f7" />
Click the blue export button on the right side of the window 

Be sure VRM0.0 is Selected and fill out the title / creator fields 
<img width="808" height="695" alt="Export settings screen VRM settings" src="https://github.com/user-attachments/assets/b4f03915-cdf3-44b4-86f6-c74fbb96dc9c" />

Once you're done filling out your name and the file name, you can click “Export” and have your file saved to your computer as a .VRM file
<img width="527" height="268" alt="Screenshot 2026-02-26 at 10 46 01 PM" src="https://github.com/user-attachments/assets/8d86aa2a-d9b6-4569-a01b-e8177d4f5633" />


## SlimeVR Server Live Mocap 

In The SlimeVR Server go to settings 

<img width="605" height="379" alt="SlimeVR settings arrow" src="https://github.com/user-attachments/assets/0e53e770-8604-4923-831c-64db22645a6b" />

Next Click on the “VMC” Text bar

<img width="1262" height="759" alt="VMC settings page" src="https://github.com/user-attachments/assets/02f58f6c-4f8a-43a3-9fd3-4bb5b69c0c64" />

Upload your VRM model, designed in Vroid Studio, here to ensure that the forward kinematic bones match. Also, make sure that your Ports and Network address match the same credentials in Blender. 


## Setting up VMC4B in Blender

Edit -> Preferences -> Addons -> and install the VRM format addon

<img width="874" height="660" alt="Blender VRM format addon" src="https://github.com/user-attachments/assets/21e15ca7-0290-4d2d-9c24-23474288b203" />


If the download from booth shows up as a folder, please compress it into a zip file

Drag and drop the zip file into blender to install it

<img width="756" height="582" alt="install from disk pop up" src="https://github.com/user-attachments/assets/4af49005-a0c7-4688-a123-68d3b9b1990d" />


<img width="216" height="190" alt="VMC4B blender window" src="https://github.com/user-attachments/assets/5c4f49c5-c37b-47eb-8e8a-ec490e084955" />

Click connect to confirm that data is being received from the SlimeVR server

Make sure the ip adress and ports in / out match up with blender

Results:
https://www.youtube.com/watch?v=_LgbQjhLgG8

<img width="1412" height="1334" alt="Milsey SlimeVR character kick" src="https://github.com/user-attachments/assets/015647a4-be22-4886-85d1-b4e9e6a70fc2" />




































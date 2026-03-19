# Trillium DIY SlimeVR Tracker

This PCB was designed so I could have a modular wrist and hand tracker that could easily be travelled with. Also used with the [Fireweed Flex Sensor Glove](https://github.com/MilseyMedia/Fireweed-DIYSlimeVR-Flex-Gloves)


## Trillium 18650 tracker with extension

![Trillium 18650 with bottom tray](https://github.com/user-attachments/assets/9f5b340f-3067-4bcb-90d8-980a38e19d0d)

![Trillium 18650 disasembled](https://github.com/user-attachments/assets/6cc425b1-5748-4a64-a43f-071cd29bdce4)

<img width="383" height="363" alt="Trillium 18650 PCB layout" src="https://github.com/user-attachments/assets/dc6067dd-3c03-409c-bdfd-2fdc8de107bc" />


## Full body set of 8 Trillium 14500 trackers

![Trillium 8 tracker set](https://github.com/user-attachments/assets/9e0e6437-6b27-4b28-88cc-94182e61f8f9)

<img width="461" height="618" alt="Trillium 14500 PCB layout" src="https://github.com/user-attachments/assets/c6bec962-3b64-48e3-b9e3-108513fe3b75" />


### [Trillium 14500 soldering livestream guide](https://www.youtube.com/live/_fhmWKOj-kA?si=LMQn1sJzI0ec3_Id)

> Trillium 18650 soldering tutorial streaming March 2026


## Parts List
- [ESP8266 USB-C version](https://www.aliexpress.com/item/1005007877904928.html?spm=a2g0o.order_list.order_list_main.10.13be1802HgETiE)
- IMU (LSM6DSV, ICM45686, BNO085, BNO08X)
- 14500 or 18650 battery with pin through holder
- [TP4056 USB-C charging module](https://www.aliexpress.com/item/32649780468.html?spm=a2g0o.order_list.order_list_main.50.13be1802HgETiE) 
- [MSS22D18 2P2T 6Pin switch](https://www.aliexpress.com/item/4000699849055.html?spm=a2g0o.productlist.main.1.41aa6d8aSzOAC4&algo_pvid=0c0f082c-a444-4a1e-ba30-c9aa43c2c727&algo_exp_id=0c0f082c-a444-4a1e-ba30-c9aa43c2c727-0&pdp_ext_f=%7B%22order%22%3A%2238%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21CAD%215.00%214.05%21%21%213.57%212.89%21%40210328df17726608201306737eea9a%2110000006192024429%21sea%21CA%211616760453%21X%211%210%21n_tag%3A-29919%3Bd%3A16d45553%3Bm03_new_user%3A-29895&curPageLogUid=wtDTKdXzcQws&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A4000699849055%7C_p_origin_prod%3A)
- [2.54mm female and male header pins](https://www.amazon.ca/Glarks-Straight-Connector-Assortment-Prototype/dp/B076GZXW3Z/ref=sr_1_1_sspa?crid=1F5HH5P9G9L88&dib=eyJ2IjoiMSJ9.TjZF0QBunFjT26SU9773UD2hgOS2woq0mgpehM-NIKy0V6c8JdizhsFmLFRs7Y_jxlFxUztN0teE8DT8oWCxGbgVASyACmYCluQU6fSojoR0BQIEMohuY0NLzc71G022ffutjDqo7BgS8VLZ_swpRCRuDSfTmgJucqK1tB5XLdhwmk40ncnR5hoOPM0eGA2HVnUCIrZa_umHOz0rs1uR6eRYj8daQCCQDO_Oo-wH1Mj8cI5F-Lpkcoq_npY8x_HfgaSnVguYkmuWvixLWKqFKqsRZZq09hhjfhCalpDvTNA.BEdFa2kkjL4L2uupkoxIJ3ZbaKjK5BBVc6-Ie2XX61A&dib_tag=se&keywords=female+header+pins&qid=1772661010&sprefix=female+header+pins%2Caps%2C148&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1)
- [2.54 Pre Crimped Male and Female Dupont cables + Connectors kit](https://www.amazon.ca/dp/B07S743PLP?ref=ppx_yo2ov_dt_b_fed_asin_title)
- [JST ZH 1.5MM 7 Pin connector](https://www.aliexpress.com/item/1005006918030218.html?spm=a2g0o.productlist.main.5.54b93LKf3LKfZH&algo_pvid=6d7cedda-086a-455d-9676-f43d9aa4318f&algo_exp_id=6d7cedda-086a-455d-9676-f43d9aa4318f-4&pdp_ext_f=%7B%22order%22%3A%22453%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21CAD%212.58%212.50%21%21%2112.73%2112.32%21%4021033d1217726650921082797e5154%2112000038722445974%21sea%21CA%211616760453%21X%211%210%21n_tag%3A-29919%3Bd%3A16d45553%3Bm03_new_user%3A-29895&curPageLogUid=U5LQq4tWU5pQ&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005006918030218%7C_p_origin_prod%3A)
- [180k Resistor](https://www.aliexpress.com/item/1005002994755806.html?spm=a2g0o.order_list.order_list_main.85.13be1802HgETiE&gatewayAdapt=4itemAdapt)
- [1N5817 Diode](https://www.aliexpress.com/item/1005001552094086.html?spm=a2g0o.order_list.order_list_main.90.13be1802HgETiE&gatewayAdapt=4itemAdapt)
- [30mm x 400mm Stretchy Velcro straps](https://www.aliexpress.com/item/1005006869319882.html?spm=a2g0o.order_list.order_list_main.100.13be1802HgETiE)

## PCB ordering Guide
<img width="1219" height="779" alt="JLCPCB ordering guide" src="https://github.com/user-attachments/assets/a3c8c45a-3c43-4293-b2f4-e26773d8859c" />

Using JLCPCB, click "order now" and drag the Gerber zip file from the repository into the file drop location.

- 1.6mm board width
- Lead-free HASL
- FR-4 Base Material



## Firmware Flashing guide
- Download the latest SlimeVR server app on mac, PC, or Linux at https://slimevr.dev
- Settings -> Utilities -> DIY firmware Tool
- Select SlimeVR main, ESP32 Wemos D1 mini, and firmware 0.7.2
<img width="1724" height="982" alt="DIY Firmware Tool step 1" src="https://github.com/user-attachments/assets/d2d40f2b-4cf3-4598-b605-c508653f1dd9" />
- Select your main and extension IMU types depending on which chips you have connected. For the Trillium Trackers, be sure to set the extension pin to D7
<img width="1718" height="973" alt="DIY Firmware Tool Step 2" src="https://github.com/user-attachments/assets/3a09cda0-9e95-4576-a191-264747820034" />
- Enter the wifi settings for your router
- Plug in your tracker via the ESP32 microcontroller and click "Flash to Device"
<img width="1711" height="973" alt="DIY Firmware tool Step 3" src="https://github.com/user-attachments/assets/48bb1fb6-f86a-43d3-8f8a-03c15a7f66ba" />


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
- SlimeVR APK: https://github.com/SlimeVR/SlimeVR-Server/releases

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

Click the Meta Quest logo and then settings

<img width="660" height="303" alt="Meta quest navigator button" src="https://github.com/user-attachments/assets/025e9eff-b508-4e53-8f57-e2c96398cca5" />

<img width="1005" height="770" alt="Meta quest navigator menu" src="https://github.com/user-attachments/assets/8907a411-676d-4ccb-a374-19df02c17031" />

Use the joystick or trigger to scroll down to Advanced → Developer → Enable Developer Settings

<img width="815" height="700" alt="Enable developer settings menu headset" src="https://github.com/user-attachments/assets/581db261-dafb-4763-af09-2a081cb0adb8" />


## On headset installation

Access the SlimeVR Android APK file at: https://github.com/SlimeVR/SlimeVR-Server/releases

Once downloaded, go to your on-device file manager and select package installer 

<img width="278" height="247" alt="Package installer for slimevr server apk" src="https://github.com/user-attachments/assets/9a38c487-fd01-48ab-a337-e5325a61e945" />

Click "install" and then "Done

<img width="242" height="323" alt="SlimeVR headset install" src="https://github.com/user-attachments/assets/452b80ed-be08-4894-bd87-276c6ced9e9b" />

<img width="233" height="305" alt="SlimeVR Headset Done" src="https://github.com/user-attachments/assets/34067dfd-8e1a-4e0a-a082-8e486e80d440" />


## Desktop SideQuest & APK files Installation

Video Tutorial from Piepop101
https://www.youtube.com/watch?v=3PsYdVUpQdk.

- Download and install SideQuest on a MacBook or Windows computer

<img width="962" height="565" alt="Sidequest home page red arrow" src="https://github.com/user-attachments/assets/d9842020-e2cf-4857-829b-d90cfe67906a" />

- Connect your headset via USB-C.

- Click on the box with the arrow pointing down to install the Amaze and SlimeVR Apk’s.


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


File -> Import -> .VRM

<img width="480" height="555" alt="VRM import guide blender" src="https://github.com/user-attachments/assets/eaef5a13-8e0c-46ce-8d72-40a50ef43bd2" />

<img width="1408" height="848" alt="VRM armature selection" src="https://github.com/user-attachments/assets/e4b37a94-fb08-4ca1-90cd-b0c10c196048" />

Click the bone to select it, then open up your side panel in Blender by pressing N on your keyboard. Select the "Armature" option from the drop down menu

<img width="216" height="190" alt="VMC4B blender window" src="https://github.com/user-attachments/assets/5c4f49c5-c37b-47eb-8e8a-ec490e084955" />

Click connect to confirm that data is being received from the SlimeVR server

Make sure the ip adress and ports in / out match up with Blender

Results:
https://www.youtube.com/watch?v=_LgbQjhLgG8

<img width="1412" height="1334" alt="Milsey SlimeVR character kick" src="https://github.com/user-attachments/assets/015647a4-be22-4886-85d1-b4e9e6a70fc2" />




































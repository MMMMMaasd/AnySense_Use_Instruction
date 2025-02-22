# How to Use AnySense 
## Last Updated: February 21, 2025
AnySense is a multisensory data collection app that enables you to record the data of RGB videos, depth videos, Bluetooth touch sensor, camera position and orientation, audio, etc. We also provide a USB streaming option so you can stream AnySense data via a USB cable to your computer. 

To start/stop recording an AR 3D video, go to the "Record" tab and press the bottom middle toggle button. 

### 1. Export, AutoSave, Delete AnySense Recorded Data
After you finish your record via toggle the button, all the data recorded at the same time will be automatically saved to your phone's storage. You can find it by going to Files-Browse-On My iPhone, the AnySense root saved data folder will be automatically created there for you. Data of your last recording will be saved as a new folder with the name of your start record time, there will be an AR RGB video file(.mp4), AR depth video file(.mp4), AR camera pose file(.txt), Tactile sensor touch data(.txt), and two folders for images of each of the video frame of your record. 

For your convenience, if you are not satisfied with the record you just did, in the "read" view, you can click the "Delete the last record" button to delete the entire new folder of the data that you just recorded. 

You can click the "Export to local" button to manually save your last recorded data into any position in want in your iPhone, however, your last recorded data folder will still be automatically saved to the AnySense folder.

### 2. Bluetooth Connection
You can go to the "ble-device" (ble means Bluetooth Low Energy) tab to check all the bluetooth peripherals that AnySense scanned with, you can click connect to that peripheral via Bluetooth, after connecting to a bluetooth device, and your top bar of the AR camera will demonstrate the connection status. Be careful, Bluetooth connection affordance in AnySense is only used for connecting with AnySense (). Only the data transmitted by AnySkin after being connected can be received by AnySense. AnySense will not receive data from other Bluetooth peripherals/devices except AnySense. 

### 3. USB Streaming Mode
You can switch to the USB mode in the "Live RGBD Streaming" option. Now you can stream AnySkin data to your computer via USB cable. After connecting your iPhone to your computer via USB cable, you can click the record toggle button in the bottom middle and run our demo script demo-main.py on your computer by using the command "python demo-main.py" in your terminal. 

### 4. Settings
In your settings, we provide the affordance of switching the streaming option between USB and normal AR camera recording, The Wi-Fi streaming option is unavable and still in development now. 

You can adjust the haptic feedback for all the buttons in AnySense, to improve your app and data collection experience

You can project grid lines to your camera to help your recording process, we provide you the option to project either a 3x3 grid line or 5x5 grid line option

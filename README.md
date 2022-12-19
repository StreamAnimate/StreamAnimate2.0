
![Logo](https://images2.imgbox.com/07/dd/4MhgLGy5_o.png)


# Stream Animate (Beta)


## Requirements
- **OBS 27 or OBS 28**
#### **Support Operating Systems -**
- **Currently Windows Only** - It has only been tested on Windows 10. I plan to test Windows 11 soon and if there is sufficent demand I will make it compatible with Mac OS and Linux

#### **obs-websocket Plugin - (does not currently support obs-websocket 5.0 or above)**
- **For OBS 27** - Tested and working version found here: [obs-websocket 4.9.1](https://github.com/obsproject/obs-websocket/releases/tag/4.9.1)
- **For OBS 28** - You will need to install a legacy version of obs-websocket plugin until I update it to work natively with OBS 28. Tested version can be found here: [obs-websocket 4.9.1-compat (OBS 28+/Qt6)](https://github.com/obsproject/obs-websocket/releases/tag/4.9.1-compat)
#### **StreamFX Plugin-  (required for certain filter options)**
- **For OBS 27** -Tested and working version found here: [StreamFX 0.11.1](https://github.com/Xaymar/obs-StreamFX/releases/tag/0.11.1)
- **For OBS 28** - This version of StreamFX is not produciton ready, so use at own discretion. Found here:  [StreamFX 0.12.0 Alpha 117](https://github.com/Xaymar/obs-StreamFX/releases/tag/0.12.0a117)

## Install
 ####  **DOWNLOAD and extract StreamAnimate.0.5.Beta.zip file found here:** [Stream Animate 0.5.0 (Beta)](https://github.com/StreamAnimate/StreamAnimate2.0/releases/tag/v5.0-Beta)

 ####  **Install obs-websocket plugin and StreamFX Plugin  - (see above)** 

 ####  **Launch Stream Animate** 
 - **Found in downloaded folder** - */Stream Animate 0.5 Beta/Stream Animate/Stream Animate.exe*
- **Create a New Collection** - Type a name for the collection and click *Start*
![App Screenshot](https://i.ibb.co/g931HrR/06f3dfd0d0588d5510b5731a733b4f14.png)

>
---

 ####  **Launch OBS and make sure obs-websocket is server is enabled** 
- **For OBS 27** - Tools > *Websocket Server Settings*
- **For OBS 28** - Tools > *Websocket Server Settings (4.x Comp)* 
>
![App Screenshot](https://i.ibb.co/FD0brKb/1d0fd46a64757884e942f7e7056e1f43.png)
>
---

#### **Make sure the Python Install Path has been loaded** (found in downloaded folder)

- **OBS** -  Tools > Scripts > *Python Settings* Tab > Browse > Navigate to *Python36* Folder
![App Screenshot](https://i.ibb.co/k1fnZKf/python-install.png)
>
---

#### **Load Python Script *StreamAnimateScript* in OBS** (found in downloaded folder)
- **OBS** - Tools > Scripts > *Scripts* Tab > Click + Symbol > Navigate to *StreamAnimateScript1-1.py*

![App Screenshot](https://i.ibb.co/wRm5QpS/ezgif-4-2c84fa01fb.gif)
>
---
#### **Connect Stream Animate with OBS Script**
- **Stream Animate** - Settings > Copy *Software Folder Location*
- **OBS** - Paste into the textbox with the *StreamAnimateScript* selected
- **OBS** - Right Click *StreamAnimateScript1-1.py* and click *Reload* (or click &#10227;)

![App Screenshot](https://i.ibb.co/r2CgCXw/ezgif-4-a8365a6a9f.gif)
>
---
#### **Connect Stream Animate to obs-websocket**
- **Stream Animate** - Settings > Enter Websocket values (found in OBS >Tools > *Websocket Server Settings*)
- **Click Start** - If correctly setup you should get a popup saying 'Succesfully Connected'
![App Screenshot](https://i.ibb.co/qjJKrLd/a33cc94770e37173c3b33320f562b1bf.png)
>
---
#### **Remember to save any changes made in Settings** (Bottom right of the window)
![App Screenshot](https://i.ibb.co/tQ6qy5z/cccd11e1cfa1f1cc7d8e271ba5b07f8f.png)

>
---
#### **If StreamFX has been installed make sure to 'switch on' in Settings** (otherwise they will not appear in the dropdowns)
![App Screenshot](https://i.ibb.co/mNzVMxJ/6cc20fb5eae175d5e036b682941ee958.png)



 ####  **You should now be able to start creating animations.** 
- I'll be making some youtube videos soon!
>
---
 ####  **STREAM DECK PLUGIN** 
- Stream Deck Software Version 6.* is currently not compatible. 
- This is a little buggy. If you want to try it download *com.stream.animate.sdPlugin.zip*
and extract the zip file. Place the extracted folder wherever the elgato plugins folder is found on your pc. eg. *C:\Users\YOURUSERNAME\AppData\Roaming\Elgato\StreamDeck\Plugins* .
Then restart the Stream Deck software.
>
---

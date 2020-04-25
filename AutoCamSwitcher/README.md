# Auto Cam Switcher  

This Script will Automatically Switch between My Setup Cam and My Face Cam every `X` Seconds.  

# Requirements  

- Two Webcams (I use two Logitech Brio's)  

- OBS-Studio [Link](https://obsproject.com/)  

- OBS-Websocket [Link](https://obsproject.com/forum/resources/obs-websocket-remote-control-obs-studio-from-websockets.466/)  

# Prepreation  

1. Create a Scene New Scene for the Webcams.  

2. Add both Webcams into the New Scene as Sources.  

3. Overlay the two Webcam Sources so one hides the other.  

# How to setup and use  

1. Save the two files in a folder on your computer.  

2. Open the SwitchCams.html file in an editor. `(VCS, NP++, Etc..)`  

3. Edit the definded VARS as needed. `(Read the Comments I Added)`  

4. In OBS-Studio: `Add a New Browser Source > Local File > SwitchCams.html`  

5. Enable the Browser Source Properties > Shutdown source when not visible.  

6. (Optional) Set a Hotkey to Enable/Disable the Browser Source you just added.
- OR use a `Elgato Streamdeck > OBS-Studio > Source` key instead, if you have one.
- This allows you to easily Enable/Disable the Webcams from Automatically Switching.  

7. Enjoy!
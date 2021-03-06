# cobbler_script
A short and sweet *Apple* Desktop testing script. Most useful for pulling specifications from large quantities of machines or batch testing hardware.

![image](https://user-images.githubusercontent.com/79986025/166068469-7fcca6ad-f7e6-455f-9644-0a507b06973d.png)


Features:\
Complete specification pull including CPU/GPU/RAM/Storage + Activation lock status, Serial Number, Last Boot Diagnostic result, battery health, etc.\
Tree menus - only want to pull specs? Choose option 1! Skip straight to hardware testing? No problem!\
Automatically opens hardware testing applications on the web and from the machine. Camera, microphone, speakers, keyboard, etc.\
Time/date stamping on file creation that logs system info and testing results.\
Feel free to modify this script as much as needed. Looking for a MacBook script of the same kind? Check out crumble_script: [here](https://github.com/crimes-johnson/crumble_script)

How to:\
    <code>cd /path/to/script</code>\
    <code>chmod u+x crumble.sh</code>\
    <code>./crumble.sh</code>

If you want the audio test to work, make sure the .mp3 file in the main resides in the same folder as the script. 

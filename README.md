# Setup for bedrock
###### I have not made these guides myself, this is from their github page for the plugin used on the server.
###### https://github.com/GeyserMC/Geyser/wiki/Using-Geyser-with-Consoles
## Xbox one
[![TEST STuff](https://img.youtube.com/vi/g8mHvasVHMs/0.jpg)](https://www.youtube.com/watch?v=g8mHvasVHMs)
## Nintendo Switch
[![TEST STuff](https://img.youtube.com/vi/zalT_oR1nPM/0.jpg)](https://www.youtube.com/watch?v=zalT_oR1nPM)
## PS4

PS4 does not have any external server support. But there is some ways around this. 
You will need to emulate a LAN game on your network. 
This can be done with either a PC, Android APP or iOS 14+, the device must be on the same network as the console.

### Wondiws | Linux | Mac OS
With PC you can use a program called Phantom. 

Download phantom from [here](https://github.com/jhead/phantom/releases)

Open Command Prompt (CMD) and change to the directory of Phantom file you downloaded.
Then start the program by typing the "Start Command" as instructed below:
### Example: 
If the Phantom file is in the Download folder:

    cd Downloads  
   Start Command
   
    phantom-FULL_FILE_NAME -bind YOUR_IP -server SERVER_ADDRESS
    See picture below on how to obtain your ip address.
   SERVER_ADDRESS is available on discord, remember to include the port number. (xxx.xxx.xxx.xxx:Port_Number
   
   #### !!!Be aware of the filename for phantom, it is different for each OS (Windows, Linux, MacOS)!!!
   
 Find ip address:
 Windows:
 
     ifconfig  
     
 Linux:
 
     ipconfig
     
  MacOS:
  
      Wired connection:
       ipconfig getifaddr en1
      Wireless (Wifi): 
       ipconfig getifaddr en0
       
 ![alt text](https://github.com/mrvasquez2/VanillaServer/blob/main/Pictures/ipconfig.PNG?raw=true)
 
 Start phantom:
 
![alt text](https://github.com/mrvasquez2/VanillaServer/blob/main/Pictures/phantom.PNG?raw=true)



### Android app
##### Work in progress Geyser Android [App](https://github.com/GeyserMC/GeyserAndroid)
##### MC Lan [Proxy](https://play.google.com/store/apps/details?id=com.luzenna.mineproxydroidtrial) (Trial)
##### MC Lan [Proxy](https://play.google.com/store/apps/details?id=com.luzenna.mineproxydroid) (Paid):
##### MC Server [Connector](https://play.google.com/store/apps/details?id=com.smokiem.mcserverconnector)
#### iOS 14+
##### [BedrockTogether](https://apps.apple.com/app/bedrocktogether/id1534593376)

## Feedback
Any kind of feedback can either be posted here under "issues" or you can DM me on discord. (#mrvasquez7574)

# Setup for bedrock
###### I have not made these video guides myself, this is from their github page for the plugin used on the server.
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

Find you local ip address with the command below.

 Windows:
 
     ifconfig  
     
 Linux:
 
     ipconfig
  MacOS:
  
      Wired connection:
       ipconfig getifaddr en1
      Wireless (Wifi): 
       ipconfig getifaddr en0
 It should look something like the picture below.    
 ![alt text](https://github.com/mrvasquez2/VanillaServer/blob/main/Pictures/ipconfig.PNG?raw=true)
 
It is the same for ipv6 if your network use it.
 
## Start Phantom
 ### Example: 
If the Phantom file is in the Downloads folder:

    cd Downloads  
   Start Command
   
    phantom-FULL_FILE_NAME -bind YOUR_IP -server SERVER_ADDRESS
    
  ![alt text](https://github.com/mrvasquez2/VanillaServer/blob/main/Pictures/phantom.PNG?raw=true)
   
   #### !!!Be aware of the filename for phantom, it is different for each OS (Windows, Linux, MacOS)!!! 

You should see something happening on the terminal when you open Minecraft on your PS4. If it works then you should be able to se that the the PS4 is sending and recieving data to phantom (See the lines in the terminal).
### Android app
##### Work in progress Geyser Android [App](https://github.com/GeyserMC/GeyserAndroid)
##### MC Lan [Proxy](https://play.google.com/store/apps/details?id=com.luzenna.mineproxydroidtrial) (Trial)
##### MC Lan [Proxy](https://play.google.com/store/apps/details?id=com.luzenna.mineproxydroid) (Paid):
##### MC Server [Connector](https://play.google.com/store/apps/details?id=com.smokiem.mcserverconnector)
#### iOS 14+
##### [BedrockTogether](https://apps.apple.com/app/bedrocktogether/id1534593376)


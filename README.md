# windowswallets

This is where you can get your Project Excelsior Windows Wallets. 
You will need to first download the projectexcelsior-0.15.1-win32-setup.exe file.
Once it has downloaded, you will need to right click and run as administrator. 
If you are using Windows 10, you will get a warning, please click "More info" and then click on run anyway.
The wallet will istall. 
Once the walled installs, you will need to add nodes to the configuration file.
Hide the pop up that first loads once you have launced the walled.
Go to settings, options, then click on "Open Configuration File"
You will need to select a text editor to make changes to the file, Note Pad will work. 
Add the following lines:
addnode=147.182.208.202
addnode=147.182.208.1
addnode=147.182.242.221
addnode=147.182.240.1
click save, then close the note pad
exit from the wallet, then restart it. 
After that, it will sink with the blockchain.
To start mining, you will need to Help, then Debug Window then Console.
In the command line area on the bottom, you will type the word generate then a number, for example, generate 1
This will start to allow you to mine 1 block. 
Mined coins are not spending until 101 blocks have been mined. At that point,they are able to spend. 

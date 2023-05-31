# NOTICE OF PROPRIETARY RIGHTS: 

Any blockchain initiated with the specific timestamp of 1637710944, nonce of 2085969695, difficulty target of 0x1e0ffff0, version number of 1, and a reward value of 50 * COIN, producing a Genesis Block hash of "0x94e01e42b72f879cb8db253ce2d74b749c338e73e428aff2bf6dd75db6ddf316" and a Merkle Root hash of "0xa507f271f981e998c341679be851c734c3b053c303589068b004f92e79e9d5fb" (collectively referred to as the "Identified Blockchain Parameters"), is hereby acknowledged as the proprietary property of Project Excelsior. The Identified Blockchain Parameters have been developed, maintained, and are the exclusive property of Project Excelsior.

Without the express written consent of Project Excelsior, no person, entity, or party has the right or license to use the Identified Blockchain Parameters for monetary gain, profit, or any form of economic advantage. Any such unauthorized use, reproduction, distribution, or other exploitation of the Identified Blockchain Parameters constitutes a violation of Project Excelsior's rights and may subject the violator to legal action, including, but not limited to, claims for damages, injunctive relief, and the recovery of costs and attorney's fees incurred in connection with the enforcement of Project Excelsior's rights.

Project Excelsior reserves all rights not expressly granted herein, and this Notice does not constitute any waiver of any rights that Project Excelsior may have, whether at law, in equity, or otherwise.

# windowswallets

This is where you can obtain your Project Excelsior Windows Wallet.

First, download the projectexcelsior-0.15.1-win32-setup.exe file.

Once the file has downloaded, right-click and select "Run as administrator."

If you're using Windows 10, you may encounter a warning. Click on "More info" and then select "Run anyway."

The wallet will begin installation.

After the wallet has installed, you will need to add nodes to the configuration file.

Hide the pop-up that appears when you first launch the wallet.

Navigate to Settings, select Options, and then click on "Open Configuration File."

Choose a text editor to modify the file. Notepad will work.

Add the following lines:

addnode=157.245.89.194

addnode=167.99.238.229

Server=1

rpcuser=user

rpcpassword=password

Click save, then close Notepad.

Exit the wallet and restart it.

The wallet will now synchronize with the blockchain.

To start mining, navigate to Help, then Debug Window, and finally Console.

In the command line area at the bottom, type the word "generate" followed by a number (e.g., generate 1).

This command will allow you to mine one block.

Mined coins are not spendable until 101 blocks have been mined. At that point, they will be available to spend.

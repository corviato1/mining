Dynamo Mining Run List
*If a windows security window pops up allow access to public network only
*Enable hidden items and file name extensions in file explorer
Do this by opening file explorer, clicking view, then checking the two boxes on the right.  This will enable you to see hidden files and the full file name, which may be helpful down the line
Move folder DYNAMO to desktop
Right click and unzip/extract-here file name: mainnet-binaries-main.zip
Open folder mainnet-binaries-main
Open folder windows-x64
Double click dynamo-qt.exe
Make sure the choice use default directory is chosen
Uncheck the box that says “Discard blocks.. (prune)”
I have no real reason for leaving the box checked as I have plenty of OS/Disk space.  And it can’t be a bad thing to have the whole chain when mining right?  Also, the chain is for sure not 350GB, that’s bitcoin’s size and this is a fork of bitcoin.  Because this is so new some things just are not updated yet, like chain size here.
Click OK
Let chain reach full synchronization
Click Create New Wallet
Name your wallet whatever you want
Do not check any of the boxes
Click Create
Click the Receive button(top middle)
Type Miner-CPU in label
Leave amount blank
Type http://ipfs.io/ipfs/Qmb6zSwFt9fYZjnztRnzqYFzeggkd4BXna7aUcbPpEnGtP in Message
Click Create new receiving address
Copy address and save it below in the notes section
Type Miner-GPU in label
Leave amount blank
Type http://ipfs.io/ipfs/Qmb6zSwFt9fYZjnztRnzqYFzeggkd4BXna7aUcbPpEnGtP in Message
Click Create new receiving address
Copy address and save it below in the notes section
Click the Overview button(upper left)
*Leave the wallet open while mining
Click the desktop start button
Type then open Command Prompt
Type ipconfig
Find the first instance of IPv4 Address
Copy that ip address in notes below
Close Command Prompt terminal
Open folder DYNAMO
Open secret-sauce folder
Right click then edit file CLICKtoMine-GPU.bat
Change “1.2.3.4” to your IPv4 address
Change the address(mine) to your address(miner-GPU) that you saved below in the notes section
Do not make any other changes to the file, including adding or removing a space
Save then close the file
Right click then edit file CLICKtoMine-CPU.bat
Change “1.2.3.4” to your IPv4 address
Change the address(mine) to your address(miner-CPU) that you saved below in the notes section
Do not make any other changes to the file, including adding or removing a space
Save then close the file
Open new file explorer window
Click This PC on the left
Open Local Disk
Open Users folder
Open the folder that is labeled as the name of your computer
Open hidden folder AppData
Open folder Roaming
Open folder Dynamo
For future reference, a quicker way to get there would be to paste in the line below in the explorers main text input box.
C:\Users\lapras\AppData\Roaming\Dynamo
*change the word lapras to your computer name
Go to secret-sauce folder
Copy file dynamo.conf and paste it into the Dynamo folder that is in the Roaming folder
Go to secret-sauce folder
Copy files CLICKmetoMINEthisBitchCPU.bat & CLICKmetoMINEthisBitchGPU.bat, then paste them into C:\Users\lapras\Desktop\DYNAMO\mainnet-binaries-main\windows-x64\miner
For clarity, it's the same folder that has dyn_miner.exe in it.
Double click file CLICKtoMine-GPU.bat to start mining with your GPU
Double click file CLICKtoMine-CPU.bat to start mining with your CPU

Hot tips:
Only run one GPU mining window
The system will only recognize 1 GPU in a rig
Open multiple CPU windows to maximize yields 
Open Task Manager(CTRL + ALT + DEL)
Click the Performance tab
Double click file CLICKtoMine-CPU.bat as many times as you want till you reach a desired CPU utilization % in Task Manager.  
*Even with proper cooling, I won’t go above 93%

Notes:
Example IPv4 address: 1.2.3.4
CPU miner address:
GPU miner address:
IP-1:
IP-2:
IP-3:

Links:
https://github.com/dynamofoundation/mainnet-binaries
https://www.dynamocoin.org/
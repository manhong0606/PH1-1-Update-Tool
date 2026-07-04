# PH1-1 Update Tool
✅ Latest Version: **V4.0**
👉 Direct Download:[ https://github.com/manhong0606/PH1-1Update-Tool/releases/tag/V4.0](https://github.com/manhong0606/PH1-1-Update-Tool)

This tool supports one-click downloading via serial port. The package contains MCU firmware files, serial port drivers, and relevant operation instructions.
本软件支持 STM32 串口一键烧录下载，安装包内已附带 MCU 程序固件、USB 转串口驱动程序与详细使用操作手册。

Preparatory work: Prepare the PH1-1 Portable lamp that need to be re-flashed for program, and connect the lamp to the computer by using a USB cable.       (The compressed file STM32_BootLoader_Tool_v3.0.rar needs to be unzipped into the computer in advance.)
Double-click to open STM32_BootLoader_Tool_v4.0.exe as shown in the following picture. In the software interface, you could select English as the language.

<img width="982" height="545" alt="image" src="https://github.com/user-attachments/assets/661ba1f5-fb3c-4dd0-b31a-2aa0c7b300eb" />


Summary: The steps for quickly re-flashing a program are as follows: 1-2-3, followed by a detailed 
introduction with pictures and text. 

<img width="600" height="585" alt="image" src="https://github.com/user-attachments/assets/1f231435-b784-40a9-9c7c-10baf86c597c" />

Step 1: Select the serial port (with CH340K) : COMxx       CH34OK 
Note: If your computer fails to recognize the CH340 serial port, please download and install the program CH341SER.EXE. 

<img width="867" height="708" alt="image" src="https://github.com/user-attachments/assets/33895ecf-9f76-4b9d-a48a-811e0a68ed53" />

Step 2: Click Browse to load the program PH1-1 260610 v9.0.3.hex  
Note: Please extract it to your computer in advance 

<img width="872" height="703" alt="image" src="https://github.com/user-attachments/assets/13d52b9a-ff12-4f95-b7db-1d1f60a9c4d6" />

Step 3, click Burn(Erase-Write-Verify), and then a prompt box will pop up: 
Click Yes (Y), and the new program will start re-flashing.

<img width="871" height="708" alt="image" src="https://github.com/user-attachments/assets/16491a7f-58b9-40bf-90de-b04c5af8a18e" />

After following the above three steps, the program will start automatically and wait for it to be fully 
reflashed. The successful re-flashing prompt is as follows:

<img width="870" height="704" alt="image" src="https://github.com/user-attachments/assets/92deb49a-ae8e-4655-ab8d-de75c551e4c4" />

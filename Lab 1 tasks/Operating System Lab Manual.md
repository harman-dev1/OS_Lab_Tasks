# Operating System 
# Name :Harmain Iftikhar 
# ROll No :2022-CS-07

###   Week 01
### LAB  Manual 02

## OBJECTIVE : 
                 of this manual is to get hands on Experience with the tool used for Operating Systems for this Course, we will be working on Virtual box.
## BACKGROUND : 
                 Students should know the basics of Operating Systems and use of Computers.

### This assesment is According to the Student participaion in this Lab. Now we see that what is virtual box Oracle with ubunto and How it is Installed.

##LET'S BEGIN  WITH AN AMAZING Software
# Virtual Box  Installation with Ubunto
## Introduction : 
                    Virtual Box is a powerful x86 and AMD64/Intel64 virtualization product for enterpriseas well as home use. Not only is Virtual Box an extremely feature rich, high performance product for enterprise customers, it is also the only professional solution that is freely available as Open Source Software under the terms of the GNUGeneral Public License (GPL) version 2.
     It allows users to install operating systems on virtual hard disks such as Windows, macOS, Solaris and Linux.

[to get more info, Click] (https://www.virtualbox.org /)

## Why is Virtualization Useful ? 

1. Running multiple operating systems simultaneously.
         Oracle VM VirtualBox enables you to run more than one OS at a time. This way, you can run software written for one OS on another, such as Windows software on Linux or a Mac, without having to reboot to use it.
         

2.Easier software installations

3.Testing and disaster recovery.

## Terminologies of Virtual Box :

### Host operating system (host OS).
          This is the OS of the physical computer on which Oracle VM VirtualBox was installed. There are versions of Oracle VM VirtualBox for Windows, macOS, Linux, and Oracle Solaris hosts.

### Guest operating system (guest OS).
          This is the OS that is running inside the virtual machine.

### Virtual machine (VM).
          This is the special environment that Oracle VM VirtualBox creates for your guest OS while it is running. In other words, you run your guest OS in a VM. Normally, a VM is shown as a window on your computer's desktop.

# ***************TASK 01*****************
# Installation Process

### Now we will start Installing Virtual Box in Windows, to install Ubuntu as virtual machine.

You can download Virtual Box version 7.0.14 setup from following link. this is Latest Version. That's why I Refer. From this Link, You can Download For (Windows)
https://www.virtualbox.org/wiki/Downloads

#### Make a seperate folder of Lab 02 OS Manual

****Make sure, you have stable Internet Connection For which Oracle is Installed and Ruuning every Obunto package smoothly ******

### STEP 1 : Following Interface will appear.

![Capture](C:\Users\pc\Desktop\Typora work\Capture.PNG)

       After Download complete of latest version Virtual Box 7.0.14, Click on downloaded exe.
      Run the installer and define the installation options.

### STEP 2 :  Following Welcome screen will appear.

![image-20240131214331022](C:\Users\pc\AppData\Roaming\Typora\typora-user-images\image-20240131214331022.png)

#### Click “Next” button

### STEP 3 : Now Further , Small change in Interface, you just place your file Location and change the way features will be installed like (Virtual Application).


![image-20240131221641438](C:\Users\pc\AppData\Roaming\Typora\typora-user-images\image-20240131221641438.png)

#### Click “Next”

###  STEP 4 :Custom Setup for different features Window is displayed. No need to change anything, just press “Next” button.

![image-20240131222611881](C:\Users\pc\AppData\Roaming\Typora\typora-user-images\image-20240131222611881.png)

### STEP 5 : Warning window is Displayed. Click Yes

![image-20240131223121254](C:\Users\pc\AppData\Roaming\Typora\typora-user-images\image-20240131223121254.png)

### STEP 6 :  “Ready to Install” window is displayed. Press “Install” button.

![image-20240131225331228](C:\Users\pc\AppData\Roaming\Typora\typora-user-images\image-20240131225331228.png)

### STEP 7 :  Finally after setup, installation will start and following window will be displayed with status bar.

Make sure Internet Connection is Satisied

![image-20240131234205971](C:\Users\pc\AppData\Roaming\Typora\typora-user-images\image-20240131234205971.png)

INSTALLATION Continues
During this process. don't need to open other Tabs Just 

 ## 	WAIT!!!!

![image-20240131234952280](C:\Users\pc\AppData\Roaming\Typora\typora-user-images\image-20240131234952280.png)



Meanwhile Windows Security will ask for the confirmation of installing hardware. e.g below.  JUST LIKE..........

![image-20240131235334271](C:\Users\pc\AppData\Roaming\Typora\typora-user-images\image-20240131235334271.png)
 #### Press Install

 ### STEP 8 : Installation Complete, Press "Finish" Button

![image-20240201000307219](C:\Users\pc\AppData\Roaming\Typora\typora-user-images\image-20240201000307219.png)

 After Installation Completed , You can Find its icon on Desktop. LIKE THIS........

![image-20240201013204694](C:\Users\pc\AppData\Roaming\Typora\typora-user-images\image-20240201013204694.png)

##             Congratulations!!!!. Oracle is Installed on your PC's

# Setting Up of Virtual Machine : 
After the Successful Installation of Virtual Box. When You open an icon Of Oracle VM Virtual Box, then this Interface First open by Clicking on icon Virtual Box Version 7.0.14.

![image-20240201014448391](C:\Users\pc\AppData\Roaming\Typora\typora-user-images\image-20240201014448391.png)


Now Make Setting of Oracle  VM Virtual box Manager, setting of a virtual machine. A special Environment of VM Virtual box machine for running of ubuntu.
 In  Further Labs, we also work on ubuntu . 

Further , Show

![arsal](C:\Users\pc\Desktop\Typora work\arsal.PNG)

 # How to use Ubuntu in VirtualBox?
First, open VirtualBox, then click "New" to create a virtual machine.
* Enter "Ubuntu" as the name, select "Linux" as the type, and select Ubuntu (64-bit) as the version.
* NOTE: Select any amount of memory you wish, but don't add more than 50 percent of your total RAM. ...
* Now, we want to select "VHD (Virtual Hard Disk)".

## Click on “New” button on top of menu bar.

### STEP 1: Clicking a new Button will lead you to setup a new Virtual Machine

![AR](C:\Users\pc\Desktop\Typora work\AR.PNG)

#### Following window will be opened to setup virtual machine name, Location folder and type. 
* Press Next.

###  STEP 2: By pressing “Next”, following window will be opened to setup memory size.

![image-20240201024538861](C:\Users\pc\AppData\Roaming\Typora\typora-user-images\image-20240201024538861.png)

* Press Next

## NOTE: Select any amount of memory you wish, but don't add more than 50 percent of your total RAM.


### STEP 3: By pressing “Next”, “Hard drive” window will be opened. Select“Create a virtual hard drive now”.

Check the "Create a virtual hard disk now" option so we can later define our Ubuntu OS virtual hard disk size.

![image-20240201025902114](C:\Users\pc\AppData\Roaming\Typora\typora-user-images\image-20240201025902114.png)

* Press “Next” button.

Now, we want to select "VHD (Virtual Hard Disk)".



![image-20240201030832974](C:\Users\pc\AppData\Roaming\Typora\typora-user-images\image-20240201030832974.png)

* Press “Finish” button.

## After creating a virtual hard disk, you'll see Ubuntu in your dashboard.

![image-20240201031903460](C:\Users\pc\AppData\Roaming\Typora\typora-user-images\image-20240201031903460.png)

# End of Virtual Machine Setup>>>


# ******************TASK 02 ******************

# NOW Compiler Installation work>>>

You have a Choice of Using one of these Compilers of one of these  Language 

** Following compilers are used for C and C++ language:
* For C language: gcc
Command: sudo apt-get install gcc
* For C++ Language: g++
Command: sudo apt-get install g++


### NOTICE : 
* You have a Compiler(C OR C++) Installed on Ubuntu 
* Then , Go the Search bar and Click on //textfile// 
* Write C++ Print "Hello World" Program on Terminal of ubuntu
* Save this Program  in Named(arsal.cc) File .    {Mind that in ubuntu Terminal Extension (not cpp) that is //cc//}
* Precautionily , one time C program on terminal, notice that execute or not.

### STEP 1: Click on Windows Button and Type Terminal , so Terminal is Open Like that :

![image-20240201111943197](C:\Users\pc\AppData\Roaming\Typora\typora-user-images\image-20240201111943197.png)

### SREP 2: Check that G++ Compiler is Already Installed OR NOT : 

   In additon, g++ Compiler is Already Installed on New Version of Ubuntu< Virtual Box VM >

![image-20240201104211986](C:\Users\pc\AppData\Roaming\Typora\typora-user-images\image-20240201104211986.png)

* If you don't have g++  -- version Compiler on Your obuntu terminal, then Try this method.
* Type that Command on Ubuntu Terminal  
####  sudo apt install build-essential >>>> Command 
* then, 
* ![image-20240201104722749](C:\Users\pc\AppData\Roaming\Typora\typora-user-images\image-20240201104722749.png)
* then go to the text editor, and write c++ code on this.
* Now run on terminal with the help of that Command.There are many ways to run exe. file in terminal. one of that is like. 

## Testing g++ Compiler Installation
* Create file by right click and name it as “test.cpp”
* Add this code into file and save: 
* Compile this code using following steps:
* To compile: g++ -o obj test.cpp 
* To run: ./obj
Done, Check the output on command prompt 

<!--\#include<iostream>

using namespace std;

int main()

{
cout<< “Testing G++ Compiler!!!!!!!”;

cout<< “Yes, G++ Compiler working Perfectly!!!!!!!”;

return 0;
}-->

## Test gcc Compiler Installation
### STEP 3: One method is to run program with  **gcc  Compiler**

•Create file by right click and name it as “test.c”

•Add this code into file and save: 

•Compile this code using following steps:

•To compile: gcc -o obj test.c 

•To run: ./obj

•Done, Check the output on command prompt 

##### CODE : 

\#include<stdio.h>

void main() {

  printf("Hello! This is my first C program with Ubuntu 11.10\n");  /* Do something more if you want */ 

} 

###  STEP 4: Also installed typora in Ubuntu Terminal:

##### For enable snapd if not have
sudo apt update
sudo apt install snapd

### For Installing Typora on Ubuntu Desktop
sudo snap install typora




# Github Repositry Link: https://github.com/harman-dev1/OS_Lab_Tasks
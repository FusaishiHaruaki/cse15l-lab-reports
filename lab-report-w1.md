# CSE 15l lab report week 1 - Remote access

## Installing VScode
You can use VScode on lab computers which are already installed. 
If you want to install VScode on your own device, go to the [Visual Studio Code website](https://code.visualstudio.com/), and follow the instructions there to download and install VScode on your computer.
When VScode is installed, your should be able to open it and see something similar to this: 
![Image](https://github.com/FusaishiHaruaki/cse15l-lab-reports/blob/main/img/Screen%20Shot%202023-01-12%20at%2011.11.45%20AM.png)


## Remotely Connecting
Type `ssh cs15lwi23XXX@ieng6.ucsd.edu` into terminal, replace XXX with your own account letters. 

If this is your first time connecting, your will see messages similar to: 
```
ssh cs15lwi23zz@ieng6.ucsd.edu
The authenticity of host 'ieng6.ucsd.edu (128.54.70.227)' can't be established.
RSA key fingerprint is SHA256:ksruYwhnYH+sySHnHAtLUHngrPEyZTDl/1x99wUQcec.
Are you sure you want to continue connecting (yes/no/[fingerprint])? 
```
type `yes` and press enter. 

Enter your password when prompted. 
After seeing messages similar to below, the terminal is successful connected to a CSE basement computer. 
```
Last login: Sun Jan  2 14:03:05 2022 from 107-217-10-235.lightspeed.sndgca.sbcglobal.net
quota: No filesystem specified.
Hello cs15lwi23zz, you are currently logged into ieng6-203.ucsd.edu

You are using 0% CPU on this system

Cluster Status 
Hostname     Time    #Users  Load  Averages  
ieng6-201   23:25:01   0  0.08,  0.17,  0.11
ieng6-202   23:25:01   1  0.09,  0.15,  0.11
ieng6-203   23:25:01   1  0.08,  0.15,  0.11

Sun Jan 02, 2022 11:28pm - Prepping cs15lwi23
```

Below is a full process of remotely connecting: 
![Image](https://github.com/FusaishiHaruaki/cse15l-lab-reports/blob/main/img/Screen%20Shot%202023-01-12%20at%2010.30.43%20AM.png)

## Trying Some Commands
Trying commands such as:
```
ls
ls -a
ls -lat
cd 
cat /home/linux/ieng6/cs15lwi23/public/hello.txt
exit
```
For example, typing `cd ..` then `ls -lat` lists all files and folders in the parent directory with details in size, modification date, permissions etc.
![Image](https://github.com/FusaishiHaruaki/cse15l-lab-reports/blob/main/img/Screen%20Shot%202023-01-12%20at%2010.35.48%20AM.png)

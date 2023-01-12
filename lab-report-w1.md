# CSE 15l lab report week 1 - Remote access

## Installing VScode
VScode was already installed on computer. 

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

## Trying Some Commands
Trying commands such as:
```
ls
ls -a
ls -lat
cd 
cat /home/linux/ieng6/cs15lwi23/public/hello.txt
```

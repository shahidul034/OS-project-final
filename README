# OS-Demo-code-project
## First we have to download Ubuntu 18.04.1 LTS.It is the latest version of ubuntu

[Ubuntu download link](https://www.ubuntu.com/download/desktop)

## Setup the environment
We should remember that we run our command individually. 
### install xorriso

```

sudo apt-get update
sudo apt-get install xorriso

```
### install grub2
```
sudo apt-get install grub2

```
latest aita grub2 name ache.aga grub cilo
### install gcc
```
sudo apt-get install gcc

```
### install nasm 
```
sudo apt-get install nasm 

```
### install virtualbox
```
sudo apt-get install virtualbox

```
### install qemu
```
sudo apt-get install qemu

```
It is good for you to install this in good internet speed.
If you run those command  individually , I hope You sucessfully complete your setup environment.:+1: :+1:
If you have face some problem to install those command,you just google those command and check latest command for those library.
After completing install you again run those command you see below pic in your command line.

![alt text](https://github.com/shahidul034/OS-Demo-code-project/blob/master/IKnowOS_EP1/Annotation%202018-11-25%20180501.jpg)


Next,we build our Kernel.

## Build the kernel
Here,we do the same things,we run our command individually.

### If we run this command ,here kasm.o file will created
```
nasm -f elf -o kasm.o kernel.asm

```
### If we run this command ,here kc.o file will created and actually we get this from compiling kernel.c
```
gcc -m32 -o kc.o -c kernel.c

```
### If we run this command ,here kernel.bin file will created
```
ld -m elf_i386 -T link.ld -o kernel.bin kasm.o kc.o

```
### If we run this command ,virtual box(qemu) run kernel.bin file and create kernel.iso file.Further we use this  kernel.iso file for running as a OS in VM Ware or Virtual box. 

```
qemu-system-i386 -kernel kernel.bin

```
![alt text](https://github.com/shahidul034/OS-Demo-code-project/blob/master/IKnowOS_EP1/Annotation%202018-11-25%20182953.jpg)

Now ,we see how we design our command line.
We design our command line in kernel.c file

![alt text](https://github.com/shahidul034/OS-Demo-code-project/blob/master/IKnowOS_EP1/Annotation%202018-11-25%20183223.jpg)
 
We give a demo design of command line.We simply add an else if condition and write our logic in c.When we write our command ,it simply checks in the file.If they have any match and execute it and show in the command line. 
If we write "nahin".It shows---
```
nahi is here
```
If we write "ankur".It shows---

```
ankur is here
```
![alt text](https://github.com/shahidul034/OS-Demo-code-project/blob/master/IKnowOS_EP1/Annotation%202018-11-25%20183246.jpg)


![alt text](https://github.com/shahidul034/OS-Demo-code-project/blob/master/IKnowOS_EP1/Annotation%202018-11-25%20183105.jpg)



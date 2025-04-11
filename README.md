# EXPERIMENT--01-ALP-FOR-8086
 Name : Vimala Rani A

 Roll no : 212223040240
 
Date of experiment : 11/03/2025





## Aim: To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	  Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
 
 
3.		write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 

4.	 Compile the program and check for the errors 
5.	Run (once there is no syntax error) 

6.	Click OK to see/view the output of your program on the Emulator screen. 


7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
8.	 


![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)











9.	Click on emulate to start emulation 








![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)








10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 






![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)







## Programs for arithmetic  operations
## 8-bit ALP
## Addition  of 8 bit ALP 
```
mov  al,60h
mov bl,20h
add al,bl
hlt
```
## Output  
![Screenshot 2025-03-07 131957](https://github.com/user-attachments/assets/3ee51790-5e76-48da-ab96-82c7378ded3a)

## Subtraction of 8 bit ALP
```
mov al,60h
mov bl,20h
sub al,bl
hlt
``` 
## Output  
![Screenshot 2025-03-07 132111](https://github.com/user-attachments/assets/934b5600-521a-4e76-9d53-8c8b587b7c4a)

## Multiplication of 8 bit ALP
```
mov al,60h
mov bl,20h
mul bl
hlt
```
## Output  
![Screenshot 2025-03-07 132242](https://github.com/user-attachments/assets/7b59e8de-f6d4-4c5b-84d9-3ec614cba424)

## Division  of 8 bit ALP
```
mov al,60h
mov bl,20h
div al
hlt
```
## Output  
![Screenshot 2025-03-07 132403](https://github.com/user-attachments/assets/4412c90d-2755-4f9a-9cf1-e126f0a4c627)

## AND operation of 8 bit ALP
```
mov al,60h
mov bl,20h
and al,bl
hlt
```
## Output
![Screenshot 2025-03-07 132659](https://github.com/user-attachments/assets/858451c3-45e4-4688-8c50-5a5c3b533eb1)

## OR operation of 8 bit ALP
```
mov al,60h
mov bl,20h
or al,bl
hlt
```
## Output
![Screenshot 2025-03-07 132839](https://github.com/user-attachments/assets/bdfa42fd-587f-4742-b5c1-708c8bb1b446)

## NOT operation of 8 bit ALP
```
mov al,6h
not al
hlt
```
## Output
![Screenshot 2025-03-07 132930](https://github.com/user-attachments/assets/3a1984b1-59d2-4267-8524-b6d296ec48d1)

## XOR operation of 8 bit ALP
```
mov al,60h
mov bl,20h
xor al,bl
hlt
```
## Output
![Screenshot 2025-03-07 133008](https://github.com/user-attachments/assets/9d45cc77-a86e-47ac-a391-7fcb3cc725b4)

## 16-bit ALP
## Addition of 16 bit ALP
```
mov ax,1234h
mov bx,5678h
add ax,bx
hlt
```
## Output
![Screenshot 2025-03-07 133008](https://github.com/user-attachments/assets/3ee3d855-0a30-4560-9158-2d80fa2dd292)

## Subtraction of 16 bit ALP:
```
mov ax,1234h
mov bx,5678h
sub ax,bx
hlt
```
## Output
![Screenshot 2025-03-07 133313](https://github.com/user-attachments/assets/4aee982c-013b-4aa5-9448-64ffe657de2e)

## Multiplication of 16 bit ALP
```
mov ax,1234h
mov bx,5678h
mul ax
hlt
```
## Output
![Screenshot 2025-03-07 133336](https://github.com/user-attachments/assets/c40897a6-834f-455c-bd25-248f9c5fe2eb)


## Division of 16 bit ALP
```
mov ax,1234h
mov bx,5678h
div ax
hlt
```
## Output
![Screenshot 2025-03-07 133400](https://github.com/user-attachments/assets/b127e5c8-6118-493c-88f6-ece8d69ed7a7)


## AND operation of 16 bit ALP
```
mov ax,1234h
mov bx,5678h
and ax,bx
hlt
```
## Output
![Screenshot 2025-03-07 133421](https://github.com/user-attachments/assets/7d8cc86b-aff4-4e25-9859-eabeaae15743)

## OR operation of 16 bit ALP
```
mov ax,1234h
mov bx,5678h
or ax,bx
hlt
```
## Output
![Screenshot 2025-03-07 133441](https://github.com/user-attachments/assets/71bfff04-85b3-4a64-99ef-54abbd7ec6cd)

## NOT operation of 16 bit ALP
```
mov ax,1234h
not ax
hlt
```
## Output
![Screenshot 2025-03-07 133541](https://github.com/user-attachments/assets/9c1a1d8a-9024-40ec-aae1-010af7b87a03)

## XOR operation of 16 bit ALP
```
mov ax,1234h
mov bx,5678h
xor ax,bx
hlt
```
## Output
![Screenshot 2025-03-07 133504](https://github.com/user-attachments/assets/fc6e56e0-4750-47b7-898a-e6ec09080df8)


## Result :
 Thus the execution of ALP on fundamental arithmetic and logical operation has been performed successfully.









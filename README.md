# EXPERIMENT--01-ALP-FOR-8086
```
Name : Harini.B
Roll no : 212221230035
Date of experiment : 09-09-20222
```

## Aim: 
To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 
8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color  
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

## Addition of 8 bit ALP
```
name "ADDITION"
org 100h
MOV AH,05H;
MOV BH,02H;
ADD AH,BH;
MOV CH,AH;
MOV AH,00H;
HLT;
```

## Output  
![Add](https://user-images.githubusercontent.com/93427253/189384335-83050947-948d-49d1-9f6b-e9ebf05e160f.png)
![Add 1](https://user-images.githubusercontent.com/93427253/189384221-a15b7685-567c-4d1e-a480-1df3627bea05.png)

## Flag
![Add 2](https://user-images.githubusercontent.com/93427253/189384402-098f59c8-c5f0-4f2b-9890-c039190bdcbc.png)
 
## Subtraction of 8 bit ALP 
```
name "SUBTRACTION"
org 100h
MOV AH,09H;
MOV BH,03H;
SUB AH,BH;
MOV CH,AH;
MOV AH,00H;
HLT;
```
 
## Output 
![Sub](https://user-images.githubusercontent.com/93427253/189384899-751ebb3d-c2c5-4555-aba8-d2c7927d2d83.png)
![Sub 1](https://user-images.githubusercontent.com/93427253/189384925-ed40bd76-c470-4861-91e9-8524c0f9468e.png)

## Flag
![Sub 2](https://user-images.githubusercontent.com/93427253/189385018-03dbf1ce-d03d-425e-b32f-56b8fa962eb8.png)

## Multiplication of 8 bit ALP
```
name "MULTIPLICATION"
org 700h
MOV AL,15H;
MOV BL,03H;
MUL BL;
MOV CL,AL;
MOV AL,00H;
HLT;
```

## Output  
![Mul](https://user-images.githubusercontent.com/93427253/189387733-46260ec2-a62c-4db7-9574-8ed4ac11d5d5.png)
![Mul 1](https://user-images.githubusercontent.com/93427253/189387766-f91bde00-188c-44c1-bf3d-5de5ad699042.png)

## Flag
![Mul 2](https://user-images.githubusercontent.com/93427253/189387835-23446350-70ac-41d2-b2f6-abccd6fe314c.png)

## Division of 8 bit ALP
```
name "DIVISION"
org 700h
MOV AL,40H;
MOV BL,02H;
DIV BL;
MOV CL,AL;
MOV AL,00H;
HLT;
```

## Output  
![Div](https://user-images.githubusercontent.com/93427253/189387924-a05b47e7-55f9-44d3-a9d5-8c41bcc13da3.png)
![div 1](https://user-images.githubusercontent.com/93427253/189387945-50cf6447-c57a-47d8-8623-68f02c2678dd.png)

## Flag
![div 2](https://user-images.githubusercontent.com/93427253/189388008-a2564967-6216-4380-929e-00a7d3a6822e.png)

## Result :
Thus, a program is executed on ALP for the fundamental arithmetic and logical operations. 

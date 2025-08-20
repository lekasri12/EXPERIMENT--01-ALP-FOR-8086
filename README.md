# EXPERIMENT--01-ALP-FOR-8086
### Name : LEKASRI G
### Roll no : 212223100025 
### Date of experiment : 20/08/2025
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

## Addition  of 8 bit ALP 
```
MOV AX, 24H
MOV BX, 50H
ADD AX, BX
HLT

```

## Output  
<img width="1920" height="1080" alt="Screenshot 2025-08-20 105443" src="https://github.com/user-attachments/assets/cd75014e-db83-4ca4-98cc-b19d84b930ff" />


## Subtraction   of 8 bit numbers  ALP :
```
MOV AX, 45H
MOV BX, 50H
SUB AX, BX
HLT
```
## Output  
<img width="1920" height="1080" alt="Screenshot 2025-08-20 105513" src="https://github.com/user-attachments/assets/7a5c9213-bfc5-4f4f-9a36-d02b38e2853a" />

## Multiplication alp :
```
MOV AX, 53H
MOV BX, 24H
MUL AX
HLT

```

 ## Output : 
<img width="1918" height="1075" alt="Screenshot 2025-08-20 102723" src="https://github.com/user-attachments/assets/dbb05153-2802-4fa4-916a-fdfa299c1ab9" />


## Division alp :
```
MOV AX, 12H
MOV BX, 24H
DIV AX
HLT

```

## Output  :
<img width="1919" height="1079" alt="Screenshot 2025-08-20 102911" src="https://github.com/user-attachments/assets/f467eabe-04a5-4e26-9ff3-71480dcc46f2" />

## PROGRAM FOR LOGICAL OPERATIONS
## AND:
```
MOV AX, 12H
MOV BX, 24H
AND AX, BX
HLT

```

## OUTPUT:
<img width="1920" height="1080" alt="Screenshot 2025-08-20 103150" src="https://github.com/user-attachments/assets/73ea86ee-f64e-4ec8-b59a-8583fc5c5bf5" />

## OR :
```
MOV AX, 20H
MOV BX, 50H
OR AX, BX
HLT

```

## OUTPUT:
<img width="1920" height="1080" alt="Screenshot 2025-08-20 103258" src="https://github.com/user-attachments/assets/8f358d54-242a-4728-935e-9bd7ab7b5ba7" />

## XOR :
```
MOV AX, 15H
MOV BX, 30H
XOR AX, BX
HLT
```

## OUTPUT:
<img width="1920" height="1080" alt="Screenshot 2025-08-20 103348" src="https://github.com/user-attachments/assets/99f2a9d2-e688-4b00-ba70-b5007b44d7c5" />

## NOT:
```
MOV AX, 220H
NOT AX
HLT

```

## OUTPUT:
  <img width="1920" height="1080" alt="Screenshot 2025-08-20 103433" src="https://github.com/user-attachments/assets/fca134a7-7903-4ec5-b2fb-fa889dab1526" />



## Result :
The execution of ALP on fundamental arithmetic and logical operations is successfully completed.
 









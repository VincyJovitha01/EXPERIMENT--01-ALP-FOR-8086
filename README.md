# EXPERIMENT--01-ALP-FOR-8086
#### Name :Vincy Jovitha V
#### Roll no :212223230242
#### Date of experiment :22.04.2026



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

## Addition  of 16 bit ALP 
```
MOV AX,1234H
MOV BX,0110H 
ADD AX,BX
MOV [3001H],AX
ret
```
## Output  
<img width="1463" height="977" alt="Screenshot 2026-04-22 111838" src="https://github.com/user-attachments/assets/1af8bad6-19c3-4158-ab20-0605ddcae948" />
 
## Subtraction   of 16 bit numbers  ALP 
 ```
MOV AX,1234H
MOV BX,0110H 
SUB AX,BX
MOV [3003H],AX
ret
```
## Output 
<img width="1579" height="1019" alt="Screenshot 2026-04-22 111913" src="https://github.com/user-attachments/assets/e084c552-40f6-4ec2-9d06-9433975d6a7a" />

## Multiplication of 16 bit numbers  ALP 
```
MOV AX,1234H
MOV BX,0110H 
MUL BX
MOV [3005H],AX
ret
```
 ## Output  
<img width="1307" height="1017" alt="Screenshot 2026-04-22 112122" src="https://github.com/user-attachments/assets/3a6644af-fad9-454a-96c9-53ef836bc6e3" />


## Division of 16 bit numbers  ALP 
```
MOV AX,1234H
MOV BX,0110H 
DIV BX
MOV [3007H],AX
ret
```

## Output  
<img width="1471" height="1018" alt="image" src="https://github.com/user-attachments/assets/e2eb55cc-bd80-4128-9475-e93cedbcd490" />

## Programs for logical  operations
## AND  Operation
```
org 100h

MOV AX,1234H
MOV BX,0006H
OR AX,BX
MOV [4001H],AX
ret
```
## Output  
<img width="1181" height="1019" alt="Screenshot 2026-04-22 112612" src="https://github.com/user-attachments/assets/ef9c9b23-5b93-4e1d-ab9b-9fc15a4a90c6" />

## OR Operation
```
org 100h

MOV AX,1234H
MOV BX,0110H
OR AX,BX
MOV [4003H],AX
ret
```
## Output  

<img width="1339" height="1015" alt="Screenshot 2026-04-22 112801" src="https://github.com/user-attachments/assets/fc61ac67-b3bc-437f-a379-fdf59e47cb01" />

## X-OR Operation
```
org 100h

MOV AX,1234H
MOV BX,0150H 
XOR AX,BX
MOV [4005H],AX
ret
```
## Output  
<img width="1310" height="1015" alt="image" src="https://github.com/user-attachments/assets/dbecde1c-c8a6-4842-9f94-2c1daba9f62e" />

## Result :
 Thus the execution for ALP on fundamental arithmetic and logical operations in done on 8086 microprocessor.











# Name :DHARSHINIYAA K S
# Roll no: 212223100004
Date of experiment : 18.08.2025
# EXPERIMENT--01-ALP-FOR-8086

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
org 100h

mov ax,5a23h
mov bx,2cdbh
add ax,bx
ret
```

## Output:

 <img width="1257" height="794" alt="Screenshot 2025-08-18 140625" src="https://github.com/user-attachments/assets/41e61d33-677b-4629-b73c-9c6be5f6dc43" />

## Subtraction   of 8 bit numbers  ALP :
```
org 100h

mov ax,5a23h
mov bx,2cdbh 
sub ax,bx
ret
```

## Output:

<img width="1243" height="782" alt="Screenshot 2025-08-18 140543" src="https://github.com/user-attachments/assets/be562a9e-2bc2-4b12-9fcc-0f12c4787a1d" />


## Multiplication alp:
```

org 100h

mov ax,5a23h
mov bx,2cdbh 
mul 3 ax,bx
ret
```

 ## Output  

<img width="1270" height="791" alt="Screenshot 2025-08-18 140449" src="https://github.com/user-attachments/assets/f6c2dbdd-30df-42e2-a68c-3a2c3615af65" />


## Division alp :
```

org 100h

mov ax,5a23h
mov bx,[2cdbh] 
div 3 ax,bx
ret
```

## Output  

<img width="1235" height="805" alt="image" src="https://github.com/user-attachments/assets/698aadda-40ad-4e04-b3ed-96c3f28cd569" />
## AND alp:
```
org 100h

mov al,34h
mov bl,2ah
and bl,al
hlt
```

## Output:
<img width="1228" height="758" alt="Screenshot 2025-08-18 143225" src="https://github.com/user-attachments/assets/ccf3d1a7-2e82-40ea-8209-59b7c884bce3" />

## OR alp:
```
org 100h

mov al,34h
mov bl,2ah
or bl,al
hlt
```
## Output:
<img width="1265" height="802" alt="Screenshot 2025-08-18 144543" src="https://github.com/user-attachments/assets/cbe9a861-135d-405f-b6fe-667e51031de7" />

## X-OR alp:
```
org 100h

mov al,34h
mov bl,2ah
xor bl,al
hlt
```
## Output:
<img width="1230" height="783" alt="Screenshot 2025-08-18 144724" src="https://github.com/user-attachments/assets/3f7e7de3-3661-4c92-ab8a-aad360e3065d" />

## NOT alp:
```
org 100h

mov al,34h
not al
hlt
```
## Output:
<img width="1261" height="806" alt="image" src="https://github.com/user-attachments/assets/0d1e701c-a313-461c-a94f-64be58dc6c64" />

## Result :
 
Thus the given operations are executed successfully.

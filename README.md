# Name :DHARSHINIYAA K S
# Roll no: 212223100004
Date of experiment : 21.08.2025
# EXPERIMENT--01-ALP-FOR-8086

# Aim: To Write and execute ALP on fundamental arithmetic and logical operations
# Components required: 8086  emulator 
# Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 # Running the Emulator :
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


# Programs for arithmetic  operations

# Addition  ALP 

```
org 100h

mov ax,5a23h
mov bx,2cdbh
add ax,[bx]
ret
```

# Output:

 <img width="1270" height="900" alt="image" src="https://github.com/user-attachments/assets/2a84d804-ad1e-4a88-b2b2-96aaa484a619" />

# Subtraction   ALP :

```
org 100h 

org 100h
mov bx,5a23h
mov ax,[5a23h]
sub  ax,bx


ret
```

# Output:

<img width="1205" height="902" alt="image" src="https://github.com/user-attachments/assets/776b2186-9883-445c-bd7a-ce3543a01d94" />



# Multiplication alp:

```
org 100h

mov ax,5a23h
mov bx,2cdbh 
mul 3 ax,bx
ret
```

 # Output  

<img width="1270" height="791" alt="Screenshot 2025-08-18 140449" src="https://github.com/user-attachments/assets/f6c2dbdd-30df-42e2-a68c-3a2c3615af65" />


# Division alp :

```
org 100h

mov ax,5a23h
mov bx,[2cdbh] 
div 3 ax,bx
ret
```

# Output  

<img width="1235" height="805" alt="image" src="https://github.com/user-attachments/assets/698aadda-40ad-4e04-b3ed-96c3f28cd569" />
# AND alp:

```
org 100h

mov ax,5a23h
mov bx,2cdbh 
and ax,bx
hlt
```

# Output:
<img width="1244" height="889" alt="Screenshot 2025-08-21 132251" src="https://github.com/user-attachments/assets/3e2eb1d9-d1f4-4933-88bc-8aaccf223c00" />


# OR alp:

```
org 100h

mov ax,5a23h
mov bx,2cdbh 
or ax,bx
hlt
```

# Output:

<img width="1236" height="888" alt="Screenshot 2025-08-21 132759" src="https://github.com/user-attachments/assets/68e89adf-62ee-4228-a6ad-a7bfcafbaeab" />

# X-OR alp:

```
org 100h

mov ax,5a23h
mov bx,2cdbh 
xor ax,bx
hlt
```

# Output:

<img width="1232" height="889" alt="Screenshot 2025-08-21 132855" src="https://github.com/user-attachments/assets/884c2d02-323e-4e24-a461-10323ecc0d3a" />

# NOT alp:

```
org 100h

mov ax,5a23h
not ax,bx
hlt
```

# Output:
<img width="1206" height="897" alt="Screenshot 2025-08-21 132703" src="https://github.com/user-attachments/assets/c2673c7f-3fd4-40a0-bd25-1f8472b76d71" />



# Result :
Thus the given operations are executed successfully.

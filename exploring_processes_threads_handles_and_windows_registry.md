# 3.2.11 Lab - Exploring Processes, Threads, Handles, and Windows Registry

## Process Explorer 

It is a program that displays a list of currently running processes. As an example I used DuckDuckGO and found the process using the "Find Windows Processes -tool" highlighted as red. After selecting the tool you can click whichever application/windows you want and the chosen process is displayed.

<img width="1570" height="1174" alt="image" src="https://github.com/user-attachments/assets/36da3878-0b7a-41bc-b2ad-3a0fce3cb591" />

### Killing the process 

Clicking riht mouse on the wanted process allows you to kill the process


<img width="1568" height="1173" alt="Screenshot 2026-01-22 123315" src="https://github.com/user-attachments/assets/63d25809-9aaf-4303-8d8d-599158a5531c" />

### Command Promt ping test 

Next I opened CMD and chose it from Process Explorer. As we can see cmd.exe has a child process conhost.exe

<img width="1452" height="1166" alt="image" src="https://github.com/user-attachments/assets/38d0431d-edc2-4bc2-ad79-d320d311589c" />

### Doing a ping test

As we can see there appears a PING.EXE process when performing a ping test from the cmd.

<img width="1446" height="1164" alt="image" src="https://github.com/user-attachments/assets/4bf88e3f-62fd-4095-8775-0891f620a563" />

<img width="1395" height="734" alt="image" src="https://github.com/user-attachments/assets/435b1a75-8d2f-412c-918a-a4e3a3c00a9d" />

Finally I killed the cmd.exe process 

<img width="1459" height="1180" alt="Screenshot 2026-01-22 124645" src="https://github.com/user-attachments/assets/b024b14c-246b-4fcd-a835-fa82ea5704a4" />


# Exploring Threads and Handles

As threads example I opened cmd from Windows and from Process Explorer `conhost.exe` properties and `threads` -tab from there. 

<img width="956" height="1190" alt="image" src="https://github.com/user-attachments/assets/e3c8045b-81ec-4572-af97-b44d384eb156" />

<img width="954" height="1194" alt="image" src="https://github.com/user-attachments/assets/1a08c05b-5026-4814-a452-2fb76122d499" />

# Exploring Handles 


<img width="1436" height="987" alt="Screenshot 2026-01-22 130316" src="https://github.com/user-attachments/assets/8a3a12c6-179e-4406-bd20-30261a08e62d" />


<img width="1432" height="802" alt="image" src="https://github.com/user-attachments/assets/561d4937-feb7-4ef1-b37c-db2957c2a886" />


# Exploring Windows Registry







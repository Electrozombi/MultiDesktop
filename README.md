MultiDesktop V 1.0
------------------
A windows systray tool that let you choose between 4 different Desktops!
Each of the 4 desktop's can have seperate files/shortcuts/whatever on them.
The layout of each desktop is saved and restored via ReIcon from https://www.sordum.org/8366/reicon-v1-9-restore-desktop-icon-layouts/

Installation Guide:
-------------------
(1) Open Powershell (ISE) as admin and type: 

Set-ExecutionPolicy Unrestricted -force

(this will running unsigned powershell scripts on your system)

(2) Go to C:\Users\Public\Desktop and move all shortcuts from there to your Desktop!

(if you don't these icons will be on each desktop)

(3) Paste the MultiDesktop folder to C:\

(so C:\MultiDesktop\)

(4) Run MultiDesktop.exe

About:
------
The program is written in powershell and compiled per PS2EXE-GUI.

Additional Info:
----------------
To make it start with windows create a task in task planing pointing to the MultiDesktop.exe and choose when user logs on.

Contact:
--------
ezpi@web.de

System Requirements:
--------------------
Windows 10 Pro 32/64

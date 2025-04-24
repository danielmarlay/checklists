# Daniel Marlay's notes for setting up the environment to run on Windows

## Source repository

Repository was sourced from here:

https://github.com/dpwiese/checklists

## Setting up a make environment

I think the approach that I am going to use is the MSYS2 approach.

https://www.msys2.org/

### Steps

1) Downloaded the installer from: https://github.com/msys2/msys2-installer/releases/download/2025-02-21/msys2-x86_64-20250221.exe
2) Run the installer and let it open a command window
3) Run the following command ```pacman -S mingw-w64-ucrt-x86_64-gcc```
4) Run the following command ```pacman -S make```
5) C drive is accessed under ```/c/``` path within MSYS
6) Download weasyprint windows zip from https://github.com/Kozea/WeasyPrint/releases
7) Copy Weasyprint.exe from the zip file to C:\msys64\usr\bin


## Other references

[GCC make on windows](https://github.com/Hugo0725/gcc-make-on-windows)

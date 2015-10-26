# PCSX2-in-Debian-Jessie-64bits
Repository that explains how to install PCSX2 in Debian Jessie of 64 bits.

Steps:

- sudo dpkg --add-repositories i386
- sudo nano /etc/apt/sources.list
- Add to sources.list:
    deb http://ftp.de.debian.org/debian sid main 
- DO NOT FORGET TO DELETE FROM sources.list AFTER INSTALL
- sudo apt-get update
- sudo apt-get install pcsx2

------------------------------------------------------------------------------------
Install BIOS in PCSX2:

Get bios from:

https://firedrop.com/3f056bd4d64181a9

Place it in the default folder for the PCSX2.
-------------------------------------------------------------------------------------
Use PS3 Sixaxis in PCSX2:

Plug it in (before PCSX2 it is running), run PCSX2 and configure the controller in PCSX2.





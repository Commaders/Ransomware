<h1 align="center">
   THE RANSOMWARE VIRUS
   <h1/>


<h1 align="center">
   RAASNet
</h1>

<h2 align="center">
   Visit our Onion site for a complete C&C !
  
   
   New Onion Domain:
   
   hplqdv5fo3vw3fjyamyer7yuc7xtvtop2j3fipc7psf3pxvhoqjoqkid.onion
</h2>

![license](https://img.shields.io/github/license/leonv024/RAASNet "License")
![compatible](https://img.shields.io/badge/Windows%2C%20Mac%20%26%20Linux-compatible-brightgreen "Platform")
![status](https://img.shields.io/website?down_message=Offline&label=Service%20Status&up_message=Online&url=https%3A%2F%2Fzeznzo.nl%2Flogin.py "Status")
![Security](https://img.shields.io/security-headers?label=Domain%20Security%20Grade&url=https%3A%2F%2Fzeznzo.nl "Security Grade")
![last commit](https://img.shields.io/github/last-commit/leonv024/RAASNet "Last Commit")




<p align="center">
  Ransomware As A Service
</p>


<h2 align="center">
   NOTICE!
   
   
   The GeoIP lib doesn't work on Python 3.9, so use Python 3.7!
   (or remove that function from the server code).
   
   We're currently testing other options for GeoIP lookups.
</h2>


![alt text](./Demo/RAASNET-demo.png)
![alt text](./Demo/panel1.png)
![alt text](./Demo/panel2.png)
![alt text](./Demo/new_profile.png)
![alt text](./Demo/demonware_demo.jpeg)

<h1 align="center">
  Super Fast Encryption!
</h1>
<br>

![alt text](./Demo/PyCrypto-vs-PyAES_demo_10fps.gif "Encryption Speed Demo")
<br>

<h1 align="center">
   Usage Demo
</h1>


<h1 align="center">
   Please read
</h1>
<br>
<p align=center>
   This project was made to demonstrate how easy ransomware are easy to make and how it work. The script works on Windows, Linux and MacOS. It is recommended to compile payload.py to EXE format to make it more portable.
</p>

<p align=center>
   I do work on security awareness trainings and test the IT security and safety for other companies and you guessed it; this was made for the demo section of my presentation, NOT TO EARN MONEY OR BRICK PEOPLES COMPUTERS.
</p>

<p align=center>
   This script does not get detected by any anti-virusses. Self made scripts go undetected 99% of the time. It's easy to write something nasty like ransomware, adware, malware, you name it. Again, this script was for research only. Not ment to be used in the open world. I am not responsible for any damage you may cause with this knowledge. 
</p>

<p align=center>
   I recommend using a VPN that allows port forwarding (For example; PIA VPN) when using this outside your network, or better, a cloud computer hosted elsewhere, like Amazon AWS. 
</p>

<p align=center>
   The conclusion of this project is that it is easy to brick a system and earn money doing it. This script doesn't use any exploits to achieve its goal, but can easily be coded into it as a nice feature.
</p>
<br>

<h1 align="center">
   Features
</h1>
<br>

+ Generate a ransomware payload
+ With or without GUI payload (SIDE NOTE: Use console payload (No GUI) if you execute it from a remote system or Terminal.)
+ FUD (Fully Undetectable by Anti-Virus)
+ Works on Windows, MacOS and Linux
+ Super fast encryption with PyCrypto
+ Compile to EXE, APP or Unix/Linux executable
+ Custom icon for your EXE payload
+ Receive keys of victims
+ Decrypt files
+ Demo mode (payload won't encrypt anything)
+ Fullscreen mode (Warning takes over the screen)
+ Custom warning message for your victim
+ Custom image in your payload
+ Ghost mode (Rename by adding .DEMON extention instead of encrypting the files)
+ Multiple encryption methods
+ Select file extentions to target
+ Decide if payload should self-destruct (Console mode feature only)
+ Decide wich drive to target for encryption (working directory)
+ Verified server access through port forwarding VPN
+ Encode payload as Morse code

<h1 align="center">
   Installation
</h1>

Download and install the latest version of Python 3.<br>
<br>
Then do:<br>
```Shell
git clone https://github.com/Commaders/Ransomware.git
```

```Shell
pip3 install -r requirements.txt
```

```Shell
python3 Commaders.py
```

On Linux, you might need to install these packages:
```Shell
sudo apt install python3-tk python3-pil python3-pil.imagetk libgeoip1 libgeoip-dev geoip-bin
```

Testing connection with remote server:
```Shell
# Change the host and port in test_socket.py, default is 127.0.0.1 on port 8989
python3 test_socket.py
```

----
# Disclaimer
I am not responsible for any damage you might cause with this tool. Use at own risk and for testing and learning only! I made this to test AV's and demo purposes only! Use this to avoid ransomware and make better tools against it because current AV tools and ransomware shields are not good enough!

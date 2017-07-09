# iPhone 3G[S] Untethered Downgrade
<br/>
I am going to make a tutorial how to downgrade 3G[S] (both new and old bootrom) to any iOS version. This ONLY works on 3G[S], not iPod touch or iPad.
<br/>
<br/>
Requirements (X.Y.Z = firmware version):
<br/>
  - iPhone 3G[S] (obviously)
  - Windows XP or later, or Mac OS X 10.7 or later
  - Linux Computer or Mac OS X 10.7 - 10.9 (Live Linux USB using WinSetupFromUSB/YUMI Multiboot/etc. works)
  - Redsn0w 0.9.15b3
  - X.Y.Z_iPhone3GS_24Kpwn.ipsw downloadable at bottom of page
  - X.Y.Z Official Apple IPSW
  - 4.3.5 Apple IBSS (uploading, or find in 4.3.5 IPSW)
  - iTunes
  - Some patience

<br/><br/>
Steps:
  1) Enter Pwned DFU<br/>
  2) Restore to the 24Kpwn ipsw (this works on new bootrom 3G[S], don't worry)<br/><br/>
  -_STOP IF YOU HAVE OLD BOOTROM, NEW BOOTROM KEEP GOING_-<br/><br/>
  3) Switch to linux PC (LiveUSB: click <a href='#LiveUSB'>here</a> to learn how to get to Linux if you do not know)
  <br/>4) Download iPwnDFU (https://github.com/axi0mX/ipwndfu#open-source-jailbreaking-tool-for-older-ios-devices) and extract it
  <br/>5) Put iOS 4.3.5 IBSS in the iPwnDFU folder
  <br/>6) Open a terminal emulator (Konsole, Terminal, etc.)
  <br/>7) Open the iPwnDFU folder (cd [Path])
  <br/>8) ./ipwndfu -p    - Enter Pwned DFU
  <br/>9) ./ipwndfu -x    - Flash NOR
  <br/>10) redsn0w > Just Boot if it does not autoboot
  <br/><br/>DONE!<br/>
  
  <br/><br/><br/>If you have issues: 
    <br/>Text me @ +1 612 469-7455
    <br/>Email me iPG1101@outlook.com
    
  <br/><br/><br/>Download links: https://drive.google.com/drive/folders/0Bx2X3o1VIqhEUzF6blRiVEgtVk0?usp=sharing (uploading more for the next week)<br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><b id='LiveUSB'>Live USB</b><br/>If you know how to boot from USB, do that. If you don't know, it depends on model. If its an HP Laptop, press ESC to get to a pause screen to find out for sure, or press F9. Otherwise, F12 is common. For me, I have an ASUS board, I press F2 to enter UEFI >Boot section> USB drive. Just google it if you do not know. (To create a USB, I reccomend using UUI (Universal USB Installer - https://www.pendrivelinux.com/universal-usb-installer-easy-as-1-2-3/) and Linux Mint - 32 bit, if you know for a fact your CPU is 64 bit, then use 64 bit, but 32 bit works on everything. I used 64)

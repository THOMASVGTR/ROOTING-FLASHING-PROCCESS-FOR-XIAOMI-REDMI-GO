# ROOTING+FLASHING-PROCCESS-FOR-XIAOMI-REDMI-GO
This process will tell you how you can root your Xiaomi Redmi Go phone easily.
AUTHOR IS NOT LIABLE FOR YOUR DEVICE BRICKING OR SOMETHING IF HAPPENS.
Do everything at your own risk.

# REQUIREMENTS:
1) A PC or LAPTOP WITH WINDOWS 10(RECOMMENDED) or UBUNTU LINUX or LINUX MINT or MACOS.
2) UNIVERSAL ADB DRIVER INSTALLER (Download the appropriate version for your OS)
  LINK: https://www.xda-developers.com/install-adb-windows-macos-linux/
3)AN ANDROID PHONE with ANDROID USB DEBUGGING ENABLED. HOW to enable? 
  Follow the previous link, every instruction is given there.
4) NEED SOME BRAINS from your head.
5) A Redmi go phone with UNLOCKED boot loader. IF bootloader is LOCKED, YOU HAVE TO UNLOCK IT.


# HOW TO UNLOCK BOOTLOAER FOR REDMI GO DEVICES:
=> ADB DRIVER HAVE TO BE INSTALLED ON YOUR COMPUTER. Install that from the link which I have given or requirements.

=> BOOT your Redmi go phone to FASTBOOT mode by holding power button and volume down button at the same time until it boots into the 
    FASTBOOT mode.

=> OPEN your computers C: drive's adb folder. Do not CLOSE or minimize the opened ADB window. 

=> Then open command prompt or powershell by holding SHIFT button + RIGHT CLICK to your mouse.

# NOW GIVE COMMAND:
 fastboot oem unlock-go

# HOW TO ROOT:
=> BOOT your Redmi go phone to FASTBOOT mode by holding power button and volume down button at the same time until it boots into the 
    FASTBOOT mode.

=> Download recommended custom recovery (TWRP) for your XIAOMI REDMI GO device.
  Link: https://sourceforge.net/projects/tiare/files/Custom%20Recovery/TWRP/

=> Place this recovery.img to your computers C: drive's adb folder. Do not CLOSE or minimize the opened ADB window. 

=> Then open command prompt or powershell by holding SHIFT button + RIGHT CLICK to your mouse.

# NOW GIVE A COMMAND or copy and paste it to CMD or POWERSHELL or TERMINAL window:
   fastboot flash recovery recovery.img

# HOW WE CAN BOOT INTO RECOVERY:
=>  BY PRESSING WITH HOLDING THE POWER BUTTON AND VOLUME UP BUTTON.

# NOW INSTALL [MAGISK for android 8.1.0 / android 9.0] or [MAGISK(phh) for android 10 ONLY].
https://sourceforge.net/projects/tiare/files/Magisk/

=> DOWNLOAD THE APPROPRIATE version for your OS,  [8.1.0(OREO) and 9(PIE) is the same].

# MAGISK INSTALLATION:
=> TRANSFER THE zip file of MAGISK to your Memory card or SD Card.

=> Then mount SD card in recovery then navigate the Magisk's zip file. Then slide to install.

=> Now press home button in twrp then select Reboot/restart option after that press reboot to system and you are done.


# INTERESTED in CUSTOM AFTER ROOTING?

IT is very easy.

link:  https://github.com/THOMASVGTR/ROOTING-FLASHING-PROCCESS-FOR-XIAOMI-REDMI-GO/blob/master/HOW%20TO%20FLASH%20CUSTOM%20ROMS%20AFTER%20ROOTING%20XIAOMI%20REDMI%20GO.txt








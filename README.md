# ROOTING+FLASHING-PROCCESS-FOR-XIAOMI-REDMI-GO
This process will tell you how you can root your Xiaomi Redmi Go phone easily.
AUTHOR IS NOT LIABLE FOR YOUR DEVICE BRICKING OR SOMETHING IF HAPPENS.
Do everything at your own risk.

    [YOUR VALUABLE DATA WILL GOING TO BE VANISHED. SO BACKUP EVERYTHING TO YOUR COMPUTER (RECOMMENDED) OR SD CARD].

# REQUIREMENTS:
1) A PC or LAPTOP WITH WINDOWS 10(RECOMMENDED) or UBUNTU LINUX or LINUX MINT or MACOS.

2) UNIVERSAL ADB DRIVER INSTALLER (Download the appropriate version for your OS)
  LINK: https://www.xda-developers.com/install-adb-windows-macos-linux/
  
3) AN ANDROID PHONE with ANDROID USB DEBUGGING ENABLED. HOW to enable? 
  Follow the previous link, every instruction is given there.
  
4) NEED SOME BRAINS from your head.

5) A Redmi go phone with UNLOCKED boot loader. IF bootloader is LOCKED, YOU HAVE TO UNLOCK IT.


# HOW TO UNLOCK BOOTLOAER FOR REDMI GO DEVICES:
=> ADB DRIVER HAVE TO BE INSTALLED ON YOUR COMPUTER. Install that from the link which I have given on requirements.

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


# INTERESTED in CUSTOM ROM AFTER ROOTING?

IT is very easy.

# INSTRUCTIONS: 
link:  https://github.com/THOMASVGTR/ROOTING-FLASHING-PROCCESS-FOR-XIAOMI-REDMI-GO/blob/master/HOW%20TO%20FLASH%20CUSTOM%20ROMS%20AFTER%20ROOTING%20XIAOMI%20REDMI%20GO.txt

1) DOWNLOAD A SMALL SOFTEARE AND PLACE IT TO YOUR C: Drive's adb folder.

2) Copy and Paste the link to your browser and click the download button, IF you have not downloaded yet.

Link:  https://github.com/THOMASVGTR/ROOTING-FLASHING-PROCCESS-FOR-XIAOMI-REDMI-GO/blob/master/GSI%20FIRMWARE%20FLASHER%202.0%20(LATEST).exe

3) Download the Redmi Go flash file. (COPY AND PASTE THE LINK).

Link:  https://drive.google.com/file/d/1PJ3gwq9jtEhaeBX5a9bXY-2APf46ZsvI/view

    [Google sign in required while downloading the flash file].
    
4) After downloading the flash file successfully, unzip or extract it.

5) Now go inside the flash file and you will see a folder named Firmware. 
   Just double click to open it.

6) You will see also a FOLDER, named images.

7) Now you have to copy some files to your C: Drives ADB folder.
   
   The files are, 
   
                  =>boot.img
   
                  =>cache.img
                  
                  =>persist.img
                  
                  =>recovery.img (Do not copy it if you have already a custom recovery
                                    inside ADB folder).
                  =>splash.img
                  
                  =>system.img
                  
                  =>userdata.img
                  
                  =>vendor.img

8) Now it is time to download the custom rom:

LINK: https://github.com/phhusson/treble_experimentations/wiki/Generic-System-Image-%28GSI%29-list

Download any rom like HAVOC OS or CAOS.

click download button and search the  "ARM-AONLY" version. Size should be 300mb to 500mb.

Note: more than 500mb will be failed to install on REDMI GO phone.

9) Unzip or extract the rom you have downloaded. Rename this downloaded image to system. (do not include .img extension).

10) copy your renamed rom file to C: drive's ADB folder.

11) now RUN the GSI FLASHER.exe and wait until it loads.

12) boot your redmi go phone to fastboot mode. Connect your phone to your computer via USB cable. Unlock the boot loader if locked.

13) Now from GSI FLASHER.exe press 1 from keyboard to navigate the FLASH ALL mode. After flashing successfully, then you are DONE.

# LINK OF THE FLASHER SOFTWARE:
https://github.com/THOMASVGTR/ROOTING-FLASHING-PROCCESS-FOR-XIAOMI-REDMI-GO/blob/master/GSI%20FIRMWARE%20FLASHER%202.0%20(LATEST).exe

Download it now. PLACE this software exe file to C: drive's adb folder.

 # NOW ENJOY YOUR NEW ROM.


# BOOTLOOPS (STUCK ON LOGO) ISSUES:

=> After passing 4 to 5 minutes and your phone still booting or stuck at the logo, then you have to go to the recovery mode by pressing power button and volume up key.

=> Now you have to flash 2 (two) more zips. 1)Permissiver_v5.zip 
                                            2)decrypt.zip
                                            3)Boot animation replacer.zip

# Permissiver.zip



# Decrypt.zip


# Boot Animation Replacer.zip



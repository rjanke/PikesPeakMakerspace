# How to install Linux onto a Mac or PC.

## Step 1
Create a bootable USB drive.
- Download [UNnetbootin](https://unetbootin.github.io/). Support for Windows, Linux, and Mac.
- Download the .iso file of the distribution (OS) you want. Like [Linux Mint](https://linuxmint.com/download.php). UNetbootin can also do this for you for many different OS(s), but the download will be faster if you can choose a local mirror. 
- Select Diskimage and select your downloaded .iso and your USB drive (at least 8GB to be safe) that you want to format and turn into a bootable USB drive. Caution: this will erase everthing on the drive.
- Press OK.
- Wait until UNetbootin is done and your flashdrive is ready.

## Step 2
Boot into new OS. 
- Plug your bootable USB into the destination computer you wish to insall Linux on. 
- Shut the destination computer down. Restart it and quickly...
- On Mac, hold the Option key to enter the boot screen menu. Choose USB device. 
- On Windows, hold down the F12 or F2 key to enter the boot screen menu. Choose USB device.
- Select the new operating system (usually the first option). 
This will boot the computer into the OS on the flashdrive.

## Step 3
Install OS on the computer. 
- There will usually be an icon on the Desktop that says Install Linux Mint (for example). 
- Click that and run through the installation process.
- It's a good idea to install 3rd party media codecs if this is your first time around Linux. If the choice is given to you, of course. 
- You can choose if you want to erase the whole disk, dual boot, etc. when installing. 

### Get an Error?
Error: Install from USB fails "An attempt to configure apt to install additional packages" 

Solution originally from this [forum](https://forum.kodi.tv/showthread.php?tid=126351).
1. Run the USB install as normal
2. When you get to the screen where you enter your user name, pc name, etc. CTRL-ALT-F1 to get a shell.
3. Run this command
> sudo rm /usr/lib/ubiquity/apt-setup/generators/40cdrom
for password just press enter
4. Press CTRL-ALT-F7 to get back to your install
5. Fill out your username password, etc as usual and continue and the install should continue and finish. 

For Linux Mint the username is 
```
$ mint
```
And the just press 'Enter' for the password. This will grant you access to the shell. [Source](https://forums.linuxmint.com/viewtopic.php?t=105008).

## Step 4
That's it! Welcome to Linux.

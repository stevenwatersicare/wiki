## Preparing a Windows 10 Computer for an Optician	(Before Disk Cloning)

#### Before Disk Cloning With CloneZilla

1.Disable EFI (**EFI should be reenabled before the computer sent out!!**)
2.Log into Windows
3.Create an **Admin** account called IT
4.Set the standard IT password we have been using for the IT account.
5.Uninstall bloatware and premium software which include but are not limited to:
- software that appear to be games (i.e. minecraft, candy crush saga, etc. )
- netflix, plex, XBOX and other media related software. The actual Windows Media player program shouldn't be uninstalled.
- The Microsoft Office Suite since we use OpenOffice as a replacement
- Dropbox Promotion software
- Skype
- Sketchbook
- Any Anti-Virus or Anti-Malware programs such McAffee (**except for Windows Defender**)
- View 3D Preview
- Remove SmartByte
- Any other third-party programs or browsers (unless it's Microsoft Edge or Firefox)
- All Dell Related Apps

6.Go to the the apps and features section in Windows 10 and set the dropdown for installing apps to "Warn me before installing apps from outside of the store." so you can install third-party apps.

7.Download, install, and run the following programs
- Angry IP Scanner (**The 32/64 bit version**)
- The Driver for the ABB Scanner and ABB Scanner Device Software (** Their software requires .NET**)
- The driver software and the program for the ABB scanner can be found on the following page: https://secure.abbconcise.com/Order/scanner.aspx
- Someone in IT should have a username and password for it, if not, then Ask Tyler Payne for access to it.
- The drivers should be called Opticon USB Drivers. The link in the instructions for the above page should take you to a website with a list of drivers. Click on the one for the USB Drivers.
- Follow the directions at the bottom of the page for installing .NET, the aforementioned scanner drivers, and the scanner software itself. The link to it is called "Upgrade".
- Latest version of LibreOffice (**But not the early adopter release** ): https://www.libreoffice.org/download/download/
- Latest version of ShareX: https://getsharex.com/downloads/
- Firefox Quantum: https://www.mozilla.org/en-US/firefox/


8.Create a new **Standard User** account called Optimart

10.Make sure to NOT set a password for that account 

11.Go to the search tool for Windows 10 and search for "Manage Your Account" or "Account" and open the program for setting the account's avatar. Then pin it to the task bar. This makes it easier for users to personalize the Optimart account further. 

12.Look for any lingering bloatware that might still be left over and unpin them from the task bar (including the mail app) and start menu. Also uninstall them if they are still installed for the Optimart profile. 


13.Set the avatar image for the IT account to following graphic. 

14.Go to Firefox Quantum > Options > and the default page to this (this will make it open up multiple tabs at once upon startup):
- https://ospre.optimart.com|http://webmail.optimart.com|https:forum.optimart.com/

15.Pin the following items to the taskbar and start menu: 
- Firefox Quantum
- Windows Calculator Program 
- ShareX
- Windows Explorer 

16.Add two printers to the computer, the ports should be set to the following host names: 

- hp-printer
- hp-printer2

17.Setup the 'Optimart' 2G WiFi Network

18.Make sure Windows Defender has the latest definitions 

19.Make sure Windows has the latest updates 

20.Clear browser Cache 

21.Adjust power settings: 

Screen 
- On battery power, turn off after: 15 minutes
- When plugged in, turn off after: 1 hour
Sleep
- On battery power, PC goes to sleep after
- When plugged in, PC goes to sleep after
1 hour

Go to aditional settings and select the power Saver" 

22.Rename the computer to Opitimart-000 (** The computer should be given a unique 3-digit post fix such as Optimart - 057 . Log into LogMeIn to see which number to use next.**)

23.Restart the computer

24.Test the following before cloning 
- Firefox is the default browser 
- Firefox loads Webmail, the Forum, and Ospre sites. 
- The computer is running normally and there is no lag (**note,windows indexing hasn't been turned off yet, so this could be something we could turn off in the future**)
- Windows Defender is running and is "actively protecting the pc" 
- 2G network WiFi is in the list of known networks for the pc 
- UEFI Secure boot is disabled for it 

25.Clone the computer using CloneZilla and don't forget to renable UEFI secure boot for it. 


#### Temporary post reflashing work

1.Disable RDP
2.Go to the settings for the power button and select the option that tells it to shut off the computer when it's pressed. 
3.Disable Cortana
4.Make sure Fastboot is On
5. Verify that the time is set to the correct time zone


#### Permanent post reflashing work 

1.Rename computer to a name such as Optimart-001, Optimart-002, etc. 
2.Install LogMeIn 
3. Verify that all of the virus and malware definitions for Windows Defender are updated
4. Verify that the computer is up to date with Windows Updates
5. turn off animations 
6. 5. Renable UEFI secure boot!





 












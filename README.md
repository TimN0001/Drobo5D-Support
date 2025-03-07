# DroboSupport
Drobo Support Firmware for 5D (5 Bay)

You will need the Drobo Software installed to install this custom firmware, provided by Drobo Support.

If you install this firmware it will make the drobo be in read only mode and use the second backup copy MBR. 
I had a MBR corruption on my drobo 5c and this was able to recover the data and allowed me to extract the data.
I then updated the firmware to the latest (4.2.3 [7.199.116068]) and have been using that for a few years now. 

This firmware is only to be used on the 5D model
![Screenshot of Drobo make model](https://github.com/TimN0001/DroboSupport/blob/main/droboscreenshot.png)



Here is a screenshot of the support email and below is the support firmware that is version 0.0.0
![Drobo Support firmware](https://github.com/TimN0001/Drobo5D-Support/assets/9089167/6f7e9116-791f-439f-95c0-98b014f6fece)

[Drobo5D_74114.zip](https://github.com/TimN0001/Drobo5D-Support/files/14539286/Drobo5D_74114.zip)




The issue I had and the firmware resolved was the drobo would start booting and the blue lights would move to one side (like a progress bar) and it would only load 90% and fail due to a coruption.  
I was told that the main NTFS MBR got corrupted and they make this custom firmware to use a secondary MBR and that allowed me to connect the drives long enough to copy all the data off.
After I copied all my data I wiped the drobo and installed the latest firmware and its been working so far. 





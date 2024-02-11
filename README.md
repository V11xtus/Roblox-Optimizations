# Roblox-Optimizations by REGENERATlON. 

	===============================
============ Some shit I wanna say: =================
	===============================

First of all make a restore point, because if you don't like something you can always restore it. 
Another thing I'd like to say is that all these reg edit optimizations is what for me feels the best and has worked the best for me on performance, 
so I can not promise you it will work for you.
These optimizations aim at smoothness and optimizations.

This list excludes disabling services, because I am to lazy to add them here, because I already have a program that does that for me. 

Also this mainly for Roblox by the way. ALSO I AM NOT LIABLE IF YOU FUCK UP YOUR PC OR IF YOU DONT SEE AN INCREASE IN PERFORMANCE EVERY PC IS DIFFERENT.


Anyways in this read me txt document I will also guide you so yeah.


First of all we are going to move to the .bat section. 



===================================================================
===========						===========
===========	        BAT Optimizations		===========
===========						===========
===================================================================


Step 1: 
You will run the NetOptimizations(as Administrator) this will clean your DNS cache. 

Step 2:
You see a TempFlusher.txt file. You must open it with Notepad and then edit the parts where it says "USERNAME" and edit it to your username on windows. 

Step 3: 
Change the ".txt" extension to a ".bat" extension. To this you will have to rename the file and only edit the extension part. After that you will run the batch file as administrator.
What does this batch file do? It basically deletes everyfile in your temp folder.


Notes: Do this once a week preferably everytime roblox updates.

Step 4:
You might see another batch file called "SetRobloxToHighPriority.bat". This is a batch file that sets roblox to higher priority everytime roblox runs. This saves you trouble with going through
task manager -> details and then setting the priority to high. Run this batch file everytime roblox is running and also run this as administrator.

Step 5:
Run "DisableServices.bat" as administrator. (If you don't like the disabled services, then you can run the "EnableServices.bat")

===================================================================
===========						===========
===========	        EXE Optimizations		===========
===========						===========
===================================================================

Moving onto the EXE optimizations. there are 4 exe files that are displayed here. 


===============================

	   Quick CPU

===============================
Step 1:
Run the installation file for Quick CPU "QuickCpuSetup-4.8.0.0-x64.msi". 

Step 2:
Open Quick CPU. AND DO NOT FUCK WITH THE SETTINGS IN QUICK CPU ESPECIALLY THE ADVANCED CPU SETTINGS TAB. 

Step 3:
Copy these settings.

https://imgur.com/a/BNQ4aSH

Step 4: 
Click Apply and exit. Also open taskmanager and go to startup apps and make sure, if it's enabled as a startup application make sure to disable it. 

===============================

	   CCleaner

===============================


Step 1:
Click on "ccsetup620.exe" and install CCleaner.

Step 2:
Open CCleaner. 

Note: Now what is CCleaner? CCleaner is an application that allows you to clean your PC. 
Like with a basic plan remove trackers, remove unneccesary registries, remove unneccesary files. 
With a premium 1 you can even do some driver updates and can have a similar effect as applications like Razer Cortex. 
Although I don't use these premium features. I only use this to remove trackers and clean up registries. 

Step 3:
Hover over the "Registry" tab and click it. You will see a tab that appears to be "registry cleaner".

Step 4:
Press scan for issues. 

Step 5: After it comes up with all the "issues"	and is finished with scanning you will then click review issues. 

Screenshot of what it should look like after you have scanned:
https://imgur.com/a/CNROIuW


Step 6: 
You will come accross a UI that pops up. Asking you if you want to make a restore point. Press no, because you are not stupid enough to be this far in and still have not made a restore point.

Step 7:
You will come accross another UI you said no. In this situation you will press "fix all selected issues".

Step 8: 
Repeat this process until you reach 0 issues or the same issues are reoccuring everytime. 

===============================

	MSI afterburner

===============================

step 1: 
Install MSI after burner.exe. 

Step 2: 
Use the MSI Overclocking Scanner and scan. 

Step 3: 
Save the config and run it background.

===============================

Regens ClientSettings Transfer

===============================

Step 1:

Open the folder called "RegensClientSettings Transfer"(This is made by me by the way). 

Step 2: 
You will see multiple files(There is no installer for this program, I am way to lazy to create 1). I will explain how this works. 


Step 3: 
This is optional, if you want to you can change the ClientAppSettings.json configurations. I have put a very basic 1 with basic optimizations for Roblox. 
Just make sure ClientSettings Folder is in the same directory as the Exe File so that it can transfer the folder. 


Step 4:
Run "MoveClientSettingsToRoblox.exe". 


===================================================================
===========						                                  ===========
===========	        Registry Edits			                ===========
===========						                                  ===========
===================================================================



Now here there aren't any steps it's kinda up to you what you want to use. WARNING some of these Reg edits are feature breaking. What this means is you will lose certain features while using Windows. KEEP THIS IN MIND BEFORE MAKING CHANGES. 

There are 20+ Reg edits that you be able to use. 



===================================================================
===========						===========
===========	        NVIDIA Graphics Profile		===========
===========						===========
===================================================================



So I don't own AMD, so this is useless if you have an AMD GPU. Anyways these are my settings for NVIDIA Control Panel. 

Step 1: 
Run Nvidia Profile Inspector.

Step 2: 
Don't fuck with this either all you have to do is press the import button in the top of your screen. 

Heres an image:
https://imgur.com/a/HIylmeJ

Step 3: Find and select "My Profile.nip"

Step 4: 
Press apply changes top right of your screen.


===================================================================
===========						===========
===========	        Disable startup apps		===========
===========						===========
===================================================================


Step 1: 
Run task manager.

Step 2: 
Go to the start up apps tab and disable all start up apps you dont want.




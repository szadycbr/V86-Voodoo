# V86-Voodoo
This is my Best of V86, its been long yourney.
I replaced Bochs adapter with S3Trio64 from Dosobox and added 3DFX from mame, ohh boy, was that thing incomplette, now mostly working.

It dont need http server, but to get it going in browser you must go into bios, set all ide channells to AUTO , then load setup defaults , save and exit.
Then go to bios again , use HDD autodetection and you should have hd, save and exit.

Firefox has litlle faster .wasm emulation for cpu, but Chrome has much faster Webgl/Voodoo in its V8 engine.

many games you can play, FM/OPL sound and MIDI works, still not perfect, timing is an issue, PCI bus had to be revamped And SeaBios also, so dont use other bios.
Resident Evil 3 works surprisingly well, even hevy begin sequence is "acceptable" 
I decoupled most of the thing from time per frame, primarly IDE so i got some speed boost.
Also you can save images less than 1Gb anything bigger you cant wih seabios version, cause i dont wont to load larger files into memmory, its an issue on mobile phone,
Award version is up to 4Gb.

Added experimental build with Award bios! Win98 installs without much of a problem. Bios settings are saved in html. Hot swap CD in windows dont work yet. You also must set hdd to auto in bios, cdrom is on secondary master. You can safely restart and shutdawn system , then safely save hd image. most of dos games work also,
Like Wolf3d, CatacombAbyss, etc. but remember for games that need more ems you must be creative in config.sys or autoexec.bat. it has 2Mb Lo-Tech EMS board , but i have not tested it, so it might not work and you need LTEMM.EXE driver (DEVICE=LTEMM.EXE /p:d000 /i:260). i need to fix Gods game flickering issue, but i was extremally happy when finally its tricky intro music played correctly :) "into...The Wonderfull" ;) yeahh!
Let me know in Discussions if anyone want src, then i will upload it.
https://www.youtube.com/watch?v=c37OYx9WIAc

And now quie nice Android app with fully working touch mouse! :)

<img width="1920" height="890" alt="nfs3-640x480-voodoo" src="https://github.com/user-attachments/assets/6fb833b3-04cc-4ba1-8d94-300856411193" />

<img width="1920" height="890" alt="Q2-640x480-voodoo" src="https://github.com/user-attachments/assets/621dcaf0-cb67-48c1-b595-595ea1c25490" />

<img width="1920" height="890" alt="RE3-voodoo-heavy" src="https://github.com/user-attachments/assets/83d22c6e-4c40-427f-a80e-b622cc180575" />

<img width="1920" height="890" alt="RE3-low" src="https://github.com/user-attachments/assets/108fc77e-df2f-421a-8815-04acc757b530" />

<img width="1920" height="890" alt="Airfix" src="https://github.com/user-attachments/assets/7927f719-da33-4501-9fe1-159bb69c04eb" />


<img width="1920" height="890" alt="Kingpin" src="https://github.com/user-attachments/assets/517a0199-36d6-40f5-bb7b-e167393ae1eb" />

<img width="400" height="700" alt="Q2-Android" src="https://github.com/user-attachments/assets/8fadeb79-5fee-429a-b3e7-d978df223e98" />


<img width="2340" height="1080" alt="fallout" src="https://github.com/user-attachments/assets/04227524-c782-44e5-8371-03f89e9556a7" />




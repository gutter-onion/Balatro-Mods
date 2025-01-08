# Balatro-Mods
Install script for Mod pack of CardSauce v.1.2.1 and Mika's Mod. 

To Download, click "Releases" on the right side of the page here, and select your Operating System.
Or click the links available here in the README.md

<b>Arch Linux Install</b> (Should work on steam deck as well)

Download [linux-install.sh](https://github.com/gutter-onion/Balatro-Mods/releases/download/mods/linux-install.sh) from the releases page. Open a terminal and navigate to
the directory where it was downloaded. 
Run:
```
chmod +x linux-install.sh
./linux-install.sh

```

<b>Windows install</b>

These Mods use code injection to work. And Windows will treat this as a virus/threat. You will need to disable any
Anti-Virus software you may have, as well as follow the directions below to temporarily disable Windows Defender.

<B>All files installed and downloaded here are open source, and you are free to
look at the code. (links below).</B>


Download both files named [windows-run-first.ps1](https://github.com/gutter-onion/Balatro-Mods/releases/download/mods/windows-run-first.ps1) and [windows-install.ps1](https://github.com/gutter-onion/Balatro-Mods/releases/download/mods/windows-install.ps1)
The windows Run first file will add the balatro Mod directory to the windows defender whitelist.

Right-click the file named "windows-run-first.ps1", and click run with powershell.

![swappy-20250107_235600](https://github.com/user-attachments/assets/95aa4b78-d394-4365-8961-9b80e4dd13d0)

Next, we need to disable realtime-protection before we execute the other script.

Click Start, and type "security", then click Windows Security.

![swappy-20250108_000219](https://github.com/user-attachments/assets/b373f797-8f59-4433-9e06-0afc2ec123f4)

Click on Virus and Threat Detection

click "Manage settings" under Virus & threat protection settings

![swappy-20250107_233212](https://github.com/user-attachments/assets/c258cded-be78-4147-ad4a-99b7f62ca9a2)

Turn off Real-time Protection

![swappy-20250107_233253](https://github.com/user-attachments/assets/6781a1db-707c-4b26-9e13-4f1410378a03)

You can turn this back on after this is all done :) 

Finally run the file "windows-install.ps1", the same way we did before.

![swappy-20250107_235600](https://github.com/user-attachments/assets/1cce7d58-82de-486e-bdf6-c08fe9e4833e)

That should do it!

 
Thanks to these wonderful people!


https://github.com/Steamodded/smods

https://github.com/ethangreen-dev/lovely-injector

https://github.com/MikaSchoenmakers/MikasBalatro

https://github.com/BarrierTrio/Cardsauce





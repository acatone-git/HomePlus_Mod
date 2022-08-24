# HomePlus Mod - L3/R3, Hotkeys & More on the RP2+!

This tiny software mod changes the function of the HOME button to an obscure, but still usable, modifier, combined with [Automate](https://llamalab.com/automate/) & some Shell Scripting, it unlocks the full potential of this great portable device!

Here's a (rough) demo of the mod in use : https://www.youtube.com/watch?v=IOeRG1G_UgY

## Default HomePlus Controls

- HOME + A  = Center Touchscreen Tap
- HOME + Y  = Application Switch / List
- HOME + X  = Brightness Up
- HOME + B  = Brightness Down
- HOME + L1 = L3
- HOME + R1 = R3
- HOME + L2 = Settings
- HOME + R2 = Back (Access menu on Dolphin & AetherSX2)
- HOME + SELECT = Home Button **[V2 Addition]**

# Disclaimer

If you decide to try this mod, please be careful, follow the video / written instructions closely & it should work.

If anything goes (very) wrong, read the [factory reset guide](https://github.com/acatone-git/Factory_Reset_RP2P) to fully recover the console back to the factory default.

# Requirements

- [HomePlus Install / Remove Files](https://github.com/acatone-git/HomePlus_Mod/releases/)
- A Good USB to USB-C Cable

# Installation [Video Tutorial]

- Download "HomePlus_Install.sh", "HomePlus_Scripts.bak" & "HomePlus_Layout.kl" from the [release page](https://github.com/acatone-git/HomePlus_Mod/releases/tag/1_Install)
- Copy the three files to the Internal Storage of the RP2+ **[NOT THE SD CARD / NO SEPARATE FOLDER]**
- Follow the installation video tutorial: https://youtu.be/O1rt_GJVZ1E
- Delete the three files from the Internal Storage, once the installation is complete they aren't needed anymore (Optional)

# Installation [Written Tutorial]

## Step 1

- Download "HomePlus_Install.sh", "HomePlus_Scripts.bak" & "HomePlus_Layout.kl" from the [release page](https://github.com/acatone-git/HomePlus_Mod/releases/tag/1_Install)
- Copy the three files to the Internal Storage of the RP2+ **[NOT THE SD CARD / NO SEPARATE FOLDER]**

## Step 2

- On the RP2+, go to Settings > Handheld Settings > Virtual Mouse
- Enable it, change the virtual mouse shortcut to START / SELECT (or both) & then disable it
- Now Scroll down to "Advanced" & Select "Run Script as Root"
- Select the file called "HomePlus_Install.sh" & tap on "Run"
- The HomePlus Installation script will run & restart the console

## Step 3

- After the restart, download, install & run [Automate](https://llamalab.com/automate/)
- In automate, tap on the menu icon (Three lines icon in the top left) & then on "Settings"
- Scroll down to the "Backup" Section & Select "Restore Backup"
- Select the file named "HomePlus_Scripts.bak" **[Now V2]**
- Return to the main menu, there should be **two** scripts there: "HomePlus - Retro" & "HomePlus - Xbox" **[Now V2]**

## Step 4

- Select any of the two script & tap on the missing privileges below
- Allow / Enable all the requested privileges / services (4 in total)
- Tap on the ticket icon (next to the share button) & disable logging 

## Step 5

- Find the controller layout currently in use in Settings > Handheld Settings > Controller Style
- Return to Automate & start the script matching the layout 
- Tap on "Start All" & That's it!
- Delete the three files from the Internal Storage, once the installation is complete they aren't needed anymore (Optional)

# Change Key Combinations / Create New Functions

- Read / Use the documentation & examples in the [development repo](https://github.com/acatone-git/HomePlus_Dev)
- Share your creations with the community! 

# Uninstall HomePlus

- Download "Remove_HomePlus.sh", "Remove_HP1.kl" & "Remove_HP2.kl" from the [release page](https://github.com/acatone-git/HomePlus_Mod/releases/tag/0_Remove)
- Copy the three files to the Internal Storage of the RP2+ **[NOT THE SD CARD / NO SEPARATE FOLDER]**
- Go to Settings > Handheld Setting > Scroll down to "Advanced" & Select "Run Script as Root"
- Select "Remove_HomePlus.sh" & tap on "Run"
- The script will remove HomePlus & restore the console back to default (after a restart)

# Credits & Thanks

https://www.goretroid.com/ (Retroid Pocket 2 Plus)

https://llamalab.com/automate/ (Automate)

https://www.youtube.com/user/HorreyForthenewstep (Factory Reset Files & Boot Sound Off Script)

https://llamalab.com/automate/community/flows/40412 (Shell Scripting Example)

https://androiderrors.com/simulating-combination-of-key-presses-from-adb-terminal/ (Find Valid Inputs)

https://unix.stackexchange.com/a/325350 (Find Permission Used on System Files)

https://stackoverflow.com/a/17263093 (Long Touch Sintax)

https://github.com/dchen327/ruzzle-solver/blob/master/ruzzle_swipe.sh (Chain Sendkey Commands)

https://www.cnblogs.com/pengdonglin137/articles/5408256.html (Dumpsys Input Filtering) 

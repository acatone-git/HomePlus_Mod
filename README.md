# HomePlus Mod - L3/R3, Hotkeys & More on the RP2+!

This tiny software mod changes the function of the HOME button to an obscure, but still usable, modifier, combined with [Automate](https://llamalab.com/automate/) & some Shell Scripting, it unlocks the full potential of this great portable device!

## Requirements

- The Three HomePlus Files **[COMING SOON]**
- A Good USB to USB-C Cable

# Installation Guide

## Step 1

- Download "HomePlus_Install.sh", "HomePlus_Scripts.bak" & "HomePlus_Layout.kl" from the release page **[COMING SOON]**
- Copy the three files mentioned above to the Internal Storage of the RP2+ **[NOT THE SD CARD]**

## Step 2

- On the RP2+, go to Settings > Handheld Settings > Virtual Mouse
- Enable it & change the shortcut keys to START / SELECT (or both) & then disable it again
- Now Scroll down to "Advanced" & Select "Run Script as Root"
- Select "HomePlus_Install.sh" & tap on "Run"
- The HomePlus script will run & the console will restart

## Step 3

- Download, Install & Run [Automate](https://llamalab.com/automate/)
- Now tap on the menu icon (Three lines icon in the top left) & then on "Settings"
- Scroll down to the "Backup" Section & Select "Restore Backup"
- Select "HomePlus_Scripts.bak"
- Return to the main menu, there should be **two** scripts there: "HomePlus - Retro" & "HomePlus - Xbox"

## Step 4

- Select any of the two script & tap on the missing privileges
- Allow / Enable all the requested privileges / services (4 in total)
- Tap on the ticket icon (next to the share button) & disable logging 
- Now Start the script matching your layout in Settings > Handheld Settings > Controller Style

## Step 5

- Tap on "Start All" & Have Fun!

# Default HomePlus Controls
## (Retro / Xbox)

- HOME + A  = Center Touchscreen Tap
- HOME + Y  = Application Switch / List
- HOME + X  = Brightness Up
- HOME + B  = Brightness Down
- HOME + L1 = L3
- HOME + R1 = R3
- HOME + L2 = Settings
- HOME + R2 = Back (Access menu on Dolphin & AetherSX2)

# Create / Change Key Combinations 

- Read / Use the instructions, documentation & examples in the development repo **[COMING SOON]**
- Share your creations with the community! 

# Credits & Thanks

https://www.goretroid.com/ (Retroid Pocket 2 Plus)

https://llamalab.com/automate/ (Automate)

https://www.youtube.com/user/HorreyForthenewstep (Factory Reset Files & Boot Sound Off Script)

https://llamalab.com/automate/community/flows/40412 (Shell Scripting Example)

https://androiderrors.com/simulating-combination-of-key-presses-from-adb-terminal/ 
(Sendkey Sintax & Finding Valid Inputs)

https://unix.stackexchange.com/a/325350 (Find Permission Used on System Files)

https://stackoverflow.com/a/17263093 (Long Touch Sintax)

https://github.com/dchen327/ruzzle-solver/blob/master/ruzzle_swipe.sh (Chain Sendkey Commands)

https://www.cnblogs.com/pengdonglin137/articles/5408256.html (Dumpsys Input Filtering) 

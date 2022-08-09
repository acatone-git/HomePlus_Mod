# HomePlus Project - RP2+ Soft Mod

This sofware mod changes the function of the HOME button to an modifier, combined with [Automate](https://llamalab.com/automate/) & Shell Scripting, it unlocks the full potential of this great portable device.

# Default Key Combinations (Retro Controller Style)

- HOME + A  = Back Button (Access Quick Settings in Dolphin / AetherSX2) 
- HOME + Y  = Application Switch / List
- HOME + X  = Brightness Up
- HOME + B  = Brightness Down
- HOME + L1 = L3
- HOME + R1 = R3

# Installation Guide

## Step 1

- Download & Copy "HomePlus_Install.sh", "HomePlus_Scripts.bak" & "HomePlus.kl" from the main release page to the Internal Storage of the RP2+ **[NOT THE SD CARD]**

## Step 2

- On the RP2+, go to Settings > Handheld Settings > Virtual Mouse
- Enable it & change the shortcut keys to START / SELECT (or both) & then disable it again
- Now Scroll down to "Advanced" & Select "Run Script as Root"
- Select "HomePlus_Install.sh" & tap on "Run"
- The script will run & the console will restart

## Step 3

- Download, Install & Run [Automate](https://llamalab.com/automate/)
- Accept their TOS > Tap on the menu icon (Three lines icon on Top Left)> Settings
- Scroll down to the "Backup" Section & Select "Restore Backup"
- Select "HomePlus_Scripts.bak"
- Return to the main menu, there should be **six** scripts there (L1_L3 / R1_R3 / X_BU / Y_AS / B_BD / A_OM)

## Step 4

- Select any script & tap on the missing privileges
- Allow / Enable all the requested privileges / services (3 in total)
- Start all the scripts individually & disable logging 
  (Tap the ticket icon next to the share button & Uncheck Logging)

## Step 5

- Have Fun!

# Create / Change Key Combinations

- Read the instructions / documentation on my development repo
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

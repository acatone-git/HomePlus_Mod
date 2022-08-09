# HomePlus Project - RP2+ Soft Mod

Changes the function of the HOME button to an modifier, combined with [Automate](https://llamalab.com/automate/) & Shell Scripting, it unlocks the full potential of the RP2+

# Key Combinations (Retro Controller Style)

- HOME + A  = Back Button (Access Quick Settings in Dolphin / AetherSX2) 
- HOME + Y  = Application Switch / List
- HOME + X  = Brightness Up
- HOME + B  = Brightness Down
- HOME + L1 = L3
- HOME + R1 = R3

# Installation Guide

## Step 1

- Download & Copy "HomePlus_Install.sh", "HomePlus_Scripts.bak" & "HomePlus.kl" to the root of the Internal Storage of the RP2+ 
- **[NOT THE SD CARD]**

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
- Return to the main menu, there should be **six** scripts there (HomePlus_L1_L3 / R1_R3 / X_BU / Y_AS / B_BD / A_OM)

## Step 4

- Select any script & tap on the missing privileges
- Allow / Enable all the requested privileges / services (3 in total)
- Start all the scripts individually & disable logging (Tap the ticket icon next to the share button & Uncheck Logging)

## Step 5

- Have Fun!

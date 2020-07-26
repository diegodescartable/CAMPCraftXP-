### CAMPCraftXP

# Read Before Use

**1** - Set your game to 1280 x 720 Bordered Window mode (Your Fallout76prefs.ini should have the below lines) I suggest using  FO76 Quick configuration mod (https://www.nexusmods.com/fallout76/mods/546) this app will help you relaunch the game changing these settings quickly for when you need to farm XP it also has a lot of useful settings and a robust Mod Manager

		bFull Screen=0
		bBorderless=0
		iSize H=720
		iSize W=1280
		
Important!: Make sure you are not using UI Scaling on Windows 10 (as this can throw the script off) You can check in you Windows 10 Settings > Display > Scale And Layout > Change the size of text, apps and other items  and make sure its set a 100%.

**2** - To avoid material costs, you need Contractor Perk maxed (Level 18 minimum)

**3** - You need to create a blueprint with 1 roof and 49 Welcome Mats on top of it.

Even though Welcome Mats do not give the most XP of all CAMP items. They will effectively cost 0 materials as contractor perk will give you back the same material cost. (you just need to have enough materials to craft 1 blueprint. The  49 amount its because 50 is the max amount of items you can put in the blueprint and you need room for the foundation.

**4** - The script is currently designed to work with this blueprint as it is looking for UI elements that may change if any other items are used.

**5** - Before starting the script, you must be in CAMP mode in the Blueprints tab see your blueprint as placeable (green) and your should be looking up. This is to make sure that after placed, the roof will still be on your aim and when scraped cause all the welcome mats to be store for scrapping later. To avoid your mouse aim from straying you can either flip your mouse or disconnect it (havent confirmed if disconnecting works well yet)

**6** - Lag could cause your toon to accidentally jump when scrapping or accepting other options which could disrupt workflow. One way to prevent this is to place a foundation right on your back, you will be stuck to the foundation, confirm you cant jump before starting the script!

**7** - It is my understanding that crouching stops enemy mobs in your area from spawning, during a whole day of testing my toon was not bothered at any point. You should also select a naturally calm area, like the clearing north of the Power Pylon after the road on the Whitespring train station.

**8** - Tested with a toon at 42 INT without any other XP buffs during double XP this blueprint should yield around 450 XP per placement around every 16 seconds)

**9** - WARNING!!!!!!! A rogue combination of R > Space could cause your blueprint/s to be deleted so USE AT YOUR OWN RISK. However, be aware that during the whole process of coding and testing this script this didnt happen, not even once, but be warned in case I missed some strange scenario anyway. The most I had was the script stop at the Delete Blueprint pop up (the script checks for UI changes pretty often and will stop in any unexpected situation) if this happens, carefully stop the script with the hotkeys below and select the No option. Reset the script and yourself to the starting position and restart.

**10** - WARNING 2!!!!! There has been reported instances of the game crashing when placing blueprints (even without the script running) that can sometimes result in a complete camp wipe, it would seem that sometimes the game could crash when placing heavy blueprints (like the one used here) not sure on whats the caused but as far as the script goes this seems to have been somewhat mitigated with running the script with Administrator privileges. So in case the script or an underlying game bug causes this it is always recommended to run the script without any important blueprints or CAMP setup you dont wanna lose!


### Usage

**ALT + P**  -  Start the script

**ALT + Z** - Stop the script

**Tab**, **Z**, **C**, **E**, **Esc**, **Space** - Force abort script to avoid accidental scrapping since they are CAMP UI keys

Note: A log will be created in ths script's folder containing some information on execution and errors (still needs a lot of work but it helped during development)

### Changelog

Version 1.0-rc1

- Initial release candidate.

Version 1.2-RC2

- Improved error checking and recovery
- More logging with option to disable for improve performance

Version 1.3-RC3

- Improved budget checking
- Updated timings and retry amounts

### Acknowledgements

https://github.com/Cipencjusz for their amazing NW afk script (https://github.com/Cipencjusz/NW-farm--New) which I started to write this script from to get an idea of how to do the basics. Thanks a lot for your assitance in Discord DMs!





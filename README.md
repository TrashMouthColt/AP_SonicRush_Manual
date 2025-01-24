# AP_SonicRush_Manual
A Manual for Sonic Rush (2005) for the Nintendo DS, to use as part of the [Archipelago Manual](https://github.com/ManualForArchipelago) Project.

This manual is intended for use with a 100% Sonic Rush Save File to ensure accessibility to all locations, regardless of settings.

# Setup Guide:

You will need:
  - A Sonic Rush ROM | **NOT PROVIDED**
  - Sonic Rush.dsv
  - manual_sonicrush_trashmouthcolt.apworld
  - [Archipelago Launcher](https://github.com/ArchipelagoMW/Archipelago/releases/tag/0.5.1)
  - [Manual for Archipelago](https://github.com/ManualForArchipelago/Manual/releases/tag/manual_stable_20241119)
  - DS Emulator of choice

  This guide is intended for the DeSmuME Emulator, things may differ for other emulators and you may need a completed .sav file instead.

# Setting up Sonic Rush
 
  1. Open the directory you installed DeSmuME to
  2. Open the "Battery" folder
  3. If theres already one, replace "Sonic Rush.dsv" with the downloaded one
  4. If there isnt one, place the downloaded "Sonic Rush.dsv" in the folder
  5. Open DeSmuME
  6. Open your Sonic Rush ROM
  7. If successful, you should have access to the "Extra" Story on the "Gameplay" tab 
  8. If the game automatically loads you into Leaf Storm Act 1 as Sonic (or you dont have access to the Extra Story), delete "Sonic Rush.dsv" and try again

# Setting up the .apworld

  1. Set up Archipelago (if it isn't already)
  2. Set up Manual for Archipelago (if it isn't already)
  3. Navigate to your Archipelago custom_worlds Folder - Usually located at: C:\ProgramData\Archipelago\custom_worlds
  4. Place "manual_sonicrush_trashmouthcolt.apworld" into the folder
  5. Open the ArchipelagoLauncher.exe
  6. Click on "Manual Client"
  7. Set the Manual Game ID to "Manual_SonicRush_trashmouthcolt"

 
# YAML Generation from the GitHub

  1. Download "Manual_SonicRush_trashmouthcolt.yaml" from GitHub
  2. Open the file and edit the settings to your liking
  3. Place the .yaml into the Archipelago Players Folder - Usually located at  C:\ProgramData\Archipelago\Players

If you are unsure what any of the settings mean, there is an explanation below OR if you're coming from a later release they will have custom descriptions (I just haven't gotten around to dusting off my Python knowledge for hooks as of 0.0.1)

# YAML Generation from the ArchipelagoLauncher

  1. Open the ArchipelagoLauncher.exe
  2. Click on Generate Template Options
  3. It should automatically open the Archipelago Templates Folder - If not it is Usually Located at  C:\ProgramData\Archipelago\Players\Templates
  4. Look for "Manual_SonicRush_trashmouthcolt.yaml"
  5. Open the file and edit the settings to your liking
  6. Move / Copy&Paste the .yaml into the Archipelago Players Folder - Usually located at  C:\ProgramData\Archipelago\Players

If you are unsure what any of the settings mean, there is an explanation below OR if you're coming from a later release they will have custom descriptions (I just haven't gotten around to dusting off my Python knowledge for hooks as of 0.0.1)

# Settings Explanation
  - chaos_emeralds: To unlock the final boss, you must obtain the 7 Chaos Emeralds
  - sol_emeralds: To unlock the final boss, you must obtain the 7 Sol Emeralds
  - all_emeralds: To unlock the final boss, you must obtain the 7 Chaos Emeralds and 7 Sol Emeralds (This is the way you unlock it in the vanilla game)
  - S_Ranks: When set to true, S-Ranking every Act & Boss will also be a check (This also applies to Blaze's Story if enabled)
  - Blaze_Story: When set to true, every Act & Boss from Blaze's Story will also be checks, Blaze's Story is locked by default and you must obtain the "Blaze The Cat" Character item to have access, afterwards all levels unlocked for Sonic are also unlocked for Blaze

# Game Generation
If you don't already know how to Generate a game from outside of the website, you can follow these guides: [Generating the Game](https://archipelago.gg/tutorial/Archipelago/setup/en#on-your-local-installation), [Hosting the Game](https://archipelago.gg/tutorial/Archipelago/setup/en#from-a-locally-generated-game)
- **Note: The host must have all of the required custom .apworlds, including this one, for the generation in their "Archipelago\custom_worlds" folder, as well as the ROMs for any game that requires those for generation which Manuals DO NOT**

# Connecting to the multiworld

  1. Once the host has generated the game and started hosting it, you'll be provided with the server address - For games hosted on the website, you should see a server address in the format of "**archipelago.gg:[XXXXX]**"
  2. Open the ArchipelagoLauncher.exe
  3. Click on "Manual Client"
  4. If not already set, set the Manual Game ID to "Manual_SonicRush_trashmouthcolt"
  5. At the top, change the server address to the address the host gives you and press Connect
  6. You shall be prompted to "Enter slot name:" which will be the name you put in the "name:" section of the .yaml
  7. If applicable you will also be prompted to input the server password
  8. Once connected, going into the "Manual" tab should show you your Starting Stage as well as all Remaining Locations
  9. To send out checks, once you have completed their requirement, just click on the corrosponding button
  10. Anything that is available for you to complete with your current items will be highlighted green
  11. Once you have completed your goal requirement, click on the "GOAL: [your_requirement]" button to release any remaining checks

# What is considered a check in Sonic Rush?

Your locations to check will be:
  - Sonic Stages Completion
    - Both Act 1 and 2
  - Sonic Bosses Completion
  - Sonic S-Ranks
    - IF S_Ranks is enabled
  - Special Stages Completion
  - Blaze Stages Completion
    - Both Act 1 and 2
    - IF Blaze_Story is enabled
  - Blaze Bosses Completion
    - IF Blaze_Story is enabled
  - Blaze S-Ranks
    - IF Blaze_Story is enabled AND S_Ranks is enabled

# What can other people send me in Sonic Rush?

Items that are part of the multiworld in this iteration of the Manual are:
  - Chaos Emeralds
  - Sol Emeralds
  - Character Unlocks
    - So far only Blaze IF Blaze_Story is enabled
  - Stage Unlocks
  - Junk Items

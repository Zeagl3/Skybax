![Logo](https://raw.githubusercontent.com/Zeagl3/Skybax/main/image/skybax-banner-transparant.png)

# Skybax

- [Skybax](#skybax)
  - [What is Skybax](#what-is-skybax)
  - [Installation](#installation)
    - [Pre-Installation](#pre-installation)
      - [Installing Microsoft Visual C++ Redistributable Package](#installing-microsoft-visual-c-redistributable-package)
      - [Steam Config](#steam-config)
        - [Disable the Steam Overlay](#disable-the-steam-overlay)
      - [Change Steams Update Behavior](#change-steams-update-behavior)
      - [Clean Skyrim](#clean-skyrim)
      - [Start Skyrim](#start-skyrim)
    - [Using Wabbajack](#using-wabbajack)
      - [Preparations](#preparations)
        - [Downgrade Skyrim](#downgrade-skyrim)
      - [Downloading and Installing](#downloading-and-installing)
        - [Problems with Wabbajack](#problems-with-wabbajack)
  - [Post-Installation](#post-installation)
    - [Stock Game](#stock-game)
    - [ENB](#enb)
  - [How to start up Skybax](#how-to-start-up-skybax)
  - [Updating](#updating)
  - [Mods you should know about](#mods-you-should-know-about)
    - [Quest and Encounter Mods](#quest-and-encounter-mods)
    - [Followers](#followers)
    - [Audio and Weather](#audio-and-weather)
    - [NSFW](#nsfw)
	- [Performance Mode](#performance-mode)
  - [Creating your Character](#creating-your-character)
  - [In-Game MCM Options](#in-game-mcm-options)
  - [Credits and Thanks](#credits-and-thanks)
  - [Contact](#contact)
  - [Changelog](#changelog)
  - [The End](#the-end)
  
  ## What is Skybax
  
  Skybax is my own take on how to play Skyrim. It adds a lot of graphical overhauls, DLC-sized additions, animations, etc.<br><br>
  <b>Oh yeah, it's also NSFW :)</b>
  
  ## Installation
  
  ### Pre-Installation
  
  #### Installing Microsoft Visual C++ Redistributable Package
  
  You need to download and install this from the [Microsoft website](https://aka.ms/vs/16/release/vc_redist.x64.exe).
  
  #### Steam Config
    
  ##### Disable the Steam Overlay
  
  Some ENB settings can look weird if you have the Steam Overlay enabled. It is recommended to turn this off.
  
  #### Change Steams Update Behavior
  
  Don't update you Skyrim SE to Skyrim AE. Head to the Properties windows, go to the Updates tab and change Automatic Updates to "Only update this game when I launch it".
  Skybax will run through SKSE so the game won't update.
  
  #### Clean Skyrim
  
  Clean your "My Documents\My Games\Skyrim Special Edition" folder.
  
  #### Start Skyrim
  
  Start your Skyrim SE once, when in the main menu, just exit the game.
  This wil generate the needed files in your clean My Documents folder.
  
  ### Using Wabbajack
  
  #### Preparations
  
  Download the latest version of Wabbajack from [here](https://github.com/wabbajack-tools/wabbajack/releases).
  Put the Wabbajack.exe in a working folder, NOT in a common folder like Desktop, Downloads or Program Files.
  
  ##### Downgrade Skyrim
  
  Skybax requires the latest version of Skyrim Special Edition (1.5.97.0), so the pre-AE version.
  If you have upgraded your Skyrim to AE, download the [Unofficial Downgrader](https://www.nexusmods.com/skyrimspecialedition/mods/57618?tab=files) (FullPatcher.exe) and let it run.
  This may take a while.
  
  #### Downloading and Installing
  
  The download and installation of Skybax can take some time depending on your internet speed and PC specs.
  It is recommended to install Skybax on an SSD drive.
  1. Download the Skybax Wabbajack file from the [Skybax Discord server](https://discord.gg/C7rqSmzNpf) (Releases channel)
  2. Open Wabbajack
  3. Click "Install From Disk"
  4. "Target Modlist": select the downloaded Skybax Wabbajack file
  5. "Installation Location": point this to the folder you want Skybax installed to (preferably on an SSD)
  6. "Download Location": Same folder as above, but with "downloads" subfolder
  7. Press the Play button
  8. Wait :)
  
  ##### Problems with Wabbajack
  
  Some mods won't be downloaded through Wabbajack because they are not available on the Skyrim Nexus.
  The mods that need a manual download are listed in the [Skybax Discord server](https://discord.gg/C7rqSmzNpf).
  Download them and put them in the mod's Download folder.
  
  ## Post-Installation
  
  ### Stock Game
  
  Skybax uses the "Stock Game" feature of Wabbajack. This means that there is a copy of a Skyrim SE installation located within Skybax's folder.
  Your own Skyrim installation will stay untouched.
  
  ### ENB
  
  Skybax comes with [Rudy ENB SE for Cathedral Weathers Zangdar's Edit Lux Edition](https://www.nexusmods.com/skyrimspecialedition/mods/39113).
  If you want a different ENB, you can choose one of the many available on the Skyrim Nexus that support Cathedral Weather.
  Just follow the install instructions of those ENB's to get them working.
  
  ## How to start up Skybax
  
  1. Go to the Skybax install directory, you'll find an executable named "ModOrganizer.exe", double click this.
  2. In the dropdown on the right, make sure "Skybax" is selected, then press the "Shortcut" button.
  3. Add a Shortcut to your Desktop.
  4. Close Mod Organizer.
  5. Run Skybax through the shortcut you created on your desktop.  
  
  It can take some seconds until the main menu shows up.
  
  ## Updating
  
  If there is a new release of Skybax, you can download the Wabbajack file from the [Skybax Discord server](https://discord.gg/C7rqSmzNpf) (Releases channel).
  Repeat the installation steps of Skybax, but before you press the Play button, check "Overwrite Installation".
  
  <b>Wabbajack will delete all files that are not part of Skybax when updating!</b>
  
  If you have added some mods of your own, they will be deleted, unless you put "[NoDelete]" in front the mod's name.
  
  ## Mods you should know about
  
  ### Quest and Encounter Mods
  
  Skybax has some DLC-sized additions like:</a>
  - [The Forgotten City](https://www.nexusmods.com/skyrimspecialedition/mods/1179)
  - [Wyrmstooth](https://www.nexusmods.com/skyrimspecialedition/mods/45565)
  - [Darkend](https://www.nexusmods.com/skyrimspecialedition/mods/10423)
  - [Helgen Reborn](https://www.nexusmods.com/skyrimspecialedition/mods/5673)
  - [Stendarr Rising](https://www.nexusmods.com/skyrimspecialedition/mods/49346)
  - [Legacy of The Dragonborn](https://www.nexusmods.com/skyrimspecialedition/mods/11802)
  - [Moonpath to Elsweyr](https://www.nexusmods.com/skyrimspecialedition/mods/4341)
  
  [Extended Encounters](https://www.nexusmods.com/skyrimspecialedition/mods/44810), [Immersive Patrols](https://www.nexusmods.com/skyrimspecialedition/mods/718) and [OBIS](https://www.nexusmods.com/skyrimspecialedition/mods/4145) are also included.
  
  ### Followers
  
  Skybax uses [Nether's Follower Framework](https://www.nexusmods.com/skyrimspecialedition/mods/55653).<br>
  The custom followers that are in the game are:
  - [INIGO](https://www.nexusmods.com/skyrimspecialedition/mods/1461)([The Suave High Poly Replacer](https://www.nexusmods.com/skyrimspecialedition/mods/38860))
  - [Lucien](https://www.nexusmods.com/skyrimspecialedition/mods/20035)([Re-Imagined SSE](https://www.nexusmods.com/skyrimspecialedition/mods/33607))
  - [Auri](https://www.nexusmods.com/skyrimspecialedition/mods/11278) ([Re-Imagined SE](https://www.nexusmods.com/skyrimspecialedition/mods/37996))
  - [Vixi Talax](https://www.nexusmods.com/skyrimspecialedition/mods/54101)
  - [Ambriel](https://www.nexusmods.com/skyrimspecialedition/mods/969) ([Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/2200))
  
  Some followers (like Auri) spawn their own mount. You need to disable "Allow Horse" in NFF for those, else they will spawn two mounts (and use the wrong one).
  ![image](https://i.imgur.com/aZyP50F.png)
  
  ### Audio and Weather
  
  Skybax uses [Cathedral Weather and Season](https://www.nexusmods.com/skyrimspecialedition/mods/24791) with the [Rudy ENB](https://www.nexusmods.com/skyrimspecialedition/mods/39113).
  
  ### NSFW
  
  Skybax uses the OSA/OSex/OStim framework.
  If you want to have a "clean" playthrough without random sex, you can disable the "OStim - ONights - NPC Sex Lives" mod.
  NPC's won't have sex then, so you have full control over the NSFW stuff.
  
  ### Performance Mode
  
  If you are having lots of FPS drops, you can try to enable Performance Mode.
  This can be done by disabling the following mods:
  - 05 - GRAPHICS --&gt; DynDOLOD Resources SE
  - 38 - GENERATED FILES --&gt; TexGen Output
  - 38 - GENERATED FILES --&gt; DynDOLOD Output
  
  And then enable these mods:
  - 05 - GRAPHICS --&gt; DynDOLOD Resources SE - Performance Mode
  - 38 - GENERATED FILES --&gt; TexGen Output Performance Mode
  - 38 - GENERATED FILES --&gt; DynDOLOD Output Performance Mode
  
  ## Creating your Character
  
  When creating a new game, you'll spawn in an Alternate Start - Live Another Life cell.
  Start creating your character, in the "Head" tab, scroll down to the "Face Part" option and select number 3 "High Poly Head".
  When choosing your brows and beard, use the ones that are compatible with High Poly Head (all of them, except vanilla).
  If you're happy with your character, save it and name it.
  
  Now just <b>wait</b> until all messages at the top left are gone.
  When the "Fertility+" popup comes up, just select "No", this mod is quite heavy on loading, so we do this later on.
  If there are no more messages coming up in the top left, press ESC, go to the "MCM" menu and scroll down to "Nemesis PCEA".
  Enable "0Dser_Animations".
  Then go to "Fertility Mode+", enable the mod, exit the options menu and wait +/- 20 seconds.
  
  Hit ESC and create a manual save, just to be sure.
  
  Now you're ready to start your adventure, interact with the Mara statue to choose a game start, then go to sleep in the bed behind you.
  
  ## In-Game MCM Options
  
  I've tweaked some of the settings, but if you don't like them, you're free to change them as you like.
  
  <b>Don't forget to go to the Nemesis PCEA mod, and enable "0Dser_Animations".</b>
  
  ## Credits and Thanks
  
  - YOU for downloading and (hopefully) playing (and enjoying) Skybax!
  - The users of the [Discord server](https://discord.gg/C7rqSmzNpf) for their support and mod suggestions.
  - The Wabbajack team - It's an incredible program!
  
  ## Contact
  
  You can contact me through the official [Discord server of Skybax](https://discord.gg/C7rqSmzNpf)<br>
  If you like my work, you can always support me on [Patreon](https://www.patreon.com/Zeagle) or donate via [PayPal](https://paypal.me/Zeagle).
  
  ## Changelog
  
  See [Changelog](https://github.com/Zeagl3/Skybax/blob/main/CHANGELOG.md)
  
  ## The End
  
  Thank you for downloading and playing Skybax.
  
  Zeagle out ![micdrop-small](https://user-images.githubusercontent.com/83012326/152408971-24b5eaf2-6487-44a5-a000-d1c471158e67.png)


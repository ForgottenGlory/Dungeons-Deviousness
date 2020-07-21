# Dungeons & Deviousness
Current version: 0.0.1 Alpha

**WARNING: This modlist is in Alpha state! Bugs and weirdness are to be expected.**

## Table of Contents
- [Table of Contents](#table-of-contents)
- [Preface](#preface)
  - [Warnings/Disclaimers](#warningsdisclaimers)
  - [System Specifications](#system-specifications)
  - [Important Links](#important-links)
    - [(SFW) Screenshots](#sfw-screenshots)
- [Pre-Installation](#pre-installation)
  - [Skyrim Setup](#skyrim-setup)
  - [Steam Setup](#steam-setup)
  - [Launching Skyrim](#launching-skyrim)
  - [Wabbajack Preparations](#wabbajack-preparations)
- [Wabbajack Installation](#wabbajack-installation)
  - [With Nexus Premium](#with-nexus-premium)
  - [Without Nexus Premium](#without-nexus-premium)
- [Post-Wabbajack Install](#post-wabbajack-install)
  - [Game Folder Files](#game-folder-files)
  - [Mod Organizer 2](#mod-organizer-2)
    - [Configuration-Specific](#configuration-specific)
  - [ENB](#enb)
- [Updating Dungeons & Deviousness](#updating-dungeons--deviousness)
- [BodySlides](#bodyslides)
  - [Prebuilt Bodyslides](#prebuilt-bodyslides)
  - [Build Your Own](#build-your-own)
  - [A Note About Presets](#a-note-about-presets)
- [Launching Dungeons & Deviousness](#launching-dungeons--deviousness)
  - [The MCM Settings](#the-mcm-settings)
- [Important Mods You Need to Know About](#important-mods-you-need-to-know-about)
  - [The Big Four](#the-big-four)
  - [The (NSFW) Big Three](#the-nsfw-big-three)
  - [The Dungeons](#the-dungeons)
  - [The Deviousness](#the-deviousness)
  - [The Other NSFW Stuff](#the-other-nsfw-stuff)
  - [Milk Mod Economy](#milk-mod-economy)
  - [Character Creation](#character-creation)
  - [The Magic Mods](#the-magic-mods)
  - [The Combat Mods](#the-combat-mods)
  - [The Enemy Mods](#the-enemy-mods)
  - [The Economy & Loot Mods](#the-economy--loot-mods)
  - [The Perks & Leveling Mods](#the-perks--leveling-mods)
  - [The HUD and UI Mods](#the-hud-and-ui-mods)
  - [Your Fellow Party Members](#your-fellow-party-members)
  - [Nether's Follower Framework](#nethers-follower-framework)
- [Final Thoughts & Best Practices](#final-thoughts--best-practices)
  - [Getting Started in Dungeons & Deviousness](#getting-started-in-dungeons--deviousness)
- [Troubleshooting & FAQ](#troubleshooting--faq)
- [Credits & Thanks](#credits--thanks)
  - [One Last Thing](#one-last-thing)

## Preface
Welcome to the dungeon! Specifically, the Dungeons & Deviousness modlist. Dungeons & Deviousness is a NSFW Skyrim SE modlist intended to be fully playable with a semi-hardcore survival experience included. Rather than a screenshot simulator or lightweight add-on to vanilla Skyrim, Dungeons & Deviousness seeks to be as intrusive as possible in the systems present in Skyrim and overhaul them to fit the theme.

What's the theme, you ask? Well, Dungeons & Deviousness, as the name might imply, is heavily inspired by old-school pen and paper tabletop RPGs. Dungeons & Dragons, Pathfinder, whatever, you name it, I've drawn inspiration from it. And then I threw it into a blender with some of the most interesting NSFW mods I could find and the result is this modlist.

This modlist, I should note, is not intended to be something you can just boot up, snap one off to, and then shut down. My intent here is to provide the ability to have fully functional playthroughs of Skyrim with sexiness and roleplaying on top of it. You absolutely will have to do some reading and spend quite a bit of time in the MCMs to get this list up and running.

However, once you do have it up and running, I'd be willing to bet you'll have a NSFWRim experience that is rather unique. The difficulty is high, the mechanics are punishing, and you'll spend as much time managing systems as you will delving into dungeons. But for those who scrape, claw, rip, and tear their way through, the rewards are exceptionally generous and that feeling of satisfaction once you've finally become the hero you're meant to be... It's not quite like anything else.

So! Assemble your adventuring party, gather your courage, and step into this unholy dungeon. Good luck!

### Warnings/Disclaimers
Wabbajack no longer requires that you have Nexus Premium to install the modlist, however, having Nexus Premium will cut your install time to a fraction of what it would be instead of downloading each mod individually (and save you a couple thousand clicks or so).  

The modlist requires ~159 (51GB Downloads/105GB Mods) of hard drive space on top of the ~11GB Skyrim: Special Edition base files. Installing onto an SSD/NVMe is not required, but **strongly recommended**. Download and installation times vary based on your computer and internet speeds but expect the entire process to take a few of hours.

**NSFW Warning:** This modlist contains explicit sexual content. Proceed at your own discretion.

This modlist only functions with female player characters. Sorry, but that's how it is.

Support is **not** provided for adding to, removing from, or changing the list in *any way*.

### System Specifications
Dungeons & Deviousness is not the most intense modlist by design - high-end graphics plus all of the scripts running is a recipe for disaster. As a result, the following hardware can run the list at a consistent 60+ FPS with ENB. Use it to gauge how your system might run the list.

- CPU: Intel i5-8600K Overclocked to 4.2GHz 
- RAM: 16GB DDR4 (16299MB actual)
- GPU: nVidia RTX 2080 Super 8GB (8192MB actual)
- Monitor: Dell S2716DGR 2560x1440 @ 144hz

Skyrim is very heavy on processors. Generally, anything above 3GHz should be fine but I can’t guarantee it. 6GB or 8GB of VRAM should be plenty, with 4GB of VRAM probably capable of 60FPS without ENB.

### Important Links 
[Dungeons & Deviousness FAQ & Troubleshooting](#troubleshooting--faq)  
[Dungeons & Deviousness Bug & Suggestions Tracker](https://github.com/ForgottenGlory/Dungeons-Deviousness/issues)  
[Dungeons & Deviousness Discord](https://discord.gg/9dFvGnc)  
[Dungeons & Deviousness Patreon](https://www.patreon.com/LivingSkyrim)

#### (SFW) Screenshots

## Pre-Installation
### Skyrim Setup
As with any modlist, it is strongly recommended that you start with a clean, unmodified installation of Skyrim: Special Edition. To get your Skyrim SE to this state, follow these steps:

1. In Steam, uninstall Skyrim: Special Edition (Right-click > Manage > Uninstall). 
2. If there are any files leftover in the Skyrim Special Edition game folder (Right-click > Properties… > Local Files > Browse Local Files…), delete them.
3. Install Skyrim: Special Edition.

### Steam Setup
1. In Steam, set Skyrim: Special Edition to update only when opened. (Right-click > Properties… > Updates > Automatic updates > Only update this game when I launch it)
2. In Steam, disable the Steam Overlay. (Right-click > Properties... > General > Enable the Steam Overlay while in-game checkbox)
   
### Launching Skyrim
Launch Skyrim SE to create any INI or registry entries the game needs. Immediately exit after the launcher has successfully selected a graphics preset for your hardware. The INIs will be overwritten by the ones included in the Wabbajack installer.

### Wabbajack Preparations
1. Download the latest version of [Wabbajack](https://github.com/wabbajack-tools/wabbajack/releases) and the latest copy of the [D&D Installer](https://drive.google.com/file/d/12rPxq2FEmgvhCv3rhYfkY7Zb_4TC_6CQ/view?usp=sharing). Do not run anything until instructed to do so. Make sure you are using the latest version of Wabbajack or else Wabbajack will report a corrupted modlist.
2. Create a new folder in the root of the drive where you want Wabbajack to be installed. (C:\ will be used as an example, but it can be placed in any drive.) Name this folder “Wabbajack”. **Important!:** Wabbajack must be placed in a separate folder from where the installation will occur. 
3. Create a second folder called C:\Dungeons & Deviousness. This folder is where the modlist will be installed.
4. Double check that you have *not* placed any of these folders in your Skyrim: Special Edition installation directory.
5.  Ensure that C:\Dungeons & Deviousness is **completely empty.**
6.  Ensure that Wabbajack.exe is in C:\Wabbajack.

## Wabbajack Installation
If you are updating your existing installation of Dungeons & Deviousness, skip to [Updating Dungeons & Deviousness](#updating-dungeons--deviousness).

1. Run Wabbajack.exe. 
2. At the bottom of the window click Install from Disk and select the D&D Installer you downloaded earlier.
3. Set the Installation Location to C:\Dungeons & Deviousness. The download location does not need to be set manually unless you have drive space limitations. Downloading to a separate folder is fine (for example, on a HDD), but as before it is recommended that the actual install be placed on a SSD. **Important!:** Do not install the modlist to your Skyrim SE installation folder OR the folder that Wabbajack.exe is in.
4. Click the play/right arrow button to begin installation.

### With Nexus Premium
5. Wabbajack will walk you through logging into the Nexus and authorizing an API key so it can download mods if you have not done so previously.
6. Let Wabbajack do its thing. This will take a little while (usually 3-4 hours at most), so go get a snack and read the [Important Mods You Need to Know About](#important-mods-you-need-to-know-about) section of this document. Seriously. Read it. This isn't optional.

### Without Nexus Premium
5. Wabbajack will prompt you to click all the needed buttons to download the modlist. Be prepared for this to take a really long time, possibly more than one day. Also be aware that due to the amount of time required when installing this list manually, the list may update during the time it takes to install and you may need to start over if that happens. Put on some music or a TV show and make a day of it. If you need a break during this process, grab a snack and read the [Important Mods You Need to Know About](#important-mods-you-need-to-know-about) section of this document. Seriously. Read it. This isn't optional.

Once complete, Wabbajack will say “Installation complete! You may exit the program.” If it does not, visit the [Wabbajack Discord server](https://discord.gg/wabbajack) for assistance. **Don’t forget to upload your log file!**  

If Wabbajack fails to download a particular mod, it means that the mod has likely been updated. This also means that an update to Dungeons & Deviousness is imminent. Be patient and wait for the new release. **Do not ask other people to share older files as this is a violation of the Nexus ToS.**  

## Post-Wabbajack Install
### Game Folder Files
Now you have to copy some files to their correct locations. Navigate to C:\Dungeons & Deviousness\Game Folder Files. Copy all of the files inside the Game Folder Files folder into [Steam Install Location]\steamapps\common\Skyrim Special Edition\ and Overwrite if prompted. This folder contains SKSE and Engine Fixes part 2, which are required to use Dungeons & Deviousness and must be placed into your Skyrim's installation folder for the list to function.

### Mod Organizer 2
1. Navigate to C:\Dungeons & Deviousness and open ModOrganizer.exe. Your Mod Organizer window will have a dark theme already selected. If it doesn’t, something has gone wrong and you’ll likely need to do the Wabbajack installation again.
2. A dialogue will appear and ask if you want to associate Mod Organizer with nxm links. Click **Yes.**

#### Configuration-Specific
If you can handle it, you have the option to enable Improved Camera, found near the bottom of the list in the left pane of MO2. I (ForgottenGlory) personally get motion sickness while using it, so feel free to not use it if that's a concern.

### ENB
ENB is not required to run Dungeons & Deviousness, but it is intended to be used with it. You may skip these instructions if you don’t want to use ENB. 

In general, any ENB that is compatible with Obsidian Weathers will work with D&D. My preferred ENBs are Rudy's, Amon Reborn, and Silent Horizons if you want some recommendations.

In general, the process to install an ENB preset is:

1. Download the latest ENB Binary from http://enbdev.com/download_mod_tesskyrimse.htm
2. Open the .zip file, go into the WrapperVersion folder, and copy ONLY d3d11.dll and d3dcompiler_46e.dll into your Skyrim SE installation folder. (Usually located at C:\Steam\steamapps\common\Skyrim Special Edition)
3. Download your selected ENB preset. **Important!: Make sure it is compatible with Obsidian Weathers!**
4. Follow any installation instructions included with your Preset. Every ENB has slight variations in their requirements, so make sure to follow the instructions included for that preset. **You should not need to download any additional files other than the preset. Things like ENB Helper and Particle Patch are already included!**

## Updating Dungeons & Deviousness
If you are updating Dungeons & Deviousness, the process is very simple. Before you update, you should at a minimum backup your saves. Updating will delete any saves that are present. Make sure you are using the latest version of Wabbajack or else Wabbajack will report a corrupted modlist.

1. Download the latest D&D installer and run Wabbajack.exe. 
2. At the bottom of the window click Install from Disk and select the D&D installer you just downloaded.
3. Set the Installation Location to wherever you already have Dungeons & Deviousness installed. 
4. **Important!:** Set your downloads folder path to the same downloads folder location you used when you first installed Dungeons & Deviousness. Failure to do this will make Wabbajack download every mod again, which you want to avoid if possible.
5. Click Run.
6. When prompted if you would like to overwrite the existing installation, click "Confirm."

## BodySlides
When you first load up D&D, there will be zero BodySlides created. You have two options here: Download the prebuilt ones I've made using the MelaRockingPhysique, or make your own. 

### Prebuilt Bodyslides
If you don't really care what preset you use and/or are fine with MelaRockingPhysique, follow these steps.

1. Download this zip file: [D&D Prebuilt Bodyslides](https://drive.google.com/file/d/1g6Z0zJqNetNTE3A05SSWyx7RVxRMKGhM/view?usp=sharing)
2. Open the ZIP file.
3. Copy everything inside the zip file into C:\Dungeons & Deviousness\mods\BodySlide Output.
4. That's it, you're done!

### Build Your Own
If you want to build them yourself, this is a fairly straightforward process, but it can be a bit time consuming.

Before you get started, if you have your own personal BodySlide preset that you like, drop the XML file into C:\Dungeons & Deviousness\mods\Custom Presets\Caliente Tools\BodySlide\SliderPresets alongside "Summer.xml".

One more thing: if you get an error about BodySlide not being able to find the output path, click on the Settings button in BodySlide, click on the "Advanced" button, and set the Output Path to C:\Dungeons & Deviousness\mods\BodySlide Output.

1. Launch BodySlide from MO2.
2. Click on the magnifying glass icon near the top of the BodySlide Window and select "Choose Groups..."
3. Put a checkmark into **ONLY** DD Armor Part 1.
4. From the Preset dropdown, select your preferred preset. I've included a couple of extras on top of the default CBBE ones, or you can make your own. 
5. Make sure that the "Build Morphs" checkbox is checked at the bottom of the BodySlide window.
6. Click "Batch Build..." and then Build on the window that appears.
7. Repeat steps 3 through 6 for DD Armor Part 2 and DD Bodies. For DD Bodies you may want to select a different Bodyslide preset if you want armor/clothing to look different than the nude bodies. (MekaRockingArmor/MelaRockingOutfit for the armors and MelaRockingPhysique for the body, for example.)

### A Note About Presets
If you have your own favorite character face/head preset, drop the JSLOT file into C:\Dungeons & Deviousness\mods\Custom Presets\SKSE\Plugins\CharGen\Presets alongside Anna.jslot and Summer.jslot. It will be available in RaceMenu the next time you go to make a character. Make sure to back this up before updating the list as updating will erase any added files like this. Adding presets (whether they be BodySlide or RaceMenu) does not void support for Dungeons & Deviousness.

If you have a preset (Bodyslide or RaceMenu, doesn't matter) that *you made* and you'd like it to be included in Dungeons & Deviousness, send it to ForgottenGlory.

## Launching Dungeons & Deviousness
The hard part is now over. Carry on, the end is in sight!

1. In Mod Organizer 2, select SKSE from the drop-down menu next to the Run button and click Run. This is how Dungeons & Deviousness should always be launched. You can create a shortcut on your desktop if you wish using the Shortcut button under the Run button.
2. Once Skyrim starts, create a new game. **Loading an old save at this point will corrupt that save, do not do this.** 
3. Create your character (make sure your character is female or else the list won't work right) and name them whatever you’d like.
4. **As soon as you gain control of your character, do nothing.** The mods are loading and this can take several minutes. You’ll see a list of mods initializing in the top left of the screen.
5. Once you see that no more items are appearing in the list in the top left, you can proceed to the next steps.

### The MCM Settings
1. Consult the [Dungeons & Deviousness MCM Configuration](d&dmcm.md) document and follow all listed steps. This step is required if you want the list to work properly.
2. Don’t forget to save your game after configuring the MCMs, I promise you don’t want to have to do this step more than once.

## Important Mods You Need to Know About
This section details the most important mods included in Dungeons & Deviousness and is intended to give you a basic understanding of what to expect when you start the game.

### The Big Four
The first four mods you need to know about are [Frostfall](https://www.nexusmods.com/skyrimspecialedition/mods/671), [Campfire](https://www.nexusmods.com/skyrimspecialedition/mods/667), [Keep It Clean](https://www.nexusmods.com/skyrimspecialedition/mods/17846), and [Realistic Needs & Diseases](https://www.nexusmods.com/skyrimspecialedition/mods/23799). These are the core survival package of D&D. Frostfall adds a warmth and coverage statistic to every piece of clothing and armor to protect you from the harsh cold of Skyrim. Campfire allows you to set up camp anywhere - provided you have the materials to do so. Your followers will camp with you and you'll need to do this on extended trips out of town. Realistic Needs & Diseases covers the rest of your needs - sleep, hunger, thirst, etc. It also overhauls the diseases in the game so they are harsher. 

With these four mods, there's going to be a lot of things you'll need to manage to make sure you don't die traveling from point A to point B. Carry food, water, and warm clothes with you at all times, or make a follower carry them for you. You never know when you'll need to take shelter against a sudden blizzard. When you have the opportunity to stop into a town, make sure you're clean and rested before selling your hard-earned loot to get the maximum gold you can - you'll need it.

### The (NSFW) Big Three
[SexLab](https://www.loverslab.com/topic/91861-sexlab-framework-se-163-beta-8-november-22nd-2019/), [Devious Devices](https://www.loverslab.com/files/file/5878-devious-devices-se-beta/), [More Nasty Critters](https://www.loverslab.com/files/file/5464-more-nasty-critters-special-edition/). These are the three pillars of NSFW content you'll find in Dungeons & Deviousness. With these, *anything* is possible. 

SexLab by itself really doesn't do much, but it does provide the backbone framework required for all the Deviousness happening in this modlist. Devious Devices adds exactly that to the game - devices ranging from collars to harnesses to full on catsuits to the game for your character to get into trouble with. More Nasty Critters is, in essence, SexLab for creatures. It's a backbone framework to allow the aforementioned Deviousness - but with creatures instead of people.

### The Dungeons
This wouldn't be a Dungeons modlist if it didn't add dungeons! Included you'll find [Hammet's Dungeon Pack](https://www.nexusmods.com/skyrimspecialedition/mods/12186), [Forgotten Dungeons](https://www.nexusmods.com/skyrimspecialedition/mods/449), [Land of Vominheim](https://www.nexusmods.com/skyrimspecialedition/mods/31472), [EasierRider's Dungeon Pack](https://www.nexusmods.com/skyrimspecialedition/mods/2218), and [Immersive Dungeons SE](https://www.nexusmods.com/skyrimspecialedition/mods/16706). All in all, there's over 150 new dungeons and locations to explore.

### The Deviousness
Alright, rapid-fire mod time: [SexLab Defeat](https://www.loverslab.com/files/file/286-sexlab-defeat/), [SexLab Survival](https://www.loverslab.com/files/file/11053-sexlab-survival-special-edition/),  [Deviously Cursed Loot](https://www.loverslab.com/topic/100032-deviously-cursed-loot-se-beta-2/),  [Deviously Helpless](https://www.loverslab.com/files/file/6561-deviously-helpless-se/), [Estrus Chaurus](https://www.loverslab.com/files/file/6160-estrus-chaurus-for-se/), [Spank That Ass](https://www.loverslab.com/files/file/9385-spank-that-ass-se/), [Egg Factory](https://www.loverslab.com/files/file/5569-egg-factory/), [Devious Followers](https://www.loverslab.com/files/file/11732-devious-followers-continued-se/), [Simple Slavery Plus Plus](https://www.loverslab.com/files/file/13531-simple-slavery-plus-plus/), [Sanguine Debauchery](https://www.loverslab.com/files/file/503-sanguine-debauchery-enhanced-sd-june-2020/), [Fill Her Up](https://www.loverslab.com/files/file/6163-fill-her-up-se/).

Scared yet? But remember, these are just obstacles in your way as you make the climb to glory. In brief, here's what the simple mods above do.

- SexLab Defeat: Alternate death mechanics that can result in NSFW activities. Also important to note that in this list Defeat is configured such that if you go down, everyone in your party goes down. 
- Deviously Helpless: If you are helpless (usually from devices), NSFW activities may happen instead of combat.
- Spank That Ass: NPCs can spank you (and you can spank them, if you want). This can be both good and bad depending on if your character likes it or not.
- Estrus Chaurus: Get spit on by a Chaurus? There's a chance for tentacle funtimes and a Chaurus Parasite.
- Simple Slavery Plus Plus: Integrates with Defeat and other mods to sometimes provide immersive slavery mechanics if your character is defeated in combat.
- Fill Her Up: Your character will get filled up with visual changes to match.
- Egg Factory: Be careful when looting nests/sacs/eggs, there's a chance to find a cursed one among them. You'll need to find/make/buy a Remove Curse potion to get rid of it.

A few mods, however, need a bit more explanation than above. The first is Deviously Cursed Loot. It will completely change how you play the game. It features a few new questlines for you to follow, changes how NPCs behave, and completely changes how loot is distributed in the game. Depending on how this mod is configured, it can be as forgiving or brutal as you want. I've included a preset that is tough but fair. It can be disabled via MCM if you are not interested in using this mod, but be aware you'll be missing out on a ton of content added by it.

That out of the way, what does Deviously Cursed Loot actually do? The answer is very simple: Any time you loot a chest, body, plant, open a door, unlock a door, search a barrel/sack/etc, there is a chance for an event to happen if your arousal is high enough. What events? Well, it could be as simple as putting a pair of shackles on your character that you need to escape from (or get a follower's help with escaping from) before proceeding with the dungeon. There are of course things that can help mitigate some of these consequences, Lucky Charms are your best friend for avoiding unwanted surprises. Hoard them and use them carefully.

Devious Followers will turn the first follower you pickup into a Devious Follower. This follower will expect to be paid regularly, and if you can't pay, guess what? That's right - there's a whole host of devious things they can do to you. Pay them often, pay them well, and all will be well.

SexLab Survival is a mod that, in its default state, is not fun. Sorry, but it's not. *However*, if you configure it just right, it's actually a *ton* of fun! With the preset included in this list, you'll be required to have at least one follower with you to leave major cities. Oh, and you'll also need to pay a toll to leave the city assuming you have at least one follower with you (they can pay it for you if you're light on gold, but don't worry, you can pay it back later). In addition, it makes cities have certain rules you'll need to follow while inside. Usually these are pretty easy - no lockpicking visibly, keep your weapon unequipped, etc. but they can have some nasty consequences if you break the rules too many times.

Survival also integrates with Frostfall to make it so that having sex warms you up, and you can get wet from it. It also integrates with Realistic Needs & Diseases to add some interesting things that happen when your character interacts with certain fluids. Lastly, Survival makes it so that if you use Bikini Armor, you'll gain experience as you wear it - but as a consequence, using regular armor becomes less effective the higher your Bikini Armor experience is. The last thing I'd like to mention: your map and compass *will not function* unless you actually have a Map & Compass. They can be bought from most general traders in major cities, or crafted if you have the materials. Yes, this does mean that fast travel will be disabled for the early stages of the game.

The last big one is Sanguine Debauchery, which, when combined with Simple Slavery, adds actual scenarios to the game where your character could end up as a slave - to people, creatures, who knows! There are also some interesting dream sequences you can have when you sleep. 

### The Other NSFW Stuff
More rapid-fire mods: [SexLab Aroused](https://www.loverslab.com/files/file/5482-sexlab-aroused-redux-sse-version-29/), [SexLab Aroused Monitor Widget](https://www.loverslab.com/files/file/11466-sexlab-aroused-monitor-widget-se/), [SexLab Solutions](https://www.loverslab.com/files/file/10742-sexlab-solutions-revisited-se/), [SexLab Eager NPCs](https://www.loverslab.com/files/file/7309-sexlab-eager-npcs-se-slen/), [SexLab Dialogues](https://www.loverslab.com/files/file/6556-sexlab-dialogues-se/), [Devious Devices Helpers](https://www.loverslab.com/files/file/9197-devious-devices-helpers-se/), [SlaveTats](https://www.loverslab.com/topic/25398-slavetats/), [The Book of Sex](https://www.loverslab.com/files/file/10091-the-book-of-sex-se/), [Amorous Adventures](https://www.nexusmods.com/skyrimspecialedition/mods/7305), [Maids II Deception](), [Immersive Wenches](https://www.nexusmods.com/skyrimspecialedition/mods/595), [Spouses Enhanced](https://www.loverslab.com/files/file/5266-spouses-enhanced-se/), [ABC](https://www.loverslab.com/files/file/7556-animated-beasts-cocksabc-for-users-le-se/), [SOS](https://www.loverslab.com/files/file/5355-schlongs-of-skyrim-se/).

In brief:

- SexLab Aroused: Your character and NPCs can get aroused. Different things happen as arousal increases.
- SexLab Aroused Monitor Widget: Adds a widget to your screen so you can constantly monitor arousal.
- SL Solutions: Adds options to a bunch of quests that let them finish on a sexy note.
- SL Eager NPCs: NPCs will be, well, eager. Your followers may want to have some fun after clearing a dungeon or may wake you up in the morning with some sexiness.
- SL Dialogues: Adds a bunch of dialogue options to interact in sexy ways with NPCs.
- Devious Devices Helpers: People will be more willing to help you out when you're cursed and can provide some lighthearted fun when at home.
- The Book of Sex: Major sexy overhaul of the quest The Book of Love.
- SlaveTats: Framework for tattoos outside of RaceMenu, required by some other mods.
- Amorous Adventures: Romantic and funny questlines.
- Maids II Deception: Major questline with some NSFW stuff going on.
- Immersive Wenches: Adds wenches!
- Spouses Enhanced: SL integration for spouses.
- ABC: The non-acronym name of this mod should explain it.
- SOS: Same as ABC, but for regular NPCs instead of creatures.

### Milk Mod Economy
This one gets its own section because it needs it, there's a lot happening here. [Milk Mod Economy](https://www.loverslab.com/files/file/6103-milk-mod-economy-se/), in essence, adds another layer to Skyrim's economy - the Milk Economy. If you are a milkmaid, you can produce milk and level up to make other female NPCs into milkmaids to make milk and sell milk for you. There are milking stations in every major hold capital, orc strongholds, and you can build them using the Campfire system if you have the materials needed. You can also craft a cuirass to milk on the go. How do you become a milkmaid? Easy: drink milk, get pregnant, or get cursed. Deviously Cursed Loot has a chance to give you a Milk Mod potion which will do it, or Egg Factory/Estrus Chaurus will turn you into one. If you're struggling to make enough money to get a follower or leave town, this is a good way to do it.

As for the actual economy part, the prices of milk will fluctuate up and down, some cities will have booms and others will have slumps. Keep an eye on the market and sell where the milk is wanted to make the most gold. 

But, as with many things in this list, the Milk Economy comes at a cost. [Milk Addict](https://www.loverslab.com/files/file/11621-milk-addict-se/) makes it so you can become addicted to milk (technically lactacid, but milk contains lactacid so... milk.). Without sating your addiction, your character will have all sorts of problems - it might even get so bad it'll be a miracle they can stand up straight anymore. 

### Character Creation
As was mentioned in the preface, Dungeons & Deviousness is heavily inspired by old-school pen and paper RPGs. Character creation is probably the single most heavily influenced thing by that inspiration in the list. [SkyRem Ava](https://www.nexusmods.com/skyrimspecialedition/mods/23329), [SkyRem Gabi](https://www.nexusmods.com/skyrimspecialedition/mods/23145), [SkyRem Elsa](https://www.nexusmods.com/skyrimspecialedition/mods/23126), [SkyRem Rae](https://www.nexusmods.com/skyrimspecialedition/mods/23223) all are included to make creating your character a *lot* like filling out a character sheet in one of those RPGs. You'll assign your attributes, pick a background, and genders and races will have unique abilities. As if that wasn't enough, as soon as you equip a weapon, you'll be given the option to select a class and your birthsign from [Classic Classes & Birthsigns](https://www.nexusmods.com/skyrimspecialedition/mods/11316). Once leaving the alternate start cell, you'll be able to select a deity to follow through [Wintersun](https://www.nexusmods.com/skyrimspecialedition/mods/22506). If you've played a pen and paper RPG before, this should all sound very familiar. 

The choices you make in the starting cell and immediately after leaving it are (in most cases) permanent, you won't be able to change your class or attributes once you've started! Choose carefully.

Oh, one last note about character creation: The options for the statue of Mara in the Alternate Start cell have been severely stripped down for a bit extra challenge. Pick whatever you like, they're all about the same difficulty.

From a purely visual perspective, I've included just about every mod I could think of that lets you customize your character's appearance. And for good measure, I've also included quite a few RaceMenu presets that you can play around with if you want a good base to start with. One mod in particular that I need to mention is High Poly Head, which requires you to change the Face Part of your character to Face Part 3. If you don't, your character won't use it. If you do use this mod, there will be some clipping issues with most of the eyebrow options, there are still quite a few to pick from that work with it though.

Otherwise, play around with all the different options - there's an absolute boatload.

### The Magic Mods
The first and most important magic mod in Dungeons & Deviousness is [Spell Research](https://www.nexusmods.com/skyrimspecialedition/mods/20983). This mod makes it possible to research new spells even if you don't have the spell tome required for that spell. You can still learn spells from spell tomes, but you have to find/buy them - and that's not always possible in this list, so for you magic users, be ready to spend some time researchin spells. The payoffs for Spell Research though are pretty great though: [Forgotten Magic Redone](https://www.nexusmods.com/skyrimspecialedition/mods/12711), [Mysticism](https://www.nexusmods.com/skyrimspecialedition/mods/27839), and [Elemental Destruction Magic](https://www.nexusmods.com/skyrimspecialedition/mods/440) are all included so you can have a vast array of spells at your disposal - eventually.

I've also included [Sustained Magic](https://www.nexusmods.com/skyrimspecialedition/mods/15871) because that mod is awesome and nobody can change my mind. It makes it so you don't have to constantly recast spells like Oakflesh every 60-90 seconds at the cost of reducing your maximum available Magicka. Be careful how many spells you have sustained or you may not have any Magicka leftover for spells like Firebolt.

### The Combat Mods
Here's where things get difficult: [Combat Evolved](https://www.nexusmods.com/skyrimspecialedition/mods/1525), [Deadly Combat](https://www.nexusmods.com/skyrimspecialedition/mods/8850), and [Archery Gameplay Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/24296) are the core of the combat package for Dungeons & Deviousness. Between these three, combat will be fast, deadly, and reward skillful play. Dungeons & Deviousness isn't a Soulslike, but it will be significantly more difficult than vanilla Skyrim.

### The Enemy Mods
Enemies in Dungeons & Deviousness, rather than coming in vast swarms (Living Skyrim, anyone?), are more focused on being individually challenging and powerful. The aforementioned combat mods make them much smarter about the way they approach combat, and on top of that, we have [Mortal Enemies](https://www.nexusmods.com/skyrimspecialedition/mods/4881), [Know Your Enemy](https://www.nexusmods.com/skyrimspecialedition/mods/13807), [SkyRem Inez](https://www.nexusmods.com/skyrimspecialedition/mods/27103), [Encounter Zones Unlocked](https://www.nexusmods.com/skyrimspecialedition/mods/19608), [Enemy Variations](https://www.nexusmods.com/skyrimspecialedition/mods/23006), and the three complimentary Wenches packs: [Forgotten Wenches](https://www.nexusmods.com/skyrimspecialedition/mods/601), [Judgment Wenches](https://www.nexusmods.com/skyrimspecialedition/mods/602), and [Hateful Wenches](https://www.nexusmods.com/skyrimspecialedition/mods/600).

For creatures, there's [SkyTest](https://www.nexusmods.com/skyrimspecialedition/mods/1104) and [Animallica](https://www.nexusmods.com/skyrimspecialedition/mods/20456) to increase the animal variety and challenge.

### The Economy & Loot Mods
If you expected the economy in Dungeons & Deviousness to be a cakewalk, think again. Gear is expensive, potions are few, and there's a lot of things to sink money into throughout the game. You'll almost constantly be just barely scraping by. [SkyRem Eve](https://www.nexusmods.com/skyrimspecialedition/mods/26325), [Trade & Barter](https://www.nexusmods.com/skyrimspecialedition/mods/23081), and [Supply and Demand](https://www.nexusmods.com/skyrimspecialedition/mods/32365) all work together to make this happen.

That is, until you embrace your heroic destiny and go delving into dungeons. Yes, there's significant risk, but the rewards, oh boy, the rewards. Dungeon loot is exceptionally generous in Dungeons & Deviousness. Chests will be filled to bursting, enemies will have lots of gold and gems, and even Dragons will have significant amounts of loot - if you can slay them. This is owed to [Narrative Loot](https://www.nexusmods.com/skyrimspecialedition/mods/12812), [Dynamic Dungeon Loot](https://www.nexusmods.com/skyrimspecialedition/mods/10308), and [GOLD](https://www.nexusmods.com/skyrimspecialedition/mods/1796).

### The Perks & Leveling Mods
[Adamant](https://www.nexusmods.com/skyrimspecialedition/mods/30191) is the perk overhaul of choice for Dungeons & Deviousness. It makes the perk trees a bit more interesting without being overpowered like some other perk overhauls. [Experience](https://www.nexusmods.com/skyrimspecialedition/mods/17751) modifies how quickly you level up and from what you get XP. For Dungeons & Deviousness you only get XP for clearing dungeons (AKA defeating bosses), completing quests, and killing enemies - just like in a traditional RPG. Experience also caps how high your skills can be based on what level you are, so if you can't level up a skill, you need to level up more before being able to level up that skill any further.

### The HUD and UI Mods
The HUD and UI for Dungeons & Deviousness can get pretty cluttered. I've done my best to clean it up as much as I can through the MCM setup, but here's the ones you need to know about: [Dear Diary](https://www.nexusmods.com/skyrimspecialedition/mods/23010) is the primary UI overhaul, with a dark mode patch made by jdsmith2816. It's really nice and I feel it fits the tone of this list really well. [A Matter of Time](https://www.nexusmods.com/skyrimspecialedition/mods/12937) lets you keep track of what time it is so you can plan your next moves, whether it's to delve into a dungeon or make your way back to town so you can sleep. [EZ2C Dialogue Menu](https://www.nexusmods.com/skyrimspecialedition/mods/2246) is fully customizable so you can setup the dialogue menus however you want. [Less Intrusive HUD II](https://www.nexusmods.com/skyrimspecialedition/mods/17974) gets pesky HUD elements out of your way when you don't need them.

### Your Fellow Party Members
In the preface I mentioned gathering your adventuring party to set out on your epic quest - I wasn't kidding. Thanks to Nether's Follower Framework (more on that later) you can recruit just about any NPC into your party if you offer them enough gold. There are also quite a few unique followers as well: [Abigail](https://www.loverslab.com/files/file/1257-abigail-the-lusty-imperial-maid/), [Shindara](https://www.nexusmods.com/skyrimspecialedition/mods/10094), [Rosa](https://www.nexusmods.com/skyrimspecialedition/mods/13209), [Sofia](https://www.nexusmods.com/skyrimspecialedition/mods/2180), [Miraak](https://www.nexusmods.com/skyrimspecialedition/mods/6835), [Hoth](https://www.nexusmods.com/skyrimspecialedition/mods/16137), [Kaidan](https://www.nexusmods.com/skyrimspecialedition/mods/19075), [Mirai](https://www.nexusmods.com/skyrimspecialedition/mods/10908), and [Interesting NPCs](https://www.nexusmods.com/skyrimspecialedition/mods/29194).

### Nether's Follower Framework
[Nether's Follower Framework](https://www.nexusmods.com/skyrimspecialedition/mods/18076) is what makes the entire "adventuring party" idea work in Dungeons & Deviousness. With it, you can set each followers individual role and combat style, teach them new spells, change their equipment, and so on. If you've ever dreamed of having that perfect 4-person party to explore Skyrim with, this is how it's done. You're going to have at least one follower with you at all times, you might as well make sure they're living up to their potential.

## Final Thoughts & Best Practices
- Autosaves are disabled. This save option is known to cause issues with heavily scripted games. Quicksaves are automatically turned into Manual Saves by SSE Engine Fixes. It is recommended to save **early** and **often**. Every 15 minutes and before interacting with quest NPCs, quest objects, and entering new zones should be sufficient. **Old saves can be deleted, but forgetting to save loses progress forever!**
- Wabbajack supports updating/upgrading over an existing installation, but it will automatically delete any files that aren’t used for the modlist installation. This means if you have changed the modlist in any way, Wabbajack will delete those changes and **delete your saves.** Keep backups of any changes you do make and your saves (as ill-advised as making changes may be).
- **NEVER** save right after a loading screen. Wait 30 seconds before saving to let scripts finish executing. It's always better to save before a loading screen than after one.
- **NEVER** use autosaves. Autosaves are unpredictable at best, and save-corrupting at worst.

### Getting Started in Dungeons & Deviousness
Here are some basic tips to get you started on your adventure.

- You need a follower. Seriously, you won't be able to leave the major cities unless you have at least one with you. The ideal adventuring party is four people including yourself, I'd recommend recruiting up to that number as you're able. There are plenty available in every city thanks to Nether's Follower Framework's expendable recruits system.
- Patience and skill are rewarded heavily in this list. Time your strikes properly and block frequently and you'll be fine. Potions and sustained spells can also go a long way to keeping you alive.
- Changing your equipment to suit the enemies you'll be facing is extremely important - if you're doing little to no damage, you likely need to try a different weapon type. Similarly, some armors are better against certain types of damage, so swapping out armor as needed can be extremely beneficial to stay alive.
- In the same vein as the previous tip, diversifying what your character is skilled with is rewarded nicely. I'm not saying you need to take *every* perk in a given perk tree, but being able to effectively use two to three different types of damage will be beneficial. Your adventuring party can also help make up for any lack of variety you have.
- You get XP from kills in this list, so if you're struggling with dungeons, try just wandering around and killing random animals to gain your first few levels. Easy quests are also your friend here, such as heading to Helgen to start the main storyline.
- When you first start out, gold is going to be extremely hard to come by. You might have to spend some time slumming it in a major city to make enough gold to hire your first follower and leave. There are a ton of options when it comes to this, everything from outright begging to less savory methods of making gold. You could also get a job as a working girl at an inn. You should be fine once you manage to clear your first two or three dungeons though.
- Camping gear is heavy and expensive but essential if you want to survive in the wilderness. You'll likely spend several days in a row adventuring so being able to sleep comfortably along with the food/water supplies needed is essential. Try to stock up when you can - make your party carry things for you if you must.
- Dragons are really difficult in this list. I'd recommend being level 20 or so before you even consider taking one on - trying to fight the first dragon too early will likely end up with you loading an earlier save from before you started the fight.

## Troubleshooting & FAQ
Additions will be made to this FAQ as needed.

**I get stuck in certain animations!**  
This is usually caused by script lag. There's really no way around it, it will happen sometimes. Normally, you can open the console using the tilde key (~) on your keyboard or pause the game (Esc) for a few seconds and it will catch up. If you're still stuck after doing that, you may need to reload an earlier save. Unfortunately the combination of mods being used can have this happen on occasion. Short of rewriting the scripts used, there's really no way to fix it. Save frequently just in case this does happen to you.

**What do/don’t you support?**  
All unmodified Wabbajack installs of Dungeons & Deviousness are supported. Pirated copies of Skyrim are illegal and not supported. Any modlist that changes Dungeons & Deviousness by adding/removing mods is not supported. Manually installed reproductions of Dungeons & Deviousness are not supported. Any ENB compatible with the weather mods installed with Dungeons & Deviousness are supported. With extremely few exceptions, mods from LE/Oldrim are not supported and will never be included in Dungeons & Deviousness. Converting old saves to Dungeons & Deviousness is not supported, only new saves created after Dungeons & Deviousness is installed are supported. The same is true of saves from previous versions of Dungeons & Deviousness.

**The installer isn’t working, what can I do?**  
The short answer: wait for an update. The long answer is you can try to install the missing mods manually if the files are still available on the Nexus, but again, do not ask for anyone to share old files. I work a full-time job in addition to several other personal projects, of which Dungeons & Deviousness is just one. If installs are failing, I will try to update as quickly as possible but sometimes it may be a couple of days before I can get to it.

**How often does Dungeons & Deviousness update?**  
There’s no set schedule for Dungeons & Deviousness updates. If a mod updates and the list requires a revision, I’ll try to get to it as quickly as possible, but I make no promises. Sometimes troubleshooting updates and rebuilding the list can take days. Anytime there is an update, it will be clearly communicated on the Wabbajack and Dungeons & Deviousness Discord servers. That being said, as long as nothing else changes, you should be safe to continue playing an existing installation unless there is an update to Skyrim itself. Remember: the point of all modlists is to play the game. If you’re spending more time updating your list than playing, you’re doing it wrong.

**I found a bug! How do I report it?**  
Check the [D&D Issues](https://github.com/ForgottenGlory/Dungeons-Deviousness/issues). If it’s not already on there, submit a new issue. Be as specific as possible, including screenshots if possible. If it is related to a specific mod, include the name of the mod and the exact steps to reproduce the issue. The best thing you can send for things like incorrect numbers/values or dark face NPCS (if there are any)  is a screenshot of the thing in question selected with the console including the ID of the object/character. Vague reports such as “my game randomly CTDs” will be ignored if they do not include more details.

**Can I play this list on a 75/100/144hz screen?**  
Yes. Display Tweaks SSE is included which allows for this.

**The modlist updated! Do I have to update and start a new save?**  
If your game is working, you’re not required to update. It’s always recommended though, as updates likely fix bugs, update mods, or add new mods or remove unsatisfactory ones. As for starting a new save, it depends on the version. In general, anything that is a 2.0.x update won’t break your save, and is usually just for when a mod updates and the list needs to be recompiled to make it work again. Anything that is an 2.x.0 update adds or removes mods, which likely will break your save (unless otherwise specified). Any full version number changes, x.0.0, are major overhauls/rebuilds of the list and are guaranteed to break your save.

**Can I stream/Let’s Play this modlist?**  
Have fun getting banned from whatever platform you use.

**My game freezes when saving.**  
Make sure you’ve disabled all overlays for Skyrim. The most common ones are Discord, Steam, and nVidia. Other overlays from things like MSI Afterburner and f.lux have also been known to cause issues.

**What the heck is going on with the dialogue menu?**  
It's being modified by [EZ2C Dialogue Menu](https://www.nexusmods.com/skyrimspecialedition/mods/2246/). Check that mod's page for details of how to configure it if it's not to your liking.

**Can I request a mod be added to Dungeons & Deviousness?**  
No.

## Credits & Thanks
- Dungeons & Deviousness created by ForgottenGlory
- Dungeons & Deviousness Beta Testers:
  - 
- Halgari & The Wabbajack Team
  - Thank you for creating Wabbajack, you’re amazing!
  - [Halgari’s Patreon](https://www.patreon.com/user?u=11907933)
- Special Thanks
  - The TUCO Modding Team - Their modlist is a great way to get a Vanilla+ experience with a tutorial that is extremely helpful for learning the basics of creating a modlist.
  - DarkLadyLexy - Her LotD list is an invaluable resource not only for an awesome modlist, but also for learning many fundamentals of modding and compiling a modlist.
  - EzioTheDeadPoet - For their SME(FT) modlist. The ability to start from scratch on a whim while building this list has been invaluable.
- Mod Authors
  - None of this would be possible without the people who make the quality content we’ve grown to know and love. Please endorse the authors’ works.

### One Last Thing
If you read through the entire readme, congratulations! You get a cookie. If you need any further help, feel free to reach out on the Wabbajack or Dungeons & Deviousness Discord Servers. **Do not direct message ForgottenGlory or any Wabbajack staff members for support. I (ForgottenGlory) speak for myself, but I do reserve the right to ignore any requests for support direct messaged to me and block you.**
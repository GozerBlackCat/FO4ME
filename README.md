# FO4ME

---

- [FO4ME](https://github.com/GozerBlackCat/FO4ME/blob/main/README.md#FO4ME)
- [Preamble](https://github.com/GozerBlackCat/FO4ME/blob/main/README.md#preamble)
- [Installation](https://github.com/GozerBlackCat/FO4ME/blob/main/README.md#installation)
  - [Pre-Installation](https://github.com/GozerBlackCat/FO4ME/blob/main/README.md#pre-installation)
    - [Installing Microsoft Visual C++ Redistributable Package](https://github.com/GozerBlackCat/FO4ME/blob/main/README.md#installing-microsoft-visual-c-redistributable-packages)
      - [Visual Studio 2015, 2017, 2019, and 2022](https://github.com/GozerBlackCat/FO4ME/blob/main/README.md#visual-studio-2015-2017-2019-and-2022)
      - [Visual Studio 2012 (VC++ 11.0) Update 4](https://github.com/GozerBlackCat/FO4ME/blob/main/README.md#visual-studio-2012-vc-110-update-4)
    - [Steam Config](https://github.com/GozerBlackCat/FO4ME/blob/main/README.md#steam-config)
      - [Disable the Steam Overlay](https://github.com/GozerBlackCat/FO4ME/blob/main/README.md#disable-the-steam-overlay)
    - [Change Steams Update Behavior](https://github.com/GozerBlackCat/FO4ME/blob/main/README.md#change-steams-update-behavior)
    - [Set the Game language to English](https://github.com/GozerBlackCat/FO4ME/blob/main/README.md#set-the-game-language-to-english)
    - [Clean Fallout 4](https://github.com/GozerBlackCat/FO4ME/blob/main/README.md#clean-fallout-4)
  - [Using Wabbajack](https://github.com/GozerBlackCat/FO4ME/blob/main/README.md#using-wabbajack)
    - [Preparations](https://github.com/GozerBlackCat/FO4ME/blob/main/README.md#preparations)
      - [Problems with Wabbajack](https://github.com/GozerBlackCat/FO4ME/blob/main/README.md#problems-with-wabbajack)
- [Post Installation](https://github.com/GozerBlackCat/FO4ME/blob/main/README.md#post-installation)
- [How do I include my favorite weapon and armor mods cleanly?](https://github.com/GozerBlackCat/FO4ME/blob/main/README.md#how-do-i-include-my-favorite-weapon-and-armor-mods-cleanly)
- [What if I don't see the weapon or armor mod I want to include in the FOMOD?](https://github.com/GozerBlackCat/FO4ME/blob/main/README.md#what-if-i-dont-see-the-weapon-or-armor-mod-i-want-to-include-in-the-fomod)
- [Noteworthy Mods](https://github.com/GozerBlackCat/FO4ME/blob/main/README.md#noteworthy-mods)
- [FAQ](https://github.com/GozerBlackCat/FO4ME/blob/main/README.md#faq)
- [Credits and Thanks](https://github.com/GozerBlackCat/FO4ME/main/README.md#credits-and-thanks)
- [Contact](https://github.com/GozerBlackCat/FO4ME/blob/main/README.md#contact)

---

# Preamble

![This is an image](https://github.com/GozerBlackCat/FO4ME/blob/main/instructionalpics/FO4ME.png?raw=true)

---

### FO4ME

FO4ME (Fallout 4 Modding Essentials) is a Fallout 4 modlist that ideally should serve as a jumping off point for anyone wanting to make their own customized list. It includes various bug fixes, stability improvements, and prerequisites for some popular mods. I tried to use mods that wouldn’t conflict with whatever you might add. This is a list for those that want to start making their own list without the hassle of manually downloading prerequisite mods on their own.

**Please read the FAQ again before reporting an issue or asking me a question.**

---

## Installation

---

### Pre-Installation

You need a legal copy of Fallout 4 through Steam, with all DLCs **EXCEPT** the High Definition DLC. This is garbage and should not be used in any case ever.

These steps are only needed if you install this Modlist for the first time. If you update the Modlist, jump straight to [Updating](#updating).

#### Installing Microsoft Visual C++ Redistributable Packages

These packages are required for MO2 and you can download them from [Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads).

##### Visual Studio 2015, 2017, 2019, and 2022

Download the x64 version under [Visual Studio 2015, 2017, 2019, and 2022](https://docs.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170#visual-studio-2015-2017-2019-and-2022).

[Direct Link](https://aka.ms/vs/17/release/vc_redist.x64.exe) if you can't find it.

##### Visual Studio 2012 (VC++ 11.0) Update 4

Download the x64 version under [Visual Studio 2012 (VC++ 11.0) Update 4](https://docs.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170#visual-studio-2012-vc-110-update-4).

[Direct Link](https://download.microsoft.com/download/1/6/B/16B06F60-3B20-4FF2-B699-5E9B7962F9AE/VSU_4/vcredist_x64.exe) if you can't find it.

#### Steam Config

#### Change Steams Update Behavior

Fallout 4 is still being updated by Bethesda (they only add Creation Club content). Whenever the game updates, the entire modding community goes silent for the next one or two weeks because some mods need to be updated to the latest game runtime version.

To ensure that Steam does not automatically updates the game for you, head over to the Properties window, navigate to the _Updates_ tab and change _Automatic updates_ to _Only update this game when I launch it_. You should also disable the Steam Cloud while you're at it.

#### Set the Game language to English

Just do it. This entire Modlist is in English and 99% of all mods you will find are also in English. I highly recommend playing the game in English and **I will not give support to people with a non-English game**. I really wish I could, but at this time, it simply isn't feasible.

Open the Steam Properties window, navigate to the _Language_ tab and select _English_ from the dropdown menu.

#### Clean Fallout 4

I highly recommend uninstalling the game through Steam, deleting the game folder and reinstalling it. You should also clean up the `Fallout 4` folder in `Documents/My Games/`. **Make sure you run the game once** to establish your registry path - otherwise, Wabbajack will be unable to locate the game directory, and thus cannot install the modlist.

---

### Using Wabbajack

---

#### Preparations

Let's get to the actual installation..

Grab the latest release of Wabbajack from [here](https://www.wabbajack.org/#/) (just click the big blue Download button). Place the `Wabbajack.exe` file in a blank folder at the root of a drive, such as `C:/Wabbajack`. Please do not put it in a Windows Protected Directory, such as Program Files or your Desktop.

Launch Wabbajack. The exe will download the rest of the program from Github and extract itself wherever you placed the exe. When it is finished extracting and installing itself, select the `Browse Modlists` option. Tick the `Show Unofficial Lists` button. Click the Download arrow for FO4ME, and you will be forwarded to the next screen when it is finished. 

Set the `Installation Location` to a blank folder at the root of a drive, such as `D:\FO4ME`. The `Download Location` will update automatically. Again, please avoid using Windows Protected Directories.

Click the `Play` arrow. If you have a Nexus Premium account, all of your downloads will be automated. Without Premium, you will need to manually click the Download button for each mod. Installation will be automated regardless of your account status.

---

### Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-running Wabbajack before posting anything. Wabbajack will continue where it left off so you lose no progress.

- **Wabbajack could not find my game folder**:

Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the [Pre-Installation](#pre-installation) step.

---

## Updating

If this Modlist receives an update, please check the Changelog before doing anything. Always backup your saves or start a new game after updating.

FO4ME updates based on a [Semantic Versioning](https://en.wikipedia.org/wiki/Software_versioning) system.

Generally speaking:  
- Full x.0 (2.0, 3.0, etc) updates requires a new game.  
- Major x.x (2.1, 2.2 etc) updates requires a new game.  
- Minor x.x.x (2.1.1, 2.1.2) updates can be applied to an ongoing playthrough.

**Wabbajack will delete all files that are not part of the Modlist when updating!**

This means that any additional mods you have installed on top of the Modlist will be deleted. Your downloads folder will not be touched!

If you wish for Wabbajack to ignore any additional mods you've installed, rename them to say `[NoDelete]` at the beginning of the name.

Updating is like installing. You only have to make sure that you select the same path and tick the _overwrite existing Modlist_ button.

---

## Post Installation

#### Copy Game Folder Files

After Wabbajack turns green and says Installation Complete, you can close it. Go to your installation folder (I will refer to this folder as the MO2 folder from now on) and you'll see a folder named `Game Folder Files`.

Copy all of the files from the `MO2/Game Folder Files` directory into your game folder. To further clarify this, you are copying **the contents** of this folder, not the entire folder itself.

---

#### Launching the Game

After you copied the Game Folder Files, launch ModOrganizer.exe from inside your installation folder you chose for Wabbajack. Make sure the bar on the right side says `F4SE` and click Run. **You need to launch the game in this exact way every time in order to play with the installed mods.**

---
## How do I include my favorite weapon and armor mods cleanly?

#### Patches For Lively's Keywords Resource and Whisper's Standalone Workbenches 

Your first plan of action is to reinstall this mod

![This is an image](https://github.com/GozerBlackCat/FO4ME/blob/main/instructionalpics/patches2finished.png?raw=true)

You will be greeted with a FOMOD. If any of the modded items you have added are listed in this FOMOD, tick the corresponding box for that item.

![This is an image](https://github.com/GozerBlackCat/FO4ME/blob/main/instructionalpics/patches3.png?raw=true)

#### LKR and WSW Weapon Patches

Do the same for "LKR and WSW Weapon Patches".

![This is an image](https://github.com/GozerBlackCat/FO4ME/blob/main/instructionalpics/patchpics1.png?raw=true)

Same process here as with the previous patch

![This is an image](https://github.com/GozerBlackCat/FO4ME/blob/main/instructionalpics/patchespic2.png?raw=true)

---

## What if I don't see the weapon or armor mod I want to include in the FOMOD?

#### There is a guide just for this situation!

LivelyDismay was nice enough to make a guide on how to patch items into his mod list "Magnum Opus"! This guide will work for patching modded items into FO4ME, as they use a similar sorting structure.

Use this guide [here](https://github.com/LivelyDismay/Learn-To-Mod/blob/e700e10be41c1a70955e8426aee040bc647d90b3/lessons/Weapon%20Patching%20for%20Magnum%20Opus.md)!

---
## Running M8r's Complex Sorter

After patching any mods that add items, you should use the complex sorter to have them be sorted correctly in game. it's very simple.

First, open FO4Edit, and make sure all of your plugins are selected, excluding ones that are grayed out. Wait for the background loader to finish.

![This is an image](https://github.com/GozerBlackCat/FO4ME/blob/main/instructionalpics/patchpic3.png?raw=true)

Next, right click in the left pane, and select `Apply Script`

![This is an image](https://github.com/GozerBlackCat/FO4ME/blob/main/instructionalpics/patchpic4.png?raw=true)

In the filter bar, type in "M8r" and find `M8r_ComplexSorter`. Run this script.

![This is an image](https://github.com/GozerBlackCat/FO4ME/blob/main/instructionalpics/patchpic5.png?raw=true)

You should be greeted with a window like this. Make sure it matches the picture, then simply click `Generate Patch`.

![This is an image](https://github.com/GozerBlackCat/FO4ME/blob/main/instructionalpics/patchpic6.png?raw=true)

Wait for the sorter to finish, then close out of it. You may now close FO4Edit. Be sure to save the new plugin.

![This is an image](https://github.com/GozerBlackCat/FO4ME/blob/main/instructionalpics/patchpic7.png?raw=true)

#### You did it!
---

## Noteworthy Mods

### Buffout 4

The equivalent of SSE Engine Fixes, Buffout basically makes lists like this possible. Memory patches, achievements enabler, memory leak warnings, and so much more. This is likely the single most important mod in the entire list.

Read more about it [here](https://www.nexusmods.com/fallout4/mods/47359)!

### Unofficial Fallout 4 Patch

A comprehensive bugfixing mod for Fallout 4. The goal of the Unofficial Fallout 4 Patch (aka UFO4P) is to eventually fix every bug with Fallout 4 not officially resolved by the developers to the limits of the Creation Kit and community-developed tools, in one easy-to-install package.

Read more about it [here](https://www.nexusmods.com/fallout4/mods/4598)

Alongside many other active mods

---

### In-Game MCM Options

I don’t have any specific options, all of the settings are left to personal preference.

---
### FAQ

**My characters have black/brown/tan faces.**

- Disable the High Definition DLC in Steam's Manage DLC section. As per the beginning of this readme, the HD DLC is absolute garbage and WILL break a ton of facegen.

**I am having random crashes.**

- A reason this could be happening is due to your Nvidia driver. Roll back to version 442.xx and the crashes will be gone.

- And yet another reason is due to BitDefender. You can temporarily disable BitDefender to alleviate this issue.

### Credits and Thanks

- To Halgari, for creating Wabbajack, the wonderful program that makes this possible.

- To LivelyDismay, creator of Magnum Opus, whose work i have been silently studying and the person who I copied most of the writing in this README from. He’s a really good mod list author, and you should check Magnum Opus out.

- To YOU, for reading this guide and following it.

---
## Contact

I'm always available on the [FO4ME discord server](https://discord.gg/W9czPm9M), and the [the Wabbajack discord server](https://discord.gg/wabbajack).

---
layout: default
title: 补丁使用与详细介绍
---

**请注意：本页面基于Beast's Lair论坛官方发布的README-patch进行搬运，如使用了该补丁有任何游戏运行的出错问题可前往[官方发布页](https://forums.nrvnqsr.com/showthread.php/9101-Fate-Stay-Night-Realta-Nua-Ultimate-Edition-2022?s=83bd12d63bc38a7ad86cb7bb54678720)进行反馈(请用英文反馈！请用英文反馈！请用英文反馈！重要的事情说三遍)**

- ### 详细补丁列表
	- patch.xp3	**主要运行补丁，一定要有**
	- patch_op.xp3	**旧版新版不同开场动画整合补丁，推荐使用**
	- patch_vita_ost.xp3	**psv版Realta Nua音乐移植补丁，推荐使用**
	- patch_lang_english.xp3	**英化补丁，可选**
	- patch_lang_simplified-chi.xp3	**汉化补丁，可选**
	- patch_lang_english-retrans.xp3	**英化重制补丁，仍在测试制作中不推荐使用**
	- patch_h.xp3	**H补丁，可选**
	- patch_hd.xp3	**HD高清化补丁，目前仅测试过可用于PC端，可选**
	- patch_hd_1600.xp3	**1600P高清化补丁，目前仅测试过可用于PC端，可选**
	- patch_hd_1920.xp3	**1920P高清化补丁，目前仅测试过可用于PC端，可选**
	- patch_hd_2400.xp3	**2400P高清化补丁，目前仅测试过可用于PC端，可选**
	- patch_hd_3200.xp3	**3200P高清化补丁，目前仅测试过可用于PC端，可选**



#### 补丁最新版本：

#### Ultimate Patch v1.1.5

#### English Patch v3.5.1

#### Simplified-Chinese Patch v1.0.2
___________________________________

######             © TYPE-MOON
###### Translation © Mirror Moon
___________________________________

#### （目前官方的文档说明仅更新到v1.1.3，估计日后会更新到v1.1.5）

Table of Contents
-----------------

* [Introduction](#introduction)
* [System requirements](#system-requirements)
* [Recommended specs](#recommended-specs)
* [Installation](#installation)
* [About the Patches](#about-the-patches)
* [First Time Running](#first-time-running)
* [Playing the Game](#playing-the-game)
* [Config Menu](#config-menu)
* [Switches Guide](#switches-guide)
* [FAQ](#faq)
* [Troubleshooting](#troubleshooting)
* [Known issues](#known-issues)
* [Credits](#credits)
* [Contact](#contact)
* [Version History](#version-history)


Introduction
------------

This readme file contains important information about the original game and the Ultimate Edition patch.  
Please read it before you start playing.

Fate/stay night Réalta Nua Ultimate Edition is an ambitious project to bring you the ultimate Fate/stay night experience.  
This is not an easy task, as the game has seen multiple releases over various platforms with each having its own unique enhancements:

* Fate/stay night trial (October 21st, 2003) - first demo release of the game.
* Fate/stay night PC (January 30th, 2004) - the original release. Henceforth known as the classic release.
* Fate/stay night PC DVD Edition (March 29th, 2006) - An updated version to the classic release with bugfixes and edits to the scripts.
* Fate/stay night Réalta Nua PS2 (April 19th, 2007) - a remaster of the game for the PS2. Censored all the mature and sexual content but also added new scenes, special effects and an extended OST.
* Fate/stay night Réalta Nua PC (beginning of 2012) - A PC version of Réalta Nua. This version, however, sold the different routes of the game separately.
* Fate/stay night Réalta Nua PS Vita (November 29th, 2012) - A Vita version of Réalta Nua. This release boasted a new remastered soundtrack, new OPs by Ufotable, and the option to play the game at wide mode.
* Fate/stay night Réalta Nua mobile (April 18th, 2015 for iOS / May 29th, 2015 for Android) - An iOS and Android version of Réalta Nua. This release is similar to the PS vita release, but also features higher resolution (x1.6) CGs.
* Fate/stay night + Fate/hollow ataraxia PC Reprint Edition (June 28th 2019) - A rerelease of the classic version.

The Ultimate Edition brings you all the goodies from all versions of the game, and allows you to decide what kind of experience you want to have using switches.  
We hope you enjoy the game at its finest.  

Here is a comparison between the classic release and (all) the Réalta Nua versions:

| Feature / Version     | Classic            | Réalta Nua                                                                        |
| --------------------- | -------------------| ----------------------------------------------------------------------------------|
| CGs                   | Original           | New CGs                                                                           |
| Soundtrack            | Original           | Extended OST with new tracks                                                      |
| Special effects       | Original           | Added special effects to a lot of scenes                                          |
| Text                  | Original           | Edited text                                                                       |
| Censorship            | Uncensored         | Censors mature content (H-scenes, nudity, gore) both visually and textually       |
| Exclusive scenes      | H-Scenes           | Alternative scenes to H-scenes (AKA H-alt), an epilogue after completing the game |


Here is a short comparison between all the versions:

| Feature / Version     | Classic PC         | PS2                 | Réalta Nua PC       | PS Vita                       | Mobile             |
| --------------------- | -------------------| --------------------|---------------------|-------------------------------|--------------------|
| Routes order          | Forced             | Forced              | Unforced            | Forced                        | Forced             |
| Soundtrack            | Original           | Extended            | Extended            | Extended (remixed)            | Extended (remixed) |
| Openings              | Original           | PS2                 | Vita                | Vita                          | Vita               |
| Resolution            | 800x600            | 640x480             | 800x600             | 800x600                       | 1280x960           |
| Wide Screen           | No                 | No                  | No                  | Yes (crop)                    | Yes (crop)         |


System requirements
-------------------

* Windows 7 with Service Pack 1 or newer
* 3D accelerated graphics drivers
* Sound drivers
* 6.5GB of free space (for installer + resulting "Ultimate Edition" with merge patch only; source unmerged Realta Nua data not accounted for)

Recommended specs
-----------------

* 2GHz dual core CPU or a GPU with hardware h.264/AVC decoding (read: any integrated or discrete GPU made in the last 10 years)
* Enough RAM to run Windows 7 without the OS bogging down too much (at least 2GB, ideally 3GB+)
* 15GB of free space (installer + resulting "Ultimate Edition" with all patches + source unmerged Realta Nua data)

Installation
------------

##### Prerequisites:
You must have the 3 separate routes of the original Fate/stay night Réalta Nua PC release from 2012 available to you in order to install the Ultimate Edition.

##### Game Installation:
Launch the provided installer and follow the instructions.  

##### Portable Installation:
Just tick the "Portable Installation" checkbox in the installer.

##### Android installation
If you want to play the game on Android devices with [Kirikiroid2] apply the following steps:
1. Install the game.
   
   > ❗ Note: If you didn't choose a [portable](#portable-installation) installation, make sure that the save folder location you choose (as part of the installation process) is inside the installed game's directory.
2. Remove any previous files you might have dropped to the game folder trying to make it run on Kirikiroid2, namely:
	* patch.tjs
	* Override2.tjs
	* xp3filter.tjs
	* config.ksc
3. Copy the contents of the `Android` folder (not the folder itself) to the game's folder.
4. Place the game folder somewhere on your phone.
5. Open Kirikiroid2 and select data.xp3 (which is inside the game's folder) to launch it.

> 💡 Tip: if the game is running slowly, apply the `Dec XP3` option in Kirikiroid2.

##### Uninstallation
Open *Control Panel* from the *Settings* in the start menu and select *Add or Remove Programs*.  
Select *Fate/stay night \[Réalta Nua\] Ultimate Edition* and press *Uninstall*.  
Afterwards follow the instructions.  
> ❗ Note: if you installed in a [portable](#portable-installation) manner, you can just delete the game folder (if you chose the save folder to be your game folder, your saves will be deleted as well).

First Time Running
------------------
Depending on your system, you might have to switch to Japanese locale or use [Locale Emulator] \(or AppLocale on pre-windows 10 systems\).  
Execute `Fate.exe` in the installation folder (or click the desktop/startup icons).  
You will be prompted to select the folder containing the save folder. Select the folder and press OK.  
Alternatively, you can press Cancel and the save folder will be placed in the installation folder.  
> ❗ Note: The save folder name is `faterealtanua_savedata`.


About the Patches
-----------------

Mandatory patches:

* `patch.xp3`  
This is the **core** patch for the game laying the foundation for the following patches.  
It merges all the routes to a single game, where each route unlocks after finishing the previous one - much like the classic and PS2/Vita releases. The title background will change depending on your progress in the game.  
Each route is unlocked after finishing the previous one, with the order being: Fate, Unlimited Blade Works, and Heaven's Feel.

The following patches are optional, and even if you add them you can turn on/off all of their features via in-game switches:

* `patch_lang_english.xp3`  
Adds an English translation to the game. (Japanese is always available even without an additional patch.)
You can switch between English, Japanese, and any other language you have installed a patch for via the "Language" section in the menu bar.

* `patch_hd.xp3, patch_hd_1600.xp3, patch_hd_1920.xp3, patch_hd_2400.xp3, patch_hd_3200.xp3`  
Adds higher resolution image assets to the game. Since these are upscales, going beyond 1920 might not necessarily give any real benefit.
The used resolution can be changed from the menu bar's "Display -> Quality" section.

* `patch_op.xp3`  
Adds high resolution Vita, PS2, and classic OPs (opening movies). The classic OP are only available at the movie menu when unlocked, while the PS2 and Vita openings play at different parts of the game as well.

* `patch_vita_ost.xp3`  
Adds an optional PS2 and remixed vita versions for the OST in the game.  
In the BGM menu at the config menu, you can individually select for each track whether to use the original, PS2, or remixed version.  
In addition, there are multiple tabs in the music menu for listening to the different variations.  
When you unlock a BGM, all its variations will unlock as well.  
  > ❗ Note: Diver and Diver2, as well as Violation and Violation2 have been merged to a single track (named Diver and Violation) in the remixed Vita OST.  
    That means, that while they will appear separately in the config BGM menu (since in the original OST they are different), they will only appear once (named Diver and Violation) in the music menu.

* `patch_h.xp3`  
Optionally restores the sex scenes, nudity, and other sexual content from the classic 18+ PC release from 2004.  
Also contains optional fan-made depixelated images for the H-scenes with removed mosaic censorship.
The settings can be changed in the menu bar's "Patch -> Censorship" section.


Playing the Game
----------------
The input differs depending on context in the following way:

##### Menu screen (title, right-click menu, etc.)
```
     Mouse left-click / Enter key / Space key
         Decision

     Mouse right-click / Escape key / Backspace key / Delete key / Home key
         Return to the previous menu (When it can not return any more, it will prompt you to exit the game)

     Tab key / → key / ↓ key
         Move to next choice (button, etc.)

     Shift + Tab key / ← key / ↑ key
         Move to previous choice (button, etc.)

     Mouse Wheel
         (When there is a scroll bar) Scroll up and down
```

> ❗ Note: Some menus are created on with the premise of operating with the mouse.

##### In-Game
```
    Mouse left-click / Enter key / Space key / Down arrow key
        (When waiting for clicking) Next
        (When options are displayed) Choose an option
        (When in auto-read mode) Cancel auto-read

    Note: You can keep the left-mouse pressed for repeated clicking.

    Mouse right-click / Escape key / Home key
        (When waiting for input) Open game menu

    Delete key / Backspace key
        (When waiting for input) Hide text layer

    Tab key / → key / ↓ key
        (When options are displayed) Move to the next option (button, etc.)

    Shift + Tab key / ← key / ↑ key
        (When options are displayed) Move to previous option (button, etc.)

    Scroll up mouse-wheel / Page Up key / R key / ↑ key
        (When waiting for input) Display text history

    Scroll down mouse-wheel
        (When waiting for clicking) Next
        (When in auto-read mode) Cancel auto-read

    C key
        Open the config menu

    A key
        Start auto-read mode

    F key
        Skip to the next unread text / choice

    Q key
        Open the quick-save menu

    Alt+F# keys (# being any number from 1 to 9 except 4)
        Create a quick-save

    F# keys (# being any number from 1 to 9 except 4)
        Load a quick-save

    Numpad-Plus key
        Scroll down background (wide mode only)

    Numpad-Minus key
        Scroll up background (wide mode only)

    Numpad-Multiply key
        Reset background position (wide mode only)
```

##### Text History Display
```
     Scroll up mouse-wheel / ← key / ↑ key
         Go to the previous page

     Scroll down mouse-wheel / → key / ↓ key
         Go to the next page
         (If you are viewing the latest history text) Scroll down to return to the game
```

##### Save/Load Menu
```
     Mouse Drag & Drop
         You can rearrange the save-slots by dragging and dropping a save-slot to an empty or existing slot (the latter will swap the slots location)
```

##### Other
```
     Alt+Enter keys
         Fullscreen <-> window switch

     Alt+F4 keys
         Exit game
```


Config Menu
-----------
This section will explain the different options in the config menu.
##### Message
```
    Unread message display interval

        Move the tab left or right to change the display interval of one letter of the unread message.
        Moving it to the left will shorten the display interval and display characters at high speed.
        Conversely, moving it to the right will display characters slower.
        The number displayed represents the concrete display interval (in milliseconds).

    Already read message display interval

        As above, change the display interval of read messages rather than unread messages.
        With the exception of being applied to already read messages,the mechanism is the same
        as unread messages.

    Automatic page switching time

        Changes the page switching wait time of the auto-read mode.
        Moving to the left shortens the waiting time and moves immediately to the next page.
        Moving to the right side, the waiting time will be long, suited for slow readers.
        The displayed number represents the specific waiting time (in milliseconds).
```

##### Message skip
```
    Skipping read scenes

        By turning it on, you can skip the scenes you have already seen.
        It is possible to progress through the game more quickly this way.

    Confirm skipping

        When turned on, asks before skipping when entering a read scene.
        It is a useful function when you want to see specific scenes without skipping.
        Of course, such confirmation is only relevant when skipping read scenes is ON.

    Message fast forward key setting

        Select the key for fast forward skipping.
        It will skip even unread text, so please use with care.
        By default it is assigned to the Ctrl key.
```

##### Sound
```
     Master volume

         Change overall volume.
         Move to the left to make it smaller, and move to the right to make it louder.

     BGM volume

         Change the volume of BGM (background music).

     SE volume

         Change the volume of SE (sound effects).
         You can check the actual SE volume by pressing the *Test* button.

     Voice volume
         Change the volume for voices.
         You can also change the volume for voices per character by pressing the `Voices` button.
```

> ❗ Note: With the voice patch the *Master volume* is removed to make place for the *Voice volume*.

##### Other
```
    Instant Effects

        When set to ON, all the effects in the scenario are displayed instantaneously.
        However, progressive effects such as vibration and shaking are produced normally.
        Note: depending on the scene, an unintended display may occur.

    Hide text when changing sprites

        In this game there's an abundance of facial expressions for each character.
        Whenever a character changes their expression the text is hidden during the transition.
        Therefore, hiding the text window is performed frequently.
        If you want to concentrate on the text you can turn off this feature.

    Display special effects

        There are several scenes in the game that use very computationally expensive effects.
        In this case, older PCs might suffer from lack of performance,
        which may be improved by turning OFF the display of the special effect.

    Font switching

        The default font used to display text is installed in your environment.
        You can choose other fonts from the list.
        (the settings will be reflected in the sample window, and confirmed when you press OK).

    Changing the opacity of the message window background

        You can change the background opacity of the message window in the range of 0 to 100%.

    Mouse right-click setting

        Normally the game menu is displayed with one right-click, but by changing the setting
        you can hide the text window for the first right-click, and display the game menu for the second right-click.

    Automatic movement of cursor

        In the title screen or right-click menu, the game will automatically move the cursor
        to the previously pressed button, etc.
        If you do not wish for such a behavior, you may uncheck this option.
```

> ❗ Note: settings in the config menu are not changed until you press the OK button.


Switches Guide
--------------

The switches can be found at the menu bar of the game, placed at the top of the game's window (if you're playing in full-screen, press F10 or hover your mouse to the top of the screen to display it).

The switches are:

* **Language**  
Use this switch to change the language of the game to whatever you like. Font configuration is saved per-language, so you can set your favorite font per language.

The following switches are under the *Patch* menu bar:

* **Textual Content**
  * Classic - the textual content of the game matches that of classic 2004 version.
  * Réalta Nua - the textual content of the game matches that of the PC RN version.
  * Mixed - the textual content of the game is a mix of both Réalta Nua and Classic.

* **Music Content**
  Same as Textual Content but for BGM.
  (Note: The **Classic** mode is very much WIP so far, with mainly the first day of the prologue and a few other selected areas actualized. The bulk of it still uses Réalta Nua's music.)

* **Movie Content**
  * Classic - the movies of the classic 2004 release are used.
  * Réalta Nua - the movies of the PS2 release are used.
  * Vita - the movies of the Vita release are used.
  * Mixed - plays route specific PS2 OP after the prologue and the route specific Vita OP after the 3rd day.
  * Skip movies in-game - if the game crashes when trying to display movies, you can use this option to bypass the problem.

> ❗ Note: In Classic/Réalta Nua/Vita mode, the Fate OP plays after the prologue, the UBW OP plays after the third day when entering UBW route, and the HF OP plays after the third day when entering HF route (classic release has no HF OP, so no movie plays).

* **Censorship**  
  * Show mature content - the game will display mature content like under-age alcohol, extreme violence & gore, and non-graphic sexual themes, like in the Classic 2004 release.

  The following 4 options are mutually exclusive:
  * No Ecchi, No Hentai - the game will not display any nudity and sex. It replaces the Classic PC release's naughty images and scenes with their Réalta Nua counterpart.
  * Show Ecchi - nudity is shown as in the Classic 2004 release, but scenes containing explicit sexual acts are replaced by their Réalta Nua counterpart.
  * Show Ecchi & Hentai - all nudity and explicit sexual acts are shown as in the Classic 2004 release.
  * Show Ecchi & Hentai + Fan-made Demosaic - as above, but additionally removes the mosaic censorship from the images the H scenes.
  * Demosaic artist - different artists have tried their hand at removing the demosaic of this game. Here you can choose which artist's work to use. (The default, `Bellandy + Anonymous` arguably provides the highest quality.)

* **Voice Playback Options**
  * Play unmatched voices - due to censoring done to the scripts in the vita version, some voices don't match the text. If you don't know Japanese you should probably keep it on since most of the times the tone matches the atmosphere.
  * Play unused voices - for whatever reasons, some voices exist in the game's files but do not play. You can choose to play those using this switch.
  * Use custom Wait-Voice tags - the vita features a nice effect where the text waits for the voice to reach a certain point before playing some special effects. While inserting the voices, some of the members added their own custom wait-voice tags to enhance the experience in places where they were missing. This switch is for the custom tags only. We recommend keeping it on.
  * Fade BGM with voice - slightly fades the BGM when a character is speaking.
  * Don't stop currently playing voice when clicking - exactly what it says.
  * Rin Chant Language - in some parts of the story Rin uses certain chants which were dubbed as Japanese (PS2 version) and German (PC RN version). The German recordings sound horrible, please stick with the Japanese ones.

* **Movie Playback Options**
  * Display subtitles in movies - display subtitles in movies. For the current English patch subtitles exist for the original OP only.
  * Force movie playback using external mpv - if it exists, uses an `mpv.exe` in the game folder instead of the internal mpv plugin for OP movie playback.
  * Movie Quality - allows to switch to low resolution movie versions if you have performance issues with the high resolution ones.

* **UI Options**
  * Gallery: Extended gallery - updates the gallery with more CGs from the classic 2004 and PS2 releases of the game.
  * Gallery: Merged gallery - removes duplicate entries between routes and rearranges some CGs to match the gallery of the PS2 version of the game.
  * History: Display scene title - display the current scene title in the history. This can potentially include some spoilers.
  * History: Use custom voice replay icons - displays character-specific icons for the voice-replay button in history instead of the generic button. Not all characters included (those who don't will use the generic button).
  * Message Window: Mobile style text break glyphs - use the text break glyphs (the animated cursor that appears when a line or a page ends) from the mobile version.
  * Message Window: Mobile style message window - use the textbox frame style from the mobile version.
  * Message Window: 4:3 message window in wide mode - in wide mode, uses a standard ratio (4:3) message box instead of a wide (16:9) one.
  * Vita style Movie Menu - when enabled, the Movie Menu will be arranged as in the Vita release, with movie thumbnails on the bottom. Classic and Vita OP movies are available only in this mode.
  * Vita style About Menu - when enabled, uses the Vita style 16:9 About Menu.
  * Show TYPE-MOON logo on startup - when disabled, skips the logo and boots directly into the game.
  * Show tooltips - when disabled, mouse-over of a button does not display the tooltip.
  * Move mouse with keyboard/joypad - allows for disabling the default behaviour of the mouse pointer being moved to the control you focus when navigating with keyboard or joypad.
  * Prologue title menu - in the PC release, the game didn't show you a title screen until you had finished the prologue at least once. In contrast, the PS2 version did show a title screen. This option restores the PS2 style title menu.
  * Disable forced auto-read - in one part of the game there's a forced auto-read. This option disables it. (It is not recommended to disable this for first time readers.)
  * Classic look for in-game choices - display choices in the more simple style of the 2004 PC release.

* **Route Lock**  
  Choose the route's title-screen to display.
  
> ❗ Note: This submenu does not unlock until you've cleared the game, which means getting all the endings and playing the epilogue.

* **Title Menu Style**  
  Choose the clear state of the title to display.  
  As a bonus, you can also see trial title screen and even watch the "Demo" (a trailer) included with it.
  
> ❗ Note: This submenu does not unlock until you've cleared the game, which means getting all the endings and playing the epilogue.

* **Tools**  
  * Open engine configuration dialog
  * Open save data directory
  * Save troubleshooting data
  * Enable repair save data mode
  * Display Flowchart - similar to the flowchart pdf bundled with the patch, but inside the game. Allows you to navigate to every scene with a click, and even edit flag values.
  > ❗ Note: the flowchart is not usable from the main menu - you need to start/load a game first.

FAQ
---

> My game is crashing when I reach an OP, the error message says "EAccessViolation", what do I do?

Choose "Skip movies in-game" in the Movie Content menu.

---

> I have the original Fate Stay Night. Will the installer work with it?

No. This project is for the digital download PC version of Realta Nua.  
You have to acquire all three routes of that version in order to perform the installation.

---

> Will this work on FHA?

![Supported Games](supported_games.png "Supported Games")

---

> I have Waku Waku's RN patch for the 2004 PC version. Is there any difference between this and that patch?

Loads. Waku's patch for the original only added what he could into FSN.

---

> What order do I play the routes in?

The official order is Fate (Saber route), Unlimited Blade Works (Rin route), Heaven's Feel (Sakura route).  
PC RN made it possible to to play the routes in any order, however with this patch it's only possible to play them in the intended order, as it was in the 2004 PC and PS2 releases.

---

> How do I unlock the OPs in the Vita OP patch?

The 2004 FSN OPs are added to the Movie menu upon completion of the prologue.  
If you complete the prologue in Fate, you will see the PS2 Fate Op, if you complete it in UBW you will see the PS2 UBW Op, and if you complete it in HF, you will see the PS2 HF Op.  
Completing Day 3 in Fate gives you the Fate Vita OP, Day 3 in UBW gives you the UBW Vita OP, and Day 3 in HF gives you the HF Vita OP.  
Completing Day 3 in each route also unlocks the respective route PS2 OP (and 2004 FSN OP), in case you don't want to replay the prologue.

---

> Where are the OP movies sourced from?

Classic OP 1: TYPE-MOON Fes. 10TH ANNIVERSARY Blu-ray Disc Box (Disc 3) / 00009.m2ts / CRC32: EF4192EA
Classic OP 2: TYPE-MOON Fes. 10TH ANNIVERSARY Blu-ray Disc Box (Disc 3) / 00010.m2ts / CRC32: 88A42F11
PS2 OP 1: TYPE-MOON Fes. 10TH ANNIVERSARY Blu-ray Disc Box (Disc 3) / 00011.m2ts / CRC32: AAC3FEA8
PS2 OP 2: TYPE-MOON Fes. 10TH ANNIVERSARY Blu-ray Disc Box (Disc 3) / 00012.m2ts / CRC32: 63C20BD8
PS2 OP 3: TYPE-MOON Fes. 10TH ANNIVERSARY Blu-ray Disc Box (Disc 3) / 00013.m2ts / CRC32: D86427D7
Vita OP 1: TYPE-MOON Fes. 10TH ANNIVERSARY Blu-ray Disc Box (Disc 3) / 00025.m2ts / CRC32: D9519A26
Vita OP 2: PlayStation Vita release data files
Vita OP 3: PlayStation Vita release data files

Troubleshooting
---------------
> I get a crash when I go to look at the backlog.

If you recently updated your patch, you need to press "Start" to clear out the backlog and the old conflicting version text. Pressing "Continue" keeps the version from the prior patch in your recent history, and the two do not always get along.

---

> I'm getting an `EAccessViolation`

Try [changing your DEP (Data Execution Prevention) settings][Data Execution Prevention] to make sure it's enabled for essential windows services only.

---

> I'm running the game from the installation folder and copy/pasted it to a new computer. Now Crash, boom.

If you put the save file in documents, it is still being directed to the pathname of your old computer (due to different usernames). Delete the `config.ksc` file in your game directory, it will ask you for a save file location next time you start, select a location (move your old save files to this location if you want to use those - press cancel to make the location your game folder itself).

---

> I initially started the game fine, now I'm getting error messages that say "messages" and/or "kag".

Try changing the location of your save folder. Delete the `config.ksc` in your game folder and it will prompt you for a new location on game start.

---

> I get a crash on game-start that says `syntax error, unexpected T_SYMBOL, expecting ")"`.

You might not be using the patches. Make sure the patches are located in your game folder (where `Fate.exe` is).

---

> The game crashes on startup with an error in Japanese/question marks with `吉里吉里` in the titlebar.

You likely have a corrupted file. Try theses solutions:
1. Redownload the patch.
2. Rename your `faterealtanua_savedata` to `faterealtanua_savadataOLD` (if it doesn't work, you may change the name back - if it does work, your savefile was corrupted).
3. Reinstall the game.

---

**Troubleshooting crashes**

1. Try re-downloading the patch first.
2. If you had no issue for a while and suddenly started crashing, something may have become corrupted, try reinstalling the game. Your saves will remain, just select the same location when you start the game for the first time.
3. If all else fails, post with the following information in the [forum thread](#contact):
- When the issue happens (if it worked fine before, mention anything that changed before it stopped working)
- Include a screenshot of the error (don't use the forum's attachment system, it sucks).
- State whether the game worked correctly at one point or if you just installed the game and this happened.
- Attach a copy of `krkr.console.log` file located in the game's directory inside a spoiler tag or a [pastebin](https://pastebin.com/) link.


Known issues
------------

* It is recommended you only change the language in the main menu or while reading a scene (i.e. not in other menus or while playing a mini-game), otherwise this could cause unexpected behaviors (they are mostly harmless, and it's nothing that doesn't solve itself by simply restarting the game). Another known issue is that switching a language in the main menu after viewing a scene in the scene menu might briefly show the last part of the scene. This is also harmless.
* In-game resolutions beyond 2.4x are not recommended for general usage since they have the potential of crashing due to the process running out of memory.
* Aspect ratios other than 4:3 and 16:9 can show glitches in the effects. Stick to the two main aspect ratios for the best experience.
* Music Content "Classic" covers only select scenes (mainly Prologue day 1 and a few others).
* Movie subtitles are not working yet.

Credits
-------

#### Developer
TYPE-MOON

#### Project leads
Jacktheinfinite101, Quibi, Kotonoha

#### The Cast

**Jacktheinfinite101**: Lead editor, programming, some image editing.

**Quibi**: Lead programmer, installer creation.

**Kotonoha**: Lead translator, text editing, some image editing.

**Hintay**: Additional programming.

**Anonamous**: Additional programming.

**Alyinghood**: Additional programming.

**uyjulian**: Krkrz development.

**Waku Waku**: Lead image editor, programming consultant, PS2 resources, legacy project.

**ニサンカタンソ**: Additional programming.

**NM64**: Audio editing, beta testing, media assets.

**SmilingWolf**: Upscaled image assets.

**Hyarion**: Initial translation of Fate H alts.

**MeruP**: Programming.

**Terrafire**: Script comparisons.

**Dallas Hickan**: Additional image editing.

**GameCreater32**: Custom voice replay icons, supplemental tools.

**Commander Rase**: Beta Testing.

**Thryfe**: Beta Testing.

**Inuhanyou**: Beta Testing.

**SkitZoFrenic**: Beta Testing.

**Ownsin**: Beta Testing.

**UnlimitedBladeWorks**: Beta Testing.

**Taka-jun, ArchDemon, Tjm, and puKKa from [Mirror Moon]**: Original translation.

**bishopcruz and Annonymous**: First H decensor patch.

**Himeros and Belldandy100**: Second H decensor patch.

**Seung "gp32" Park, Ed Keyes, Lee "Clammerz" Massi and zalas (Takeda Honyakubu) from [insani]**: Trial Edition translation, image editing and QA.

**Bohemian Waxwing**: Image editing.

**Poki#3**: New flowchart pdf.

#### Special Thanks

Special thanks to any other BL members who helped out.

Contact
-------

[Patch home page](https://ultimate-moon.github.io/fate/)

[Patch forum thread](https://ultimate-moon.github.io/fate/support/)

[English translation project page](http://mirrormoon.org/projects/complete/fatestay-night/)

[TYPE-MOON website](https://www.typemoon.com/)

Version History
---------------

##### v1.1.3
* Fixed icon-related crash on Android Kirikiroid2 (reported by BOOP 2022-10-07).
* Fixed movie playback issue on SteamDeck (reported by vnrando 2022-10-16).
* Fixed english chapter title of "十四日目/フィナーレ" to "14th Day/Finale" (reported by Poki#3 on 2022-10-19).
* Fixed bug that prevented the mature version of scene "Intermission - Last Piece" from playing.
* Added missing japanese mature version of scene "Intermission - Last Piece".
* Fixed broken flag change popup when language is not Japanese (reported by Dimoks on 2022-10-22).
* Fixed issue that caused lost sprite animations in multiple scenes.
* Fixed crash when accessing the Movie menu on Android Kirikiroid2.
* Fixed issue that prevented Status menu Noble Phantasm icon text from showing on Android Kirikiroid2.
* Fixed issue that prevented the game from returning to the Title Menu after completing the Prologue for the first time.
* Fixed issue with noise effect coverage.
* Fixed many typos.
* Corrected errors in the descriptions of the japanese Weapon Menu (fix offered by Dimoks).
* Added more authentic fonts to japanese Weapon Menu (fix offered by you Dimoks).
* Added more authentic fonts to japanese Status Menu.
* Added Poki#3's new flowchart.
* Added controller support on PC.
* Added test version of the English retranslation by FBates (beta ver. 2.0)

##### v1.1.2
* Fixed issue of wrongly sized mobile window frames in 2.4x and 3.0x modes (reported by TrainerRad164 2022-09-08).
* Fixed mouse not working correctly in Gallery Menu and QuickList Menu.
* Fixed 1 px vertical offset of video rectangle in Movie Menu during 1.6x mode.
* Added higher resolution Classic & PS2 OP videos.
* Added low quality versions of OP videos for weaker hardware. [Menu -> Patch -> Movie Playback Options -> Movie Quality -> Low].
* Removed neccessity to restart game to change 'Message Window' and 'Show mature content' settings (reported by TrainerRad164 2022-09-08).
* Fixed text error in HF Day 16, Crazy Train II, page 13 (reported by Twhite90 2022-09-24).
* Fixed incorrect sprite positioning when game window isn't at 100% size.
* Fixed broken animations in several scenes (reported by Twhite90 2022-09-24).
* Fixed broken save data time stamps (reported by vnrando 2022-10-02).

##### v1.1.1
* Added automatic window icon switching based on route (needs icon_FATE.ico, icon_UBW.ico, icon_HF.ico within game folder).
* Updated installer: will now create icon_FATE.ico, icon_UBW.ico, icon_HF.ico in the game folder.
* Fixed visual glitches of quick list (q-key) menu in wide mode.
* Fixed issue of BGM menu not containing all tracks on fresh save (reported by Twhite90 2022-07-08).
* Fixed animation glitches in wide mode due to wrong size of rule-wide images (reported by loicfr 2022-07-09).
* Fixed issue of unnecessary blank lines under specific conditions (reported by hexashadow 2022-07-10).
* Fixed issue of text sometimes overflowing the message frame (reported by hexashadow 2022-07-10).
* Fixed editing error in image 凛制服11d(近) (reported by hexashadow 2022-07-10).
* Fixed low quality video option not working (reported by NM64 2022-07-12).
* Fixed crashes related to "Missing image in images_hd.dic: c12b" (reported by hexashadow 2022-07-13).
* Fixed crash when trying to access the Movie Menu in kirikiroid (reported by LonelyShadow 2022-07-14).
* Improved translation of UBW Day 3 "VS Berserker - Choice" (reported by Twhite90 2022-07-19).
* Fixed visual glitches in popups like "Skip Cancelled" and the like (reported by Twhite90 2022-07-19).
* Fixed text issue in Fate route day 15, "Go along the cheek" (reported by Twhite90 2022-07-19).
* Fixed right side of the screen not scrolling in normal and wide mode on UBW Day scene "Compensation for the pride" and "Tohsaka Rin (III)" (reported by Twhite90 2022-07-19).
* Fixed visual glitch in Archer's sprite in normal and wide mode on HF Day 15, "Nine Bullet Revolver" (reported by Twhite90 2022-07-19).
* Fixed BGM getting interrupted on scene change (reported by Twhite90 2022-07-19).
* Fixed sound effect loop issue on Fate Day 11 "Ruins in the forest - Dragon’s core" (reported by Twhite90 2022-07-19).
* Changed HF True End to play BGM "Turning Seasons 2" instead of "Blue Sky" for mixed music option (proposed by Twhite90 2022-07-19).
* Changed HF True End to play BGM "Days" instead of "Turning Seasons (Réalta Nua ver.)" for mixed music option (proposed by Twhite90 2022-07-19).
* Fixed door open/close animations not showing in wide mode (reported by Twhite90 2022-07-19).
* Fixed date display screens in wide mode (reported by Twhite90 2022-07-19).
* Fixed interlude screens in wide mode (reported by Twhite90 2022-07-19).
* Fixed issue of choice boxes being stuck to the left side of the screen in wide mode (reported by Twhite90 2022-07-19).
* Fixed Saber sprite positioning glitch in wide mode on Fate Day 6, "Missing Ariadne" (reported by Twhite90 2022-07-19).
* Fixed positioning glitch of image of Saber lying on the bed in wide mode in "Ruins in the forest - Dragon’s core" (reported by Twhite90 2022-07-19).
* Fixed black border positioning error in wide mode at 5 places, including the one on Fate Day 14, "Oldest King" (reported by Twhite90 2022-07-19).
* Fixed Gilgamesh sprite positioning glitch in wide mode on Fate Day 15, "Fate/stay night (II)" (reported by Twhite90 2022-07-19).
* Fixed Rin sprite positioning glitch in wide mode in Tiger Dojo 11 & 16 (reported by Twhite90 2022-07-19).
* Fixed 2 cases of Rin sprite positioning glitches in wide mode on UBW Day 9, "Fight back, projection magic" (reported by Twhite90 2022-07-19).
* Fixed letter sprite positioning glitch in wide mode on HF Day 5, "The great devil gets very angry" (reported by Twhite90 2022-07-19).
* Fixed missing tank animation and positioning errors in wide mode in Tiger Dojo 28 (reported by Twhite90 2022-07-19).
* Fixed Sakura's sprite position in wide mode in Tiger Dojo 29 (reported by Twhite90 2022-07-19).
* Fixed background offset in wide mode on HF Day 14, Sacrilege Sisters (VI) page24 (reported by Twhite90 2022-07-19).
* Fixed positioning discrepancy between caution and title screen in wide mode (reported by Twhite90 2022-07-19).
* Fixed Prev/Back/Next buttons in gallery getting separated in wide mode (reported by Twhite90 2022-07-19).
* Fixed visual glitch of the separator line in the title/date screen in wide mode (reported by Twhite90 2022-07-19).

##### v1.1.0
* Huge speed up for menu and in-game navigation.
* Fixed sprite positioning in HD and wide modes.
* Improved menu positioning in wide modes.
* Added higher resolution modes: x2.0 / x2.4 / x3.0 / x4.0 (Needs respective HD patch files installed.)
* Fixed banding/posterization in artwork.
* Improved look of GUI elements by recreating their graphics from scratch.
* Fixed some translation errors in the English translation by Mirror Moon.
* Added a menu option to limit the game window's size to the deskop. (Display -> Window Size -> Limit to Screen)
* Fixed resizing window by dragging its borders not working even with **Fixed Size** disabled.
* Fixed right mouse button events not being captured when clicking too fast.
* Fixed dash lines's shadows in text being too dark compared to text shadows.
* Fixed dash lines in the history being broken up in multiple segments.

##### v1.0.0
* Fixed bug where in some cases H and Mature content would not display correctly.
* Added upscaled (waifu2x'd) menu images, so the menu looks much better in HD mode.
* Added higher resolution (and waifu2x'd) OP videos.
* Fixed some visual glitches in HD mode.
* Wide aspect ratio is now stable.
* Fixed some video playing bugs.
* Added better versions of some OST tracks.
* Added more switches (see [Switches Guide](#switches-guide)).
* Improved localization.

##### v0.9.1
* Installer now has a function to download patches directly when run, and check for updates to said patches.
* Fixed error causing UBW and HF Vita openings to not play.
* Fixed an error causing one of the pop up menus to not translate.
* Implemented a missing image translation.
* Implemented an HD version of the correct version of one of the HF CGs.
* Implemented a new feature to the OST switch so that Changing Seasons now has a "classic" option to play the 2004 PC version during credits scenes.
* Adjusted the numbers on the resolution scaling ~for NintendoManiac's sake~ so it's more consistent.
* Uploaded a 100% savefile to use for those who wish to avoid CTRLing through the VN and could not get their old saves to work.
* Actually remembered to upload a file pertaining to a feature I forgot to mention exists...

##### v0.9.0
* First public beta.

[Ultimate Moon]: https://ultimate-moon.github.io/
[Hollow Moon]: https://hollow-moon.github.io/
[Mirror Moon]: http://mirrormoon.org/
[insani]: http://insani.org/fate.html
[Data Execution Prevention]: https://web.archive.org/web/20140911011045/http://support.microsoft.com/kb/875352/en-us
[Locale Emulator]: https://pooi.moe/Locale-Emulator/
[Kirikiroid2]: https://github.com/zeas2/Kirikiroid2

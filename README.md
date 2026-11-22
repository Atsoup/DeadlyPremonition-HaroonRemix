# Deadly Premonition: The Director's Cut – Haroon Remix

A fix and enhancement package for the Steam version of Deadly Premonition: The Director's Cut (1.01b) on Windows 10/11.
It fixes the crashes, freezes and stutter the PC port is known for and adds a set of optional upgrades.

## Download

Get the files from the [Releases](../../releases) page:

- **DP-Win11-Fix.zip** – the fix itself (required).
- **DP-Win11-Fix-HDUI-1440p / -4k / -8k.zip** – optional high-resolution interface. Pick one and unzip it into the same folder as `Setup.exe`.

## Install

1. Close the game and unzip `DP-Win11-Fix.zip` anywhere.
2. Run `Setup.exe` and click **Configure for me** (or choose settings yourself), then **Apply**.
3. Start the game from Steam as usual.

Everything is backed up before it is changed; Setup's Uninstall puts it all back.
If the game ever crashes, a "SEND THIS TO DEVELOPER" zip appears on your Desktop – please send it over.

## What it fixes

- The main random crash and the crash on exit (the video player unloaded the game's sound engine).
- Codec packs (LAV / K-Lite) crashing cutscenes and breaking the Steam overlay.
- Crashes with 7.1 / surround headsets, black screen after sleep or a driver update.
- Companion hangs (Ch3 hospital, Ch7/13 "hang around with colleagues") and saves that would not load afterwards.
- Corrupted saves after a crash (safe writes with backups).
- Ch20 vine corridor softlock, Psychic Spot B instant failure, episode recap lock-up.
- Map / side-missions freeze, the save prompt "Yes" that did nothing, NPC cars driving in circles.
- Rivers and the lake not animating on PC.

## Smoothness and visuals

- Locked 60 fps with even frame pacing, including menus and video cutscenes (they were 30).
- Fewer hitches when opening the pause menu, item pages and map; no stutter without a controller connected.
- Optional Vulkan renderer: smoother pacing, less input lag, less memory.
- Up to 4K with supersampling, SMAA, ambient occlusion and sharper shadows.
- Native HDR10 output for HDR TVs (Setup > HDR), tunable while you play.
- Optional HD interface packs up to 8K, each part switchable.
- HD rumble for Xbox-style controllers: engine hum, crash thumps, a kick for every shot.
- Built on UltimateFIXDP, so you also get its full town map with waypoints, photo mode, DualSense support, modern aiming and more (press F10 in game).

## Credits

UltimateFIXDP by LittleBitUA and contributors (MIT), DXVK by Philip Rebohle and contributors (zlib), RenHDrum by Three-Dola (MIT / Apache-2.0),
and earlier work by DPStabilityFix (Cesario67), DPfix (Peter "Durante" Thoman), ZachFix and Behelit09's fixes.
Full notices are in `THIRD-PARTY-NOTICES.txt` inside the download.

Deadly Premonition is a trademark of its respective owners. This is an unofficial fan project; you need your own copy of the game.

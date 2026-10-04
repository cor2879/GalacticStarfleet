# Galactic Starfleet

An unfinished science-fiction JRPG created by David Cole around the early 2000s, now being restored for modern systems and browser play.

Originally built in RPG Maker 2000 and later upgraded to RPG Maker 2003, the recovered project runs through EasyRPG Player. The story follows humans caught in a space war who crash on a world inhabited by elves, where reptilians harvest crystallized tears. The playable material includes a town besieged by a lich whose buried heart must be destroyed alongside him.

## Restoration status

- Recovered the later project containing 44 maps and five historical saves.
- The author has played through the implemented story using the browser build.
- Added substitute resources for missing battle graphics, UI and effects.
- Prepared an R48 editing kit for macOS and Linux.
- Corrected Forest Merchant weapon-shop stock, its exit destination and the armor-shop entrance trigger.
- Increased HP-healing skills to match the game's health scale; Healing Beam now calculates 255–345 HP before the maximum-health cap.

The latest map and healing changes have passed structural data checks and still require gameplay confirmation.

## Current work

Create an original soundtrack before preparing the public Arcade edition. The main title theme is intended to be a heroic early-1990s space-opera march with synthesized orchestral instruments and a 16-bit-era sound.

The current restoration packages are maintained separately. This initial repository contains project documentation only; game data, media and runtime binaries have not yet been imported.

## Intended workflow

1. Establish one canonical editable game folder.
2. Track map/database revisions and original or cleared media here.
3. Run with EasyRPG Player; use R48 or targeted tooling for edits.
4. Validate changes and playtest on macOS/Linux and in a browser.
5. Prepare browser packaging and a build workflow after the project layout is established.

## Ownership and dependencies

No blanket open-source license is granted for the game or its assets by this repository. Third-party runtimes, editor tools and replacement resources retain their own licenses and attribution requirements.

- [EasyRPG Player](https://easyrpg.org/player/)
- [R48](https://github.com/20kdc/gabien-app-r48)

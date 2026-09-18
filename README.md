# anno1800mods

A personal collection of Anno 1800 mods used for gameplay tweaks, building additions, quality-of-life improvements, and custom content. This repo is not a single monolithic mod project; it is a curated set of separate mod folders, each packaged as its own mini-mod with metadata, data assets, and often a localized README.

The repository description is intentionally simple: these are mods I play with, and some may be changed from the original content or balanced differently from the vanilla game. Use them with that in mind.

## What is in this repo?

This repository contains dozens of independent Anno 1800 mod folders, grouped by purpose and category. The structure is consistent across the collection:

- `modinfo.json` or `modinfo.Json` metadata files
- `README.md` explaining purpose, features, and changelog
- `content*.txt` localization or text entries
- `data/` folders containing the mod assets and game data
- Artwork such as `banner.jpg` or similar preview images

Most entries are not code projects in the usual sense; they are game data and metadata packages built for Anno 1800.

## Repository layout

The top-level folders are organized into categories such as:

- Building and construction
- Gameplay balance and changes
- Harbor and logistics
- Maps and world generation
- Miscellaneous quality-of-life additions
- Shared dependency mods
- Cheat / convenience modifications

### Building and structures

- `[Building] Nate's Windmill (Jakob)`

### Gameplay and balance

- `[Gameplay] 01 Combat Overhaul Ships`
- `[Gameplay] 02 Combat Overhaul AI`
- `[Gameplay] 03 Combat Overhaul Pirates`
- `[Gameplay] 6 Field Crops_ 2 Field Animals`
- `[Gameplay] AI not asking for alliances`
- `[Gameplay] Active Trader Nate`
- `[Gameplay] Commuter pier unlocked with workers`
- `[Gameplay] Configurable_Maintenance`
- `[Gameplay] Fire_Station_MU`
- `[Gameplay] Free Farmfield Placement (Taludas)`
- `[Gameplay] Hospital_MU`
- `[Gameplay] Increased Harbourarea`
- `[Gameplay] Industrial Low Tier Production (Kurila)`
- `[Gameplay] Item Buildings Affect Entire Island`
- `[Gameplay] Large Fishery (Kurila)`
- `[Gameplay] Open Pit Mines`
- `[Gameplay] Police_Station_MU`
- `[Gameplay] Unlimited Itemtrade`
- `[Gameplay] Vanilla Riverslot Buildings NW (Taludas)`
- `[Gameplay] Vanilla Riverslot Buildings OW (Taludas)`

### Harbor, trade, and world systems

- `BT Passive Trading (Serp)`
- `Depot Land 100t (Serp)`
- `Faster Piers (Serp)`
- `NoSunkenTreasureSession (Serp)`
- `P Peaceful Pirates (Serp)`
- `[Addon] Harborlife`
- `[Adjustments] Harbor Blocking`
- `[lonelyPorter] More Trade contracts`

### Maps and special content

- `[Map] Crownfalls Small V2`

### Miscellaneous and cosmetic

- `[Misc] Buildable Residences`
- `[Misc] More Player Logos`
- `[Misc] color-changer`
- `[Ornamental] Construction Sites`

### Shared dependencies and helpers

- `[Shared] Riverslots NW (Taludas)`
- `[Shared] Riverslots OW (Taludas)`
- `!all_slotables_unlocked_at_traders`

### Cheats and convenience

- `[Cheat] Combined Influence Mod for Residences (Taludas)`
- `[Cheat] No Royal Taxes`
- `[schwubbe][Cheat]] LowTransfertime`

## Representative mods in the collection

A few examples illustrate the common mod pattern in this repository:

- `[Building] Nate's Windmill (Jakob)`
  - Adds a windmill building with custom balance values and influence logic.
  - Includes a `README.md`, `modinfo.json`, and shared dependency data.
  - Shows the repository's pattern of original content plus compatibility support.

- `[Gameplay] Fire_Station_MU`
  - Adds additional fire station variants and custom balance values.
  - Includes `modinfo.Json`, `content_en.txt`, localization files, and a preview banner.
  - Demonstrates the gameplay-changing mods in this repo.

- `[Misc] More Player Logos`
  - Adds extra logos for player customization.
  - Uses lightweight data files and localization entries rather than large custom systems.

These examples show that the repo is mostly a pack of small, targeted Anno 1800 data mods rather than a single codebase.

## Typical mod structure

Most entries follow a similar pattern:

```text
mod-folder/
├── README.md
├── modinfo.json
├── content_en.txt
├── data/
├── banner.jpg
└── other localization or asset files
```

Where present, the `modinfo.json` file describes metadata such as:

- mod version
- compatibility dependencies
- creator name/contact
- language strings
- category and description

## How to use

To use the mods:

1. Download or clone this repository.
2. Copy the relevant mod folders into your Anno 1800 mod directory.
3. Enable the mods in the game launcher or mod manager.
4. Check each mod's own `README.md` for compatibility notes and dependency requirements.

Some entries depend on other mods or shared resources, so it is best to read the individual folder documentation before activating everything at once.

## Notes and caveats

- This is a personal mod collection rather than a formal public mod framework.
- Some mods may be modified versions of original content.
- Balance, compatibility, and dependencies vary from folder to folder.
- Some entries may be intended for specific DLCs or expansions.

## License and usage

This repository does not declare a formal software license in the root README, so treat it as a personal mod collection for use in Anno 1800 rather than a package intended for redistribution without checking the original mod authors' rights and permissions.

If you plan to use any of these mods in a public or shared setup, review the individual mod folders and any referenced upstream creators before distributing or re-uploading content.

## Summary

`anno1800mods` is a curated archive of Anno 1800 gameplay and visual enhancements, centered around several distinct gameplay themes and custom-building modifications. Most folders are self-contained mods with metadata and data assets, and the repo is best understood as a collection of mod packages rather than a single app or library.

This README is intended to provide an overview of the collection and help you browse the available content quickly.

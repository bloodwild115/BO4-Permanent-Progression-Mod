# BO4 Permanent Progression Mod

A standalone long-term progression mod for **Call of Duty: Black Ops 4 Zombies** running through **Shield Client**.

Permanent Progression adds persistent upgrades, keys, mastery systems, Loadout Mastery, and a reworked weapon-camo progression system designed to give BO4 Zombies a longer-term progression loop across matches.

## Current Release

**v1.0.0 — Standalone**

BO4 Enhancement compatibility is **not included in v1.0.0**. An optional compatibility release may be developed in the future.

## Features

- Permanent upgrade progression across BO4 Zombies
- Persistent key economy and Sentinel / mastery progression
- Upgrade enable/disable controls
- Standalone **PERMANENT UPGRADES** lobby integration
- Standalone Loadout Mastery support
- Weapon-specific Performance camo requirements
- Lifetime-stat Armory camo progress display
- Rebalanced Technical camo challenges
- Existing earned weapon camos are not intentionally revoked
- Drag-and-drop Shield Client installation
- No Python, compiler, or development tools required for players

## Installation

1. Install and configure **Shield Client** for Black Ops 4.
2. Download `PermanentProgression-v1.0.0.zip` from this repository's Releases page.
3. Close Black Ops 4 completely.
4. Extract the ZIP.
5. Copy the included `PermanentProgression` folder into:

   ```text
   C:\Call of Duty Black Ops 4\project-bo4\mods\
   ```

6. The final path should look like:

   ```text
   C:\Call of Duty Black Ops 4\project-bo4\mods\PermanentProgression\
   ```

7. Launch Black Ops 4 through Shield Client.
8. Open Zombies and confirm **PERMANENT UPGRADES** appears in the lobby.

See [Installation & Troubleshooting](docs/INSTALLATION.md) for more detail.

## Enhancement-Only Upgrade Trees

The following upgrade trees are intentionally hidden in the standalone v1.0.0 release because they depend on BO4 Enhancement gameplay/perk support:

- Speed Cola
- Vulture Aid
- Juggernog
- Double Tap
- Who's Who
- Elemental Pop

Their implementation is reserved for a possible future optional Enhancement compatibility release.

## Weapon Camo Progression

Permanent Progression v1.0.0 includes weapon-specific Performance challenge balancing and scaled Technical challenge requirements. Armory requirement text and progress use lifetime weapon statistics wherever supported.

See [Weapon Camo Changes](docs/WEAPON_CAMOS.md).

## Reporting Problems

When opening an issue, please include:

- map
- weapon/perk/upgrade involved
- what you expected
- what actually happened
- screenshot if UI-related
- Shield `project-bo4.log` when relevant

## Credits / References

Development and research were assisted by community BO4 and Shield resources including:

- Shield Client modding documentation
- `shiversoftdev/t8-src`
- `ate47/bo4-source-lua`
- `ate47/t8-atian-menu`
- community BO4 compiler/recompilation research

Third-party projects retain their own copyrights and licenses.

## Disclaimer

This is an unofficial community mod and is not affiliated with or endorsed by Activision, Treyarch, or the Shield Client project.

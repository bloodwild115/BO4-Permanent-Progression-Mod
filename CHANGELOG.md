# Changelog

## v1.0.1 (11/1/2026)
### Added Content
- Project BO4 Zombies Contract rewards for Permanent Progression keys.
- Daily generic: +2 independently rolled random normal Keys.
- Normal generic: +1 random normal Key.
- Hard generic: +1 random Sentinel Key.
- Map-specific contracts award the matching map family instead of random families.

- Classified's "Project Skadi" easter egg now grants the Classified Main Quest cutscene as well as +1 Sentinel Key as an alternative route from reaching Round 150.

### New Upgrades (7 new upgrades across 19 purchase-able tiers!)
REQUISITIONS (3 new)
-----------
Second Harvest (Danu Keys) - Perk purchase discounts to help with the increase of perk slot quantity. (4 tiers)

Happy Hour (Zeus Keys) - Going down gives some recovery money for perk purchases to help with per quantity recovery. (4 tiers)

Security Clearance (Apothicon Keys) -  Mystery Box has a chance to give upgraded weapons. (4 tiers)


SENTINEL UPGRADES
-----------------
Homonculus Mastery (Ra Keys) - Homunculus now drops the beat a little longer and harder. (2 tiers)

Hands of Rapture (Zeus Keys) - Expansion to all 4 hands in stats and utility + damage. (2 tiers)

Arctic Arsenal (Group 935 Keys) - Buffs to both Tag Der Toten wonder weapons based upon community feedback. (2 tiers)

Death and Taxes (Apothicon Keys) - Welling upgraded is now up to par with Mustang and Sally in flare and firepower. (1 tier)


### Fixed
- Fixed Project BO4 1.1.2 hard crashes during map load caused by a static dependency on the Classified-only Winter's Howl/freezegun script.
Cold Winter's Night now passively watches Winter's Howl shots instead of replacing/chaining the native weapon-fired callback.
- Camos not unlocking due to requirements met prior to Permanent Progression mod being enabled should be fixed now.
- Addressed an issue where re-packing weapons would fill the gun to max ammunition.
- Addressed an issue where level 3 scepter of ra damage field would kill the final zombie in a round and not progress to the next round.
- Addressed an issue where on Tag Der Toten, if the last zombie died due to being frozen they would not progress the round. Zombies can now get frostbite with no fear of stalling out a match!
- Addressed an issue where Hellhounds and Nova Crawlers would not take damage from the Winters Howl after anabling Cold Winters Night sentinel upgrade. They now take proper damage!

Known limitation
- Additional Permanent Progression Contract rewards are not currently shown on the Project BO4 Contracts screen. Rewards are still granted in-game.


## v1.0.0

First stable standalone release.

### Core progression
- Finalized persistent Permanent Upgrade progression.
- Finalized normal-key and Sentinel-key economy.
- Finalized mastery systems and upgrade toggles.
- Removed release-blocking development/test key grants and destructive development migrations.

### Frontend
- Added standalone **PERMANENT UPGRADES** Zombies lobby integration.
- Added standalone Loadout Mastery Armory support.
- Finalized menu layout and tier controls.
- Enhancement-only perk upgrade trees are hidden in standalone v1.0.0.

### Weapon camos
- Added weapon-specific Performance challenge profiles.
- Added lifetime-stat Armory progress display.
- Added scaled Technical camo challenge requirements.
- Added special handling for kill-based weapons and special weapon challenge sets.
- Existing earned camos are not intentionally revoked.

### Compatibility
- v1.0.0 is standalone.
- BO4 Enhancement compatibility is deferred to a future optional release.

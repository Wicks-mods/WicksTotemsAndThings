<p align="center"><img src="images/wick-thumb-totems.png" alt="Wick's Totems and Things"></p>

# Wick's Totems and Things

<!-- wick:badges:start -->
[![Downloads](https://img.shields.io/curseforge/dt/1535194?style=flat-square&labelColor=171124&label=downloads&color=4FC778)](https://www.curseforge.com/wow/addons/wicks-totems-and-things)
![Forever](https://img.shields.io/badge/client-Forever-383058?style=flat-square&labelColor=171124)
[![License](https://img.shields.io/badge/license-MIT%20%2B%20trademark-383058?style=flat-square&labelColor=171124)](LICENSE)
[![Discord](https://img.shields.io/badge/discord-join-4FC778?style=flat-square&labelColor=171124)](https://discord.gg/GWGTMhYBZY)
<!-- wick:badges:end -->

> Shaman loadout kit for World of Warcraft: Forever. Totem presets, secure cast bar, Call of the Elements sync, imbues, talents, pre-pull checklist, racials.

Part of the **[Wick suite](https://github.com/Wicks-mods/WickSuite)**: precision addons built around a single fel-green-on-deep-purple aesthetic. This branch (`forever`) is the Forever build on [WickCore](https://github.com/Wicks-mods/WickCore). The TBC Anniversary build lives on `main`.

## What it is on Forever

Forever runs retail's engine with Midnight's addon rules. Totem state and the
player's own auras and cooldowns are secret in combat, and group auras are
unreadable. So the combat trackers from the TBC build are gone, and this is a
loadout kit: everything a shaman sets up before the pull.

- **Presets.** Named sets of four totems, one per element, with a drop order.
  Right-click any element button to change it. Cycle presets on a keybind.
- **Cast bar.** Four secure buttons that cast the active preset's totems, plus
  a drop-all keybind that runs them in sequence.
- **Call of the Elements.** The active preset is kept in Blizzard's four totem
  bar slots, and a keybind casts Call of the Elements to drop the whole set in
  one cast.
- **Twisting.** Two totems on one element button through a castsequence.
- **Imbues and ankhs.** Main hand and off hand imbue at a glance; ankh count.
- **Talents.** Export the active build as a Blizzard import string, import a
  string as a new loadout, save builds to an account-wide library, apply one
  with a click.
- **Pre-pull checklist.** Shield, both imbues, ankhs, preset complete. Rows
  go quiet the moment combat starts.
- **Racials.** Your race's actives as cast buttons with cooldown display.

## Install

Requires **[WickCore](https://github.com/Wicks-mods/WickCore)**. Extract both
folders into the Forever client's `Interface\AddOns\`.

## Usage

| Command | Effect |
|---|---|
| `/wtt` | Main panel: Active, Presets, Bindings, Options |
| `/wtt kit` | Talents, checklist, racials |
| `/wtt bar` | Toggle the icon strip |
| `/wtt sync` | Push the active preset into Blizzard's totem bar |
| `/wtt twist <element> on|off` | Totem twisting |
| `/wtt order fire earth water air` | Drop order |
| `/wtt status` | Diagnostics |

Keybinds for the element buttons, drop-all, Call of the Elements, panel, bar
and preset cycling are under Key Bindings, AddOns.

## Compatibility

World of Warcraft: Forever, 1.60.x, Interface 16001. Requires WickCore.

## More from Wick

<!-- wick:suite-table:start -->
| Addon | GitHub | CurseForge |
|---|---|---|
| **WickCore** | [repo](https://github.com/Wicks-mods/WickCore) | [CurseForge](https://www.curseforge.com/wow/addons/wickcore) |
| **Wick's Comforts** | [repo](https://github.com/Wicks-mods/WicksComforts) | [CurseForge](https://www.curseforge.com/wow/addons/wicks-comforts) |
| **Wick's Beasts and Things** | [repo](https://github.com/Wicks-mods/WicksBeastsAndThings) | [CurseForge](https://www.curseforge.com/wow/addons/wicks-beasts-and-things) |
| **Wick's Stances and Things** | [repo](https://github.com/Wicks-mods/WicksStancesAndThings) | [CurseForge](https://www.curseforge.com/wow/addons/wicks-stances-and-things) |
| **Wick's Seals and Things** | [repo](https://github.com/Wicks-mods/WicksSealsAndThings) | [CurseForge](https://www.curseforge.com/wow/addons/wicks-seals-and-things) |
| **Wick's Conjures and Things** | [repo](https://github.com/Wicks-mods/WicksConjuresAndThings) | [CurseForge](https://www.curseforge.com/wow/addons/wicks-conjures-and-things) |
| **Wick's Poisons and Things** | [repo](https://github.com/Wicks-mods/WicksPoisonsAndThings) | [CurseForge](https://www.curseforge.com/wow/addons/wicks-poisons-and-things) |
| **Wick's Demons and Things** | [repo](https://github.com/Wicks-mods/WicksDemonsAndThings) | [CurseForge](https://www.curseforge.com/wow/addons/wicks-demons-and-things) |
| **Wick's Bags** | [repo](https://github.com/Wicks-mods/WicksBags) | [CurseForge](https://www.curseforge.com/wow/addons/wicks-bags) |
| **Wick's Trade Hall** | [repo](https://github.com/Wicks-mods/WicksTradeHall) | [CurseForge](https://www.curseforge.com/wow/addons/trade-hall) |
| **Wick's Gear** | [repo](https://github.com/Wicks-mods/WicksGear) | [CurseForge](https://www.curseforge.com/wow/addons/wicks-gear) |
| **Wick's UI** | [repo](https://github.com/Wicks-mods/WicksUIForever) | [CurseForge](https://www.curseforge.com/wow/addons/wicks-ui) |
| **Wick's Reminders** | [repo](https://github.com/Wicks-mods/WicksReminders) | [CurseForge](https://www.curseforge.com/wow/addons/wicks-reminders) |
| **Wick's Map** | [repo](https://github.com/Wicks-mods/WicksMap) | [CurseForge](https://www.curseforge.com/wow/addons/wicks-map) |

**Community:** [Discord](https://discord.gg/GWGTMhYBZY)
<!-- wick:suite-table:end -->

## License

MIT for code (see [LICENSE](LICENSE)). Brand chrome and the "Wick's" wordmark are trademarked, see [TRADEMARK.md](https://github.com/Wicks-mods/WickSuite/blob/main/TRADEMARK.md). Racial data from [talentsforever.com](https://talentsforever.com) (CC BY 4.0) via WickCore.

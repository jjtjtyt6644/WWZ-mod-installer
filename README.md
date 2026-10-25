# WWZ Mod — Installer

**WWZ Mod** is a save editor, mod manager and trainer for **World War Z: Aftermath** on Steam (PC).

## Download
➡️ **[Download the latest WWZModSetup.exe](https://github.com/jjtjtyt6644/WWZ-mod-installer/releases/latest)**

1. On this page, look at the right side. Under **Releases**, click the latest version (marked **Latest**).
2. Under **Assets**, click **WWZModSetup.exe** to download it.
3. Run it and click **Next**, then **Finish**. It installs just for you, so it needs no admin rights and nothing else (no Python, no extra downloads).

### "Windows protected your PC"
The installer isn't code-signed yet, so Windows SmartScreen doesn't recognise it and may show a blue warning.
Click **More info → Run anyway**.

### Antivirus / VirusTotal
WWZ Mod reads and writes the game's memory the same way Cheat Engine does, and it isn't code-signed, so a scanner's
**machine-learning** guess can flag it even though it's clean. A detection whose name ends in `!ml` (for example
Microsoft's `Trojan:Win32/Wacatac.C!ml`) is a guess from that model, not a known virus — on v1.0.8 that was the only
flag, 1 of 68 engines, with the other 67 finding nothing.

You can check any build yourself on [VirusTotal](https://www.virustotal.com/gui/search): paste its SHA-256, or upload
the installer. v1.0.9's SHA-256 is `0ad28d30e317d254928b5841c8cf157fcedae64c2de7aaec9f01fe1c9a7d2b9c`.
If you want to be completely sure, you can decompile it and check the code yourself.

## What it does
- **Save editor:** set your Supplies, Challenge Coins and account level. It updates both your Steam Cloud and local saves, and backs them up first. If the game is open, WWZ Mod can close it for you so your changes stick.
- **Class mastery:** set any class to any level and prestige, or max them all (level 30, Prestige 9) in one click.
- **Mod browser:** search Nexus Mods. It only downloads files that passed Nexus's virus scan (the green check), and lets you turn mods on or off at any time.
- **Steam achievements:** view them, and unlock or relock them. WWZ Mod tells you if Steam isn't open.
- **Cheats:** infinite ammo, health, class equipment and more, applied live while you play.
  - **Quick cheats (F5–F8):** type the number you see, press its key, use it, wait 2 seconds, press again. A rising beep means it's found. **F9** switches every cheat on or off. Ammo lives in each gun, so press the key again after you change guns or start a new match.
  - **Class detection:** your class is read from your save, so F7 follows it (Slasher: stun gun, and so on).
  - **Safe freezing:** each value is checked before every write, so changing guns switches the cheat off cleanly and asks for a fresh find instead of freezing or crashing the game.
  - **Advanced scanner:** find any value by its hex address, narrow it down with *Value decreased*, then freeze it.
  - **In-game overlay (F10):** shows which cheats are on, over the game. Play in **Borderless** mode to see it.
- **Play history:** tracks what each play session earned you, with automatic backups.
- **Backups:** restore, compare, and export or import your save.
- **Appearance:** background art with visibility and blur, accent colours, and a reduce-motion option.

## Play fair
Cheats only change your own game. Use them **solo/offline or in private lobbies with friends who agree**.
Don't use them in public matches.

## Updates
WWZ Mod checks this page for new versions. You can install updates with one click, or turn on
**Settings → Updates → Install updates automatically**.

## Versions
| Version | Notes |
| --- | --- |
| [v1.0.9](https://github.com/jjtjtyt6644/WWZ-mod-installer/releases/tag/v1.0.9) | Fixed the freeze/crash when changing guns with infinite ammo on; removed the unreliable Make permanent auto-load |
| [v1.0.8](https://github.com/jjtjtyt6644/WWZ-mod-installer/releases/tag/v1.0.8) | Cheats page, quick cheats with F5–F9, class detection, advanced hex scanner, in-game overlay |
| [v1.0.2](https://github.com/jjtjtyt6644/WWZ-mod-installer/releases/tag/v1.0.2) | Steam check with Open Steam button, account level note, Armory removed |
| [v1.0.1](https://github.com/jjtjtyt6644/WWZ-mod-installer/releases/tag/v1.0.1) | Perk loadouts, equip suggested perks on all guns, tier skin unlocks, weapon renaming |
| [v1.0.0](https://github.com/jjtjtyt6644/WWZ-mod-installer/releases/tag/v1.0.0) | First public release |

## Disclaimer
WWZ Mod isn't affiliated with Saber Interactive, Valve or Nexus Mods. Back up your save before making changes.
Use it on your own save, at your own risk. Modded saves and content can be flagged in online play.

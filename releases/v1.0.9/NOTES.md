### Fixes

- **No more freeze/crash when you change guns.** With infinite ammo on, switching weapons (or starting a new match)
  used to let WWZ Mod keep writing into memory the game had reused, which could freeze or crash it. Each frozen
  value is now checked before every write: if the slot no longer holds a sensible value, the cheat switches itself
  off cleanly instead of writing into it.
- **Ammo lives in each gun**, so after you change guns, just press **F5** again to find it on the gun you're holding.
  WWZ Mod tells you when a cheat has switched off for this reason.

### Removed

- **Make permanent** has been removed. It was unreliable, so quick cheats (F5–F8) are the way to use infinite ammo
  and health now. Nothing you need to do: any old saved entries are simply ignored.

Cheats are for solo/offline play or private lobbies with friends who agree. Don't use them in public matches.

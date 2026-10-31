# Azeroth Survivors — Windows build mirror

A download mirror for the Windows build of [Azeroth Survivors](https://wow.aethus.pl/), the game by
Aethus. The official download is slow, so this hosts the same archive the author shared on the
game's Discord (October 25, 2026, "mirror by @Meexa").

Nothing here is modified. The archive is byte-for-byte the one the author posted hashes for.

## Download

Get `AzerothSurvivorsWindowsNew.rar` from the [latest release](../../releases/latest).

## Check the file

Before you extract it, make sure the hash matches what the author posted:

```
sha256 971db7968dc37ec50b18d64a1de7f693e137f6793a7368e4d5c27bd9522eccd8
md5    7748bfdffaccd2f46d868cf69ad3e72c
```

Windows (PowerShell):

```powershell
Get-FileHash .\AzerothSurvivorsWindowsNew.rar -Algorithm SHA256
```

If the hash does not match, do not run anything from it.

## Install

1. Extract the archive with 7-Zip or WinRAR into its own folder.
2. Run `AzerothSurvivors.exe`.

The archive holds game version 0.115.0. On first launch the game updates itself to the latest
version: it downloads any missing data patches, replaces its exe and restarts. You need nothing
else.

## Links

- Official site: https://wow.aethus.pl/
- Discord: https://discord.gg/azerothsurvivors
- Co-op guide (fan site): https://azerothsurvivorsgame.com/co-op/

This is not an official Aethus or Blizzard project. All game content belongs to its owners.

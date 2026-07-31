<p align="center">
  <img alt="Menace SMP logo" width="420" src="Season%202/imgs/menace_logo_alt2_finalfinal.png" />
</p>

# Menace SMP Season 2 (MC 26.1.2)

Private downloads and pack layout for friends.

## Downloads

### In this repo

- `Season 2/mods/` — unzipped mod folders (`Menace_Mods_2_0`, `Menace_Mods_2_1`)
- `Season 2/downloads/` — packs that fit in git (Essential Mods, Datapacks, Modrinth)
- `Season 2/datapacks/` — individual datapack zips

### On Releases (files over GitHub’s 100 MB git limit)

Use **[Releases → v2.1.2](https://github.com/marcosdherrero/Menace-Content/releases/tag/v2.1.2)**:

| Asset | What it is | Local path (your PC) |
|-------|------------|----------------------|
| **Menace.S2.1.2.Prism.zip** | Full Prism Launcher instance | `Season 2/downloads/` |
| **Menace.S2.1.2.Curseforge.zip** | CurseForge pack | `Season 2/downloads/` |
| **Menace.S2.1.2.Modrinth.mrpack** | Modrinth pack installer | also in repo `downloads/` |
| **Menace.S2.1.2.Essential.Mods.zip** | Essential mods zip | also in repo `downloads/` |
| **Menace.S2.1.2.Datapacks.zip** | Datapacks zip | also in repo `downloads/` |
| **Menace.SMP.Season.2.Pruned.July.9.2026.zip** | Pruned world save | `Season 2/worlds/` |

Pick one launcher pack (Prism / Modrinth / CurseForge). Use **Essential Mods** if you already have an instance. Use **Datapacks** for world/server datapacks.

### S2.1.2 notes

- **FairStructureLoot 1.0.2** — C2ME watchdog fix (`getBlockEntity` during chunk scan)
- **Removed name colors datapack** — it created persisted scoreboard teams that spammed Waystones rate-limits on boot
- **JEI** stays in client packs (Prism / CurseForge / Modrinth / Essential). Do **not** install JEI on the dedicated server jar folder
- Resource packs (VT Aesthetic / Bars / Util) are included in the Prism zip but **not enabled** in `options.txt` (`resourcePacks:["vanilla"]`) — enable in-game if you want them
- After removing name colors, clear leftover teams once on the server: `/team list` then `/team remove <name_colors.*>` (or leave them unused; boot spam stops once they are gone)

### Not on GitHub

`Season 2/zipped_versions/Menace_7_8_26.tar.gz` is ~29 GB — over GitHub’s **2 GB** release-asset limit and far over git’s **100 MB** file limit. Host it elsewhere (Drive, Mega, etc.) if friends need it. No special git uploader can bypass that.

## Repo layout

```
Season 2/
  imgs/              brand art (logo)
  datapacks/         individual datapack zips
  downloads/         packs (large Prism/CurseForge → Releases only)
  mods/              unzipped mod folders
  worlds/            world .zip on Releases; unzipped saves stay local
  zipped_versions/   full dump too large for GitHub
```

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

Use **[Releases → v2.1.4](https://github.com/marcosdherrero/Menace-Content/releases/tag/v2.1.4)**:

| Asset | What it is | Local path (your PC) |
|-------|------------|----------------------|
| **Menace.S2.1.4.Prism.zip** | Lean Prism Launcher instance (mods + server list) | `Season 2/downloads/` |
| **Menace.S2.1.4.Curseforge.zip** | Lean CurseForge pack (mods overrides + server list) | `Season 2/downloads/` |
| **Menace.S2.1.4.Modrinth.mrpack** | Lean Modrinth pack installer | also in repo `downloads/` |
| **Menace.S2.1.4.Essential.Mods.zip** | Essential mods zip (server-oriented; **no JEI**) | also in repo `downloads/` |
| **Menace.S2.1.4.Datapacks.zip** | Datapacks zip (no name colors) | also in repo `downloads/` |
| **Menace.SMP.Season.2.Menace_S2.1.1.LootrCleaned.July.31.2026.zip** | World save (`Menace_S2.1.1`) — Lootr→vanilla outside inhabited safety zones | `Season 2/worlds/` |
| **Menace.SMP.Season.2.Pruned.July.9.2026.zip** | Older pruned world (v2.1.0) | `Season 2/worlds/` |

Pick one launcher pack (Prism / Modrinth / CurseForge). Use **Essential Mods** if you already have an instance / for the dedicated server. Use **Datapacks** for world/server datapacks.

**Server world replace:** unzip so the folder is named `Menace_S2.1.1`, set `level-name=Menace_S2.1.1` in `server.properties`, backup the old world first. Bases near long-played chunks keep Lootr blocks (safety radius); far/unvisited Lootr was converted to vanilla containers. Optional: delete leftover `config/lootr*` on the server (Lootr jar should already be gone).

### S2.1.4 notes

- **VanillaPlusAccents 1.0.1** — path speed persists through jumps / Slow Falling, and path/mud modifiers are excluded from FOV zoom
- **FairStructureLoot 1.0.2** — unchanged
- **`Menace_Mods_2_1`** synced from live Prism instance (full client mod set)
- **Essential Mods** refreshed to current Prism versions; **JEI removed** from Essential (still in client packs)
- **Datapacks** — name colors remains removed
- **Lean packs** — mods + `servers.dat` + minimal launcher metadata only
- **Flashback** (~201 MB) is in Prism/CurseForge release packs; gitignored from `Menace_Mods_2_1` (over git’s 100 MB file limit)

### S2.1.3 notes (prior)

- VanillaPlusAccents 1.0.1 — path speed jump/Slow Falling persistence (FOV exclusion added in the S2.1.4 rebuild of the same 1.0.1 jar)
- Lean packs introduced; world `Menace_S2.1.1` Lootr-cleaned on that release

### S2.1.2 notes (prior)

- FairStructureLoot 1.0.2 + removed name colors datapack
- After removing name colors, clear leftover teams once on the server: `/team list` then `/team remove <name_colors.*>`

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

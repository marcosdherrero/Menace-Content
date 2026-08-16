<p align="center">
  <img alt="Menace SMP logo" width="420" src="Season%202/imgs/menace_logo_alt2_finalfinal.png" />
</p>

# Menace SMP Season 2 (MC 26.1.2)

Private downloads and pack layout for friends.

## Downloads

### Pack products (S2.1.5)

Two folders under `Season 2/downloads/`:

| Folder | What it is |
|--------|------------|
| **`essential_mods_menace/`** | Server-safe mods (~66 jars, **no JEI** / no Sodium·Iris·Mod Menu·minimap etc.) + Menace server entry + resource packs **included but inactive** |
| **`client_adds_menace/`** | Full Prism client mod set (~135 jars, includes JEI + client-only) + same server entry + packs inactive |

Each folder has Prism / CurseForge / Modrinth variants (Essential also has a plain `Essential.Mods.zip` for dropping jars onto a server).

**Local paths (your PC):**

- `F:\Games\Minecraft Things\Menace\Season 2\downloads\essential_mods_menace\`
- `F:\Games\Minecraft Things\Menace\Season 2\downloads\client_adds_menace\`
- Mirrored in this repo under `Season 2/downloads/…` (Essential Mods.zip in git; large Prism/CurseForge/Modrinth instance packs on Releases only)

### On Releases (over GitHub’s 100 MB git limit)

Use **[Releases → v2.1.5](https://github.com/marcosdherrero/Menace-Content/releases/tag/v2.1.5)**:

| Asset | What it is |
|-------|------------|
| **Menace.S2.1.5.Essential.Prism.zip** | Essential Prism instance |
| **Menace.S2.1.5.Essential.Curseforge.zip** | Essential CurseForge pack (jars in overrides) |
| **Menace.S2.1.5.Essential.Modrinth.mrpack** | Essential Modrinth pack (jars in overrides) |
| **Menace.S2.1.5.Essential.Mods.zip** | Essential mods folder only (dedicated server) |
| **Menace.S2.1.5.Client.Prism.zip** | Full client Prism instance |
| **Menace.S2.1.5.Client.Curseforge.zip** | Full client CurseForge pack |
| **Menace.S2.1.5.Client.Modrinth.mrpack** | Full client Modrinth pack |
| **Menace.S2.1.5.Datapacks.zip** | Datapacks zip (**no name colors**) |
| **Menace.SMP.Season.2.Menace_S2.1.1.LootrCleaned.July.31.2026.zip** | World save (`Menace_S2.1.1`) |
| **Menace.SMP.Season.2.Pruned.July.9.2026.zip** | Older pruned world (v2.1.0) |

Pick **Essential** to match the dedicated server / minimal connect set. Pick **Client** for the full experience (performance, JEI, minimap, shaders available but off by default).

### Pack contents (both folders)

- **Menace server** — `servers.dat` from Prism (`Mennacce` / `208.84.103.237:25578`)
- **Resource packs** — VT Aesthetic / Bars / Util copied from the Prism instance, but `options.txt` has `resourcePacks:["vanilla"]` only (not active)
- **Shaders** — none shipped from the instance (folder empty); Client packs set `config/iris.properties` with `enableShaders=false`
- **VPA 1.0.2** — flower patches break with the block below; stonecutter woodcutting (stairs/slabs/fences/gates); **FSL 1.0.2**
- **No name colors** datapack

### Also in this repo

- `Season 2/mods/` — unzipped mod folders (`Menace_Mods_2_0`, `Menace_Mods_2_1`)
- `Season 2/datapacks/` — individual datapack zips
- `Season 2/downloads/Menace.S2.1.5.Datapacks.zip` — datapacks bundle

**Server world replace:** unzip so the folder is named `Menace_S2.1.1`, set `level-name=Menace_S2.1.1` in `server.properties`, backup the old world first.

### S2.1.5 notes

- Synced from the live Prism instance (`Menace S2.1(1)`)
- **VanillaPlusAccents 1.0.2** — flower patches break when support is removed; 3–4 flower layouts; stonecutter plank stairs/slabs, log→fence, log→fence gate
- **ClientSort** added to the full client set
- **Essential** — same ~66 server-oriented jars with VPA 1.0.2 (no JEI / Sodium / Iris / Mod Menu / minimap)
- **Client** — full live Prism mod set (~135 jars), including Flashback in Prism/CurseForge/Modrinth release assets
- **Datapacks** — unchanged from S2.1.4 (name colors remains removed)

### S2.1.4 notes (prior)

- Split pack products into **essential_mods_menace** vs **client_adds_menace**
- **VanillaPlusAccents 1.0.1** — path speed persists through jumps / Slow Falling; path/mud modifiers excluded from FOV zoom
- **FairStructureLoot 1.0.2** — unchanged
- **Essential** — ~66 server-oriented jars; JEI and pure client mods excluded
- **Client** — full live Prism mod set (~134 jars), including Flashback in Prism/CurseForge release assets
- **Datapacks** — name colors remains removed
- Flashback (~201 MB) is gitignored from `Menace_Mods_2_1` (over git’s 100 MB file limit)

### S2.1.3 notes (prior)

- VanillaPlusAccents 1.0.1 — path speed jump/Slow Falling persistence
- Lean packs introduced; world `Menace_S2.1.1` Lootr-cleaned on that release

### S2.1.2 notes (prior)

- FairStructureLoot 1.0.2 + removed name colors datapack
- After removing name colors, clear leftover teams once on the server: `/team list` then `/team remove <name_colors.*>`

### Not on GitHub

`Season 2/zipped_versions/Menace_7_8_26.tar.gz` is ~29 GB — over GitHub’s **2 GB** release-asset limit and far over git’s **100 MB** file limit. Host it elsewhere (Drive, Mega, etc.) if friends need it.

## Repo layout

```
Season 2/
  imgs/              brand art (logo)
  datapacks/         individual datapack zips
  downloads/
    essential_mods_menace/   Essential Prism/CF/MR + Mods.zip
    client_adds_menace/      Client Prism/CF/MR (large → Releases)
    *.Datapacks.zip          datapacks bundle
  mods/              unzipped mod folders
  worlds/            world .zip on Releases; unzipped saves stay local
  zipped_versions/   full dump too large for GitHub
```

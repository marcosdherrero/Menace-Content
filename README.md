<p align="center">
  <img alt="Menace SMP logo" width="420" src="Season%202/imgs/menace_logo_alt2_finalfinal.png" />
</p>

# Menace SMP Season 2 (MC 26.1.2)

Private downloads and pack layout for friends.

## Downloads

### Pack products (S2.1.7)

`Season 2/mods/Menace_Mods_2_1` is the **Essential / dedicated-server set** (66 jars). No Sodium, Iris, JEI, Axiom, Litematica, Flashback, or minimap.

Two **separate** zip assets (not nested):

| Zip | What it is |
|-----|------------|
| **`Menace.S2.1.7.Essential.Mods.zip`** | 66 server-safe jars at the **zip root**. Unzip straight into Lagless `/mods`. |
| **`Menace.S2.1.7.Extended.Mods.zip`** | Those same Essential jars **plus** client mods (Sodium, Iris, JEI, Axiom, …) and Prism settings (`mods/`, `config/`, `options.txt`, `servers.dat`, resource packs). Unzip into a Prism `minecraft` folder. |

**Client and server must use the same Essential jars** (especially Waystones + Shogi).

### On Releases (over GitHub’s 100 MB git limit)

Use **[Releases → v2.1.7](https://github.com/marcosdherrero/Menace-Content/releases/tag/v2.1.7)**:

| Asset | What it is |
|-------|------------|
| **Menace.S2.1.7.Essential.Mods.zip** | Essential jars at zip root (Lagless `/mods`) — also in git |
| **Menace.S2.1.7.Extended.Mods.zip** | Essential + client mods + configs (too large for git) |
| **Menace.S2.1.7.Datapacks.zip** | Current Season 2 datapacks (**no name colors**, **no wood stripper**) |

World saves stay on older releases: **[v2.1.3](https://github.com/marcosdherrero/Menace-Content/releases/tag/v2.1.3)** (`Menace_S2.1.1` Lootr-cleaned) and **[v2.1.0](https://github.com/marcosdherrero/Menace-Content/releases/tag/v2.1.0)** (pruned world).

Upload **Essential.Mods.zip** to the dedicated server. Friends who want the full client set use **Extended.Mods.zip**.

### Pack contents

- **Menace server** — `servers.dat` from Prism (`Mennacce` / `208.84.103.237:25578`)
- **Resource packs** (Extended) — VT Aesthetic / Bars / Util from the Prism instance
- **Shaders** — none shipped; Extended `config/iris.properties` has `enableShaders=false`
- **VPA 1.0.4** — fence-lead hitch / catenary / shears, flush signs, flower patches, stonecutter woodcutting; **FSL 1.0.2**; **NMD 1.0.1**

### Also in this repo

- `Season 2/mods/Menace_Mods_2_1` — Essential/server jars only (matches the S2.1.7 Essential zip)
- `Season 2/datapacks/` — individual datapack zips (current set, no wood stripper)
- `Season 2/downloads/Menace.S2.1.7.Essential.Mods.zip`
- `Season 2/downloads/Menace.S2.1.7.Datapacks.zip`
- `Season 2/downloads/Menace.S2.1.7.Extended.Mods.zip` — local copy; published on Releases only (over 100 MB)

**Server world replace:** unzip so the folder is named `Menace_S2.1.1`, set `level-name=Menace_S2.1.1` in `server.properties`, backup the old world first.

### S2.1.7 notes

- **Two zip products** — Essential (server/Lagless) and Extended (full client + settings), same season version, separate assets
- Essential membership matches Lagless / S2.1.6: **Waystones 26.1.2.14**, **Shogi 26.1.2.8**, **Balm 26.1.2.12**, Fabric API 0.155.2, Lithium 0.24.7, VPA 1.0.4 (26.1.2)
- Extended adds client mods (Sodium 0.9.1, Iris, JEI 29.33.0.87, Axiom, Litematica, Flashback 0.43.3, Xaero, …) plus Prism `config/` / `options.txt`
- **Not included:** Async, Sodium 0.9.2-alpha, DBTools 2.2.2_AX, any 26.2-only VPA
- **Datapacks** — wood stripper removed; T-Birds structures updated to `[1.21.5--26.2]tbirds_structures.zip`

### S2.1.6 notes (prior)

- **Waystones 26.1.2.14 + Shogi 26.1.2.8 + Balm 26.1.2.12** — put this Essential zip on **both** the dedicated server and every client so Waystones matches
- **VanillaPlusAccents 1.0.4** (26.1.2) — fence-lead hitch/catenary/shears, flush signs; sneak-shear item frames is **not** in this 26.1.2 jar (that is unreleased 1.0.7 on 26.2)
- **NaturalMobDrops 1.0.1** — egg/head rates match vanilla wither-skeleton skull chance (2.5%)
- Fabric API 0.155.2, Lithium 0.24.7, Voice chat 2.6.22, plus other 26.1.2 patch updates (Architectury, Friends&Foes, Tom's Storage, Traveler's Backpack, …)
- **Not included:** Async, Sodium 0.9.2-alpha, DBTools 2.2.2_AX, any 26.2-only VPA
- **`Menace_Mods_2_1` is essential-only** — client jars (Sodium, Iris, JEI, Axiom, Litematica, Flashback, Xaero, …) were moved aside, not shipped
- **Essential.Mods.zip** — 66 jars at zip root for Lagless `/mods`

### S2.1.5 notes (prior)

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
    Menace.S2.1.7.Essential.Mods.zip
    Menace.S2.1.7.Datapacks.zip
    Menace.S2.1.7.Extended.Mods.zip   (gitignored; on Releases)
  mods/              unzipped mod folders (Essential only in git)
  worlds/            world .zip on Releases; unzipped saves stay local
  zipped_versions/   full dump too large for GitHub
```

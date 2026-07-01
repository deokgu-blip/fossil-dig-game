# Fossil Dig — 3D Model Credits

All buried "dig-up" 3D models are open-license assets sourced from [Poly Pizza](https://poly.pizza)
(no login required). Files were downloaded to `assets/_raw/models/` (git-excluded) and optimized into
`assets/models/*.glb` with `gltf-transform` (dedup + prune + weld + texture→webp@512 + KHR mesh quantization).

## Attribution required (CC-BY)

The following models are licensed **CC-BY 3.0** and **must be credited** on an in-game credits screen:

| Item (objKey) | Title | Author | License | Source |
|---------------|-------|--------|---------|--------|
| `shell` (암모나이트 화석) | Nautilus shell | Poly by Google | CC-BY 3.0 | https://poly.pizza/m/bceVxKNzLaJ |
| `vase` (고대 항아리) | Amphora | Bruno Oliveira | CC-BY 3.0 | https://poly.pizza/m/7Q8MkXjALbL |

Suggested credits-screen text:

> "Nautilus shell" by Poly by Google — CC-BY 3.0 (https://poly.pizza/m/bceVxKNzLaJ)
> "Amphora" by Bruno Oliveira — CC-BY 3.0 (https://poly.pizza/m/7Q8MkXjALbL)

## No attribution required (CC0 1.0)

The following models are **CC0 1.0** (public domain) and require **no attribution**. All are by
**Quaternius**, giving a consistent low-poly art style across the tier set:

| Item (objKey) | Title | Author | License | Source |
|---------------|-------|--------|---------|--------|
| `junk_bottle` | Prop Bottle | Quaternius | CC0 1.0 | https://poly.pizza/m/FO1yWXFzac |
| `junk_can` | Can | Quaternius | CC0 1.0 | https://poly.pizza/m/YnowJvWqxE |
| `coin` | Coins | Quaternius | CC0 1.0 | https://poly.pizza/m/VaGFKE0n0F |
| `gem` | Gem Blue | Quaternius | CC0 1.0 | https://poly.pizza/m/QgQ4rESqNc |
| `crown` | Crown | Quaternius | CC0 1.0 | https://poly.pizza/m/i0PZVuVlYv |
| `skull` | Skull | Quaternius | CC0 1.0 | https://poly.pizza/m/DJT7N0HuVB |
| `sword` | Sword | Quaternius | CC0 1.0 | https://poly.pizza/m/Ds2bJiNI5w |
| `dino` | T-Rex (animated) | Quaternius | CC0 1.0 | https://poly.pizza/m/UYtneO5FpF |
| `chest` | Chest Gold | Quaternius | CC0 1.0 | https://poly.pizza/m/4jqKCGHpUO |
| `goldbag` | Gold Bag | Quaternius | CC0 1.0 | https://poly.pizza/m/vFFblhnHtb |

> Note: CC0 items need no attribution, but crediting Quaternius (https://quaternius.com) is appreciated.

## Batch 2 — Bulk collection expansion (2026-07)

Added ~168 new "dig-up" collectibles for the grab-bag collection. Two sources:

### Kenney kits — CC0 1.0 (no attribution required)

162 models drawn from the following **CC0** Kenney kits (all by **Kenney**, https://kenney.nl):
Food Kit, Furniture Kit, Graveyard Kit, Holiday Kit, Nature Kit, Pirate Kit, Survival Kit.
Each kit is a single CC0 ZIP; individual GLBs were extracted and re-optimized with `gltf-transform`
(`--compress quantize` = KHR mesh quantization, textures→webp@512, **no meshopt/draco**).

> Models by Kenney (kenney.nl) — CC0 1.0 (public domain). No attribution required, but appreciated.

### Poly Pizza artifact/fossil/treasure tier

6 higher-rarity artifact/fossil/dinosaur models from Poly Pizza. One is CC0 (Quaternius);
the rest are **CC-BY** and **must be credited**:

| Item (objKey) | Author | License | Source |
|---------------|--------|---------|--------|
| `velociraptor` (벨로키랍토르 화석) | Quaternius | CC0 1.0 | https://poly.pizza/m/cnlGH2UcDd |
| `diplodocus` (디플로도쿠스 화석) | Poly by Google | CC-BY 3.0 | https://poly.pizza/m/12n6ICAVpYB |
| `tiltasaurus` (틸타사우루스 화석) | Anonymous | CC-BY 3.0 | https://poly.pizza/m/0DS8Ln10GRc |
| `trilobite` (삼엽충 화석) | Jakob Hippe | CC-BY 3.0 | https://poly.pizza/m/3Gyw-gUrpp0 |
| `jeweled_crown` (보석 왕관) | Poly by Google | CC-BY 3.0 | https://poly.pizza/m/0seQ0mn72s5 |
| `ancient_idol` (고대 우상) | Oded Sharon | CC-BY 3.0 | https://poly.pizza/m/2uQZ8GxU8nQ |

Suggested credits-screen text (append to existing CC-BY list):

> "Diplodocus" by Poly by Google — CC-BY 3.0 (https://poly.pizza/m/12n6ICAVpYB)
> "Tiltasaurus" — CC-BY 3.0 (https://poly.pizza/m/0DS8Ln10GRc)
> "Trilobite" by Jakob Hippe — CC-BY 3.0 (https://poly.pizza/m/3Gyw-gUrpp0)
> "Crown" by Poly by Google — CC-BY 3.0 (https://poly.pizza/m/0seQ0mn72s5)
> "Idol" by Oded Sharon — CC-BY 3.0 (https://poly.pizza/m/2uQZ8GxU8nQ)

## Batch 3 — Collection expansion (2026-07), +124 dig-up items

Added **124 more** "dig-up" collectibles (manifest total: **304**). Same pipeline as Batch 2
(`gltf-transform optimize --compress quantize --texture-compress webp --texture-size 512`,
**all animations stripped**, no meshopt/draco). Every file re-verified: 0 skins, 0 validation
errors, all under 300 KB.

### Kenney kits — CC0 1.0 (no attribution required)

92 models from these additional **CC0** Kenney kits (all by **Kenney**, https://kenney.nl):
Blaster Kit, Car Kit, Toy Car Kit, Castle Kit, Space Kit, Fantasy Town Kit, Racing Kit,
Tower Defense Kit, Mini Arena, Mini Dungeon, Mini Market.

> Models by Kenney (kenney.nl) — CC0 1.0 (public domain). No attribution required, but appreciated.

### Poly Pizza artifact / treasure / fossil tier

32 higher-rarity models from Poly Pizza. **6 are CC0** (no attribution): `gold_ingots`,
`gold_rocks`, `open_chest`, `gold_sword` (Quaternius), `purple_crystal` (iPoly3D),
`mystical_weapon` (MaverickFX). The remaining **26 are CC-BY 3.0** and **must be credited**:

| Item (objKey) | Author | License | Source |
|---------------|--------|---------|--------|
| `gold_stack` (금화 더미) | Garrett LeFever | CC-BY 3.0 | https://poly.pizza/m/4VbbgjDm87J |
| `treasure_chest2` (보물 궤짝) | Alex Safayan | CC-BY 3.0 | https://poly.pizza/m/3SGvQIwe214 |
| `treasure_map` (보물 지도) | jeremy | CC-BY 3.0 | https://poly.pizza/m/4hvGyOso598 |
| `red_gem` (붉은 보석) | Wesley Thompson | CC-BY 3.0 | https://poly.pizza/m/6K1VsAxWLwH |
| `google_gem` (푸른 원석) | Poly by Google | CC-BY 3.0 | https://poly.pizza/m/09p9-Mnp4Sc |
| `gold_nugget` (황금 덩이) | Poly by Google | CC-BY 3.0 | https://poly.pizza/m/0w-WpQf7O9J |
| `blue_diamond` (푸른 다이아몬드) | Sutu Eats Flies | CC-BY 3.0 | https://poly.pizza/m/2c3eNMf_J4y |
| `gem_cluster` (보석 원석) | Natalia Wojtkowska | CC-BY 3.0 | https://poly.pizza/m/3fdgnvEHWpS |
| `crystal_shards` (수정 조각) | Ashley Alicea | CC-BY 3.0 | https://poly.pizza/m/5wGpIRD2AKD |
| `diamond_ore` (다이아몬드 원석) | Mark Steelman | CC-BY 3.0 | https://poly.pizza/m/6Y2ykcwTCH0 |
| `stone_statue` (석상) | Zsky | CC-BY 3.0 | https://poly.pizza/m/0Mkdl3SJDT |
| `angel_statue` (천사 석상) | Zsky | CC-BY 3.0 | https://poly.pizza/m/6v4CL0nKfT |
| `anubis_statue` (아누비스 석상) | Zach Miller | CC-BY 3.0 | https://poly.pizza/m/9iPeQxL30oq |
| `ancient_monument` (고대 기념비) | Yogoshimo 2.0 | CC-BY 3.0 | https://poly.pizza/m/0un2vO8OCLn |
| `colossus` (거상) | Darwin Yamamoto | CC-BY 3.0 | https://poly.pizza/m/1JrbPYnWdeA |
| `guardian_statue` (수호신상) | apelab | CC-BY 3.0 | https://poly.pizza/m/2aGRBnKMLmt |
| `ancient_shrine` (고대 신전) | Aidan K McLaughlin | CC-BY 3.0 | https://poly.pizza/m/a68qNnAC4m- |
| `eight_vases` (고대 항아리 무리) | Paul Spooner | CC-BY 3.0 | https://poly.pizza/m/083bnosQpkP |
| `ancient_vase` (고대 화병) | Poly by Google | CC-BY 3.0 | https://poly.pizza/m/20LOTk3BnjO |
| `battle_axe` (전투 도끼) | Mobolaji | CC-BY 3.0 | https://poly.pizza/m/0joKOIPbu7 |
| `human_skull` (두개골) | Ian Wall | CC-BY 3.0 | https://poly.pizza/m/738EKrsYz96 |
| `shark_tooth` (상어 이빨 화석) | Poly by Google | CC-BY 3.0 | https://poly.pizza/m/6lZSwZSWTPw |
| `dino_skeleton` (공룡 골격 화석) | jeremy | CC-BY 3.0 | https://poly.pizza/m/7GKj5zdc1RZ |
| `google_dino` (공룡 화석) | Poly by Google | CC-BY 3.0 | https://poly.pizza/m/f5AfWX7Fyeb |
| `ancient_octopus` (고대 문어 화석) | Poly by Google | CC-BY 3.0 | https://poly.pizza/m/26XWuxd1G4R |
| `gold_trophy` (황금 트로피) | J-Toastie | CC-BY 3.0 | https://poly.pizza/m/3EOEqKBvy4 |

## Loader compatibility note

Optimized files require the glTF extensions `KHR_mesh_quantization` and `EXT_texture_webp`
(some also use `KHR_texture_transform` and `KHR_materials_unlit`). The project's vendored
`vendor/models/GLTFLoader.js` supports **all four** natively (no external decoder needed).
`EXT_meshopt_compression` and `KHR_draco_mesh_compression` were intentionally **not** used,
because no Meshopt/Draco decoder is wired into the engine and such files would fail to load
at runtime. All 304 models load through this loader with the same extension set already proven
in production by the Batch 1/2 models.

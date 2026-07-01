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

## Loader compatibility note

Optimized files require the glTF extensions `KHR_mesh_quantization` and `EXT_texture_webp`.
The project's vendored `vendor/models/GLTFLoader.js` supports both natively (no external decoder needed).
`EXT_meshopt_compression` was intentionally **not** used, because no MeshoptDecoder is wired into the
engine and meshopt-compressed files would fail to load at runtime.

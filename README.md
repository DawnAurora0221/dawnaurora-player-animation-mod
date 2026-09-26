# DawnAurora Player Animation
Fabric Mod for Minecraft 1.20.1

## About
This is a Minecraft Fabric mod for version 1.20.1, which implements a custom bone animation system for players.
- Third-person: Full body player animations, including walk, run, jump and attack motions.
- First-person: Arm animations for digging, item holding and swinging.
- Independent resource pack: All models and animation files are stored inside the resource pack. Animation assets can be edited separately without recompiling the mod source code.

## Project Info
- Game Version: Minecraft 1.20.1
- Mod Loader: Fabric
- License: Apache License 2.0

> You may use, study and distribute this project. Modified or derivative works must keep the original copyright notice. You are not allowed to apply patents based on this project.

## Repository Structure
dawnaurora-player-animation-mod/
├── src/                    # Fabric mod source code
├── resource-pack/          # Supporting animation resource pack
│   ├── pack.mcmeta
│   └── assets/dawnaurora/
│       ├── models/
│       └── animations/
├── README.md
└── .gitignore

## Installation
1. Install Fabric Loader 1.20.1 and Fabric API.
2. Put the mod jar file into your `mods` folder.
3. Put the matching resource pack into your `resourcepacks` folder and enable it inside Minecraft.

## Notes
- This is a personal development project. Learning and discussion are welcome. If you publish modified derivative works, follow the Apache 2.0 license and credit the original project.
- Still under active development. Features will be added step by step.

## Disclaimer
This mod is provided "as is", without warranty of any kind, express or implied.
In no event shall the author be liable for any claims, damages or other liabilities, whether in an action of contract, tort or otherwise, arising from, out of or in connection with the mod or the use or other dealings in the mod.

## Development Todo List
- [ ] Basic third-person walk & run animations
- [ ] First-person digging arm animation
- [ ] Jump & hurt animations
- [ ] More animation presets to switch between

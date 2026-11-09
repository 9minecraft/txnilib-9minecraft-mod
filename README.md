# TxniLib — Power Smooth Custom Animations in Your World

TxniLib 9minecraft Mod supplies shared code, networking tools, and animation helpers for other mods to run properly. This mod adds no standalone items, blocks, or mobs into your world on its own. Instead, it works behind the scenes to manage configuration files and utility helpers whenever a supported project requires it.

Powers animation systems across all projects that depend on it. Handles background networking and data transfer between the client and server.

## What this build is

An unofficial rebuild of **Txni's Minecraft Mods**'s original work, kept running on current Minecraft releases by 9Minecraft Studios. Not affiliated with the original author and not endorsed by them.

Most of the porting work sits in the mixin layer. Each Minecraft release moves or renames the methods this mod hooks into, so the hooks are re-pointed and re-tested against that version rather than rewritten. The behaviour underneath is upstream's and is deliberately left alone — that is the part that makes the mod feel right, and it is not ours to redesign.

## Source code

Upstream is licensed **MIT**. The port tree is not mirrored here; if you want it for review, for a fork, or to build it yourself, ask at **9minecraft.net@gmail.com** and it will be sent over.

## Versions

| Minecraft | Loader |
|---|---|
| 26.3 | Fabric, fabric |
| 26.2 | Fabric, fabric |
| 1.21.11 | Fabric, fabric |

## Getting the built mod

Install steps, the dependency list, the screenshot gallery and what changed in each release are kept together on the download page:

[9minecraft.net/txnilib-9minecraft-mod](https://www.9minecraft.net/txnilib-9minecraft-mod/)

## Credits

Original work by **Txni's Minecraft Mods**. Port and maintenance by 9Minecraft Studios. Licensed MIT; the upstream licence text ships inside every build.

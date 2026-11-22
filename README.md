# Karp-Launcher
A fast, tidy Minecraft launcher and mod manager, built in Rust.

Status: early development. Code will be published here once the core is stable.

Why

Existing mod platforms and launchers are slow, cluttered and full of ads. This project aims to be the opposite: one clean app that installs, updates and launches modded Minecraft without getting in your way.

Planned features
Every major loader in one place: Vanilla, Fabric, NeoForge, Forge and Horizon
Mod search and install across Modrinth and CurseForge, with automatic dependency handling
Separate instances, each with its own version, loader, mods and settings
Fast: parallel, checksum-verified downloads; nothing is re-downloaded that's already on disk
No Java setup: the correct Java runtime is downloaded automatically
Microsoft account sign-in using the official Microsoft/Xbox authentication flow

Progress
[x] Install and launch vanilla Minecraft (old and new versions)
[x] Automatic Java runtime download
[x] Fabric
[ ] NeoForge and Forge
[ ] Microsoft account sign-in
[ ] Horizon
[ ] Mod search and install (Modrinth, CurseForge)
[ ] Desktop UI
Notes

This is an independent hobby project and is not affiliated with Mojang or Microsoft. Minecraft game files are downloaded directly from Mojang's servers at runtime and are never included in this repository.

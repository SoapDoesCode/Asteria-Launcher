# Asteria-Launcher
Asteria Launcher is a custom Minecraft launcher written in Tauri, Python, and Node.js (with React)

## What is Asteria Launcher
Asteria Launcher (Asteria for short) is a custom minecraft launcher written in Python and Node.js (with React) using the Tauri framework. Asteria is built for simplicity, compatibility, and improved Minecraft version and mod management.

## Features
* Account management
  * Supports adding multiple Minecraft accounts
  * Microsoft OAuth 2.0 authentication
* Game version management
  * Supports creating/managing multiple versions of the game
  * Supports both versions and instances
* Settings management
  * Supports modifying launch settings (e.g. RAM)
  * Modify in-game settings straight from the launcher (e.g. Controls, Video Settings)
* Mod management
  * Supports all mods and mod loaders - we do not modify the actual game
  * Modrinth API support, allows installing mods inside the launcher itself
  * Automatically updates mods to new game versions using the Modrinth API
  * Performance mod suggestions when adding a game version (modded versions only)
  * Dynamic mod switching between game versions - no need to manually move mods around

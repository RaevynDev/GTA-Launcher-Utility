# GTA Trilogy Launcher

A Windows launcher and utility hub for the original Grand Theft Auto Trilogy, designed to bring game launching, save management, Discord Rich Presence, and modding utilities together in one place.

The **GTA Trilogy Launcher** provides a central place to manage and launch supported games from the original trilogy. It includes **GTA Trilogy RPC**, the project's Discord Rich Presence application, built directly into the launcher so you can enjoy detailed Discord activity without needing to run the standalone RPC application separately.

The project is actively developed, with the goal of expanding the launcher into a more comprehensive utility for players of the original PC releases.

## Supported Games

The launcher is designed around the original PC releases of:

- **Grand Theft Auto III**
- **Grand Theft Auto: Vice City**
- **Grand Theft Auto: San Andreas**

Game detection and compatibility may vary depending on the installed edition, executable, installation location, and game configuration. Not every version or distribution has been verified.

## Current Features

### Game Installation Detection

The launcher can attempt to locate supported GTA installations so that you can access your games through a central interface.

- Detects supported game installations where possible.
- Helps identify the game installations available on your system.
- Provides a foundation for future game-specific configuration and management features.

**Note:** Installation detection is still being refined and may not correctly identify every installation. Some editions, custom installation paths, or unusual configurations may require further compatibility work.

### Direct Game Launching

Launch supported games directly from the launcher instead of navigating to their installation directories and starting their executables manually.

The aim is to make accessing your installed games quicker and more convenient from one place.

### Basic Save Management

The current release includes basic save-management functionality for supported games.

This provides an initial foundation for managing game saves through the launcher, with scope for additional functionality and improvements in future releases.

Save compatibility and management capabilities may vary by game and installation. Always keep backups of important save files.

### Built-in GTA Trilogy RPC

The launcher includes **GTA Trilogy RPC**, the project's Discord Rich Presence integration for the original trilogy.

RPC allows your Discord profile to display information about your current game session, with supported states and details including:

- Automatic detection of supported GTA games.
- Custom Discord Rich Presence artwork for each game.
- Live game-state information, including menus, loading screens, free roam, missions, cutscenes, and paused states.
- Location and mission information where supported.
- Lightweight background operation through the Windows system tray.

The RPC component is maintained as a separate project and is also available as a standalone application for users who do not want to use the launcher.

## Planned Features

The launcher is an evolving project. The following areas represent planned development and potential future functionality; they should not be considered available in the current release unless explicitly documented.

- **Improved game detection:** More reliable identification of supported games, editions, executable versions, and custom installation paths.
- **Expanded save management:** Additional tools for managing, backing up, and organising game saves.
- **Mod management:** Tools to inspect, organise, and manage supported modifications, with attention to compatibility and safe installation.
- **Dependency management:** Better identification of required mod dependencies and assistance finding trusted downloads.
- **Game-specific utilities:** Additional tools and configuration options tailored to individual games in the trilogy.
- **Launcher improvements:** Continued refinements to usability, configuration, diagnostics, and overall reliability.

Planned features may change during development as compatibility, technical limitations, and user feedback are evaluated.

## Requirements

- Windows 10 or Windows 11, 64-bit.
- At least one supported original GTA PC game installed for game-specific functionality.
- Discord desktop application running for Discord Rich Presence.

Individual features may have additional requirements depending on the game, its version, or the functionality being used.

## Installation

1. Visit the [GTA Trilogy Launcher Releases page](https://github.com/RaevynDev/GTA-Trilogy-Launcher/releases).
2. Download the latest available release.
3. Extract the downloaded archive into a folder, if required by the release package.
4. Launch the GTA Trilogy Launcher executable.
5. Allow the launcher to detect your game installations, and configure any settings as needed.
6. Launch a supported game through the launcher and check your Discord profile to verify Rich Presence functionality.

Refer to the notes accompanying each release for version-specific installation instructions and known limitations.

## Versions and Releases

The launcher and GTA Trilogy RPC use **separate version numbers** because they are maintained and released as distinct components.

The launcher bundles a version of GTA Trilogy RPC, while the standalone RPC project has its own release history. The RPC version included with a particular launcher release may differ from the latest standalone release.

Check the release notes for the launcher version you are using to see the changes, fixes, and included component versions.

## Development Status

The launcher is under active development. Current functionality provides the foundation for a central GTA Trilogy utility, while detection reliability, game compatibility, and additional management tools continue to evolve.

Features may be incomplete, compatibility may vary between installations, and some planned functionality may not yet be available.

Bug reports and actionable feedback are welcome through the repository's [Issues page](https://github.com/RaevynDev/GTA-Trilogy-Launcher/issues).

When reporting a problem, include the launcher version, affected game and edition, relevant installation details, and steps to reproduce the issue. Please avoid sharing personal information or private files in reports.

## Related Project: GTA Trilogy RPC

**GTA Trilogy RPC** is the standalone Discord Rich Presence application that also powers the launcher's built-in RPC functionality.

Users who only want Discord Rich Presence can use the standalone project without installing the launcher.

[Visit the GTA Trilogy RPC repository](https://github.com/RaevynDev/GTA-Trilogy-RPC)

## Copyright and Disclaimer

Copyright © 2026 RaevynDev. All rights reserved.

This project is proprietary. No permission is granted to copy, modify, or redistribute its source code without the author's permission.

GTA Trilogy Launcher is an unofficial fan-made project. It is not affiliated with, endorsed by, or sponsored by Rockstar Games or Take-Two Interactive. Grand Theft Auto and its associated names and trademarks belong to their respective owners.

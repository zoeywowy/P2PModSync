# P2PModSync

P2PModSync syncs Lua mods for Solarpunk sessions.

Download P2PModSync-Windows.zip from the [latest release](https://github.com/zoeywowy/P2PModSync/releases/latest) and extract its HostSharedModSync folder into your existing UE4SS Mods folder while Solarpunk is closed. The mod checks for updates at startup. Press Ctrl+F11 to check again.

## Roadmap

### PAK and IoStore mods

- Install verified PAK and IoStore packages as complete sets and apply enable or disable changes on the next launch.
- Integrate package installation, restart, and reconnection with the multiplayer join flow.
- Explore runtime mesh, texture, and sound swaps for mods designed for them. Verify which import and asset creation APIs Solarpunk exposes, switch live objects to the replacement assets, and restore the original references when a mod is disabled.

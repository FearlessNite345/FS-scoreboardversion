# Changelog v1.2.1
- Fixed LUX hybrid dispatch totals counting the same dispatcher once from the connected roster and again from CAD.
- Added automatic LUX CAD civilian-service detection through the `/civilian-services` API.

# Changelog v1.2.0
- Added roster search, quick filters, optional department grouping, and clearer live player updates.
- Added smoother UI animations, connection details, streamer mode, and three new themes: Aurora, Ember, and Noir.
- Added early LUX CAD support alongside the existing standalone, framework, SonoranCAD, and hybrid modes. LUX CAD has not yet been fully live-tested.
- Reworked custom jobs into civilian services with optional global and per-service permissions while keeping `/setjob` simple.
- Added a Discord status webhook that maintains one live message and reports the server offline during a normal shutdown/restart.
- Added a server extension API for custom player badges, metadata, search terms, and role or status overrides.

# Changelog v1.1.3
- Added NAT2K15 framework job/department support with a configurable framework resource name.
- NAT2K15 support has not been tested against a live NAT2K15 installation and is based on its published documentation. Please report any integration issues.

# Changelog v1.1.2
- Updated SonoranCAD player matching for Linking V2 using `communityUserId`.
- Preserved legacy SonoranCAD API ID and server ID matching as fallbacks.
- Added support for SonoranCAD's newer `isDispatch` unit flag.
- Fixed players without role data falling through without a Civilian role.
- Hidden role and status columns when the current player data does not use them.
- Removed the legacy `+fs_scoreboard` and `-fs_scoreboard` keybind commands.

# Changelog v1.1.1
- Added debug config toggle.

# Changelog v1.1.0
- Major UI refresh with four themes (Nebula, Ledger, Pulse, Terminal) and updated typography
- Added standalone, SonoranCAD, framework, and hybrid data source modes.
- Added QBox, QBCore, and ESX job support.
- Added configurable keybind
- Added server-configurable theme, default sort, and optional per-player theme override (stored via KVP)
- Added sorting by ID/name/role plus a “show services only” toggle and richer summary stats
- Added custom job overrides via `/setjob`, optional ACE permission gate, and config-driven job list
- Added SonoranCAD department alias mapping to display full department names
- Added SonoranCAD LEO activity export (`IsActiveLeo`) for permission checks

# Changelog v1.0.1
- Added automatic scoreboard refreshing while open
- Resolved an issue where `config.lua` was locked/encrypted

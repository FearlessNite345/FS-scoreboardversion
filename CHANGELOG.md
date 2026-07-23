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

# Mandate desktop downloads

This repository distributes Mandate desktop installers. Application source is maintained separately.

Mandate production runs at https://mandate.agentlefs.com and uses production AgentleFS and Clerk. Development builds use separate endpoints and saved state.

Official macOS releases contain signed and notarized Apple Silicon (`arm64`) and Intel (`x64`) DMG and ZIP downloads, plus SHA-256 checksums. Unsigned previews, when available, are explicitly marked as prereleases and have `-unsigned` in the asset filename; they are not signed official releases.

See [Releases](https://github.com/agentleFS/mandate-downloads/releases) for available builds. A release is available only when its assets have been uploaded; this repository's existence alone does not mean a production installer has shipped.

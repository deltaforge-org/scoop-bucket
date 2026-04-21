# Delta Forge Scoop bucket

Scoop manifests for [Delta Forge](https://deltaforge.org) CLI packages on Windows.

## Install

```powershell
scoop bucket add deltaforge https://github.com/deltaforge-org/scoop-bucket
scoop install deltaforge-cli
scoop install deltaforge-mcp
scoop install deltaforge-compute
```

For the desktop application, use [winget](https://deltaforge.org) instead:

```powershell
winget install DeltaForge.Desktop
```

## What's in this bucket

- `bucket/deltaforge-cli.json` — Command-line interface
- `bucket/deltaforge-mcp.json` — Model Context Protocol server
- `bucket/deltaforge-compute.json` — Compute node

## Release channel

Manifests point at signed release artifacts hosted at
[github.com/deltaforge-org/delta-forge/releases](https://github.com/deltaforge-org/delta-forge/releases).
SHA256 hashes are pinned in each manifest.

## Issues

File Delta Forge bugs at [deltaforge-org/delta-forge/issues](https://github.com/deltaforge-org/delta-forge/issues).
For bucket-specific issues (a manifest fails to install, etc.), open an issue in this repository.

## License

See the main project at [deltaforge.org](https://deltaforge.org) for license terms.

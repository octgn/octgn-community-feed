# OCTGN Community Games Feed

This repository serves as the official community feed for OCTGN game definitions. Games listed here are available to all OCTGN users automatically.

## For Game Developers

To add your game to this feed:

1. Create a repository for your game with an `octgn-manifest.json` at the root.
2. Open a Pull Request to this repo adding your game entry to `index.json`.

### Entry Format

```json
{
  "guid": "your-game-guid",
  "name": "Your Game Name",
  "repo": "owner/repo",
  "branch": "main"
}
```

If your manifest is not at the repo root, add `"manifestPath": "path/to/octgn-manifest.json"`.

## For Feed Maintainers

This feed is maintained by the OCTGN community. To suggest changes, open an issue or PR.

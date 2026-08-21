# assets-ui-icons

Game UI icons (inventory, skills, status, navigation)

## Stats

- **Total assets**: 9035
- **License**: CC0-1.0 (all Kenney assets are public domain)
- **Source**: [kenney.nl](https://kenney.nl)

## Source Packs

| Pack | Assets | License | Link |
|------|--------|---------|------|
| Kenney Crosshair Pack | 2009 | CC0-1.0 | [Link](https://kenney.nl/assets/crosshair-pack) |
| Kenney Emotes Pack | 514 | CC0-1.0 | [Link](https://kenney.nl/assets/emotes-pack) |
| Kenney Flag Pack | 697 | CC0-1.0 | [Link](https://kenney.nl/assets/flag-pack) |
| Kenney Game Icons | 427 | CC0-1.0 | [Link](https://kenney.nl/assets/game-icons) |
| Kenney Game Icons Expansion | 794 | CC0-1.0 | [Link](https://kenney.nl/assets/game-icons-expansion) |
| Kenney Input Prompts | 4594 | CC0-1.0 | [Link](https://kenney.nl/assets/input-prompts) |

## Structure

```
assets-ui-icons/
├── assets/kenney/    # Organized by source pack
├── previews/         # Pack preview images
├── LICENSES/         # License files per pack
├── manifest.json     # Machine-readable asset index (9035 entries)
├── tags.json         # Genre, theme, style tags
└── README.md
```

## Usage

Browse `manifest.json` for the full asset index. Each entry includes:

```json
{
  "id": "kenney-<pack>/<asset-name>",
  "name": "Human Readable Name",
  "path": "assets/kenney/<pack>/...",
  "source": "Kenney <Pack Name>",
  "sourceUrl": "https://kenney.nl/assets/<pack>",
  "license": "CC0-1.0",
  "tags": [...],
  "fileType": "png|ogg|obj|..."
}
```

## License

All assets are **CC0-1.0** (Creative Commons Zero) — public domain, free for any use including commercial, no attribution required. See `LICENSES/` for original license files from each pack.

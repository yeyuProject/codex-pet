# Codex Pet Collection

This repository packages two local Codex desktop pets.

## Pets

- `luoxi` - see `pets/luoxi/pet.json`
- `cartethyia` - see `pets/cartethyia/pet.json`

Each pet folder contains:

- `pet.json`
- `spritesheet.webp`

The spritesheets are `1536x1872` WebP files with transparency, matching the
Codex pet atlas layout.

## Install Locally

Copy a pet folder into your Codex pets directory:

```powershell
Copy-Item -Recurse -Force .\pets\luoxi "$env:USERPROFILE\.codex\pets\luoxi"
Copy-Item -Recurse -Force .\pets\cartethyia "$env:USERPROFILE\.codex\pets\cartethyia"
```


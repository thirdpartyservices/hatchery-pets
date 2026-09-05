# hatchery-pets

Custom animated pets for OpenAI Codex (and OpenPets, which bridges Claude Code, Cursor, OpenCode, Gemini CLI and Pi CLI), hatched at **https://3ps.online/pets/**. One new pet drops here every day.

Every pet is the standard 1536x1872 atlas (8 columns x 9 rows of 192x208 frames) plus `pet.json`, validated with OpenAI's own open-source validator, with clean alpha (no magenta halo, no RGB residue on transparent pixels).

## Install a pet

```bash
# macOS / Linux
cp -r pets/lil-mayo ~/.codex/pets/
```

```powershell
# Windows
Copy-Item -Recurse pets\lil-mayo "$env:USERPROFILE\.codex\pets\"
```

Then in the Codex app: Settings > Appearance > Pets > refresh. Codex CLI: `/pets lil-mayo`. OpenPets reads the same folder.

## Make your own

https://3ps.online/pets/ is a free browser tool: describe a pet, get a validated pack in about two minutes. Submissions go up in the gallery with your name on them.

## Pets

| Pet | Preview | Description |
|---|---|---|
| [Lil Mayo](pets/lil-mayo/) | <img src="pets/lil-mayo/preview.gif" width="96"> | A tiny grey alien who floats, judges your code, and loves mayo. |
| [Pwny](pets/pwny/) | <img src="pets/pwny/preview.gif" width="96"> | A tiny e-ink face that pwns your bugs and naps in between. |
| [Glitch Cat](pets/glitch-cat/) | <img src="pets/glitch-cat/preview.gif" width="96"> | A hoodie-wearing hacker cat with a laptop and matrix-green eyes. |

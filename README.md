# s2k Skin Gallery

Curated skins converted from VS Code themes with
[`s2k`'s `vscode2skin.py`](https://github.com/RetricSu/s2k), served to the
s2k editor's **View → Skin Gallery…** menu.

`index.json` is the gallery manifest: name, author, license, source, download
URL, and three preview colors (`bg` / `accent` / `text` as `rrggbb`).

## Add a skin

1. Convert a theme (MIT or similarly permissive — keep the attribution):
   `python3 scripts/vscode2skin.py theme.json -o skins/<name>.skin.txt`
2. Append an entry to `index.json` with its preview colors and raw URL.

## Licenses

Each `.skin.txt` header notes its source theme. All themes currently listed
are MIT-licensed; check a theme's license before adding it here.

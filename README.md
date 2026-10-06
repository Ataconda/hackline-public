# HackLine public files

Served by GitHub Pages at `https://ataconda.github.io/hackline-public/`.

- `privacy/` — the HackLine privacy policy, linked from Google Play and the App Store. Keep its address unchanged; a new version gets a new effective date.
- `daily/v1/` — three daily puzzles a day (Easy, Medium, and Hard), at `daily/v1/YYYY-MM-DD-<tier>.json`. They are generated a month at a time by `tool/generate_daily.dart` in the HackLine project and checked by its tests before they are copied here. Do not edit them by hand, and never change a published file. `v1` is the file format; a later format would sit beside it.

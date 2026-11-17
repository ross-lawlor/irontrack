# Fonts

Kept in the repo so the app works offline and never contacts a font service. Both are licensed under the SIL Open Font License 1.1 (https://openfontlicense.org), which allows bundling them with the app.

| File | Font | Copyright |
| --- | --- | --- |
| `archivo.woff2`, `archivo-italic.woff2` | Archivo (variable: weight 100–900, width 62–125%), Latin subset | Copyright 2020 The Archivo Project Authors (https://github.com/Omnibus-Type/Archivo) |
| `jetbrains-mono.woff2` | JetBrains Mono (variable weight), Latin subset | Copyright 2020 The JetBrains Mono Project Authors (https://github.com/JetBrains/JetBrainsMono) |

Downloaded from Google Fonts (fonts.gstatic.com) on 2026-11-17. If you add or replace a file, also update `ASSETS` in `sw.js` so it's cached for offline use.

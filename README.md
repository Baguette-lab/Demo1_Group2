# Sa Iisang Bubong

A buildless DEMO 1 presentation about coming together, sharing a home, parting ways, and beginning again. The six phases follow the supplied Mika and Eli script.

## Run or upload

Upload this folder’s **contents** to the GitHub repository root, with `index.html` alongside `app.js`, `catalog.js`, and the media folders. Use GitHub Settings → Pages → Deploy from a branch → main → /(root). Keep `.nojekyll`. This also works on repository subpaths.

For local rehearsal, run `python3 -m http.server 8000` in this folder and open http://localhost:8000. No installation, build, API key, account login, or visitor import/export workflow is needed. Fonts and published YouTube videos use the internet; the packaged music, skit, prepared cuts, and charts are local.

## The final seven-song playlist

Only the seven songs in the supplied list are included, in that order. The playlist, story music, lyric passages, sing-alongs, and packaged audio use the same selection.

| # | Song | Artist | Release year | Full recording |
| --- | --- | --- | --- | --- |
| 1 | Panalangin | APO Hiking Society | 1980 | 3:49 |
| 2 | When I Met You | APO Hiking Society | 1982 | 4:15 |
| 3 | Vines | The Ridleys | 2024 | 3:17 |
| 4 | True Love Waits | Radiohead | 2016 | 4:44 |
| 5 | Unti-Unti | UDD (Up Dharma Down) | 2017 | 4:58 |
| 6 | The Apartment We Won’t Share | NIKI | 2022 | 2:30 |
| 7 | Sa Susunod na Habang Buhay | Ben&Ben | 2020 | 4:40 |

Full playlist: **28:12**. Prepared skit music: **3:02**, plus dialogue and discussion. The selection meets the guide’s 6–8 songs and approximate 20–30 minute range. Each per-song interpretation stays under 100 words.

## Presentation flow

1. Our topic: original title, theme, reasons, and the group’s position on divorce as an option.
2. Story & song cuts: six animated phases, four reader roles, dialogue controls, reading pace, original instrumental background music, short native vocal cuts, line highlighting, rehearsal script, and phase cue sheet.
3. Full playlist: the same songs grouped by phase. Phase filters, search, Play all, next/previous, seek, volume, and official/fan sing-along video access are available.
4. Closing data: census charts, qualitative research context, youth union-status figures, demographic concepts, household scenarios, overall reflection, legal distinctions, and APA references.

## Prepared cuts

`CUE_SHEET.md` records each phase, source interval, cut duration, and narrative connection. `cuts/manifest.json` records input/output SHA-256 hashes and the clip timeline. Every prepared clip is an MP3 with a recipe-based filename. Old WAV cuts have been removed; changed cuts use new names and the page loads versioned scripts.

Original full recordings remain in `mp3/`. The selected lyric passages from `documents/selected-playlist.md` are in `catalog.js` and matching `.lrc` files. The native lyric stage uses the prepared cut’s zero-based timing, and clicking a line starts at that line. Complete published sing-along videos are separate from these excerpts. Vines uses an official live performance whose on-screen lyrics are not verified.

The dialogue follows `documents/group-script.pdf`, with the duplicated Part 2 narrator paragraph shown once and generic narration divided between Narrator 1 and Narrator 2. Music transitions use the final seven-song selection. `STORY.md` is the rehearsal version.

## Evidence and interpretation

Sources were reviewed November 9, 2026. `SOURCE_NOTES.md` explains their scope. PSA observations remain historical 2015/2020 figures for household population aged 10+. The combined divorced/separated/annulled category is not divorce alone or an annual rate. YAFS covers ages 15–24; fictional Eli, 25, falls outside it. Kuang’s focus groups provide qualitative context, not national prevalence.

Mika and Eli are fictional unmarried adults. Their breakup illustrates cohabiting-union dissolution and household reorganization, not a legal divorce. The group’s support for divorce is a policy position, distinguished from observations and existing legal routes. Song readings are the group’s interpretations, not claims about the artists’ intended meanings.

## Files

- `index.html`, `app.js`, `styles.css`, `revision.css`: website and interactions.
- `catalog.js`: the seven selected songs and their metadata.
- `presentation-data.js`, `STORY.md`, `CUE_SHEET.md`, `documents/group-script.pdf`: phases, dialogue, roles, cues, and supplied script.
- `mp3/`, `cuts/`, `lyrics/`: full recordings, prepared cuts, selected lyrics.
- `concepts.js`, `laws.js`, `SOURCE_NOTES.md`: academic context and references.
- `story-world.js`, `assets/sprites/`: pixel scenes and local CC0 sprites; attribution in `assets/ARTWORK.md`.
- `story-music.js`, `assets/audio/`: original ambience, separate from the songs.

The presentation is fixed to these seven selected songs. There is no visitor editor or import/export workflow. The original ambient background music is separate from the seven playlist recordings.

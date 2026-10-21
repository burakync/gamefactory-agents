# Authentic gameplay recordings

[← Three iterations](README.md) · [Playable releases and source](SOURCE.md)

Recorded on 21 October 2026 from the preserved, exported Windows executables of Little Star Jump v0.2.0, v0.2.1 and v0.2.2. No game source was changed and no production workflow was rerun to make these clips.

The recorder captured the live game client at 960 × 540 and 20 fps while foreground-guarded physical keyboard events controlled the game. FFmpeg reduced the captures to **480 × 270, 15 fps, 128-color GIFs**, using nearest-neighbor scaling. No generated gameplay, compositing or simulated frames were used. The four GIFs total **936,513 bytes (0.94 MB)**.

| Clip | Release | Length | GIF size | Still fallback |
| --- | --- | --- | --- | --- |
| [create](media/01-create.gif) | v0.2.0 | 8 s | 338 KB | [PNG](media/01-create.png) |
| [before](media/02-before.gif) | v0.2.0 | 4 s | 117 KB | [PNG](media/02-before.png) |
| [after](media/02-improve.gif) | v0.2.1 | 4 s | 183 KB | [PNG](media/02-improve.png) |
| [platform](media/03-extend.gif) | v0.2.2 | 7 s | 298 KB | [PNG](media/03-extend.png) |

The first clip reaches the three-star victory. The second pair uses the same short-tap and held-jump sequence before and after tuning. The final clip boards and rides the moving platform through its turnarounds. The before/after clips are live recordings and are not synchronized frame by frame; the precise 25% airtime reduction comes from the retained scene-test measurements.

The same Codex operator inspected sampled frames for actual content and clean client-area framing. All GIFs decoded successfully. This is presentation verification, not independent review, owner visual approval or a rerun of the release regression suites.

[Machine-readable provenance](evidence/media.json) records executable, raw recording, GIF and still-image SHA-256 hashes. Executable hashes match the historical release verification snapshots. Raw recordings and capture receipts remain local. An initial recorder-wrapper exit-code reporting failure was retained locally; successful captures were repeated and checked before encoding these GIFs.

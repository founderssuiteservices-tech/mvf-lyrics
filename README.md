# MVF — Lyric Video Portfolio

Live site: https://founderssuiteservices-tech.github.io/mvf-lyrics/

A single static page to send to leads: showreel, five lyric videos (40–48 s highlights with sound),
three 9:16 reels, how it works, and WhatsApp CTAs (+91 79772 31182).

- `index.html`: the whole page (inline CSS + JS, no build step)
- `media/`: `<slug>.mp4` highlight with sound, `<slug>-loop.mp4` muted grid loop, `<slug>-poster.webp`,
  `<slug>-glow.jpg` ambient light, `<slug>-reel.mp4` / `-reel-loop.mp4` / `-reel-poster.webp`, `showreel.mp4`
- `assets/`: logo sizes, favicon, `og.jpg` (WhatsApp / social link preview, 1200x630)

Media is cut and encoded from the final masters by `D:\mvf-lyrics-work\build_media.py`
(segments, loudness −14 LUFS, H.264 faststart). The page carries `noindex`, so it is shared by link only.

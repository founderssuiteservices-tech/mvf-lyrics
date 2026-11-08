# MVF — Lyric Video Portfolio

Live site: https://founderssuiteservices-tech.github.io/mvf-lyrics/

A single static samples page to send to leads: a compact hero, a 2-column grid on every screen
(two YouTube style references, then MVF's own lyric videos with sound), three 9:16 reels, how it works,
and WhatsApp CTAs (+91 79772 31182). Reference tiles link to the official YouTube videos; their footage
is never re-hosted here.

- `index.html`: the whole page (inline CSS + JS, no build step)
- `media/`: `<slug>.mp4` highlight with sound, `<slug>-loop.mp4` muted grid loop, `<slug>-poster.webp`,
  `<slug>-glow.jpg` ambient light, `<slug>-loop-sm.mp4` light phone loop, `<slug>-reel.mp4` / `-reel-loop(-sm).mp4` / `-reel-poster.webp`
- `assets/`: logo sizes, favicon, `og.jpg` (WhatsApp / social link preview, 1200x630)

Media is cut and encoded from the final masters by `D:\mvf-lyrics-work\build_media.py`
(segments, loudness −14 LUFS, H.264 faststart). The page carries `noindex`, so it is shared by link only.

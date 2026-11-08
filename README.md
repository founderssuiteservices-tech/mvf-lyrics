# Credvert — Lyric Video Samples

Live site: https://founderssuiteservices-tech.github.io/mvf-lyrics/

A single static samples page to send to leads: a compact hero, a 2-column grid on every screen
(two YouTube style references, then Credvert's own lyric videos with sound, ending on a Credvert card),
three 9:16 reels, and how it works. There are no WhatsApp or contact buttons. Reference tiles link to the
official YouTube videos; their footage is never re-hosted here.

- `index.html`: the whole page (inline CSS + JS, no build step). The Credvert mark is an inline SVG symbol
  (`#cv` full logo, `#cv-c` the pixel C alone), brand colours `#7fee63` / `#111`.
- `media/`: `<slug>.mp4` highlight with sound, `<slug>-loop.mp4` muted grid loop, `<slug>-poster.webp`,
  `<slug>-glow.jpg` ambient light, `<slug>-loop-sm.mp4` light phone loop, `<slug>-reel.mp4` / `-reel-loop(-sm).mp4` / `-reel-poster.webp`
- `assets/`: `credvert.svg` + `credvert-32.png` favicons, `credvert-180.png` home-screen icon,
  `og-credvert.jpg` link preview (1200x630, rendered from the gitignored `_og.html`)

Media is cut and encoded from the final masters by `D:\mvf-lyrics-work\build_media.py`
(segments, loudness −14 LUFS, H.264 faststart). The page carries `noindex`, so it is shared by link only.

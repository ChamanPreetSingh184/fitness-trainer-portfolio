# Images guide

Replace the placeholder photos with the trainer's real ones, **keeping the same file names**
(or change the paths in the `CONFIG` block at the top of the script in `index.html`).

| File | Purpose | Size | Ratio |
| --- | --- | --- | --- |
| `hero.webp` | Main photo in the top section | 900 x 1125 | 4:5 portrait |
| `trainer.webp` | About section photo | 800 x 1000 | 4:5 portrait |
| `transformations/t1-before.webp` / `t1-after.webp` | Transformation pair 1 | 800 x 1000 | 4:5, same framing for both |
| `transformations/t2-*.webp`, `t3-*.webp` | More pairs | 800 x 1000 | 4:5 |
| `og-cover.jpg` | Preview shown when the link is shared on WhatsApp / Instagram | 1200 x 630 | 1.91:1 |
| `favicon.svg` | Browser tab icon | any | square |

## Rules for production
- Format: **WebP**, quality about 70-75. Aim for under **100 KB** per photo (currently 22-83 KB).
- Never upload phone originals (3-8 MB). Resize to the width in the table first (squoosh.app is free).
- Before/after pairs must have the same crop and lighting so the slider lines up.
- Use client photos only with their written consent.
- Adding a pair: put the two files in `transformations/` and add one line to `transformations` in `CONFIG`.
- For link previews to work, change `og:image` in `index.html` to the full URL after deploy,
  e.g. `https://your-site.vercel.app/images/og-cover.jpg`.

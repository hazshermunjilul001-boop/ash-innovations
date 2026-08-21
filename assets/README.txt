Images needed in this /assets folder for the site to display correctly:

ALREADY INCLUDED IN THIS ZIP:
1. hazsher1.png — background removed, used as the LEFT flanking pillar figure
2. hazsher2.png — background removed, used as the RIGHT flanking pillar figure
   (Both are auto-cutout via AI background removal. Edges are decent but not
   pixel-perfect — if you want them cleaner, touch up the edges in Photopea
   or Remove.bg's manual refine tool before final deploy.)
   Pillars are hidden automatically on screens narrower than 1200px so they
   never crowd the orbit on tablet/mobile — no action needed there.

STILL NEEDED FROM YOU (not included — these are your own photos):
3. hazsher.jpeg
   - Your main portrait, used in the CENTER of the orbital hero (the
     "Mission Control" circle) and as the Open Graph share image.
   - Square-ish or portrait orientation, at least 800x800px, well-lit,
     clear face shot.

4. sir-ash-icon.jpg
   - Small icon used as the header logo/brand icon and as the favicon.
   - Square, at least 128x128px. Renders very small (~38px) so keep it
     simple and high-contrast.

Optional, mentioned in earlier review, not required to launch:
5. og-image.jpg — dedicated 1200x630px social-share image. Until added,
   the site falls back to hazsher.jpeg for social shares.
6. favicon.ico — browsers already fall back to sir-ash-icon.jpg via the
   <link rel="icon"> tag, but a .ico is more universally supported.

Place all files directly in this /assets folder with these exact
filenames — the site references them by that path.

Duel PVP — Final Site (v2)
- Glow moved to the other side (right by default). Adjust in :root if needed.
- Logo smaller and positioned near the title (top). Animated glow via CSS.
- Temporary fix if your logo PNG is not transparent: a circular clip-path hides square edges.
  Replace assets/logo-pvp.png with a transparent PNG to remove the clip workaround.

Tweak glow alignment in index.html (top):
  --glow-x: 72%;
  --glow-y: 58%;
  --glow-w: 300px;
  --glow-h: 520px;

If aligning, add ?debug=1 to the URL to see the overlay bounds.

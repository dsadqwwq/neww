Duel PVP — Final Site (v4)

- Coordinated slower glow: background lava, corner logo, title, and slogan pulse together (4s cycle).
- Logo pinned to top-left corner; brand block (DUEL PVP + slogan) moved to bottom-center.
- Slogan set to: "Real time, real skill, real rewards."
- Adjust glow alignment in :root (index.html):
    --glow-x: 72%; --glow-y: 58%; --glow-w: 264px; --glow-h: 458px;
  Add ?debug=1 to the URL while adjusting.
- Replace assets/logo-pvp.png with a transparent PNG to remove the clip-path.

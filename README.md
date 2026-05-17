# Reincarnating a Decade-Old jQuery Project

![Reincarnating a Decade-Old jQuery Project](assets/poster.jpg)

Cleaning my old drive, I found `burger.zip` dated 2015 — one of my first paid web gigs, a burger builder for a Swiss client built on jQuery 1.7. I gave it a second life: archived the original as-is, rebuilt it in TypeScript next door, then ran three agents in parallel to make the rebuild feel real.

The radial menu shrank from a 780-line jQuery plugin to ~50 lines of trig. The stack-height switch statement became one flex column with negative margin. Two gotchas bit me along the way.

## What's Inside

- Why I kept the original code untouched in `legacy/` instead of rewriting history
- The 50-line trig replacement for the 780-line `jQuery.radmenu` plugin
- Replacing a hand-crafted stack-height switch statement with flex + negative margin
- Tumble, motion blur, squash, idle jiggle, and a 3D tilt — what realism actually costs
- The CSS `translateY` that GSAP silently stomped and dragged the burger off-screen
- Why I reverted my agent's "improved" bottom bun back to the 2015 hand-drawn SVG

## 📎 Read Full

[Reincarnating a Decade-Old jQuery Project](https://dev.to/tegos/PLACEHOLDER)

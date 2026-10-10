# Marble Fun

A playful **Ebru (water marbling)** drawing tool that runs in the browser — no install, just open `index.html`.

**▶ Try it:** https://juljuljuljuljul.github.io/marble-fun/

## How it works

Marbling ink floats on thickened water: it never blurs or mixes, it only gets pushed and stretched, and every color keeps its exact area. The tool follows the math of *Mathematical Marbling* (Jaffer, Lu et al.):

- **Ink drop** at C with radius r: `P' = C + (P−C)·√(1 + r²/|P−C|²)` — older ink is pushed out in rings, area preserved exactly.
- **Stylus / comb** moving by M: `P' = P + M·g(d)` — ink near a tooth moves with it, and the pull fades with distance.
- **Swirl**: rotation that decays with distance from the center.

Each color is stored as a vector outline, and edges are refined along the true curve, so lines stay crisp however much you comb.

## Tools

Drop · Sprinkle · Stylus · Comb · Swirl · Pour, plus whole-tray Gelgit and Comb passes.

**Kid mode** (switch at the bottom of the panel): four big tools, five sizes, a bright palette, faster drops, and full screen.

---

A personal, just-for-fun project inspired by the traditional Turkish art of Ebru marbling. Made for personal use only — not for sale, and no profit is made from it.

# 🍉 Fruit Ninja

A fast, juicy browser remake of the classic slice-the-fruit arcade game. Built as a single self-contained HTML file — no build step, no dependencies, no backend. Just open it and swipe.

## How to Play

- **Swipe** across the screen with your mouse or finger to slice flying fruit.
- **Chain slices** within a short window to build a **combo** for bonus points — the more fruit in one swipe, the bigger the score.
- **Avoid the bombs.** Slicing one costs you a life and flashes the screen red.
- **Don't let fruit fall.** Any fruit that drops off the bottom un-sliced costs a life too.
- You have **3 lives**. Lose them all and it's game over.

Difficulty ramps up the longer you survive: fruit flies faster, waves get bigger, and bombs appear more often.

## Features

- Seven hand-drawn fruits (watermelon, orange, lemon, apple, kiwi, plum, lime), each with realistic spherical shading, specular highlights, and fruit-specific details — stripes, citrus pores, stems, and leaves.
- Fruit splits into two clipped halves with juicy interiors, wet cut faces, and correct innards (seeds, cores, pits, citrus segments).
- Glossy cast-iron bombs with a curved, sparking fuse.
- Glowing blade trail, juice-particle splatter, screen flash, and combo pops.
- Combo scoring, 3-life system with heart icons, and a personal **best score** saved in your browser.
- Retina-aware canvas, responsive layout, and full mouse + touch support.

## Running It

No server required — it's a static page.

- **Locally:** open `index.html` in any modern browser.
- **Hosted:** deploy the folder to any static host (GitHub Pages, Netlify, etc.).

## Tech

Vanilla HTML, CSS, and JavaScript rendered on a `<canvas>`. Type from [Google Fonts (Fredoka)](https://fonts.google.com/specimen/Fredoka). Best score persists via `localStorage`.

---

Made with 🔪 and a lot of fruit.

# Landing-Page

## Introduction

This project is my submission for The Odin Project's Foundations: Landing Page assignment. The goal was to rebuild a landing page from a provided design (a full mockup image plus a color/font reference) using only HTML and CSS, with Flexbox as the main layout tool. The page has four main sections plus a footer, and I was free to swap in my own content, images, and colors as long as I kept the overall structure and spacing close to the design. It didn't need to be pixel-perfect or responsive — the point was practicing how to break a static design into HTML markup and then lay it out with Flexbox.

## Skills

- CSS

- Flexbox

- CSS custom properties (variables) for reusable colors/spacing

- align-items vs. align-content for cross-axis alignment

- justify-content variants for main-axis spacing

- flex: 1 1 0 with min-width: 0 to prevent flex items from overflowing their container

- The outer-wrapper / inner-container pattern for full-width section backgrounds with a constrained content width

- The width: 100vw breakout trick for full-bleed sections inside a centered layout
  max-width vs. fixed width for more resilient sizing

- Handling replaced elements (like <img>) and their intrinsic sizing inside flex containers

## Self-Reflection

Building this page was the first time I had to translate a static design into real layout decisions instead of just following exercise instructions. The hardest part was getting sections to span the full width of the viewport while keeping the actual content (text, buttons, images) centered and constrained — that's where the outer-wrapper/inner-container pattern and the 100vw breakout trick actually clicked for me, since I'd only seen them explained in the abstract before.

I also ran into the classic "why is this image squishing/stretching weirdly inside my flex row" problem, which pushed me to actually understand intrinsic sizing on replaced elements rather than just guessing with object-fit. Using flex: 1 1 0 alongside min-width: 0 fixed a related issue where text-heavy flex items refused to shrink below their content size and broke the row.

Overall this project made Flexbox feel less like memorized properties and more like a toolkit I reach for on purpose — I could look at a section of the design and reason about which axis needed to grow, shrink, or align before writing any CSS.

## References

- Video by Ron Lach : https://www.pexels.com/video/people-sitting-on-the-floor-while-playing-video-games-7856589/

Photo by <a href="https://unsplash.com/@lukassouza?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Lukas Souza</a> on <a href="https://unsplash.com/photos/illuminated-manhattan-skyline-at-night-with-one-world-trade-center-zBrNJfN76BA?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>

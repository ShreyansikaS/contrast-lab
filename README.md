# Contrast Lab

A small tool that checks whether two colors are readable together, based on the WCAG 2.1 accessibility rules.

Live demo: https://YOUR-USERNAME.github.io/contrast-lab/

## Why I made this
I like projects where the math is simple but the result affects real people. Low contrast text is one of the most common accessibility problems on the web, and most designers check it with a browser plugin without knowing how the number is calculated. I wanted to build it from scratch so I understood the formula, and so I could export the colors straight into CSS.

## What it does
You pick a text color and a background color. The page shows a live preview, the contrast ratio, and whether the pair passes AA and AAA for normal text, large text, and UI components. There is a button to swap the two colors and one to copy the result as CSS variables.

## What I did
- Wrote the luminance and contrast ratio calculation by hand from the WCAG formula, including the gamma correction step that people often skip.
- Validated the hex input so a typo shows a message instead of breaking the page.
- Made it work with only a keyboard, added visible focus outlines, and sized buttons to 44px for touch.
- Added a dark mode that follows the system setting.

## Skills used
JavaScript, HTML, CSS, WCAG 2.1, color theory, design tokens, responsive layout, keyboard accessibility.

## Roles this project fits
UX Engineer, Front-End Engineer, Accessibility Engineer, Design Systems, Product Design (technical).

## Run it
Open `index.html` in a browser. There is nothing to install.

## What I would add next
A button that suggests the closest color that passes, and a color blindness preview.

# Simple Tabs

A small UI exercise from [roadmap.sh](https://roadmap.sh/projects/simple-tabs) that builds a four-tab interface with vanilla HTML, CSS, and JavaScript. The first tab is active on load; selecting another tab hides the current panel and shows the chosen one.

## Features
- Three tabs with active state styling and smooth content switching
- Responsive layout: horizontal tabs on desktop, stacked on narrow screens
- Minimal, framework-free implementation for easy reuse or extension

## Getting Started
1) Clone or download this repo.
2) Open `index.html` in a browser. No build tools or dependencies are required.

## File Overview
- index.html — markup for the tab buttons and panels
- style.css — layout, spacing, responsive rules, and active tab visuals
- script.js — click handlers that toggle active tab buttons and content sections

## How It Works
- Tabs are grouped in a `.tab-buttons` container; panels live in `.tab-contents`.
- Clicking a `.tab-button` sets it to the `.active` state and removes that state from others.
- The script maps each button to a corresponding `.tab-content`, showing one panel at a time.

## Customization Tips
- Change labels: edit the button text in `index.html`.
- Update colors/spacing: tweak CSS variables or rules in `style.css`.
- More tabs: add another button/panel pair following the existing structure, then ensure the script maps IDs correctly.

## Notes
- Works offline; pure front-end.
- Tested in modern evergreen browsers.

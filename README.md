# iOS-style Calculator

A single-file, client-side calculator designed to closely match the iPhone Calculator portrait layout from the supplied reference screenshot.

## Included
- Backspace, AC, %, ÷, ×, −, +, ±, decimal, 0–9, and =
- Chained arithmetic
- Calculation history via localStorage
- Keyboard support on desktop
- iPhone safe-area handling and standalone web-app metadata
- No build step or backend

## GitHub Pages
Upload `index.html`, `manifest.webmanifest`, `icon-180.png`, and `README.md` to the root of a GitHub repository. Enable GitHub Pages from Settings → Pages → Deploy from a branch → main → / (root).

Apple's private Calculator/SF Symbols assets are not distributed as a public web library, so the interface uses CSS and inline SVG to reproduce the appearance.

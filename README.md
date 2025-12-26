# Apology Hearts

A minimal, self-contained HTML page that renders floating red hearts on a black
background with a centered apology message. Built with pure HTML, CSS, and
vanilla JavaScript.

## Features
- CSS heart shapes with `::before`/`::after` pseudo-elements
- Continuous heart spawning with randomized position, size, and speed
- Smooth floating, scaling, and fade-out animations
- Centered, high-contrast apology message overlay
- No dependencies or build tools required

## Demo
Open `index.html` directly in any modern browser.

## Project Structure
- `index.html` - Complete page with embedded styles and script

## Customization
- **Heart color**: Update `--heart-color` in the `:root` section
- **Message text**: Edit the `.apology` element in `index.html`
- **Spawn rate**: Adjust the `setInterval` delay in the script
- **Density**: Change `maxHearts` in the script

## License
MIT

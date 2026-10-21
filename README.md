# TEDxTUWien Speaker Timer

A simple full-screen count-up timer for speakers at TEDxTUWien. Opening the site shows the timer right away.

## Usage

Open the site (or `index.html`) in a browser. The old `/timer/` link redirects to the root.

| Key | Action |
|-----|--------|
| `Space` | Start / pause |
| `R` | Reset |
| `1`–`9`, `0` | Time limit 11, 12, 13, 4, 5, 6, 7, 8, 9, 10 min (`1`=11, `2`=12, `3`=13, `0`=10). Default: 4 min |
| `D` | Debug mode (1 s = 1 min) |
| `P` | Back to normal mode |

The numbers turn red once the selected time limit is reached.

## Files

- `index.html` – the whole timer (HTML, CSS, JS, embedded logo)
- `timer/index.html` – redirect to the root, keeps old links working

## Hosting

Static page, no build step. Works with GitHub Pages.

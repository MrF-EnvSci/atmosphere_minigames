
# Atmosphere Mini‑Games & Virtual Labs

Interactive simulations for Environmental Science (air pressure vs. altitude; airplane cabin pressurization). Ready for GitHub Pages + Canvas embedding.

## Files
- `index.html` — Landing page with embedded mini‑game and Canvas instructions
- `Altitude_Pressure_Virtual_Lab.html` — Full self‑contained simulation (balloon + airplane)

## Quick Start (GitHub Pages)
1. Push these files to your repository (e.g., `MrF-EnvSci/atmosphere_minigames`).
2. In your repo: **Settings → Pages → Build and deployment → Source = Deploy from a branch**.
3. Set **Branch = main**, **Folder = / (root)**, then **Save**.
4. After Pages builds, your site will be live at:
   ```
   https://YOUR_GITHUB_USERNAME.github.io/atmosphere_minigames/
   ```

## Embed in Canvas
Paste this into a Canvas Page (HTML Editor):
```html
<iframe src="https://YOUR_GITHUB_USERNAME.github.io/atmosphere_minigames/Altitude_Pressure_Virtual_Lab.html"
        title="Altitude &amp; Pressure Lab" width="100%" height="740"
        style="border:1px solid #e2e8f0;border-radius:10px" allowfullscreen loading="lazy"></iframe>
```

## Teacher Prompts
Use the prompts on `index.html` under “Teacher Prompts” or adapt them for your assignment.

## Notes
- The physics model is intentionally simplified (exponential barometric pressure). It is accurate enough for conceptual learning.
- All assets are inline (no external JS/CSS). Works well inside Canvas iframed or as a standalone page.

## License
Consider adding a license if you’d like others to reuse/modify the mini‑game (e.g., MIT).

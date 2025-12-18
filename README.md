# Starship Sheet Module

This Foundry VTT module packages the Starship PDF sheet for quick access.

## Installation

1. Create a GitHub repository named `starship-sheet-module` and upload the module folder contents to the `main` branch.
2. In Foundry VTT, go to Add-on Modules → Install Module.
3. Paste the manifest URL:
   `https://raw.githubusercontent.com/Samuel/starship-sheet-module/main/module.json`
4. Install and then enable the module in Manage Modules for your world.

## Files included

- `module.json` — module manifest (manifest URL above)
- `scripts/open-pdf.js` — adds a UI button to open the PDF
- `styles/module.css` — minimal styling
- `templates/starship-sheet.html` — optional HTML viewer
- `assets/Sheet - Starship.pdf` — the PDF sheet

## Notes

- If you change the repository name or GitHub username, update the `manifest` and `download` URLs in `module.json`.
- Adjust `minimumCoreVersion` to match your Foundry core version if needed.

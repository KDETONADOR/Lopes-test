# Lopes Tile Guy Corp — GitHub Pages Site

Static website with a bilingual (English/Portuguese) tile installation labor estimate calculator.

## Files

- `index.html` — website structure
- `styles.css` — Lopes Tile Guy dark / gold / white theme
- `script.js` — language switch + calculator
- `.nojekyll` — keeps GitHub Pages simple for this static site

## Publish on GitHub Pages

1. Create a new GitHub repository, for example `lopes-tile-guy`.
2. Upload the files from this folder to the root of the repository.
3. Open the repository on GitHub.
4. Go to **Settings → Pages**.
5. Under **Build and deployment**, choose:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/(root)**
6. Save.
7. GitHub will display the public Pages URL after deployment.

## Custom domain later

If you want to connect `lopestileguycorp.com` to GitHub Pages, configure the custom domain inside **Settings → Pages** and update the DNS records at the domain provider. Do not add a `CNAME` file until the domain is ready to point to this repository.

## Calculator rules currently used

- Basic floor tile: $8.50/sq ft
- Porcelain / Large Format: $12.50/sq ft
- Shower Walls: $20.00/sq ft
- Mosaic: $22.00/sq ft
- Glass Tile: $18.00/sq ft
- Marble Tile: $19.00/sq ft
- Surface prep:
  - Basic: $1.50/sq ft, $150 minimum
  - Standard: $3.00/sq ft, $150 minimum
  - Heavy: $5.00/sq ft, $150 minimum
- Waterproofing: +$3.50/sq ft
- Demolition: +$3.50/sq ft
- Floor leveling: +$2.50/sq ft
- Herringbone / diagonal: +25% of installation
- Niche: +$250
- Schluter trim: +$150
- Material pickup: +$125
- Travel: first 10 miles included; +$2/mile after 10
- Materials are optional and stay separate from labor.

## Existing logo

This package uses a text wordmark and a simple geometric tile mark so the website works immediately without depending on an external image file. To use the exact Lopes Tile Guy logo, add your logo image to the repository and replace the `.brand-mark` / `.brand-text` area in `index.html`.

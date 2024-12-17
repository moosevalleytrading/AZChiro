# Hansen Chiropractic SEO Dashboard

This repository contains a static SEO dashboard for Hansen Chiropractic, built for GitHub Pages hosting. It includes:

- A homepage dashboard with SEO metrics
- Content calendar overview
- Site copy analysis
- Keyword research insights

## File Structure

seo-dashboard/ ├── index.html ├── pages/ │ ├── content-calendar.html │ ├── site-copy.html │ └── keyword-research.html ├── assets/ │ ├── css/ │ │ ├── styles.css │ │ └── components/ │ │ ├── dashboard.css │ │ ├── calendar.css │ │ └── tables.css │ ├── js/ │ │ ├── main.js │ │ └── components/ │ │ ├── charts.js │ │ ├── calendar.js │ │ └── tables.js │ └── images/ │ ├── icons/ │ └── branding/ ├── data/ │ ├── keywords.json │ ├── content-calendar.json │ ├── site-copy.json │ ├── pages.json │ ├── metrics.json └── README.md

## How to Use

1. **Hosting**: Push this repo to GitHub. In your repository settings, enable GitHub Pages from the `main` branch.
2. **Data Updates**: Update the JSON files in `data/` as needed.
3. **Customization**: Modify CSS/JS to fit your branding and functionality needs.

## GitHub Pages Deployment

1. Go to repository Settings > Pages
2. Set source branch to `main`
3. Set folder to `/ (root)`
4. Save the settings
5. Access your site at `https://[username].github.io/AZChiro`

### Important Notes

- All paths in HTML files use relative paths (starting with `./`)
- JSON data files must be committed to the repository
- The site uses client-side JavaScript to fetch and display data
- CORS must be properly configured if fetching external data

## Built With

- **Tailwind CSS** for responsive layout
- **Chart.js** for data visualization (if used)
- **Vanilla JS** for data loading and manipulation
- **JSON** for structured data storage

## License

This project is provided for demonstration purposes by Carson Cruz for ComCreate LLC.

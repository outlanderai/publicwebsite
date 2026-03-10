# Outerland Website

A modern, professional static website for Outerland - a boutique advisory firm helping organizations navigate complex transformations in regulated environments.

## Features

- Modern, responsive design inspired by clean, professional aesthetics
- AI-Powered Process Intelligence showcase
- Comprehensive service offerings and engagement models
- Optimized for GitHub Pages deployment
- Mobile-friendly and accessible

## Deployment

This website is automatically deployed to GitHub Pages via GitHub Actions whenever changes are pushed to the main branch.

### Setup Instructions

1. **Enable GitHub Pages**:
   - Go to your repository settings
   - Navigate to "Pages" section
   - Under "Build and deployment", select "GitHub Actions" as the source

2. **Push to Deploy**:
   ```bash
   git add .
   git commit -m "Initial website deployment"
   git push origin main
   ```

3. The site will be available at: `https://outlanderai.github.io/publicwebsite/`

## Local Development

To view the website locally, simply open `index.html` in a web browser, or use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve
```

Then navigate to `http://localhost:8000` in your browser.

## Structure

```
.
├── index.html          # Main website file
├── styles.css          # Stylesheet
├── script.js           # JavaScript functionality
├── .github/
│   └── workflows/
│       └── deploy.yml  # GitHub Actions deployment workflow
└── README.md          # This file
```

## Contact

For inquiries: steve@outerland.ai

## License

© 2026 Outerland. All rights reserved.

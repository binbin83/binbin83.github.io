# Robin Quillivic - Academic Website

Source code for Robin Quillivic's academic website, built with [Quarto](https://quarto.org).

## Setup

### Prerequisites
- [Quarto](https://quarto.org/docs/get-started/)
- [Git](https://git-scm.com/)

### Build and Preview
```bash
# Preview locally
quarto preview

# Render the site
quarto render
```

### Deploy to GitHub Pages
1. Go to repository Settings > Pages
2. Set Source to "Deploy from a branch"
3. Choose `main` branch and `docs` folder
4. Save

Site URL: `https://binbin83.github.io`

## File Structure

```
├── _quarto.yml          # Site configuration
├── index.qmd            # Homepage
├── publications.qmd     # Publications page
├── projects.qmd         # Projects page
├── contact.qmd          # Contact page
├── 404.qmd              # Error page
├── custom.scss           # Custom styling
├── robots.txt            # SEO configuration
└── files/
    └── images/
        └── robin_website.jpeg
```

## Customization

- Edit `.qmd` files to update content
- Modify `custom.scss` for styling (colors, fonts, layout)
- Update `_quarto.yml` for site configuration and navigation

### Academic Icons

- `{{< ai doi >}}` for DOI
- `{{< ai orcid >}}` for ORCID
- `{{< ai google-scholar >}}` for Google Scholar
- `{{< ai hal >}}` for HAL

## Contact

Robin Quillivic - robin.quillivic@cnrs.fr

## License

MIT License

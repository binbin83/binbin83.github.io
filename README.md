# Robin Quillivic - Academic Website

This is the source code for Robin Quillivic's academic website, built with [Quarto](https://quarto.org).

## Quick Setup Guide

### 1. Prerequisites
- Install [Quarto](https://quarto.org/docs/get-started/)
- Install [Git](https://git-scm.com/)
- Create a [GitHub](https://github.com) account

### 2. Setup Repository
1. Create a new repository named `yourusername.github.io` (replace with your GitHub username)
2. Clone this repository to your local machine
3. Upload all files to your repository

### 3. Customize Content
- Replace `files/images/profile.jpg` with your photo
- Update `_quarto.yml` with your information
- Modify content in all `.qmd` files to reflect your experience
- Update social media links and contact information

### 4. Deploy to GitHub Pages
1. Go to your repository Settings
2. Navigate to Pages (under Code and automation)
3. Set Source to "Deploy from a branch"
4. Choose `main` branch and `docs` folder
5. Save settings

### 5. Build and Preview
```bash
# Preview locally
quarto preview

# Render the site
quarto render
```

Your site will be available at `https://yourusername.github.io`

## File Structure

```
├── _quarto.yml          # Site configuration
├── index.qmd           # Homepage
├── publications.qmd    # Publications page
├── projects.qmd        # Projects page
├── teaching.qmd        # Teaching page
├── cv.qmd             # CV page
├── contact.qmd        # Contact page
├── custom.scss        # Custom styling
├── styles.css         # Additional CSS
├── 404.qmd           # Error page
└── files/            # Images and documents
    └── images/
        └── profile.jpg
```

## Customization Tips

### Adding Publications
Edit `publications.qmd` and add new entries following the existing format.

### Adding Projects
Edit `projects.qmd` and create new project sections.

### Styling Changes
- Modify `custom.scss` for major styling changes
- Use `styles.css` for minor adjustments
- Colors and fonts are defined in `custom.scss`

### Adding Pages
1. Create a new `.qmd` file
2. Add it to the navbar in `_quarto.yml`
3. Link to it from other pages as needed

## Academic Icons

This template supports academic icons. Examples:
- `{{< ai doi >}}` for DOI icon
- `{{< ai orcid >}}` for ORCID icon
- `{{< ai google-scholar >}}` for Google Scholar icon
- `{{< ai hal >}}` for HAL icon

## Updating Content

### Regular Updates
- Add new publications to `publications.qmd`
- Update project status in `projects.qmd`
- Keep CV current in `cv.qmd`
- Add news items to homepage

### After Updates
```bash
quarto render
git add .
git commit -m "Update content"
git push
```

## Troubleshooting

### Site Not Displaying
- Check GitHub Pages settings
- Ensure `docs` folder is selected as source
- Wait 5-10 minutes for deployment

### Styling Issues
- Clear browser cache
- Check for CSS syntax errors
- Validate HTML output

### Build Errors
- Check Quarto installation
- Validate YAML syntax in headers
- Ensure all linked files exist

## Support

For technical issues with Quarto, see the [official documentation](https://quarto.org/docs/).

For questions about this template, contact Robin Quillivic at quillivicrobin@hotmail.fr.

## License

This template is available under MIT License. Feel free to use and modify for your own academic website.

---

Built with ❤️ and [Quarto](https://quarto.org)

# Elegant Academic Personal Website

A modern, elegant, and luxury-inspired personal academic website template designed to showcase your research, publications, and academic background.

## Features

- Responsive design with elegant typography and animations
- Luxury-inspired white and dark color scheme
- Organized sections for education, research focus, projects, and publications
- Modern UI with a focus on readability and visual hierarchy
- Smooth scrolling and navigation experience

## Getting Started

1. Replace `profile.jpg` with your own profile photo
2. Add a background image as `images/hero-bg.jpg` for the hero section
3. Update your personal information in `index.html`
4. Customize the research topics, projects, and publications to match your academic profile

## Customization

### Colors

The color scheme can be customized by editing the CSS variables in the `:root` section of the `styles.css` file:

```css
:root {
    --primary-dark: #1a1a1a;
    --secondary-dark: #333333;
    --accent-gold: #d4af37;
    --accent-soft: #e0c080;
    --text-dark: #1a1a1a;
    --text-light: #ffffff;
    --text-muted: #888888;
    --bg-white: #ffffff;
    --bg-light: #f8f8f8;
}
```

### Typography

The website uses three beautiful fonts from Google Fonts:
- Playfair Display: For headings and titles
- Cormorant Garamond: For elegant, serif text elements
- Montserrat: For body text

### Icons

This template uses Font Awesome icons. You can change them by updating the `<i>` elements with different Font Awesome classes.

## Structure

- `index.html` - Main HTML file
- `styles.css` - CSS styles
- `images/` - Directory for images
- `profile.jpg` - Your profile photo

## Browser Compatibility

This template works well in all modern browsers including:
- Chrome
- Firefox
- Safari
- Edge

## Deployment

This site is deployed from the [SiruiruiRen/academic-website](https://github.com/SiruiruiRen/academic-website) repository via GitHub Pages, publishing from the `main` branch (root).

Because the repository is **not** named `<username>.github.io`, GitHub Pages serves it under a project subpath rather than at the domain root:

**Live site:** https://siruiruiren.github.io/academic-website/

`sitemap.xml` and `robots.txt` are already configured to point at this URL — if the repository is ever renamed or moved to a `<username>.github.io` repo (serving at the domain root instead), update both files' base URL to match.

### Making updates

1. Edit the HTML/CSS files locally
2. Commit and push to `main`:
```
git add <changed files>
git commit -m "Describe the change"
git push origin main
```
3. GitHub Pages rebuilds automatically within a minute or two

### Enabling Pages on a fresh clone

If setting this up on a new repository from scratch:
1. Push the repository to GitHub
2. Go to the repository's "Settings" → "Pages"
3. Under "Source", select the `main` branch (root)
4. Click "Save" — the site will be live shortly at the URL GitHub shows on that page

## Need Help?

If you encounter any issues with the deployment, please consult GitHub's documentation on GitHub Pages:
https://docs.github.com/en/pages 
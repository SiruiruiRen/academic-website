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

## Deployment Instructions

### 1. Create a New GitHub Repository

1. Go to [GitHub](https://github.com/) and sign in to your account
2. Click the "+" icon in the top right corner and select "New repository"
3. Name your repository exactly: `siruiruiren.github.io` (replace "siruiruiren" with your GitHub username)
4. Make sure the repository is set to "Public"
5. Click "Create repository"

### 2. Upload the Website Files

Once your repository is created, you need to upload these website files:

#### Option 1: Upload via GitHub Web Interface
1. In your new repository, click "Add file" → "Upload files"
2. Drag and drop all the files from this folder or click to browse and select them
3. Click "Commit changes"

#### Option 2: Upload via Git Command Line
1. Open Terminal/Command Prompt
2. Navigate to the folder containing these website files
3. Run the following commands:
```
git init
git add .
git commit -m "Initial website setup"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_USERNAME.github.io.git
git push -u origin main
```
(Replace YOUR_USERNAME with your actual GitHub username)

### 3. Add Your Profile Photo

1. Add a photo named `profile.jpg` to your repository
2. This should be a professional headshot or portrait photo
3. Ideally, use a square photo with dimensions of at least 500x500 pixels

### 4. Enable GitHub Pages

1. In your repository, go to "Settings" (tab at the top)
2. Scroll down to the "GitHub Pages" section
3. Under "Source", select "main" branch
4. Click "Save"

### 5. Check Your Website

After a few minutes, your website should be live at:
`https://YOUR_USERNAME.github.io` (replace YOUR_USERNAME with your GitHub username)

## Need Help?

If you encounter any issues with the deployment, please consult GitHub's documentation on GitHub Pages:
https://docs.github.com/en/pages 
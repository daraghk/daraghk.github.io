# Personal Academic Website

This is a personal academic website built for GitHub Pages.

## Setup Instructions

### 1. Customize Your Content

Edit the following files to add your information:

- `index.html` - Update your name, position, affiliation, research interests, and contact info
- `publications.html` - Add your publications with links to PDFs and DOIs
- Replace or add `profile.jpg` with your photo (180x180px recommended)

### 2. Deploy to GitHub Pages

#### Option A: Using GitHub Username Site (recommended)
1. Create a new repository named `username.github.io` (replace `username` with your GitHub username)
2. Push this code to the repository
3. Your site will be available at `https://username.github.io`

#### Option B: Using Project Site
1. Create a repository with any name (e.g., `personal-website`)
2. Push this code to the repository
3. Go to repository Settings → Pages
4. Under "Source", select the branch (usually `main`) and click Save
5. Your site will be available at `https://username.github.io/repository-name`

### 3. Git Commands to Deploy

```bash
# Initialize git (if not already done)
git init

# Add all files
git add .

# Commit your changes
git commit -m "Initial commit: Academic website"

# Add your GitHub repository as remote
git remote add origin https://github.com/username/repository-name.git

# Push to GitHub
git push -u origin main
```

## Customization Tips

### Adding a Profile Photo
- Add a file named `profile.jpg` in the root directory
- Recommended size: 180x180px or larger (square aspect ratio)
- Supported formats: JPG, PNG

### Changing Colors
- Edit `style.css` to change the color scheme
- Main colors are defined in the CSS (purple gradient, blue accents)
- Search for color hex codes like `#667eea` to modify

### Adding More Sections
- Copy the `<section>` structure from `index.html`
- Add a corresponding link in the navigation

### Adding a Custom Domain
1. Buy a domain name
2. Add a file named `CNAME` with your domain (e.g., `www.yourname.com`)
3. Configure DNS settings with your domain provider

## Files Overview

- `index.html` - Main homepage with about, research, publications, teaching, contact
- `publications.html` - Complete publications list
- `style.css` - All styling and responsive design
- `README.md` - This file with instructions

## License

Feel free to use this template for your own academic website!

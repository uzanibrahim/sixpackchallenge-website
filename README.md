# 6Pack Crunch Challenge - Website

A simple, modern landing page for the 6Pack Crunch Challenge iOS app.

## Structure

```
sixpackchallenge-website/
├── index.html          # Main landing page
├── privacy.html        # Privacy Policy page
├── styles.css          # All styles
├── script.js           # JavaScript interactions
├── assets/             # Images and icons
│   └── icon.png        # App icon
└── _headers            # Cloudflare headers config
```

## Cloudflare Pages Deployment

### Option 1: Direct Upload

1. Go to [Cloudflare Pages](https://pages.cloudflare.com/)
2. Create a new project
3. Choose "Upload assets"
4. Upload the entire `sixpackchallenge-website` folder
5. Your site will be live at `your-project.pages.dev`

### Option 2: Git Integration

1. Push this folder to a GitHub/GitLab repository
2. Connect the repository to Cloudflare Pages
3. Configure build settings:
   - **Build command:** (leave empty - no build needed)
   - **Build output directory:** `/` or `.`
4. Deploy!

## Custom Domain

To use a custom domain:

1. Go to your Cloudflare Pages project
2. Navigate to "Custom domains"
3. Add your domain (e.g., `sixpackcrunch.app`)
4. Update DNS records as instructed

## Features

- ✅ Fully responsive design
- ✅ Modern dark theme with orange accent
- ✅ Smooth animations
- ✅ SEO optimized
- ✅ Apple Store ready Privacy Policy
- ✅ Fast loading (no build step needed)

## Notes

- Replace `assets/icon.png` with your actual app icon
- Update App Store link when available
- The site uses Google Fonts (Inter) - loads automatically

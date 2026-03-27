# Filmed by Jaymes — Portfolio Website

**Live site:** [filmedbyjaymes.com](https://filmedbyjaymes.com)

## Setup

### 1. Add your photo
Place your headshot in the `images/` folder named exactly:
```
images/jaymes.jpg
```
The image will appear in both the hero section (darkened background) and the About section.

### 2. Deploy to GitHub Pages
1. Push this folder to a GitHub repository
2. Go to **Settings → Pages**
3. Set source to **main branch / root**
4. Point your custom domain (`filmedbyjaymes.com`) to GitHub Pages

### 3. Add video links
In `index.html`, update the work grid items with your actual YouTube video IDs:
```html
<!-- Replace the href with your specific video URLs -->
<a href="https://youtu.be/YOUR_VIDEO_ID" ...>
```

### 4. Update portfolio thumbnails (optional)
Add real video thumbnails to the `images/` folder and reference them in the work grid:
```html
<img src="images/wedding-thumbnail.jpg" alt="..." class="work-thumb" />
```

## File Structure
```
filmedbyjaymes/
├── index.html        ← Main website (single file, everything included)
├── images/
│   └── jaymes.jpg    ← ADD YOUR PHOTO HERE
└── README.md
```

## Customization

- **Colors:** All in CSS `:root` variables at the top of `<style>`
- **Services:** Edit the three `.service-card` blocks
- **Clients:** Edit the `.clients-grid` section
- **Contact info:** Search for `filmedbyjaymes@gmail.com` and `714-499-6088`
- **Social links:** Update Instagram and YouTube URLs in the Work and Contact sections

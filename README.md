# StudioTenwu GitHub Pages

Simple, elegant placeholder website for StudioTenwu organization.

## Features

- 🎨 Modern gradient design
- ✨ Floating particle animation
- 📱 Fully responsive (mobile-friendly)
- 🚀 Lightweight (single HTML file, no dependencies)
- 💫 Smooth animations and effects

## Quick Setup

### Deploy to GitHub Pages

1. **Create a new repository** named `studiotenwu.github.io` (or `[your-org-name].github.io`)

2. **Upload the files**:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: StudioTenwu placeholder site"
   git branch -M main
   git remote add origin https://github.com/StudioTenwu/studiotenwu.github.io.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**:
   - Go to repository Settings → Pages
   - Source: Deploy from branch `main`
   - Folder: `/ (root)`
   - Save

4. **Visit your site** at `https://studiotenwu.github.io` (may take a few minutes to deploy)

## Customization

### Change Colors

Edit the gradient in `index.html` (line 16-18):

```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

Try these alternatives:
- Ocean: `#2E3192 0%, #1BFFFF 100%`
- Sunset: `#FF6B6B 0%, #FFE66D 100%`
- Forest: `#134E5E 0%, #71B280 100%`

### Update Content

- **Logo/Name** (line 113): Change `StudioTenwu`
- **Tagline** (line 114): Change `Creating Something Amazing`
- **Status** (line 116): Change `Coming Soon`
- **Links** (line 120-122): Update GitHub and contact links

### Add More Links

Duplicate and modify the social links section:

```html
<a href="https://twitter.com/studiotenwu" target="_blank">Twitter</a>
<a href="https://linkedin.com/company/studiotenwu" target="_blank">LinkedIn</a>
```

## File Structure

```
studiotenwu-gh-pages/
├── index.html          # Main website file
└── README.md          # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## License

Free to use and modify for your organization.

---

Built with ❤️ for StudioTenwu

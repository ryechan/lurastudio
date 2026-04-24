# Lura Studio — Website

Static website for Lura Studio, a home staging and interior styling company based in Oakland, CA.

## Structure

```
lura-studio/
├── index.html        # Main page
├── css/
│   └── style.css     # All styles
├── js/
│   └── main.js       # Scroll animations
└── images/           # Add your photos here
```

## Getting started

No build tools needed — open `index.html` directly in a browser, or serve with any static host.

```bash
# Quick local server (Python)
python3 -m http.server 3000

# Or with Node
npx serve .
```

## Customisation

- **Colors**: Edit CSS variables at the top of `style.css` under `:root`
- **Fonts**: Loaded from Google Fonts — swap in `<head>` of `index.html`
- **Content**: Edit text directly in `index.html`
- **Images**: Place photos in `/images` and reference them in `style.css` as `background-image: url('../images/your-photo.jpg')`

## Deployment

Drop the folder into any static hosting service:
- [Netlify](https://netlify.com) — drag and drop the folder
- [Vercel](https://vercel.com) — `vercel deploy`
- [GitHub Pages](https://pages.github.com)

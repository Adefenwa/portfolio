# Damilola Priscilla — Virtual Assistant Portfolio

A clean, responsive portfolio website for a Virtual Assistant.

## Project Structure

```
portfolio/
├── index.html    ← Main HTML (structure & content)
├── style.css     ← All styles (separated from HTML)
└── README.md     ← This file
```

## Getting Started

No build tools needed. Just open `index.html` in any browser.

```bash
# Option 1: Open directly
open index.html

# Option 2: Serve locally (recommended for development)
npx serve .
# or
python3 -m http.server 3000
```

## Customisation Checklist

Before publishing, update the following in `index.html`:

- [ ] **Email address** — replace `your@email.com` with your real email (appears in 2 places: hero & contact section)
- [ ] **Phone number** — `+234 902 593 6252` in the hero and contact sections
- [ ] **LinkedIn URL** — already set to `linkedin.com/in/damilola-osifuye`

## Colour Palette

All colours are defined as CSS variables in `style.css` under `:root`:

| Variable       | Value     | Usage                  |
|----------------|-----------|------------------------|
| `--navy`       | `#1a3a5c` | Primary dark colour    |
| `--teal`       | `#0d7377` | Accent / highlights    |
| `--goldbright` | `#f0c040` | Gold accent            |
| `--cream`      | `#faf9f6` | Page background        |
| `--sky`        | `#eaf4fb` | Light blue backgrounds |

## Deployment

The site is static HTML/CSS — deploy anywhere:

- **Netlify**: Drag & drop the folder at netlify.com/drop
- **GitHub Pages**: Push to a repo and enable Pages in settings
- **Vercel**: `vercel --prod` from the project folder
- **Shared hosting**: Upload files via FTP/cPanel

## Fonts

Loaded from Google Fonts (requires internet connection):
- **Cormorant Garamond** — headings / display text
- **Jost** — body text and UI elements

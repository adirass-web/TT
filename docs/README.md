# Think Tank — Internal Strategy

A static website for internal strategy documentation: Sovereign Defense Realism & Tech-First Power.

## Quick Start

Open `dist/index.html` in any browser — no build step required.

## Production Files

```
dist/
├── index.html    # Complete single-page site
└── styles.css    # Production-optimized CSS (no CDN dependencies)
```

**Deploy the `dist/` folder contents to any static hosting.**

## Features

- **Dark theme** with near-white text on deep navy background
- **3-color palette**: Navy (#0b1220), Sky Blue (#38bdf8), Semantic colors
- **Collapsible sections** for each major content area
- **Responsive hamburger menu** for mobile navigation
- **Swipe gestures** on mobile (swipe right from edge to open, left to close)
- **Production CSS** — no Tailwind CDN, optimized and self-contained
- **Google Fonts**: Outfit (display) + Source Sans 3 (body)
- **Lucide Icons** via CDN (lightweight, tree-shakeable)
- **Print-friendly** styles included

## Deployment

### GitHub Pages

1. Copy the contents of `dist/` to your repository root (or use a `/docs` folder)
2. Go to **Settings → Pages**
3. Under "Source", select **Deploy from a branch**
4. Choose `main` branch and the folder containing your files
5. Click **Save**

### Render Static Site

1. Push this repository to GitHub/GitLab
2. Go to [Render Dashboard](https://dashboard.render.com/)
3. Click **New → Static Site**
4. Connect your repository
5. Configure:
   - **Build Command**: (leave empty)
   - **Publish Directory**: `dist`
6. Click **Create Static Site**

### Netlify

1. Drag and drop the `dist` folder to [Netlify Drop](https://app.netlify.com/drop)
2. Or connect via Git with publish directory set to `dist`

### Vercel

1. Import your repository
2. Set **Output Directory** to `dist`
3. Deploy

## Content Structure

1. **Strategic Doctrine** — Core thesis, premises, operating constraints
2. **Leadership & Roles** — D.A. (Chair), Dr. T.L. (Lead Expert), operating rhythm, expertise-to-campaign mapping
3. **Research Programs** — Six programs with campaign quarter tags showing roadmap alignment
4. **24-Month Roadmap** — Year 1 (Shock & Position-Locking) + Year 2 (Consolidation & Brokerage) with Dr. T.L. expertise applied
5. **Operations** — Media seeding workflow, donor logic, contribution tiers
6. **Impact Metrics** — Power signals, influence indicators

## Responsive Breakpoints

- **Mobile**: < 640px — Single column, hamburger menu, touch gestures
- **Tablet**: 640px–1023px — Enhanced spacing, visible section descriptions
- **Desktop**: ≥ 1024px — Two-column grids, full navigation

## Browser Support

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+
- Mobile Safari / Chrome for iOS and Android

## Accessibility

- Semantic HTML structure
- Keyboard navigation support (Escape to close menu)
- ARIA labels on interactive elements
- Sufficient color contrast ratios
- Focusable interactive elements

---

**Internal document** • Built for high-friction agenda setting and sovereign-state defense realism

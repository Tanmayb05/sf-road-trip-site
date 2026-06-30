# SF Road Trip Site — Quick Start

## Overview
Static HTML/CSS site. No build tools, no dependencies. Just open `index.html` in a browser.

## Getting Started

### 1. Open in Browser
```bash
open index.html
# or
cd /path/to/sf-road-trip-site
open index.html
```

### 2. Local Development Server (Optional)
If you want live reload during edits:
```bash
# Python 3
python3 -m http.server 8000

# Node.js
npx http-server
```
Then visit `http://localhost:8000`

### 3. File Structure
```
sf-road-trip-site/
├── index.html          # All 10 sections
├── styles.css          # Design tokens & layout
├── images/             # Hero bg, accommodation photos, etc.
├── docs/
│   ├── MILESTONES.md   # Project phases & deliverables
│   └── STARTUP.md      # This file
```

## Current Status

**Milestone 1: Site Skeleton** — In progress
- ✅ HTML structure complete (all 10 sections)
- ✅ CSS design tokens & mobile-first grid
- ⏳ Content & styling refinements

### Sections
1. **Sticky Nav** — Navigation links + date/people info
2. **Hero** — Title, subtitle, date pill, 6 people chips
3. **Route Strip** — SF→SJ→Redwoods→Big Sur→Monterey→Carmel→SF nodes
4. **Itinerary** — 5-day cards + Google Maps embed
5. **Accommodation** — 5 stay cards with photos & confirmation details
6. **Flights** — 6 person accordions (vanilla JS)
7. **Places to Explore** — 3 tabbed regions with place entries
8. **Weather** — Fog advisory banner + live forecast link
9. **Photo Gallery** — Placeholder boxes (real photos after Jul 13)
10. **Footer** — Quote, trip name, people list

## Design Tokens
- **Background:** `#FAF7F2` (warm off-white)
- **Primary:** `#1B2A4A` (deep navy)
- **Accent:** `#C0603A` (terracotta)
- **Secondary:** `#4A9B8E` (soft teal)
- **Cards:** white, `border-radius: 12px`, shadow `0 2px 12px rgba(0,0,0,0.08)`
- **Typography:** Georgia (headings), system-ui (body)
- **Mobile Base:** 375px

## Next Steps

1. **Refine styling** — polish card layouts, spacing, responsiveness
2. **Add JS interactions** — flights accordion, scroll-spy nav, tab switching (Milestone 2)
3. **Gallery & meta** — lightbox, OG tags, favicon, QA (Milestone 3)

## Testing

### Visual Check
- [ ] Open in Chrome, Safari, Firefox
- [ ] Test on mobile (375px min width)
- [ ] All sections visible without horizontal scroll
- [ ] No console errors

### Responsive
- [ ] Mobile (375px)
- [ ] Tablet (768px)
- [ ] Desktop (1024px+)

### Links
- [ ] All nav links scroll to correct sections
- [ ] External links open in new tab (`target="_blank"`)

## Useful Commands

```bash
# View in browser
open index.html

# Start local server
python3 -m http.server 8000

# Check for broken links (macOS)
linkchecker index.html
```

---

See [docs/MILESTONES.md](docs/MILESTONES.md) for full phase deliverables.

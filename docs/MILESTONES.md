# SF Road Trip Site — Milestones

## Milestone 1 · Site Skeleton
*Full HTML/CSS skeleton with all sections stubbed, correct structure, zero real content gaps.*

### Deliverables
- `index.html` — all 10 sections present with correct semantic markup
- `styles.css` — design tokens (colors, typography, spacing), layout grid, mobile-first breakpoints

### Sections to scaffold (all with real data, no lorem)
1. **Sticky Nav** — links to all sections, "Jul 9–13, 2026 · 6 Friends" right side
2. **Hero** — bg image, dark overlay, title, subtitle, date pill, 6 people chips
3. **Route Strip** — node/connector strip SF→SJ→Redwoods→Big Sur→Monterey→Carmel→SF with dates; 4 stats pills
4. **Itinerary** — 5 day cards (Day 0–4) left column + Google Maps embed iframe right column; all bullet points populated
5. **Accommodation** — 5 stay cards (Night -1 through Night 3) with photos, address, check-in/out, confirmation inside `<details>`
6. **Flights** — 6 person accordions (vanilla JS); boarding-pass two-column layout; Dhyey shows TBD
7. **Places to Explore** — 3 tabbed/collapsible regions, all place entries listed
8. **Weather** — fog advisory banner + live forecast link
9. **Photo Gallery** — 6 placeholder boxes, `📸` + "Photos after Jul 13"
10. **Footer** — quote, trip name, people list

### Design tokens (from image references)
- Background: `#FAF7F2` (warm off-white)
- Primary: `#1B2A4A` (deep navy)
- Accent: `#C0603A` (terracotta)
- Secondary: `#4A9B8E` (soft teal)
- Cards: white, `border-radius: 12px`, `box-shadow: 0 2px 12px rgba(0,0,0,0.08)`
- Headings: Georgia/serif; Body: system-ui/sans-serif
- Mobile-first, 375px base

---

## Milestone 2 · Polish & Interactions
*All JS interactions wired, visual refinements, responsive desktop layout.*

### Deliverables
- Flights accordion: smooth expand/collapse, chevron rotation
- Day cards: active state highlight, scroll-spy on nav
- Route Strip: animated connector line on load (CSS keyframe)
- Accommodation cards: image hover zoom (CSS transform)
- Places tabs: keyboard-accessible tab switching
- Desktop 2-col layout for Itinerary (cards left, map right)
- Accommodation horizontal scroll on mobile → 2-col grid on desktop
- Print stylesheet: clean single-column for printing itinerary

---

## Milestone 3 · Photo Gallery & Final QA
*Gallery ready for real photos post-trip; cross-browser/device QA pass.*

### Deliverables
- Photo gallery: replace placeholder grid with lightbox (vanilla JS, no lib) — click image → fullscreen overlay with arrow nav
- Gallery: lazy-load images (`loading="lazy"`)
- Add `<meta>` tags: OG image, description, title for share links
- Favicon (emoji fallback `<link rel="icon">` with 🌉)
- Test on iOS Safari, Chrome Android, Firefox desktop
- Validate all external links open `target="_blank" rel="noopener"`
- Confirm all confirmation numbers inside `<details>` are hidden by default
- Lighthouse mobile score ≥ 90 performance, 100 accessibility

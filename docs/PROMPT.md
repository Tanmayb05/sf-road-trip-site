# Trip Site — SF Road Trip: Build Prompt

## Context

6 friends road trip **Jul 9–13, 2026**. Route: **SF → San Jose → Henry Cowell Redwoods → Big Sur → Monterey → Carmel & 17 Mile Drive → SF**. All data from San Francisco.md. Images in `../images/` are for style/design reference only. Build mobile-first static site from scratch.

---

## IMPLEMENTATION PROMPT

```
Build mobile-first static trip website from scratch.

=== OUTPUT FILES ===
- sf-road-trip-site/index.html
- sf-road-trip-site/styles.css

=== DESIGN REFERENCE IMAGES ===
Images at ../images/obsidian/ show warm coastal aesthetic (warm off-white, deep navy, terracotta, soft teal).
Serif headings, sans-serif body. White cards, 12px rounded, subtle shadow. Sticky nav.
Use these for style inspiration only — DO NOT assume data matches images.

=== ACTUAL TRIP DATA ===
From San Francisco.md:
- Dates: Jul 9–13, 2026 (5 days)
- People: Tanmay, Tejas, Kinjal, Antara, Vaishnovi, Dhyey (6 people)
- Route: SF → San Jose → Henry Cowell Redwoods → Big Sur → Monterey → Carmel-by-the-Sea → 17 Mile Drive → SF

=== SECTIONS ===

--- 1. STICKY NAV ---
Links scroll-to: Overview · Itinerary · Stay · Flights · Places
Right: "Jul 9–13, 2026 · 6 Friends"

--- 2. HERO ---
Background: ../images/sf-website/sf-website-hero-road-trip.png (cover, dark 0.45 overlay)
Title: "San Francisco Road Trip"
Subtitle: "SF → San Jose → Henry Cowell Redwoods → Big Sur → Monterey → Carmel → 17 Mile Drive → SF"
Date pill: "Jul 9–13, 2026"
People chips: Tanmay · Tejas · Kinjal · Antara · Vaishnovi · Dhyey

--- 3. ROUTE STRIP ---
Connected node/icon strip with labels + dates:
  SF (Start Jul 9) → San Jose (Jul 9–10) → Henry Cowell (Jul 10) → Big Sur (Jul 10) → Monterey (Jul 10–11) → Carmel & 17 Mile (Jul 11) → SF (Jul 11–12 stay, depart Jul 13)
Stats: ~810 miles · 5 days · ~16h drive · 6 people

--- 4. ITINERARY AT A GLANCE ---
Left column: 5 day cards. Right: Google Maps embed.

**DAY 0 · Thu Jul 9 · Arrivals**
Image: ✈️ emoji placeholder
- Everyone flies into SFO
- Check-in: San Jose (Hyatt Place San Jose Airport)
- Depart: N/A
Map: https://www.google.com/maps/dir/San+Francisco+International+Airport/82+Karina+Ct,+San+Jose,+CA+95131/

**DAY 1 · Fri Jul 10 · Big Sur & Monterey**
Image: ../images/sf-website/sf-website-big-sur-bixby.png (reference)
- Depart San Jose early morning
- Henry Cowell Redwoods State Park: Redwood Grove Loop, Fremont Tree, observation deck (1–2 hrs)
- Drive to Big Sur: Bixby Bridge, Big Sur River Gorge, McWay Falls, Pfeiffer Beach (3–4 hrs exploring)
- Drive to Monterey (overnight)
Depart: ~7 hrs drive + exploration
Map: https://www.google.com/maps/dir/112+Giotto,+Irvine,+CA+92614,+USA/Big+Sur,+California/Bixby+Bridge/Point+Lobos+State+Natural+Reserve/

**DAY 2 · Sat Jul 11 · Carmel & 17 Mile Drive**
Image: ../images/sf-website/sf-website-monterey-carmel.png (reference)
- Point Lobos State Reserve: China Cove, Bird Island Trail, Cypress Grove (2–3 hrs)
- Carmel-by-the-Sea: beach, Ocean Ave shopping, galleries (1–2 hrs)
- 17 Mile Drive: Lone Cypress, Seal Rock, Bird Rock, Cypress Point (2–3 hrs)
- Drive back to SF (overnight at SF Airbnb)
Depart: ~3 hrs drive (Carmel → SF)
Map: https://www.google.com/maps/dir/Big+Sur,+California/Monterey,+California/Carmel-By-The-Sea,+California/17+Mile+Dr,+California/Golden+Gate+Bridge,+San+Francisco/

**DAY 3 · Sun Jul 12 · San Francisco**
Image: ../images/sf-website/sf-website-golden-gate-point-reyes.png (reference)
- Golden Gate Bridge walk
- Palace of Fine Arts
- Baker Beach / Marshall's Beach (GGB photos)
- Lombard Street (crooked street)
- Chinatown
- Twin Peaks
- Optional: Point Reyes Lighthouse (north of SF, scenic drive)
Depart: Local exploration, no drive time
Map: https://www.google.com/maps/dir/Golden+Gate+Bridge,+San+Francisco/Point+Reyes+Lighthouse,+Inverness,+CA/

**DAY 4 · Mon Jul 13 · Departure**
Image: ✈️ emoji placeholder
- Final morning in SF (free time)
- Drive to SFO (~30 min from SF)
- Return rental car
- Flights home
Depart: ~1 hr drive to SFO

Map embed iframe (full route):
https://www.google.com/maps/embed?pb=!1m28!1m12!1m3!1d1596922.4635838452!2d-122.85376!3d36.30000!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!4m13!3e0!4m5!1s0x80dcee9d0b8bd7d7:0x8da9c19db7a6ae8!2sIrvine%2C+CA!3m2!1d33.6846!2d-117.8265!4m5!1s0x80ea7edba653175f:0x1177ac30b99a9f4e!2sBig+Sur%2C+CA!3m2!1d36.2704!2d-121.8087!5e0!3m2!1sen!2sus!4v1718876543

--- 5. ACCOMMODATION ---
Timeline: 4 cards, each with night label pill, photo, property name, "All" or "Tejas only", address, check-in/out, confirmation, maps link.

**Night -1 · Wed Jul 8 → Thu Jul 9 · Tejas only**
Photo: ../images/obsidian/obsidian-sfo-trip-stay-night--1.png
Tejas Mama Mami's Place
325 Berry St Apt 425, San Francisco, CA
Check-in: Wed Jul 8 · Check-out: Thu Jul 9
Maps: https://maps.app.goo.gl/Ayk2yCrmamerKg3F7

**Night 0 · Thu Jul 9 → Fri Jul 10 · All**
Photo: ../images/obsidian/obsidian-sfo-trip-stay-night-0.png
Hyatt Place San Jose Airport
82 Karina Ct, San Jose, CA 95131
Check-in: Thu Jul 9 · Check-out: Fri Jul 10
Confirmation: 6398365658 · PIN: 8563
Room: Queen Room w/ Two Queen Beds + Sofa Bed
Maps: https://maps.app.goo.gl/V13nF8Hb6ukZnPeG7
Booking: https://www.booking.com/Share-4FaLn5I

**Night 1 · Fri Jul 10 → Sat Jul 11 · All**
Photo: ../images/obsidian/obsidian-sfo-trip-stay-night-1.png
Comfort Inn Marina on the Monterey Bay
140 Reservation Road, Marina, CA 93933
Check-in: Fri Jul 10 · Check-out: Sat Jul 11
Booking ref: 6981707640
Maps: https://maps.app.goo.gl/JSsf4twr3fE7nKpY7
Booking: https://www.booking.com/Share-KJAs9m

**Night 2 · Sat Jul 11 → Sun Jul 12 · All**
Photo: ../images/obsidian/obsidian-sfo-trip-stay-night-2.png
Airbnb — Room in San Francisco
700 Moscow Street, San Francisco, CA 94112
Check-in: Sat Jul 11, 3:00 PM · Check-out: Sun Jul 12, 11:00 AM
Confirmation: HMRJFRMSR9 · Keypad entry (instructions 48h before)
Host: Silming (Yingming Zhou) · Ground room w/ private bath (4 guests)
Maps: https://maps.app.goo.gl/4XFrVsdCxgGRyGPU6

**Night 3 · Sun Jul 12 → Mon Jul 13 · All**
Photo: ../images/obsidian/obsidian-sfo-trip-stay-night-3.png
HI Point Montara Lighthouse Hostel
8800 Cabrillo Hwy, Montara, CA 94037
Check-in: Sun Jul 12, 3:00 PM · Check-out: Mon Jul 13, 11:00 AM
Confirmation: HMR5CYF999 · Private Room Suite (5 guests, max 6)
Host: Aaron Richard Chaffee
⚠️ Note: 20 miles south of SF, 7 miles north of Half Moon Bay. Hidden driveway — approach from north.
Maps: https://maps.app.goo.gl/z4s1UNibx7N3ZMWZ7

--- 6. FLIGHTS ---
Per-person accordion. Click name → expand boarding-pass style (two columns: Outbound | Return).

Tanmay
Image: ../images/obsidian/obsidian-sfo-trip-flight-chatgpt-tanmay.png
Outbound (Wed Jul 8):
  CVG → DFW  AA 1713  11:19 AM → 12:45 PM (CDT)
  DFW → SFO  AA 2810  4:17 PM → 5:59 PM (PDT)
Return (Mon Jul 13):
  SFO → SNA  F9 3582  5:26 PM → 7:08 PM (PDT)

Tejas
Image: ../images/obsidian/obsidian-sfo-trip-flight-chatgpt-tejas.png
Outbound (Wed Jul 8):
  PHX → SFO  F9 1191  2:02 PM → 4:11 PM (PDT)
Return (Wed Jul 15, stays +2 days):
  SFO → PHX  F9 2538  7:08 PM → 9:18 PM (MST)

Kinjal
Image: ../images/obsidian/obsidian-sfo-trip-flight-chatgpt-kinjal.png
Outbound (Thu Jul 9):
  SEA → SFO  AS 590  8:42 PM → 10:55 PM (PDT)
Return (Mon Jul 13):
  SFO → SEA  AS 591  8:28 PM → 10:41 PM (PDT)

Antara
Image: ../images/obsidian/obsidian-sfo-trip-flight-chatgpt-antara.png
Outbound (Thu Jul 9):
  SNA → SFO  AS 3495  8:25 PM → 10:03 PM (PDT)
Return (Mon Jul 13):
  SFO → SNA  AS 3244  6:35 AM → 8:15 AM (PDT)

Vaishnovi
Image: ../images/obsidian/obsidian-sfo-trip-flight-chatgpt-vaish.png
Outbound (Thu Jul 9):
  BOS → SFO  DL 577  7:20 AM → 10:51 AM (PDT)
Return (Mon Jul 13):
  SFO → BOS  DL 1645  10:10 PM → 6:45 AM+1 (EDT)

Dhyey
No flight info provided. Show as TBD.

--- 7. PLACES TO EXPLORE ---
3 collapsible/tabbed regions: Big Sur & Coast | Monterey & Carmel | San Francisco

**Big Sur & Coast:**
- Henry Cowell Redwoods State Park — Redwood grove, Fremont Tree, observation deck, river trails — 1–2 hrs
- Bixby Bridge — Iconic arch bridge, photography stop — 30–45 min
- Big Sur River Gorge — Swimming (summer), multiple trails — 30–90 min
- Pfeiffer Big Sur State Park — Redwood walks, river trails, observation points — 1–3 hrs
- McWay Falls — Famous waterfall to beach, viewpoint trail — 30–45 min
- Pfeiffer Beach — Purple sand, Keyhole Rock, sunset views — 1 hr
- Partington Cove — Coastal tunnel hike — 45–60 min
- Garrapata State Park — Wildflowers, coastal cliffs, beach — 45–90 min
- Santa Cruz (optional) — Coastal town en route — variable
- Shark Fin Cove — Unique rock formation between Santa Cruz & Monterey — 30 min
- Restaurants: Big Sur Bakery, Big Sur Roadhouse, Cafe Kevah, Nepenthe

**Monterey & Carmel:**
- Point Lobos State Reserve — China Cove, Bird Island Trail, Sea Lion Point, Cypress Grove — 2–3 hrs
- Carmel-by-the-Sea — Beach, Ocean Ave shops, galleries, wine tasting, Carmel Mission — 1–2 hrs
- 17 Mile Drive — Lone Cypress, Seal Rock, Bird Rock, Pebble Beach, Cypress Point Lookout — 2–3 hrs
- Monterey Bay Aquarium — Major attraction, sea otters — 2–3 hrs
- Cannery Row — Historic district, shops, restaurants — 1 hr
- Old Fisherman's Wharf — Pier, sea lions, fishing boats — 1 hr
- Pacific Grove: Lovers Point Park (beach) — 30 min
- Optional: Whale watching (3–4 hrs from Carmel)
- Restaurants: Old Fisherman's Grotto, Rosine's Restaurant, Alvarado Street Brewery, La Bicyclette

**San Francisco:**
- Golden Gate Bridge Walk — Bay views, iconic landmark — 1–2 hrs
- Baker Beach — Best GGB photography spot — 45 min
- Marshall's Beach — Less crowded, excellent bridge view — 45 min
- Palace of Fine Arts — Rotunda, lagoon, architecture — 30 min
- Lands End Trail — Coastal hike, stunning views — 1.5 hrs
- Lombard Street — Crooked street — 20 min
- Fisherman's Wharf & Pier 39 — Sea lions, clam chowder — 1 hr
- Chinatown — Largest Chinese enclave outside Asia — 1 hr
- Twin Peaks — City panorama — 30 min
- Painted Ladies at Alamo Square — Victorian houses — 20 min
- Fort Point — Under GGB, military fort — 45 min
- Point Reyes Lighthouse — North of SF, scenic drive — 2–3 hrs round trip
- Alcatraz Island — Book weeks ahead — 3 hrs
- Neighborhoods: North Beach (Italian), Mission District (murals, food), Haight-Ashbury (hippie culture)
- Museums: California Academy of Sciences, Exploratorium, SFMOMA
- Restaurants: Tony's Pizza Napoletana, Blue Bottle Coffee, Scoma's, Fog Harbor Fish House

--- 8. WEATHER ---
"☁️ July in Big Sur, Monterey & SF = marine layer mornings (Karl the Fog), 55–65°F even in summer. Pack a jacket — it's colder than you think."
Link: "Check live forecast →" https://wttr.in/San+Francisco

--- 9. PHOTO GALLERY ---
"Trip Photos · Coming Soon"
Placeholder grid: 6 boxes, 3-col desktop / 2-col mobile
Each: aspect-ratio 4/3, light gray bg, centered 📸 + "Photos after Jul 13"

--- 10. FOOTER ---
Quote: "Good friends, great roads, and unforgettable views."
Trip: "San Francisco Road Trip • Jul 9–13, 2026"
People: Tanmay, Tejas, Kinjal, Antara, Vaishnovi, Dhyey

=== TECHNICAL CONSTRAINTS ===
- Pure HTML + CSS + vanilla JS. No frameworks, no build.
- Mobile-first. 375px viewport perfect.
- All external links: target="_blank" rel="noopener"
- Smooth scroll for nav (CSS: scroll-behavior: smooth)
- Flights accordion: vanilla JS toggle
- Confirmations/PINs: wrap in <details> tag for light privacy
- Image paths: ../images/filename.png (relative to index.html)
```

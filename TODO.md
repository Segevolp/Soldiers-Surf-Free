# Soldiers Surf Free — Landing Page TODO

A complete checklist of everything still missing or unfinished on the landing page,
broken down by section. Tackle in roughly the order shown for the biggest impact-per-minute.

---

## 🚨 Critical (won't work without these)

### Real URLs
- [ ] **Live website URL** — replace `href="#"` in the "Visit the live website" card (Try it section)
- [ ] **GitHub repo URL** — replace `href="#"` in the "GitHub repository" card
      (currently `Segevolp/Soldiers-Surf-Free` is implied but not linked)
- [ ] **Hero "Visit the website" button** — also points to `#try` instead of the real site
- [ ] **Each team member's GitHub link** — all four `href="#"` in the team cards

---

## 🎬 Media

### Demo video
- [ ] **`assets/demo.mp4`** — your demo video. The page already auto-detects it; just drop the file in.
- [ ] Optional: a poster image (`assets/demo-poster.jpg`) shown before play

### Manual screenshots (the dashed placeholder boxes)
- [ ] `assets/manual/soldier-dashboard.png` — main soldier screen
- [ ] `assets/manual/id-upload.png` — IDF card upload UI
- [ ] `assets/manual/reservation.png` — reservation screen
- [ ] `assets/manual/manager-console.png` — site-manager dashboard
- [ ] `assets/manual/malfunctions.png` — malfunction queue
- [ ] `assets/manual/site-policy.png` — policy editor
- [ ] `assets/manual/admin-dashboard.png` — admin dashboard
- [ ] `assets/manual/permissions.png` — permission tree
- [ ] `assets/manual/inventory.png` — inventory / lockers / items management

### Team photos (currently initials in colored circles)
- [ ] Photo of Ofek Yabo
- [ ] Photo of Dolev David
- [ ] Photo of Segev Olpak
- [ ] Photo of Guy Yehoshua
- [ ] Optional: photo of Gil Hurvitz (customer card)
- [ ] Optional: photo of Ido Aviv himself, somewhere meaningful
      (probably in the hero or a dedicated dedication strip)

---

## 📄 Documents (referenced as "coming soon" — drop into `/docs/`)

- [ ] **SRD** (Software Requirements Document)
- [ ] **TDD** (Technical Design Document)
- [ ] **Final report**
- [ ] **User survey results** (you have the *plan* but not results)
- [ ] **ARD** (mentioned in early decks but no standalone file uploaded)
- [ ] **Test report / coverage** PDF
- [ ] **Patent reference** for the IDF-card scanning OCR (mentioned as patented — link or PDF would be good)
- [ ] **Final presentation deck** (when you make it)

---

## 🎨 Polish & content

- [ ] **Real bios** for each team member (currently rough role descriptions — replace with what each of you actually did)
- [ ] **Real role split** — confirm the "Backend / Frontend / Hardware / QA" split I assumed; rename if wrong
- [ ] **LinkedIn links** for team members (worth adding next to GitHub/email)
- [ ] **Phone numbers** — already in your proposal; decide whether you want them on the public page (probably not)
- [ ] **A photo/portrait of Ido Aviv** in the dedication card instead of just text — would be very meaningful
- [ ] **Logo** — currently a generic wave SVG. A real Soldiers Surf Free logo would elevate the page
- [ ] **Favicon** — `favicon.ico` or `favicon.svg` referenced from `<head>` (currently missing)
- [ ] **Open Graph / social preview** — `<meta property="og:image">` etc.
      so the link previews nicely on WhatsApp/LinkedIn/Twitter
- [ ] **Hebrew translation toggle** — given the project's audience (IDF soldiers + Hebrew-speaking families),
      an EN/HE toggle would be powerful

---

## 🛠 Functionality (post-publish polish)

- [ ] **Mobile menu** — nav links collapse on mobile but there's no hamburger replacement
- [ ] **Contact form / "Add my city" CTA** — for municipalities or families wanting to host a cabinet
- [ ] **Donation link** — your system supports donations; the marketing page should too
- [ ] **Press / media section** — if any news outlets covered Ido or the project, link them
- [ ] **Newsletter / "Notify me when there's a cabinet near me"** signup
- [ ] **Map of beaches with cabinets** — currently no visualization of where the cabinets actually are
- [ ] **Live status** ("3 boards available now in Kiryat Yam") — pulling from your real backend would be a stunning touch
- [ ] **404 page** — for GitHub Pages
- [ ] **README.md** in the GitHub repo so the source link looks professional

---

## 🔒 Legal / accessibility

- [ ] **Privacy policy** — you handle IDF IDs; required by Israeli privacy law
- [ ] **Terms of service**
- [ ] **Cookie / consent banner** if you add analytics
- [ ] **Alt text audit** — most images currently have minimal alt text
- [ ] **Lang switching** — `<html lang="en">` is fine but Hebrew content needs `dir="rtl"` blocks

---

## 📊 Analytics & ops

- [ ] **Google Analytics / Plausible / Umami** snippet
- [ ] **Custom domain** (e.g. `soldierssurffree.com` or `.co.il`) pointing at GitHub Pages
- [ ] **HTTPS verified** on the custom domain (one-click in GitHub Pages settings)
- [ ] **Sitemap.xml + robots.txt** for SEO

---

## ✅ Recommended order

1. Real URLs (5 min)
2. Demo video + a few key screenshots (biggest visual impact)
3. SRD / TDD / Final report when written
4. Logo + favicon + Open Graph image
5. Real bios + photos
6. Custom domain + analytics

---

## 🤖 Things I can build right now (no extra assets needed)

- Logo (SVG)
- Favicon
- Open Graph / social preview image
- 404 page
- `README.md` for the GitHub repo
- Mobile hamburger menu
- Privacy policy / terms boilerplate
- Hebrew translation pass
- Contact form (mailto-based, no backend)
- Map placeholder section

Just ask.

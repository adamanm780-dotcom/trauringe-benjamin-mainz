# Trauringe Benjamin

**Slug:** trauringe-benjamin-mainz
**Branche:** Juwelier / Trauringe-Spezialist
**Build-Datum:** 2026-05-02
**Live-URL:** https://adamanm780-dotcom.github.io/trauringe-benjamin-mainz/
**Repo:** https://github.com/adamanm780-dotcom/trauringe-benjamin-mainz
**Lokal:** C:\Users\Adria\claude-discord-projects\allgemein\trauringe-benjamin-3

## Kontakt
- Adresse: Lotharstraße 15, 55116 Mainz
- Telefon: 06131 2073734
- E-Mail: info@juwelier-benjamin.eu
- Öffnungszeiten: Mo–Fr 10:00–18:00 · Sa 10:00–16:00 · So geschlossen
- Website (Original): trauringe-benjamin.de · juwelier-benjamin.eu
- Instagram: n/a

## Design
- Palette: #F7F0E4 #F1E8D9 #FBF6EC #2A1F18 #B7935C #D8B98A
- Tokens: bg #F7F0E4 (cream) · bg-raised #F1E8D9 · bg-elevated #FBF6EC · bg-deep #2A1F18 (espresso) · accent #B7935C (klassisches Gold) · accent-light #D8B98A (champagne) · accent-dark #8C6B3A · ink #2A1F18 · ink-soft #6B5A47
- Fonts: Cormorant Garamond + Italiana + Inter
- Style-Richtung: helles romantic editorial, cream + champagner + gold, classic bridal magazine. User-Wunsch "alles in einem hellen design" umgesetzt — kein dunkler Hero, sondern Body in Cream, dunkle Akzente nur in Topbar/Marquee/Kontakt/Footer.

## Assets
- Hero: assets/hero.webp (Nano Banana 21:9 → Real-ESRGAN 4K → 2560px webp). Zwei Goldringe + Schleierkraut auf Cream-Linen.
- Maps-Fotos: 4 (assets/maps-01..04.webp) — Filiale außen Wiesbaden, Schaufenster mit GUESS, Halsketten-Vitrine, Innenraum mit Marken
- Insta-Posts: n/a (kein Handle gefunden)
- Scroll-Frames: 50 × WebP (assets/scroll/frames-clean/), Source-Video assets/scroll/source.mp4 (Seedance 1-pro, 5s, 1080p, ChatGPT-Replacement via Nano Banana mit Seed=42)
- Zusatz-Assets: texture.webp (cream paper), detail-01.webp (Goldschmied-Hände), detail-02.webp (Gravierter Diamant-Goldring), about.webp (s/w Werkstatt-Doku)

## Build-Stats
- Build-Zeit: ~7m (Phase 0–7 ohne Scroll-Animation)
- Sections im HTML: 12 (Topbar, Header, Hero, Marquee, Intro, Categories Bento, Featured 4-Cards, Atelier, Gallery, Testimonials, Contact, Footer)

## Updates
- 2026-05-02: Initial Build (light design) + Scroll-Frame-Animation (zwei Ringe verschränken sich, 50 Frames, Seedance 1-pro)
- 2026-05-02: Scroll-Animation auf Canvas-Rendering umgestellt (statt img.src-Swap) — entfernt die doppelte drop-shadow-Filter-Re-Rasterisierung pro Frame, dadurch komplett smooth auf Laptop-iGPUs; Ambient-Schatten als statischer radial-gradient unter Canvas; Fallback auf Nachbar-Frames falls einer beim Scroll noch nicht decoded ist (kein Verschwinden mehr).
- 2026-05-02: Mobile-Optimierung — Gallery (.gallery__grid) und Testimonials (.tgrid) auf ≤768px als horizontale Swipe-Carousels (CSS scroll-snap-type:x mandatory, Karten mit 82–85% Breite + Peek der nächsten Karte als Wisch-Hinweis, Scrollbar versteckt, dezenter „← Wischen →"-Indikator unter beiden Sektionen).

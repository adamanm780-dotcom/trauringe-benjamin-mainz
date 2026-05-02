# Inspo — Trauringe Benjamin (Branche: Trauringe / Bridal Jewelry)

## Übergeordnete Richtung
Helles, romantisches Editorial-Design für einen klassischen Trauring-Spezialisten. Off-White / Cream / warmes Champagner-Beige als Grundton, Gold und Roségold als Akzent. Klassische Serif-Schriften (Cormorant Garamond + Italiana) treffen auf moderne Sans (Inter). Viel Weißraum, große Bilder, ruhige Editorial-Anmutung wie ein Hochzeitsmagazin. Bilder eher hell-warm gegradet, intime Close-Ups von Händen, Ringen, Atelier-Werkzeugen.

## Referenzen (Dribbble Grid → inspo/grid.jpg)
Quelle: dribbble.com/search/wedding-rings-website (Limited inspo — Synthese aus dem Grid-Overview, da das Light-Mood-Pattern dort sehr konsistent über mehrere Shots war).

### 1. Romantic Wedding Rings Editorial
- Stil: editorial cream serif soft
- Übernehmen:
  - Großer Hero mit Serif-Headline links + Ring-Closeup rechts
  - Cream/Champagner Background statt Reinweiß
  - Dünne Gold-Linie als Trenner zwischen Sections

### 2. Bailey & Scott Bridal Studio
- Stil: classic warm minimal
- Übernehmen:
  - Roman-Numeral-Labels für Kollektionen ("I · Klassisch", "II · Modern")
  - Großzügige Vertikal-Bilder für Atelier-Section
  - Handwerk-Detail-Shots als Galerie

### 3. Heritage Jewellery Layout
- Stil: timeless editorial gold accents
- Übernehmen:
  - Sticky-Header mit zentralem Logo, Nav links und rechts
  - Topbar in Gold-on-Cream mit Tel/Adresse
  - Bento-Grid für Kategorien (Klassisch / Modern / Diamant / Memoire)

### 4. Wedding Brand Bento
- Stil: soft pastel bento
- Übernehmen:
  - 4er-Grid Featured Items mit unterschiedlichen Bildhöhen
  - Subtile Marmor-Textur-Overlay (papier statt glanz)

### 5. Pearl & Craft (atelier-zentriert)
- Stil: artisan documentary
- Übernehmen:
  - Atelier/Über-uns als Image-Text-Split mit Werkstatt-Detail
  - "Seit 1965" Heritage-Zahl groß als Display-Akzent
  - Familien-Geschichte als ruhiger Längstext

### 6. Cream Boutique Hero
- Stil: cream serif full-width
- Übernehmen:
  - Hero-Treatment mit Headline auf Cream + Bild als zweites Element darunter
  - Inset-Border auf Hero-Bild in dünnem Gold (`::after rgba(gold,.28)`)

### 7. Soft Bridal Marquee
- Stil: soft pastel marquee
- Übernehmen:
  - Marquee-Band mit Service-Tags ("TRAURINGE · GOLDANKAUF · WERKSTATT · UHREN") als Section-Trenner
  - Sehr dezent, langsame Geschwindigkeit

## Konkrete Anpassungen für Phase 6
- **Font-Pair**: `Cormorant Garamond` (h1–h4, body-serif) + `Italiana` (display/numerals) + `Inter` (sans für nav/overline/captions). Klassisch-romantisch, passt zu Trauringen besser als Playfair (mehr Stille).
- **Hero-Treatment**: Cream-Background, Headline links Serif gigantisch, rechts Close-Up-Bild mit dünnem Gold-Inset-Border. Kein dunkler Overlay nötig — das Bild ist hell. Ken-Burns dezent.
- **Section-Flourishes**:
  - Topbar in dunklem Champagner mit Gold-Text
  - Marquee-Band aus Service-Tags zwischen Hero und Intro
  - Roman-Numeral-Labels auf den 4 Featured Items (I–IV)
  - Bento-Grid für Kategorien (4 Karten mit unterschiedlichen Höhen)
  - Atelier-Section mit großer "Seit 1965"-Display-Zahl + Image-Split
  - Detail-Grid 6-Bilder mit Maps-Material (sehr subtil duotone-warm)
- **Mikro-Interaktionen**:
  - Underline-Reveal auf Nav (gold)
  - Hover-Scale auf Gallery-Bildern
  - Fade-in-on-scroll via IntersectionObserver
  - Sticky Caption beim Scrollen über Atelier-Section
  - Subtile Magnetic-Buttons (CTA in Hero + Kontakt)
- **Farb-Mood-Hinweis**: Helles Cream + warmes Champagner + zwei Gold-Töne (klassisch + roségold). Kein Reinweiß als Body-BG (zu kalt). Dunkelste Farbe ist ein tiefes Espresso-Braun für Topbar/Footer, nicht Schwarz.

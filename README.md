# Mila — glamping kućica na Zlatiboru

Statički sajt (HTML/CSS, bez bilda). Spreman za GitHub Pages.

## Sadržaj
- `index.html` — glavna stranica (hero, o kućici, sadržaji, galerija, utisci, lokacija, rezervacija)
- `utisci.html` — posebna stranica sa utiscima gostiju
- `hero.png`, `int-*.png` — fotografije
- `.nojekyll` — isključuje Jekyll obradu na GitHub Pages

Stranice su povezane relativnim linkovima, pa rade i lokalno i na hostingu.

## Hostovanje na GitHub Pages
1. Napravi novi repozitorijum na GitHub-u (npr. `mila-zlatibor`).
2. Ubaci sve fajlove iz ove fascikle u koren repozitorijuma (index.html mora biti u korenu).
3. U repozitorijumu idi na **Settings → Pages**.
4. Pod **Build and deployment → Source** izaberi **Deploy from a branch**.
5. Branch: **main**, folder: **/ (root)**, pa **Save**.
6. Za minut-dva sajt će biti dostupan na `https://<tvoj-nalog>.github.io/<ime-repoa>/`.

### Sopstveni domen (opciono)
Ako imaš domen (npr. `mila-zlatibor.rs`): u Settings → Pages → Custom domain upiši domen,
pa kod registrara dodaj DNS zapise prema GitHub uputstvu. GitHub automatski doda `CNAME` fajl.

## Pre objave zameni placeholder podatke
- Booking i Airbnb linkove (sada vode na booking.com / airbnb.com) — stavi link ka svom oglasu.
- Telefon, email, Instagram i WhatsApp broj (u sekciji Rezervacija).
- Cenu po noćenju i tačnu lokaciju.
- Utiske na `utisci.html` i u sekciji „Utisci" — zameni pravim recenzijama gostiju.

## Lokalni pregled
Samo otvori `index.html` u pretraživaču (dupli klik), ili pokreni mali server:
`python3 -m http.server` pa otvori `http://localhost:8000`.

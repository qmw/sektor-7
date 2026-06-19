# Sektor 7 — Escape Room

Strona-wizytówka fikcyjnego escape roomu "Sektor 7" w Warszawie.
Portfolio projektu demonstrującego styl **Immersyjny Mrok / Kino-Thriller**.

## Styl
- Paleta: czerń (#07080a) + toksyczna zieleń neon (#4ade80) + krwista czerwień (#ef2b2b)
- Fonty: Saira Condensed (display) + Space Mono (mono) + Barlow (body)
- Efekty: scanline overlay, grain noise, glitch na tytule, odliczanie countdown, własny kursor
- Layout: asymetryczny, ogromna typografia (clamp 4–12vw), nachodzące elementy, terminal vibe

## Sekcje
- Nav (fixed, transparent → blurred scroll)
- Hero (countdown 60:00, hasło z efektem glitch, statystyki)
- Pokoje / scenariusze (4 pokoje, alternating layout)
- Jak grać / zasady
- Dla kogo (urodziny, integracje, randki, znajomi)
- Cennik (wg liczby graczy)
- Opinie graczy
- Rezerwacja (formularz + mapa OSM)
- Stopka z creditem

## Stack
- Astro 5 + Tailwind CSS 4 (via @tailwindcss/vite)

## Komendy
```
npm install
npm run dev
npm run build
```

## Hosting
Vercel — deploy przez `vercel` CLI.

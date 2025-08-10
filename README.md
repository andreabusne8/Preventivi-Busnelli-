# Gestionale Preventivi – Retail Moda (PWA)

Questa cartella è pronta per **GitHub Pages**.

## Come pubblicare
1. Crea un repository su GitHub (pubblico o privato con Pages).
2. Carica **tutti i file** di questa cartella (index.html, manifest.json, sw.js, /assets, /icons).
3. Vai su **Settings → Pages** → Source: *Deploy from a branch* → Branch: `main` (root).  
4. Dopo il deploy, apri l'URL su iPhone in Safari → **Condividi → Aggiungi a schermata Home**.

## Loghi
Sostituisci i segnaposto in `/assets` con i loghi reali:
- `assets/bottega-busnelli.svg`
- `assets/busnelli-corporate.svg`

Puoi usare anche PNG/JPG: mantieni lo stesso nome **e** aggiorna l'estensione in `index.html` se necessario.

## Offline
La PWA funziona offline dopo il primo caricamento grazie al service worker (`sw.js`).

## Dati
I preventivi vengono salvati in `localStorage`. Usa **Export** per backup `.json` e **Import** per ripristinare.

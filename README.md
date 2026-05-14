![logo_ok.png](logo_ok.png)
# Rosario Giordano — Parrucchiere a Pallanza (VB)

Sito web monopagina (single-page) del salone di parrucchiere **Rosario Giordano**, situato nel cuore di Pallanza, Verbania.

Realizzato come migrazione da un precedente sito multi-pagina a una moderna applicazione statica responsive, accessibile e performante.

## Caratteristiche

- **Monopagina** con navigazione smooth scroll tra le sezioni
- **Design responsive** adattabile a mobile, tablet e desktop
- **Accessibilità WCAG AA**: contrasti, attributi `alt`, navigazione da tastiera
- **Google Maps** integrato per la sezione "Dove Siamo"
- **Scroll reveal** con Intersection Observer
- **Pulsante "Torna su"** per una navigazione rapida
- **Header dinamico** con effetto scroll
- **Icone Font Awesome** e **Google Fonts** (Playfair Display + Quicksand)

## Struttura del progetto

```
.
├── index.html          # Monopagina principale
├── style.css           # Stili consolidati
├── script.js           # Script (nav, scroll, animazioni)
├── logo_ok.png         # Logo del salone
├── salone-rosario.jpg  # Foto del salone
└── README.md           # Questo file
```

## Sezioni del sito

| Sezione | Descrizione |
|---|---|
| **Hero** | Presentazione con logo e claim |
| **Il Salone** | Chi siamo, servizi offerti |
| **Dove Siamo** | Mappa e indirizzo |
| **Contatti & Orari** | Recapiti, orari di apertura |
| **Accesso Facilitato** | Postazione accessibile per disabilità |

## Tecnologie utilizzate

- HTML5 semantico
- CSS3 (flexbox, grid, media query, animazioni)
- JavaScript vanilla (Intersection Observer, gestione eventi)
- [Font Awesome 6](https://fontawesome.com)
- [Google Fonts](https://fonts.google.com)

## Installazione

1. Clona il repository:
   ```bash
   git clone https://github.com/tuo-utente/rosario-giordano.git
   ```

2. Apri `index.html` nel browser oppure avvia un server locale:
   ```bash
   # con Python
   python -m http.server 8000

   # con Node.js (se hai serve installato)
   npx serve .
   ```

3. Visita `http://localhost:8000`.

## Requisiti

Nessun build tool o npm necessario. Il sito è puro HTML/CSS/JS e funziona su qualsiasi server HTTP statico.

## Accessibilità

- Contrasti verificati per conformità WCAG AA
- Attributi `aria-label` e ruoli ARIA
- Navigazione da tastiera (`Tab`, `Enter`)
- Attributi `alt` descrittivi su tutte le immagini
- Struttura semantica con `<header>`, `<main>`, `<footer>`, `<nav>`

## Licenza

Tutti i diritti riservati &copy; 2026 Rosario Giordano.

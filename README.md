# Five Tales of Wisdom

A one-page site about a book of five folk tales from Azerbaijan, Georgia and Uzbekistan in which girls solve the problem themselves. Jamal Naghizade chose the tales, made the book and printed more than 250 copies, and on 27 September 2026 gave them to pupils in grades 2–4 at LANDAU School, Ganjlik campus / Simurq Liseyi, in Baku. Static HTML, no build step. Available in English, Azerbaijani and Russian.

## Files

- `index.html`: the page. English text lives here.
- `assets/styles.css`: design tokens (colours, fonts, motion) at the top, then the layout.
- `assets/i18n.js`: Azerbaijani and Russian translations, keyed by each element's `data-i18n` (or `data-i18n-alt` / `data-i18n-aria`) attribute.
- `assets/main.js`: the language switcher, the tale tabs, the copy-email button, and pausing the star bands when they are off screen.
- `assets/img/`: the book cover, illustrations cropped from the book, and photos from the school visit, re-encoded without metadata.
- `assets/ornament/`: tiles for the moving star band.

## Ornament

An eight-pointed star made of two overlapping squares, a motif found in Azerbaijani, Georgian and Uzbek decoration. The colours (deep teal, turquoise, saffron) are those of glazed tilework, chosen to differ from the earlier sites.

## Publishing on GitHub Pages

Push this folder to a GitHub repository. Then go to **Settings → Pages**, choose **Deploy from a branch**, and select `main` with the `/ (root)` folder.

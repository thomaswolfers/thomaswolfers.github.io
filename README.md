# Thomas Wolfers – personal website

Live at **https://thomaswolfers.github.io**. GitHub Pages rebuilds the site automatically about a minute after every change. It uses the same design as the lab website (https://mhm-lab.github.io).

The site is bilingual: German is the default at `/`, English lives under `/en/`. Each page names its translation in `alt:` at the top, which drives the *English / Deutsch* switch in the menu.

## What is where

| To change…                               | Edit this file                          |
|------------------------------------------|-----------------------------------------|
| Homepage text (German / English)         | `index.html` / `en/index.html`          |
| Science page intro (German / English)    | `science.html` / `en/science.html`      |
| Research themes (cards + Science page)   | `_data/themes.yml` (both languages)     |
| Menu, footer links, site description     | `_config.yml`                           |
| Impressum, privacy policy                | `impressum.md`, `privacy_policy.md`     |
| Colors, fonts, spacing                   | `assets/style.css`                      |
| Page frame (header/footer)               | `_layouts/default.html`                 |
| Portrait                                 | `images/portrait.jpg` (400 × 400)       |

You can edit everything directly on github.com: open the file, click the pencil icon, change it, then "Commit changes".

## Writing style
- English: American spelling (*modeling, aging*), serial comma, *and* rather than *&* in running text.
- German: gender-inclusive forms as used so far (*WissenschaftlerInnen*).
- When you change text in one language, change the other one too.

## Tips
- YAML is picky about indentation: use spaces (not tabs) and keep the same indentation as the block you copied.
- To preview locally (optional): `gem install jekyll` then `jekyll serve` in this folder, and open http://localhost:4000.

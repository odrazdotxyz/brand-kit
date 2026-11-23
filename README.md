# Odraz brand kit

Odraz is the parent brand for every client app and the website. The full brand book (logo rules, colors, typography, components) lives in the Odraz design system; this kit holds the files to build with. Colors, fonts and tokens below are shared by all brands.

## Brands
Each brand has its own folder with `svg/`, `png/` and `web/` assets and a README:
- [`odraz/`](odraz/): the parent brand (logo, lockups, icon, favicons).
- [`ogram/`](ogram/): the photo gallery app.
- [`odrive/`](odrive/): the drive (file storage) app.

## tokens/
- `tokens.json`: colors (light + dark), type styles, spacing, radius, shadows
- `odraz.css`: the same as CSS custom properties (`var(--brand-blue)`, `var(--space-4)`...) plus `.text-body`, `.text-h1`... classes. Set `data-theme="dark"` on `<html>` for dark mode.

## fonts/
Poppins Regular (400) and SemiBold (600), SIL Open Font License (`OFL.txt`).

## Colors
| Token | Light | Dark |
|---|---|---|
| brand-blue | #4A9CFF | #4A9CFF |
| brand-aqua | #4DDCFF | #4DDCFF |
| brand-purple | #6B4FD8 | #6B4FD8 |
| brand-deep / brand-deepest | #1A044C / #0F0133 | same |
| surface-page | #F9FAFB | #0F0133 |
| surface-raised | #FFFFFF | #1A044C |
| ink | #111827 | #F9FAFB |
| ink-muted | #6B7280 | #A7A3C9 |
| link | #1D6FE0 | #4A9CFF |
| ink-on-brand (text on blue/aqua) | #0F0133 | #0F0133 |

## License
© Odraz. Three licences, by folder:

* **Logos and brand assets** (`odraz/`, `odrive/`, `ogram/`) are licensed under [CC BY-ND 4.0](https://creativecommons.org/licenses/by-nd/4.0/) (see `LICENSE`). Press, articles and reviews are welcome to use them as-is. Please don't modify them or use them in a way that implies endorsement by or affiliation with Odraz.
* **Design tokens** (`tokens/`: `odraz.css`, `tokens.json`) are licensed under the **MIT licence** (`tokens/LICENSE`). Use and change them freely, for example to build your own theme or to drop the Google Fonts import. Their use does not give you the right to use Odraz's logos or name.
* **Fonts** (`fonts/`) are Poppins, licensed under the SIL Open Font License (`fonts/OFL.txt`).

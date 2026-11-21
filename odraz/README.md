# Odraz brand kit

Odraz is the parent brand for every client app and the website. Shared rules (colors, fonts, tokens, license) are in the [root README](../README.md).

## svg/ (masters, transparent unless noted)
- `odraz-mark.svg`: the mark (clouds + reflection)
- `odraz-lockup-dark-text.svg`, `odraz-lockup-light-text.svg`: horizontal lockups for light / dark grounds
- `odraz-lockup-stacked-dark-text.svg`, `odraz-lockup-stacked-light-text.svg`: stacked lockups
- `odraz-wordmark-dark.svg`, `odraz-wordmark-light.svg`: "odraz" alone
- `odraz-mark-monochrome-dark.svg`, `odraz-mark-monochrome-white.svg`: one-color marks
- `odraz-icon.svg`: app icon master (full-bleed dark gradient)
- `odraz-favicon.svg`: favicon master (clouds only, rounded dark tile)

Wordmark text is converted to outlines; no font needed to use these files.

## png/
Renders of the mark, monochrome marks, all lockups and the app icon at several sizes.

## web/
```html
<link rel="icon" href="/favicon.ico" sizes="any">
<link rel="icon" href="/favicon.svg" type="image/svg+xml">
<link rel="apple-touch-icon" href="/apple-touch-icon-180.png">
<link rel="manifest" href="/manifest.webmanifest">  <!-- icons: icon-192.png, icon-512.png -->
<meta property="og:image" content="/og-image-1200x630.png">
```

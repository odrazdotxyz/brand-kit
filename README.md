# Odraz brand kit

Odraz is the parent brand for every client app and the website. The full brand book (logo rules, colors, typography, components) lives in the Odraz design system; this kit holds the files to build with.

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

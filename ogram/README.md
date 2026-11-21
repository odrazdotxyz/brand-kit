# ogram brand kit

ogram is the photo gallery app in the Odraz family. Its mark is a lotus: three petals in Odraz purple, blue and aqua, standing on a flat waterline with a thin gap above a fading reflection, like the Odraz and odrive logos. It follows the Odraz brandbook for colors, type (Poppins) and usage rules.

## svg/ (masters, transparent unless noted)
- `ogram-mark.svg`: the mark (petals + reflection)
- `ogram-lockup-dark-text.svg`, `ogram-lockup-light-text.svg`: horizontal lockups for light / dark grounds
- `ogram-lockup-stacked-dark-text.svg`, `ogram-lockup-stacked-light-text.svg`: stacked lockups
- `ogram-wordmark-dark.svg`, `ogram-wordmark-light.svg`: "ogram" alone
- `ogram-mark-monochrome-dark.svg`, `ogram-mark-monochrome-white.svg`: one-color marks
- `ogram-icon.svg`: app icon master (full-bleed dark gradient #1A044C → #0F0133)
- `ogram-favicon.svg`: favicon master (petals only, rounded dark tile)

Wordmark text is converted to outlines.

## png/
Mark, monochrome marks, lockups and app icon at several sizes.

## web/
```html
<link rel="icon" href="/favicon.ico" sizes="any">
<link rel="icon" href="/favicon.svg" type="image/svg+xml">
<link rel="apple-touch-icon" href="/apple-touch-icon-180.png">
<link rel="manifest" href="/manifest.webmanifest">  <!-- icons: icon-192.png, icon-512.png -->
<meta property="og:image" content="/og-image-1200x630.png">
```

## Usage
- Light grounds: dark-text lockups. Dark grounds: light-text lockups.
- Below 24px use the favicon (the reflection is dropped on purpose at small sizes).
- Don't recolor or reorder the petals (purple left, blue center, aqua right) or remove the reflection from the full mark.

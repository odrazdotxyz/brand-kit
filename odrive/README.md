# odrive brand kit

odrive is the drive (file storage) app in the Odraz family. Its mark is a storage cube: a rounded box with a purple left side, blue right side and aqua top, mirrored in a fading reflection like the Odraz logo. It follows the Odraz brandbook for colors, type (Poppins) and usage rules.

## svg/ (masters, transparent unless noted)
- `odrive-mark.svg`: the mark (cube + reflection)
- `odrive-lockup-dark-text.svg`, `odrive-lockup-light-text.svg`: horizontal lockups for light / dark grounds
- `odrive-lockup-stacked-dark-text.svg`, `odrive-lockup-stacked-light-text.svg`: stacked lockups
- `odrive-wordmark-dark.svg`, `odrive-wordmark-light.svg`: "odrive" alone
- `odrive-mark-monochrome-dark.svg`, `odrive-mark-monochrome-white.svg`: one-color marks
- `odrive-icon.svg`: app icon master (full-bleed dark gradient #1A044C → #0F0133)
- `odrive-favicon.svg`: favicon master (cube only, rounded dark tile)

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
- Don't recolor the faces (purple left, blue right, aqua top) or remove the reflection from the full mark.

# Hada Type

Public distribution files for Hada Type fonts.

This repository contains completed font artifacts only. The source build
repository is private, so production web projects should load these files
through jsDelivr's GitHub CDN endpoint.

## CDN

Use a version-pinned URL:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/hada0127/hada-type@v2026.09.01/css/hada-type.css">
```

Individual family CSS files:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/hada0127/hada-type@v2026.09.01/css/hada-sans.css">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/hada0127/hada-type@v2026.09.01/css/hada-batang.css">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/hada0127/hada-type@v2026.09.01/css/dancing-peoples.css">
```

Direct WOFF2 example:

```css
@font-face {
  font-family: "Hada Sans";
  src: url("https://cdn.jsdelivr.net/gh/hada0127/hada-type@v2026.09.01/fonts/hada-sans/woff2/HadaSans-Regular.woff2") format("woff2");
  font-weight: 400;
  font-display: swap;
}
```

## Packages

ZIP packages are attached to the GitHub release because the Hada Sans
bundle is larger than jsDelivr's GitHub single-file limit.

- https://github.com/hada0127/hada-type/releases/download/v2026.09.01/HadaSans.zip
- https://github.com/hada0127/hada-type/releases/download/v2026.09.01/HadaBatang.zip
- https://github.com/hada0127/hada-type/releases/download/v2026.09.01/DancingPeoples.zip

Each ZIP includes TTF, OTF, WOFF2, `WEBFONT.css`, `WEBFONT-USAGE.txt`,
`LICENSE.txt`, and `COPYRIGHT.txt`.

## License

The fonts are distributed under the SIL Open Font License 1.1.

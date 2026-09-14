# Hada Type

[Hada Type](https://type.hada0127.net) — 한글·라틴 오픈 폰트 / Korean & Latin open fonts, SIL Open Font License 1.1.

Public distribution files for Hada Type fonts.

This repository contains completed font artifacts only. The source build
repository is private, so production web projects should load these files
through jsDelivr's GitHub CDN endpoint.

## Families

- [Hada Sans](https://type.hada0127.net/hada-sans) — 화면용 산세리프
- [Hada Mono](https://type.hada0127.net/hada-mono) — 한글 코딩 고정폭 글꼴
- [Hada Round](https://type.hada0127.net/hada-round) — 부드러운 둥근 산세리프
- [Hada Condensed](https://type.hada0127.net/hada-condensed) — 좁은 공간의 한글 글꼴
- [Hada Batang](https://type.hada0127.net/hada-batang) — 긴 글을 위한 바탕체
- [Dancing Peoples](https://type.hada0127.net/dancing-peoples) — DANC 가변 글꼴
- [Dancing Peoples Mono](https://type.hada0127.net/dancing-peoples-mono) — 가변 고정폭 글꼴

## CDN

Use a version-pinned URL:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/hada0127/hada-type@v2026.09.05/css/hada-type.css">
```

Individual family CSS files:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/hada0127/hada-type@v2026.09.05/css/hada-sans.css">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/hada0127/hada-type@v2026.09.05/css/hada-batang.css">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/hada0127/hada-type@v2026.09.05/css/hada-mono.css">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/hada0127/hada-type@v2026.09.05/css/hada-round.css">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/hada0127/hada-type@v2026.09.05/css/hada-condensed.css">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/hada0127/hada-type@v2026.09.05/css/dancing-peoples.css">
```

Direct WOFF2 example:

```css
@font-face {
  font-family: "Hada Sans";
  src: url("https://cdn.jsdelivr.net/gh/hada0127/hada-type@v2026.09.05/fonts/hada-sans/woff2/HadaSans-Regular.woff2") format("woff2");
  font-weight: 400;
  font-display: swap;
}
```

## Packages

ZIP packages are attached to the GitHub release and split by format.

| Family | TTF | OTF | WOFF2 |
| --- | --- | --- | --- |
| Hada Sans | [HadaSans-TTF.zip](https://github.com/hada0127/hada-type/releases/download/v2026.09.05/HadaSans-TTF.zip) | [HadaSans-OTF.zip](https://github.com/hada0127/hada-type/releases/download/v2026.09.05/HadaSans-OTF.zip) | [HadaSans-WOFF2.zip](https://github.com/hada0127/hada-type/releases/download/v2026.09.05/HadaSans-WOFF2.zip) |
| Hada Batang | [HadaBatang-TTF.zip](https://github.com/hada0127/hada-type/releases/download/v2026.09.05/HadaBatang-TTF.zip) | [HadaBatang-OTF.zip](https://github.com/hada0127/hada-type/releases/download/v2026.09.05/HadaBatang-OTF.zip) | [HadaBatang-WOFF2.zip](https://github.com/hada0127/hada-type/releases/download/v2026.09.05/HadaBatang-WOFF2.zip) |
| Hada Mono | [HadaMono-TTF.zip](https://github.com/hada0127/hada-type/releases/download/v2026.09.05/HadaMono-TTF.zip) | [HadaMono-OTF.zip](https://github.com/hada0127/hada-type/releases/download/v2026.09.05/HadaMono-OTF.zip) | [HadaMono-WOFF2.zip](https://github.com/hada0127/hada-type/releases/download/v2026.09.05/HadaMono-WOFF2.zip) |
| Hada Round | [HadaRound-TTF.zip](https://github.com/hada0127/hada-type/releases/download/v2026.09.05/HadaRound-TTF.zip) | [HadaRound-OTF.zip](https://github.com/hada0127/hada-type/releases/download/v2026.09.05/HadaRound-OTF.zip) | [HadaRound-WOFF2.zip](https://github.com/hada0127/hada-type/releases/download/v2026.09.05/HadaRound-WOFF2.zip) |
| Hada Condensed | [HadaCondensed-TTF.zip](https://github.com/hada0127/hada-type/releases/download/v2026.09.05/HadaCondensed-TTF.zip) | [HadaCondensed-OTF.zip](https://github.com/hada0127/hada-type/releases/download/v2026.09.05/HadaCondensed-OTF.zip) | [HadaCondensed-WOFF2.zip](https://github.com/hada0127/hada-type/releases/download/v2026.09.05/HadaCondensed-WOFF2.zip) |
| Dancing Peoples | [DancingPeoples-TTF.zip](https://github.com/hada0127/hada-type/releases/download/v2026.09.05/DancingPeoples-TTF.zip) | [DancingPeoples-OTF.zip](https://github.com/hada0127/hada-type/releases/download/v2026.09.05/DancingPeoples-OTF.zip) | [DancingPeoples-WOFF2.zip](https://github.com/hada0127/hada-type/releases/download/v2026.09.05/DancingPeoples-WOFF2.zip) |

Each ZIP includes `WEBFONT-USAGE.txt`, `LICENSE.txt`, and
`COPYRIGHT.txt`. WOFF2 ZIPs also include `WEBFONT.css` for self-hosted
webfont use.

## License

The fonts are distributed under the [SIL Open Font License 1.1](LICENSE.txt).

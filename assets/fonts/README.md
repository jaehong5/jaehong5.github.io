# Bundled webfonts

These files are served from the site so typography does not depend on fonts installed on a visitor's device or on a third-party font CDN at page-view time.

- `ioskeley-mono-light.woff2`, `ioskeley-mono-regular.woff2`, `ioskeley-mono-medium.woff2`, `ioskeley-mono-bold.woff2`: Ioskeley Mono v2.1.0, normal width, weights 300/400/500/700. Unmodified WOFF2 files from the [official web release](https://github.com/ahatem/IoskeleyMono/releases/tag/v2.1.0), licensed under the SIL Open Font License in `OFL-IoskeleyMono.txt`.
- `hack-regular.woff2`, `hack-bold.woff2`: Hack 3, licensed under the Hack Open Font License and Bitstream Vera license in `LICENSE-Hack.md`.
- `red-hat-text-latin.woff2`: Red Hat Text variable font, Latin subset, licensed under the SIL Open Font License in `OFL-RedHatText.txt`.
- `newsreader-latin.woff2`: Newsreader variable font, Latin subset, licensed under the SIL Open Font License in `OFL-Newsreader.txt`.
- `noto-sans-kr-jaehong.woff2`: Noto Sans KR regular font, subset for the Hangul name `오재홍`, licensed under the SIL Open Font License in `OFL-NotoSansKR.txt`.

`assets/site.css` uses Ioskeley Mono throughout the page, with Noto Sans KR for the Hangul name. Each face uses a bundled URL without a `local()` source. Regular and Medium are preloaded for the first screen. The earlier Hack, Red Hat Text, and Newsreader assets remain available but are not loaded by the current stylesheet.

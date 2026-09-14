# Asset manifest — maternal anaemia datathon deck

All files downloaded 2026-09-13 with curl (LottieFiles asset CDN URLs were resolved in a browser because lottiefiles.com itself sits behind a Cloudflare challenge). Every SVG parses as XML; every Lottie JSON parses and contains `layers`. Total folder size ≈ 396 KB.

Palette reminder: cream #F2EEDF · oxide red #C0392B · sage #B7C7A8 · blush #E8C9B6 · plum #A03A6E · indigo #2E6DB4.

| File | Depicts | Format | Source | License | Attribution required |
|---|---|---|---|---|---|
| `mascot-planet-kawaii.svg` | Round sage-green planet with blissful face and red tongue (recommended mascot) | SVG 240×240, groups `#body`, `#face`, `#eyes`, `#mouth`, `#blush` | https://github.com/miukimiu/react-kawaii — `packages/react-kawaii/src/components/Planet.tsx` + `common/Face.tsx`, `common/paths.ts` | MIT | No (MIT asks only that the copyright/licence notice stay with the code; a comment crediting react-kawaii is embedded in each file) |
| `mascot-ghost-kawaii.svg` | Friendly sage-green ghost, blissful face | SVG, same group ids | react-kawaii `Ghost.tsx` | MIT | No |
| `mascot-icecream-kawaii.svg` | Sage ice-lolly with blush stick, happy dot-eyes and smile | SVG, same group ids | react-kawaii `IceCream.tsx` | MIT | No |
| `mother-baby-crib-storyset-motherhood.svg` | Mother standing by a crib holding a newborn, green line-art (Storyset "Motherhood", green colourway) | SVG 500×500, fixed fills (primary `#92E3A9`, line `#263238`) | https://storyset.com/illustration/motherhood/rafiki — file https://stories.freepiklabs.com/storage/6292/Motherhood-01.svg | Freepik/Storyset free licence | **Yes** |
| `mother-baby-flowers-storyset-motherhood.svg` | Mother cradling a baby amid coral flowers (Storyset "Motherhood", flat colourway) | SVG 500×500, fixed fills (primary `#FF725E`, skin `#eb996e`, line `#263238`) | https://storyset.com/illustration/motherhood/pana — file https://stories.freepiklabs.com/storage/2440/Motherhood-01.svg | Freepik/Storyset free licence | **Yes** |
| `mother-breastfeeding-storyset.svg` | Seated mother in a green sari breastfeeding a baby, line-art with pattern (Storyset "Breastfeeding") | SVG 500×500, fixed fills (primary `#92E3A9`) | https://storyset.com/illustration/breastfeeding/pana — file https://stories.freepiklabs.com/storage/37891/Breastfeeding-01.svg | Freepik/Storyset free licence | **Yes** |
| `mother-baby-undraw-motherhood.svg` | Mother hugging a toddler, unDraw flat style (original primary `#6c63ff`) | SVG 668×538 | https://undraw.co/search/motherhood — file https://cdn.undraw.co/illustrations/motherhood_9s9r.svg | unDraw licence | No |
| `mother-baby-undraw-motherhood-oxide.svg` | Same, primary recoloured to `#C0392B` | SVG | derived from the above | unDraw licence (modification allowed) | No |
| `mother-child-walking-undraw-quality-time.svg` | Mother and young child walking hand in hand past a window (unDraw "Quality time") | SVG | https://undraw.co/search/mother — file https://cdn.undraw.co/illustrations/quality-time_ay6x.svg | unDraw licence | No |
| `mother-child-walking-undraw-quality-time-oxide.svg` | Same, primary recoloured to `#C0392B` | SVG | derived from the above | unDraw licence | No |
| `anim-heartbeat-lottiefiles.json` | Pulsing heart icon, 2 layers, 25 fps, 40 frames, 596×842 | Lottie JSON (extracted from dotLottie) | https://lottiefiles.com/free-animation/heart-beat-icon-Usuxc3qEKJ (by Дмитрий Рязанцев) — asset https://assets-v2.lottiefiles.com/a/57229b8e-1151-11ee-8696-3728c0e93fba/93U6ulZXnw.lottie | Lottie Simple License | No (encouraged) |
| `anim-rotating-earth-lottiefiles.json` | Rotating flat-style Earth, 5 layers, 60 fps, 598 frames, 600×550 | Lottie JSON (extracted from dotLottie) | https://lottiefiles.com/free-animation/rotating-earth-3W6zKpi6cc (by Kele) — asset https://assets-v2.lottiefiles.com/a/eafe136c-1168-11ee-9b9f-f7f73c73900c/PU16zg8ahA.lottie | Lottie Simple License | No (encouraged) |

## Licence texts (quoted from the source pages)

**react-kawaii — MIT** (`LICENSE.md` in repo): "The MIT License (MIT) Copyright (c) Elizabet aka Miuki Miu. Permission is hereby granted, free of charge, to any person obtaining a copy …" The three mascot SVGs are new standalone files built from the component path data; the body fill was changed from `#A6E191` to sage `#B7C7A8` and the tongue from `#E74144` to `#C0392B`.

**unDraw licence** (https://undraw.co/license): "All images, assets and vectors published on unDraw can be used for free. You can use them for noncommercial and commercial purposes. You do not need to ask permission from or provide credit to the creator or unDraw. More precisely, unDraw grants you an nonexclusive, worldwide copyright license to download, copy, modify, distribute, perform, and use the assets provided from unDraw for free, including for commercial purposes, without permission from or attributing the creator or unDraw. This license does not include the right to compile assets, vectors or images from unDraw to replicate a similar or competing service…" Copyright 2026 Katerina Limpitsouni.

**Storyset (Freepik Company)** — illustration page: "Freepik License. Free for personal and commercial purpose with attribution." Terms of Use (https://storyset.com/terms): "The authorization to use the Storyset Content shall be free provided that any use of the Storyset Content by the User is credited to the Company/Website as stated by the Company from time to time. In order to benefit from using the Storyset Content without acknowledging the Company/Website, the User must purchase a Flaticon Premium Subscription…"
→ Put a visible credit on the slide or in the deck's closing credits, e.g. **"Illustrations by Storyset (storyset.com)"** with a link to https://storyset.com. Note the SVGs were fetched from Storyset's own preview CDN (the same file the site serves for "Download SVG"); no login was needed.

**Lottie Simple License (FL 9.13.21)** (https://lottiefiles.com/page/license), Copyright © 2021 Design Barn Inc.: "Permission is hereby granted, free of charge, to any person obtaining a copy of the public animation files available for download at the LottieFiles site ("Files") to download, reproduce, modify, publish, distribute, publicly display, and publicly digitally perform such Files, including for commercial purposes, provided that any display, publication, performance, or distribution of Files must contain (and be subject to) the same terms and conditions of this license. … Use of Files without attributing the creator(s) of the Files is permitted under this license, though attribution is strongly encouraged. If attributions are included, such attributions should be visible to the end user." Each animation page states "Free to use under the Lottie Simple License".

## Usage notes

- Mascots: `#eyes`, `#mouth`, `#blush` are separate groups; `#eye-left`/`#eye-right` and `#tongue` also have ids. Recolour with CSS `.body-fill { fill: var(--sage) }` (the body path carries `class="body-fill"`). Blink by scaling `#eyes` in Y; bob by translating `#body` + `#face` together.
- unDraw: the `-oxide` copies simply replace `#6c63ff` with `#C0392B`; skin tones (`#ffb6b6`, `#a0616a`) and greys are untouched.
- Storyset files have hard-coded fills; to match the palette, replace `#92E3A9` → `#B7C7A8` (green ones) or `#FF725E` → `#C0392B` (coral one) with a find-and-replace.
- Lottie JSON: play with `lottie-web` or `@lottiefiles/dotlottie-web` from a CDN. The earth file is the largest asset (~200 KB); the heart is ~15 KB.

## Not obtained

- Open Peeps (CC0), Open Doodles (CC0), Humaaans (CC0): checked their sites — none offer a parent-with-child pose, so nothing was taken.
- LottieFiles "Outlined Globe" (Jan) was the top globe hit but is 1.2–1.6 MB; skipped for size in favour of Kele's 200 KB "Rotating Earth".
- Storyset animated (Lottie) exports: the illustration pages expose static SVG/PNG without login; the animate/Lottie export goes through Storyset's editor and was not attempted.
- lordicon: licence page is JS-rendered and its free tier is attribution-based; not needed once LottieFiles worked, so skipped.

## Favicon (added 2026-09-13)

`favicon.svg`, `favicon-32.png`, `apple-touch-icon.png`: an original pea-pod mark drawn for the deck in its own palette (sage pod, green peas, oxide stem); no third-party content, no attribution needed.

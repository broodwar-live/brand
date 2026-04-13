# broodwar.live brand

Brand assets for the broodwar.live project.

## Brandmark

Typographic wordmark using **Orbitron** (weight 900). Two-part construction: "BROODWAR" in uppercase + "LIVE" in a contrasting box with -8deg skew.

### Wordmark

Full BROODWAR LIVE logotype for headers, banners, and documentation.

| Variant | File | Use |
|---|---|---|
| Light text | [broodwar-live-light.svg](wordmark/broodwar-live-light.svg) | Dark backgrounds |
| Dark text | [broodwar-live-dark.svg](wordmark/broodwar-live-dark.svg) | Light backgrounds |
| On dark bg | [broodwar-live-on-dark.svg](wordmark/broodwar-live-on-dark.svg) | Standalone, dark |
| On light bg | [broodwar-live-on-light.svg](wordmark/broodwar-live-on-light.svg) | Standalone, light |

### Square Mark

Shield icon with BW monogram, using the blue-to-teal gradient. For avatars, app icons, and social.

| Variant | File | Use |
|---|---|---|
| Dark | [bw-square-dark.svg](square/bw-square-dark.svg) | Primary — GitHub, social, app icon |
| Light | [bw-square-light.svg](square/bw-square-light.svg) | Light contexts |
| Gradient | [bw-square-gradient.svg](square/bw-square-gradient.svg) | Accent — gradient BW letters on dark |

### Favicon

Shield with B/W letterforms, matches the site's `priv/static/images/brandmark.svg`.

| File | Use |
|---|---|
| [favicon.svg](favicon/favicon.svg) | Browser tab icon |

## Colors

Inspired by ASL Season 21 / SOOP broadcast aesthetic.

### Core Palette

| Name | Value | Hex | Use |
|---|---|---|---|
| Navy (base) | `oklch(14% 0.03 255)` | ~`#0c1120` | Dark backgrounds |
| Off-white | `oklch(94% 0.006 250)` | ~`#EDEDED` | Text on dark |
| White | `#FFFFFF` | | LIVE box bg (dark mode) |

### Accent Colors

| Name | Value | Hex | Use |
|---|---|---|---|
| SOOP Blue | `oklch(60% 0.2 250)` | `#0182ff` | Primary accent, links, interactive |
| Teal | `oklch(78% 0.14 180)` | `#32f6e0` | Gradient endpoint, secondary |
| Purple | `oklch(55% 0.25 290)` | `#925aff` | Tertiary accent |

### State Colors

| Name | Hex | Use |
|---|---|---|
| Live red | `#ff2f00` | Live indicators, urgent |
| Success green | `oklch(72% 0.19 155)` | Online, success states |
| Warning amber | `oklch(78% 0.15 80)` | Warnings |

### Race Colors

| Race | Value | Use |
|---|---|---|
| Terran | `oklch(62% 0.22 25)` | Gold/orange |
| Protoss | `oklch(80% 0.16 90)` | Yellow |
| Zerg | `oklch(58% 0.2 310)` | Purple |

## Typography

### Brandmark Font

**Orbitron** — weight 900 (ultra-bold), loaded from Google Fonts.

- **BROODWAR** — letter-spacing: 0.04em, `color-base-content`
- **LIVE** — letter-spacing: 0.06em, font-size: 0.55em relative, skewX(-8deg), inverted colors in a box

### Site Fonts

| Font | Class | Use |
|---|---|---|
| Pretendard Variable | (default body) | All UI text |
| Black Han Sans | `.font-display` | Hero text, section titles |
| Orbitron 900 | `.brandmark` | Brandmark only |
| JetBrains Mono | `.font-stats` | Scores, Elo, APM, timestamps |

## Brandmark Construction

```
┌─────────────────────────────────────────────────────┐
│                                                     │
│  BROODWAR ┌────────┐                                │
│           │ LIVE   │  ← skewed -8deg                │
│           └────────┘                                │
│  ▲ Orbitron 900    ▲ Orbitron 900, 0.55em           │
│  letter-sp 0.04em  letter-sp 0.06em                 │
│                    box: white on dark, navy on light │
│                                                     │
└─────────────────────────────────────────────────────┘
```

## Legal

This project is not affiliated with Blizzard Entertainment, Inc. or Microsoft Corporation. "StarCraft" and "Brood War" are registered trademarks of Blizzard Entertainment, Inc.

🇰🇷 [한국어](README.ko.md)

# broodwar.live brand

Brand assets for the broodwar.live project. All assets are rendered from the actual site CSS using Orbitron 900 via headless Chrome.

## Brandmark

Two-part typographic wordmark: **BROODWAR** in Orbitron 900 + **LIVE** in a contrasting box with -8deg italic skew.

### Wordmark

Full BROODWAR LIVE logotype for headers, banners, and documentation.

| Variant | File | Use |
|---|---|---|
| Light text (no bg) | [broodwar-live-light.png](wordmark/broodwar-live-light.png) | Over dark backgrounds |
| Dark text (no bg) | [broodwar-live-dark.png](wordmark/broodwar-live-dark.png) | Over light backgrounds |
| On dark bg | [broodwar-live-on-dark.png](wordmark/broodwar-live-on-dark.png) | Standalone, dark |
| On light bg | [broodwar-live-on-light.png](wordmark/broodwar-live-on-light.png) | Standalone, light |

### Square Mark

Full brandmark in a 512x512 rounded square for avatars, app icons, and social.

| Variant | File | Use |
|---|---|---|
| Dark | [bw-square-dark.png](square/bw-square-dark.png) | Primary — GitHub, social, app icon |
| Light | [bw-square-light.png](square/bw-square-light.png) | Light contexts |
| Gradient | [bw-square-gradient.png](square/bw-square-gradient.png) | Accent — blue-to-teal ASL gradient |

### Favicon

Shield icon with BW letterforms using the blue-to-teal gradient. Matches the site's `priv/static/images/brandmark.svg`.

| File | Use |
|---|---|
| [favicon.svg](favicon/favicon.svg) | Browser tab icon |

## Colors

Inspired by ASL Season 21 / SOOP broadcast aesthetic. Colors are defined in OKLCH.

### Core Palette

| Name | OKLCH | Approx Hex | Use |
|---|---|---|---|
| Navy (base-100) | `oklch(14% 0.03 255)` | `#0c1120` | Dark backgrounds |
| Darker navy (base-200) | `oklch(11% 0.025 255)` | | Cards, secondary surfaces |
| Darkest navy (base-300) | `oklch(8% 0.02 255)` | | Header, tertiary surfaces |
| Off-white (base-content) | `oklch(94% 0.006 250)` | `#EDEDED` | Text on dark |

### Accent Colors

| Name | OKLCH | Hex | Use |
|---|---|---|---|
| SOOP Blue (primary) | `oklch(60% 0.2 250)` | `#0182ff` | Links, interactive, brand accent |
| Teal (secondary) | `oklch(78% 0.14 180)` | `#32f6e0` | Gradient endpoint, secondary accent |
| Purple (accent) | `oklch(55% 0.25 290)` | `#925aff` | Tertiary accent |

### Race Colors

| Race | OKLCH | Use |
|---|---|---|
| Terran | `oklch(62% 0.22 25)` | Gold/orange |
| Protoss | `oklch(80% 0.16 90)` | Yellow |
| Zerg | `oklch(58% 0.2 310)` | Purple |

## Typography

### Brandmark

**Orbitron** — weight 900, loaded from Google Fonts.

- **BROODWAR**: letter-spacing 0.04em, base-content color
- **LIVE**: letter-spacing 0.06em, font-size 0.55em, skewX(-8deg), white box on dark / navy box on light

### Site Font Stack

| Font | Class | Use |
|---|---|---|
| Pretendard Variable | (body default) | All UI text |
| Black Han Sans | `.font-display` | Hero text, section titles, player callouts |
| Orbitron 900 | `.brandmark` | Brandmark only |
| JetBrains Mono | `.font-stats` | Scores, Elo, APM, timestamps |

## Brandmark Construction

```
┌──────────────────────────────────────────────┐
│                                              │
│  BROODWAR  ┌────────┐                        │
│            │ LIVE   │  <- skewX(-8deg)       │
│            └────────┘                        │
│                                              │
│  Orbitron 900        Orbitron 900, 0.55em    │
│  letter-sp 0.04em   letter-sp 0.06em        │
│                      dark: white box         │
│                      light: navy box         │
│                                              │
└──────────────────────────────────────────────┘
```

## Legal

This project is not affiliated with Blizzard Entertainment, Inc. or Microsoft Corporation. "StarCraft" and "Brood War" are registered trademarks of Blizzard Entertainment, Inc.

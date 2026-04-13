🇺🇸 [English](README.md)

# broodwar.live 브랜드

broodwar.live 프로젝트의 브랜드 에셋입니다. 모든 에셋은 Orbitron 900을 사용하는 실제 사이트 CSS에서 헤드리스 Chrome을 통해 렌더링됩니다.

## 브랜드마크

두 부분으로 구성된 타이포그래픽 워드마크: **BROODWAR** (Orbitron 900) + **LIVE** (대비 박스, -8deg 이탤릭 기울기).

### 워드마크

헤더, 배너, 문서용 전체 BROODWAR LIVE 로고타입.

| 변형 | 파일 | 용도 |
|---|---|---|
| 밝은 텍스트 (배경 없음) | [broodwar-live-light.png](wordmark/broodwar-live-light.png) | 어두운 배경 위에 사용 |
| 어두운 텍스트 (배경 없음) | [broodwar-live-dark.png](wordmark/broodwar-live-dark.png) | 밝은 배경 위에 사용 |
| 어두운 배경 포함 | [broodwar-live-on-dark.png](wordmark/broodwar-live-on-dark.png) | 단독 사용, 어두운 버전 |
| 밝은 배경 포함 | [broodwar-live-on-light.png](wordmark/broodwar-live-on-light.png) | 단독 사용, 밝은 버전 |

### 정사각형 마크

아바타, 앱 아이콘, 소셜 미디어용 512x512 라운드 정사각형 브랜드마크.

| 변형 | 파일 | 용도 |
|---|---|---|
| 어두운 버전 | [bw-square-dark.png](square/bw-square-dark.png) | 기본 — GitHub, 소셜 미디어, 앱 아이콘 |
| 밝은 버전 | [bw-square-light.png](square/bw-square-light.png) | 밝은 맥락에서 사용 |
| 그라디언트 | [bw-square-gradient.png](square/bw-square-gradient.png) | 강조 — 블루-투-틸 ASL 그라디언트 |

### 파비콘

블루-투-틸 그라디언트를 사용한 BW 레터폼 방패 아이콘. 사이트의 `priv/static/images/brandmark.svg`와 일치합니다.

| 파일 | 용도 |
|---|---|
| [favicon.svg](favicon/favicon.svg) | 브라우저 탭 아이콘 |

## 색상

ASL 시즌 21 / SOOP 방송 미학에서 영감을 받았습니다. 색상은 OKLCH로 정의됩니다.

### 핵심 팔레트

| 이름 | OKLCH | 근사 Hex | 용도 |
|---|---|---|---|
| Navy (base-100) | `oklch(14% 0.03 255)` | `#0c1120` | 어두운 배경 |
| Darker navy (base-200) | `oklch(11% 0.025 255)` | | 카드, 보조 표면 |
| Darkest navy (base-300) | `oklch(8% 0.02 255)` | | 헤더, 3차 표면 |
| Off-white (base-content) | `oklch(94% 0.006 250)` | `#EDEDED` | 어두운 배경 위 텍스트 |

### 강조 색상

| 이름 | OKLCH | Hex | 용도 |
|---|---|---|---|
| SOOP Blue (primary) | `oklch(60% 0.2 250)` | `#0182ff` | 링크, 인터랙티브 요소, 브랜드 강조 |
| Teal (secondary) | `oklch(78% 0.14 180)` | `#32f6e0` | 그라디언트 끝점, 보조 강조 |
| Purple (accent) | `oklch(55% 0.25 290)` | `#925aff` | 3차 강조 |

### 종족 색상

| 종족 | OKLCH | 용도 |
|---|---|---|
| Terran | `oklch(62% 0.22 25)` | 골드/오렌지 |
| Protoss | `oklch(80% 0.16 90)` | 옐로 |
| Zerg | `oklch(58% 0.2 310)` | 퍼플 |

## 타이포그래피

### 브랜드마크

**Orbitron** — 굵기 900, Google Fonts에서 로드.

- **BROODWAR**: letter-spacing 0.04em, base-content 색상
- **LIVE**: letter-spacing 0.06em, font-size 0.55em, skewX(-8deg), 어두운 테마에서 흰색 박스 / 밝은 테마에서 네이비 박스

### 사이트 폰트 스택

| 폰트 | 클래스 | 용도 |
|---|---|---|
| Pretendard Variable | (본문 기본) | 모든 UI 텍스트 |
| Black Han Sans | `.font-display` | 히어로 텍스트, 섹션 제목, 선수 강조 |
| Orbitron 900 | `.brandmark` | 브랜드마크 전용 |
| JetBrains Mono | `.font-stats` | 점수, Elo, APM, 타임스탬프 |

## 브랜드마크 구성

```
┌──────────────────────────────────────────────┐
│                                              │
│  BROODWAR  ┌────────┐                        │
│            │ LIVE   │  <- skewX(-8deg)       │
│            └────────┘                        │
│                                              │
│  Orbitron 900        Orbitron 900, 0.55em    │
│  letter-sp 0.04em   letter-sp 0.06em        │
│                      dark: 흰색 박스          │
│                      light: 네이비 박스       │
│                                              │
└──────────────────────────────────────────────┘
```

## 법적 고지

이 프로젝트는 Blizzard Entertainment, Inc. 또는 Microsoft Corporation과 제휴, 보증, 연관되어 있지 않습니다. "StarCraft"와 "Brood War"는 Blizzard Entertainment, Inc.의 등록 상표입니다.

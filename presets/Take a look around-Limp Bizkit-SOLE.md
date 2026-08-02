---
type: preset
artist: Limp Bizkit
song: Take A Look Around
session: SOLE
tags:
  - preset
  - nu-metal
  - clean-heavy
guitar: "[[fender-mx-stratocastor-2016]]"
amp-sim: "[[dual-to-the-max]] / [[fragrant-orlando]]"
created: 2026-08-02
updated: 2026-08-02
---

# Limp Bizkit - Take A Look Around (SOLE)

> [!info] 사운드 컨셉
> 인트로의 차갑고 넓은 첩보물 테마 클린 톤 ↔ 코러스의 미드 스쿱(Scooped) 뉴메탈 헤비 디스토션의 극명한 대비.
> 시뮬 자체가 파트별로 전환 ([[fragrant-orlando]] 클린 ↔ [[dual-to-the-max]] 드라이브).

## 사용 장비 · 시그널 체인

| 구분 | 장비 |
| --- | --- |
| 기타 | [[fender-mx-stratocastor-2016]] |
| 앰프 시뮬 (드라이브) | [[dual-to-the-max]] (Mesa Dual Rectifier 기반) |
| 앰프 시뮬 (클린) | [[fragrant-orlando]] (Roland JC-120 기반) |
| 활성 페달 (드라이브) | [[tc-electronic-polytune-3]], [[fulltone-ocd]], [[neunaber-immerse]] |
| 활성 페달 (클린) | [[tc-electronic-polytune-3]], [[wampler-terraform]], [[boss-dd-7]], [[neunaber-immerse]] |

```mermaid
flowchart LR
  G[기타] --> PT[Polytune 3<br/>ON·버퍼] --> OCD[OCD<br/>드라이브 ON·LP] --> TX[TONEX<br/>Dual to the Max ↔ Fragrant Orlando] --> TER[Terraform<br/>클린 ON·Chorus] --> DD7[DD-7<br/>클린 ON·Analog] --> IMM[Immerse<br/>ON] --> IF[인터페이스]
```

## 기본 톤

### TONEX 설정

| 구분 | 모듈 / 파라미터 | 설정값 | 비고 |
| --- | --- | --- | --- |
| AMP & CAB | AMP SIM (드라이브/클린) | `Dual to the Max` / `Fragrant Orlando` | Mesa Dual Rectifier / Roland JC-120 |
| | CAB SIM (드라이브/클린) | `Mesa Recto Traditional` / `Roland JC120` | 각 앰프 전용 캐비닛 |
| AMP EQ (드라이브) | Gain | 6.5 (1시) | 뉴메탈 특유의 거대한 저음 |
| | Bass | 7.5 (2~3시) | |
| | Mid | 3.5 (10시, Scooped) | 과감한 미드 컷 + 날카로운 고음 |
| | Treble | 7.0 (2시) | |
| | Presence | 6.5 (1시) | |
| NOISE GATE | Power | 드라이브 시 ON (클린 OFF) | 리프 쉼표 칼같이 차단 |
| | Position | FIRST | |
| | Threshold | −40~−45dB (1~2시) | 뮤트 시 잔향 제로화 |
| | Release | 50~100ms (9시) | |
| | Depth | −60dB (12시) | |
| COMPRESSOR | Power | ON | 타격감 유지 |
| | Position | PRE | |
| | Threshold | 12시 | |
| | Gain | 0dB (2시) | |
| | Attack | 26ms (12시) | |

### 물리 페달 설정

| 페달 | ON/OFF | 노브/스위치 | 값 |
| --- | --- | --- | --- |
| [[tc-electronic-polytune-3]] | ON (상시) | Buffer | Bonafide Buffer ON |
| [[fulltone-ocd]] | 드라이브 시 ON (클린 OFF) | HP/LP | LP |
| | | Volume | 2시 |
| | | Drive | 9시 |
| | | Tone | 12시 |
| [[suhr-riot]] | OFF | - | - |
| [[mooer-pure-booster]] | OFF | - | - |
| [[fairfield-circuitry-meet-maude]] | OFF | - | - |
| [[wampler-terraform]] | 클린 시 ON (드라이브 OFF) | Mode | Chorus |
| | | Rate | 10시 |
| | | Depth | 1시 |
| | | Blend | 12시 |
| [[boss-dd-7]] | 클린 시 ON (드라이브 OFF) | Mode | Analog |
| | | E.Level | 1시 |
| | | F.Back | 1시 |
| | | D.Time | 12시 |
| [[neunaber-immerse]] | ON (상시) | Mode | Wet 또는 Spring |
| | | Mix | 12시 |
| | | Depth | 12시 |
| | | Tone/Time | 11시 |

## Play (곡 진행별 톤 변경)

> 파트별로 **시뮬 자체가 전환**됨. 클린(Fragrant Orlando)과 드라이브(Dual to the Max)에서 활성 페달군 전체가 교체됨.

### 1. 인트로 / 클린

| 조작 대상 | 상태 |
| --- | --- |
| TONEX AMP SIM | **`Fragrant Orlando`** (Roland JC-120 클린) |
| TONEX Noise Gate | OFF |
| [[fulltone-ocd]] | OFF |
| [[wampler-terraform]] | OFF → **ON** (Chorus, 차가운 입체감) |
| [[boss-dd-7]] | OFF → **ON** (Analog, 깊은 공간 테일) |
| [[neunaber-immerse]] | ON (깊은 리버브) |

- 첩보물 테마의 차갑고 넓은 클린 → Chorus + Analog 딜레이 + 리버브 조합

### 2. 코러스 / 헤비 디스토션

| 조작 대상 | 변경 |
| --- | --- |
| TONEX AMP SIM | `Fragrant Orlando` → **`Dual to the Max`** (Mesa Recto) |
| TONEX Noise Gate | OFF → **ON** (리프 쉼표 차단) |
| [[fulltone-ocd]] | OFF → **ON** (LP, 저음·고음 엣지) |
| [[wampler-terraform]] | ON → **OFF** |
| [[boss-dd-7]] | ON → **OFF** |
| [[neunaber-immerse]] | ON 유지 |

- 미드 스쿱된 뉴메탈 헤비 디스토션 → OCD(LP)가 앰프 엣지 강조, 클린계 모듈레이션·딜레이 전부 OFF

## 관련 문서

- [[signal-chain]]
- [[dual-to-the-max]]
- [[fragrant-orlando]]

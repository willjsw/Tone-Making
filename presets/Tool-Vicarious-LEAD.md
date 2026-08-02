---
type: preset
artist: Tool
song: Vicarious
session: LEAD
tags:
  - preset
  - high-gain
  - progressive
guitar: "[[fender-mx-stratocastor-2016]]"
amp-sim: "[[third-gain]]"
created: 2026-08-02
updated: 2026-08-02
---

# Tool - Vicarious (LEAD)

> [!info] 사운드 컨셉
> 어둡고 육중한 프로그레시브 하이게인. 정교한 리프를 위한 타이트한 저음 + 피킹 어택감.

## 사용 장비 · 시그널 체인

| 구분 | 장비 |
| --- | --- |
| 기타 | [[fender-mx-stratocastor-2016]] |
| 메인 앰프 시뮬 | [[third-gain]] (Diezel VH4 기반) |
| 활성 페달 | [[tc-electronic-polytune-3]], [[fulltone-ocd]], [[neunaber-immerse]] |
| 솔로 부스트 | [[mooer-pure-booster]], [[boss-dd-7]] (솔로 시 ON) |

```mermaid
flowchart LR
  G[기타] --> PT[Polytune 3<br/>ON·버퍼] --> OCD[OCD<br/>ON·HP] --> RIOT[Riot<br/>OFF] --> BST[Pure Boost<br/>솔로 ON] --> TX[TONEX<br/>Third Gain] --> DD7[DD-7<br/>솔로 ON] --> IMM[Immerse<br/>ON·Plate] --> IF[인터페이스]
```

## 기본 톤

### TONEX 설정

| 구분 | 모듈 / 파라미터 | 설정값 | 비고 |
| --- | --- | --- | --- |
| AMP & CAB | AMP SIM | `Third Gain` | Diezel VH4 기반 캡처 |
| | CAB SIM | `Diezel 4x12` | Diezel 4x12 캐비닛 |
| AMP EQ | Gain | 4.5 (11시) | 저음 벙벙거림 제어 |
| | Bass | 5.0 (12시) | |
| | Mid | 6.5 (1시) | 믹스 뚫는 미드레인지 |
| | Treble | 6.0 (1시) | |
| | Presence | 6.0 (1시) | |
| NOISE GATE | Power | ON | 앞단 노이즈 차단 |
| | Position | FIRST | |
| | Threshold | −50~−55dB (11~12시) | 뮤트 시 깔끔 차단 |
| | Release | 150~200ms (10~11시) | |
| | Depth | −60dB (12시) | |
| COMPRESSOR | Power | ON | 피킹 어택 정돈 |
| | Position | PRE | |
| | Threshold | 11시 | 어택 보존 |
| | Gain | 0dB (2시) | |
| | Attack | 15ms (9시) | |

### 물리 페달 설정

| 페달 | ON/OFF | 노브·스위치 |
| --- | --- | --- |
| [[tc-electronic-polytune-3]] | ON (상시) | Bonafide Buffer ON |
| [[fulltone-ocd]] | ON (상시) | HP · Vol 12시 / Drive 10시 / Tone 12시 |
| [[suhr-riot]] | OFF | - |
| [[mooer-pure-booster]] | OFF (솔로 ON) | Vol 2시 / Gain 9시 / Bass·Treble 12시 |
| [[fairfield-circuitry-meet-maude]] | OFF | - |
| [[wampler-terraform]] | OFF | - |
| [[boss-dd-7]] | OFF (솔로 ON) | 800ms / E.Level 10시 / F.Back 10시 / D.Time 곡 템포 |
| [[neunaber-immerse]] | ON (상시) | Plate / Mix 10시 / Depth 10시 / Tone·Time 12시 |

## Play (곡 진행별 톤 변경)

> 기본 톤(OCD 상시 크런치 + Immerse) 유지, 솔로에서 풋 페달로만 부스트

### 1. 리프 / 백킹

| 조작 대상 | 상태 |
| --- | --- |
| [[fulltone-ocd]] | ON (HP, 메인 드라이브) |
| [[mooer-pure-booster]] / [[boss-dd-7]] | OFF |

- 타이트한 저음 리프 → OCD가 Third Gain 입자를 단단하게 푸시

### 2. 솔로 / 리드

| 조작 대상 | 변경 |
| --- | --- |
| [[mooer-pure-booster]] | OFF → **ON** (순수 볼륨 부스트) |
| [[boss-dd-7]] | OFF → **ON** (800ms 딜레이) |

- 부스터는 드라이브 뒷단 → 톤 찌그러짐 없이 음량만 펌핑, 밴드 믹스 관통 ([[booster-pedal-position]])

## 관련 문서

- [[signal-chain]]
- [[third-gain]]
- [[booster-pedal-position]]

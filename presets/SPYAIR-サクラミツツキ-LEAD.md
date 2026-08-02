---
type: preset
artist: SPYAIR
song: サクラミツツキ
session: LEAD
tags:
  - preset
  - j-rock
  - modern-high-gain
guitar: "[[fender-mx-stratocastor-2016]]"
amp-sim: "[[disclosed-secret]] / High Value Secret"
created: 2026-08-02
updated: 2026-08-02
---

# SPYAIR - サクラミツツキ (LEAD)

> [!info] 사운드 컨셉
> 화려하고 시원하게 뻗는 J-Rock 모던 하이게인. 꽉 찬 믹스 속에서도 6줄 코드가 선명히 분리되는 고해상도 사운드.

## 사용 장비 · 시그널 체인

| 구분 | 장비 |
| --- | --- |
| 기타 | [[fender-mx-stratocastor-2016]] |
| 앰프 시뮬 (리프) | [[disclosed-secret]] (EVH 5150 III Stealth 기반) |
| 앰프 시뮬 (솔로) | High Value Secret |
| 활성 페달 | [[tc-electronic-polytune-3]], [[fulltone-ocd]], [[neunaber-immerse]] |
| 솔로 부스트 | [[mooer-pure-booster]], [[boss-dd-7]] (솔로·탭핑 시 ON) |

```mermaid
flowchart LR
  G[기타] --> PT[Polytune 3<br/>ON·버퍼] --> OCD[OCD<br/>ON·HP] --> BST[Pure Boost<br/>솔로 ON] --> TX[TONEX<br/>Disclosed Secret ↔ High Value Secret] --> DD7[DD-7<br/>솔로·탭핑 ON] --> IMM[Immerse<br/>ON·Plate] --> IF[인터페이스]
```

## 기본 톤

### TONEX 설정

| 구분         | 모듈 / 파라미터                   | 설정값                                             | 비고                      |
| ---------- | --------------------------- | ----------------------------------------------- | ----------------------- |
| AMP & CAB  | AMP SIM (리프/솔로)             | `Disclosed Secret` / `High Value Secret`        | EVH 5150 III Stealth 기반 |
|            | CAB SIM                     | `Marshall 1960`                                 | Marshall 1960 캐비닛       |
| AMP EQ | Gain | 5.0~5.5 (12시) | 코드 분해능 위해 게인 절제 |
| | Bass | 5.0 (12시) | |
| | Mid | 6.0 (1시) | 화사하고 시원한 High-Mid |
| | Treble | 6.5 (1~2시) | |
| | Presence | 6.5 (1~2시) | |
| NOISE GATE | Power | ON | 깔끔한 차단 |
| | Position | FIRST | |
| | Threshold | −50dB (12시) | 자연스러운 감쇄 |
| | Release | 150ms (10시) | |
| | Depth | −60dB (12시) | |
| COMPRESSOR | Power | ON | 펀치감 확보 |
| | Position | PRE | |
| | Threshold | 12시 | |
| | Gain | 0dB (2시) | |
| | Attack | 26ms (12시) | |

### 물리 페달 설정

| 페달 | ON/OFF | 노브/스위치 | 값 |
| --- | --- | --- | --- |
| [[tc-electronic-polytune-3]] | ON (상시) | Buffer | Bonafide Buffer ON |
| [[fulltone-ocd]] | ON (상시) | HP/LP | HP |
| | | Volume | 2시 |
| | | Drive | 9~10시 |
| | | Tone | 1시 |
| [[suhr-riot]] | OFF | - | - |
| [[mooer-pure-booster]] | OFF (솔로 시 ON) | Volume | 2시 |
| | | Gain | 9시 |
| | | Bass | 12시 |
| | | Treble | 12시 |
| [[fairfield-circuitry-meet-maude]] | OFF | - | - |
| [[wampler-terraform]] | OFF | - | - |
| [[boss-dd-7]] | OFF (솔로·탭핑 시 ON) | Mode | 800ms |
| | | E.Level | 12시 |
| | | F.Back | 1시 |
| | | D.Time | 템포 맞춤 |
| [[neunaber-immerse]] | ON (상시) | Mode | Plate |
| | | Mix | 10시 |
| | | Depth | 11시 |
| | | Tone/Time | 12시 |

## Play (곡 진행별 톤 변경)

> 기본 톤(OCD HP 상시 + Immerse) 유지. 솔로에서 Pure Boost로 음량 부스트, 인트로 탭핑에서 DD-7 + 넥 픽업 전환.

### 1. 리프 / 백킹

| 조작 대상 | 상태 |
| --- | --- |
| TONEX AMP SIM | `Disclosed Secret` (리프) |
| [[fulltone-ocd]] | ON (HP, 고음 엣지 + 5150 게인 결합) |
| [[mooer-pure-booster]] / [[boss-dd-7]] | OFF |

- 화려한 하이게인 리프, 6줄 코드 분리 유지

### 2. 솔로 / 리드

| 조작 대상 | 변경 |
| --- | --- |
| TONEX AMP SIM | `Disclosed Secret` → **`High Value Secret`** (솔로 전용) |
| [[mooer-pure-booster]] | OFF → **ON** (음색 변화 없이 볼륨만 상승) |
| [[boss-dd-7]] | OFF → **ON** (서스틴 지원) |

- 부스터는 드라이브 뒷단 → 톤 찌그러짐 없이 솔로 음량만 펌핑 ([[booster-pedal-position]])

### 3. 인트로 탭핑

| 조작 대상 | 변경 |
| --- | --- |
| 기타 픽업 | 브릿지 → **넥으로 전환** |
| [[boss-dd-7]] | OFF → **ON** (탭핑 라인 유려한 공간감) |
| [[mooer-pure-booster]] | OFF |

- 넥 픽업 + DD-7 조합으로 탭핑 라인의 부드러운 서스틴·공간감 확보

## 관련 문서

- [[signal-chain]]
- [[booster-pedal-position]]
- [[disclosed-secret]]

---
type: preset
artist: 럼블피쉬
song: 예감 좋은 날
session: SOLE
tags:
  - preset
  - k-rock
  - crunch
guitar: "[[fender-mx-stratocastor-2016]]"
amp-sim: "[[wrong-input]]"
created: 2026-08-02
updated: 2026-08-02
---

# 럼블피쉬 - 예감 좋은 날 (SOLE)

> [!info] 사운드 컨셉
> 2000년대 K-Pop 모던 록의 청량하고 시원한 백킹 톤. 터져 나오는 기타 솔로와의 대비.

## 사용 장비 · 시그널 체인

| 구분 | 장비 |
| --- | --- |
| 기타 | [[fender-mx-stratocastor-2016]] |
| 메인 앰프 시뮬 | [[wrong-input]] (Marshall JCM800 기반) |
| 활성 페달 | [[tc-electronic-polytune-3]], [[fulltone-ocd]], [[neunaber-immerse]] |
| 솔로 부스트 | [[mooer-pure-booster]], [[boss-dd-7]] (솔로 시 ON) |

```mermaid
flowchart LR
  G[기타] --> PT[Polytune 3<br/>ON·버퍼] --> OCD[OCD<br/>ON·LP] --> RIOT[Riot<br/>OFF] --> BST[Pure Boost<br/>솔로 ON] --> TX[TONEX<br/>Wrong Input] --> DD7[DD-7<br/>솔로 ON] --> IMM[Immerse<br/>ON·Plate] --> IF[인터페이스]
```

## 기본 톤

### TONEX 설정

| 구분 | 모듈 / 파라미터 | 설정값 | 비고 |
| --- | --- | --- | --- |
| AMP & CAB | AMP SIM | `Wrong Input` | Marshall JCM 800 기반 |
| | CAB SIM | `Marshall 1960BV` | Marshall 1960BV 캐비닛 |
| AMP EQ | Gain | 4.0~4.5 (11시) | 청량한 약한 크런치 |
| | Bass | 5.0 (12시) | |
| | Mid | 6.5 (1시) | 시원한 쇳소리와 미드 엣지 |
| | Treble | 6.5 (1시) | |
| | Presence | 6.5 (1시) | |
| NOISE GATE | Power | ON | 앞단 노이즈 차단 |
| | Position | FIRST | |
| | Threshold | −55~−60dB (10~11시) | 여음 보존 세팅 |
| | Release | 100~150ms (10시) | |
| | Depth | −60dB (12시) | |
| COMPRESSOR | Power | ON | 리듬 스트로크 안정화 |
| | Position | PRE | |
| | Threshold | 11~12시 | 리듬 안정화 |
| | Gain | 0dB (2시) | |
| | Attack | 11~12시 | |

### 물리 페달 설정

| 페달 | ON/OFF | 노브/스위치 | 값 |
| --- | --- | --- | --- |
| [[tc-electronic-polytune-3]] | ON (상시) | Buffer | Bonafide Buffer ON |
| [[fulltone-ocd]] | ON (상시) | HP/LP | LP |
| | | Volume | 12시 |
| | | Drive | 9~10시 |
| | | Tone | 12시 |
| [[suhr-riot]] | OFF | - | - |
| [[mooer-pure-booster]] | OFF (솔로 ON) | Volume | 2~3시 (볼륨 부스팅) |
| | | Gain | 9시 |
| [[fairfield-circuitry-meet-maude]] | OFF | - | - |
| [[wampler-terraform]] | OFF | - | - |
| [[boss-dd-7]] | OFF (솔로 ON) | Mode | 800ms 또는 Analog |
| | | E.Level | 10~11시 |
| | | F.Back | 10시 |
| [[neunaber-immerse]] | ON (상시) | Mode | Plate |
| | | Mix | 9~10시 |
| | | Depth | 10시 |
| | | Tone/Time | 12시 |

## Play (곡 진행별 톤 변경)

> 기본 톤(OCD LP 크런치 + Immerse) 유지, 솔로에서 풋 페달로만 부스트

### 1. 백킹 / 반주

| 조작 대상 | 상태 |
| --- | --- |
| [[fulltone-ocd]] | ON (LP, 청량한 크런치 부스팅) |
| [[mooer-pure-booster]] / [[boss-dd-7]] | OFF |

- LP 모드 OCD가 JCM800 크런치를 투명하고 찰랑거리게 부스팅 → 청량한 백킹

### 2. 솔로 / 리드

| 조작 대상 | 변경 |
| --- | --- |
| [[mooer-pure-booster]] | OFF → **ON** (순수 볼륨 펌핑) |
| [[boss-dd-7]] | OFF → **ON** (깔끔한 딜레이) |

- 부스터는 드라이브 뒷단 → 게인 추가 없이 볼륨만 펌핑, 솔로가 반주를 압도 ([[booster-pedal-position]])

## 관련 문서

- [[signal-chain]]
- [[wrong-input]]
- [[booster-pedal-position]]

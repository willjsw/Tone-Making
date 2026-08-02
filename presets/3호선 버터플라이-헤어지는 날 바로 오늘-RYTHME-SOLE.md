---
type: preset
artist: 3호선 버터플라이
song: 헤어지는 날 바로 오늘
session: RYTHME-SOLE
tags:
  - preset
  - shoegaze
  - dream-pop
  - wall-of-sound
guitar: "[[fender-mx-stratocastor-2016]]"
amp-sim: "[[polite-twin]]"
created: 2026-08-02
updated: 2026-08-02
---

# 3호선 버터플라이 - 헤어지는 날 바로 오늘 (RYTHME-SOLE)

> [!info] 사운드 컨셉
> 거대한 공간감 속에 거칠게 부서지는 노이즈. 소리의 장벽(Wall of Sound)을 구축하는 슈게이징 / 드림팝 사운드.

## 사용 장비 · 시그널 체인

| 구분 | 장비 |
| --- | --- |
| 기타 | [[fender-mx-stratocastor-2016]] |
| 메인 앰프 시뮬 | [[polite-twin]] (Fender Twin Reverb 기반) |
| 상시 활성 페달 | [[tc-electronic-polytune-3]], [[fairfield-circuitry-meet-maude]], [[suhr-riot]], [[wampler-terraform]], [[boss-dd-7]], [[neunaber-immerse]] |
| 특징 | 거의 전 페달 상시 ON — 레이어 중첩으로 Wall of Sound 구축 |

```mermaid
flowchart LR
  G[기타] --> PT[Polytune 3<br/>ON·버퍼] --> MM[Meet Maude<br/>ON·앞단 딜레이] --> RIOT[Riot<br/>ON·과격] --> TX[TONEX<br/>Polite Twin] --> TF[Terraform<br/>ON·Flanger/Chorus] --> DD7[DD-7<br/>ON·Modulate] --> IMM[Immerse<br/>ON·W3T/Wet] --> IF[인터페이스]
```

## 기본 톤

### TONEX 설정

| 구분 | 모듈 / 파라미터 | 설정값 | 비고 |
| --- | --- | --- | --- |
| AMP & CAB | AMP SIM | `Polite Twin` | Fender Twin Reverb '65 기반 |
| | CAB SIM | `Fender Twin Reverb '65` | Fender Twin Reverb '65 캐비닛 |
| AMP EQ | Gain | 3.0~4.0 (10시) | 넓은 헤드룸의 투명 클린 |
| | Bass | 5.0 (12시) | |
| | Mid | 5.0 (12시) | 이펙터 질감을 온전히 수용 |
| | Treble | 6.0 (1시) | |
| | Presence | 5.0 (12시) | |
| NOISE GATE | Power | OFF | 피드백 노이즈 활용 |
| | Threshold | −100dB (7시 가장 왼쪽) | 게이트 미작동 세팅 |
| | Release | 20ms (7시) | |
| | Depth | −60dB (12시) | |
| COMPRESSOR | Power | ON | 롱 서스틴 확보 |
| | Position | PRE | |
| | Threshold | 10시 | |
| | Gain | 0dB (2시) | |
| | Attack | 7시 (가장 왼쪽, 둥근 어택) | |

### 물리 페달 설정

| 페달 | ON/OFF | 노브·스위치 |
| --- | --- | --- |
| [[tc-electronic-polytune-3]] | ON (상시) | Bonafide Buffer ON |
| [[fulltone-ocd]] | OFF | - |
| [[suhr-riot]] | ON (상시) | Voice 가운데 또는 왼쪽 / Level 12시 / Dist 2~3시(과격함) / Tone 1~2시 |
| [[mooer-pure-booster]] | OFF | - |
| [[fairfield-circuitry-meet-maude]] | ON (상시) | Time 11시 / Fbk 1시 / Mix 1시 (앰프 앞단 아날로그 딜레이) |
| [[wampler-terraform]] | ON (상시) | Flanger 또는 Chorus / Rate 10시 / Depth 2시 / Blend 12시 |
| [[boss-dd-7]] | ON (상시) | Modulate / E.Level 1~2시(원음 수준) / F.Back 2시 / D.Time 12~1시 |
| [[neunaber-immerse]] | ON (상시) | W3T 또는 Wet / Mix 3시 이상(압도적) / Depth 3시 이상 / Tone·Time 1시 |

## Play (곡 진행별 톤 변경 — 레이어 구축)

> 거의 전 페달 상시 ON. 파트 전환보다 레이어를 쌓아 소리의 장벽을 완성하는 구성.

### 1. 인풋단 — 지저분한 아날로그 잔향

| 조작 대상 | 상태 |
| --- | --- |
| [[fairfield-circuitry-meet-maude]] | ON (앰프 앞단 아날로그 딜레이) |
| [[suhr-riot]] | ON (Dist 2~3시, 퍼즈에 가까운 과격한 장벽) |

- Meet Maude가 TONEX 앞단에서 찌그러지는 인풋 잔향 형성 → Riot이 그 위에 거친 디스토션 장벽 구축

### 2. 앰프 뒷단 — 모듈레이션 + 공간계 압도

| 조작 대상 | 상태 |
| --- | --- |
| [[wampler-terraform]] | ON (Flanger/Chorus, 일렁이는 모듈레이션) |
| [[boss-dd-7]] | ON (Modulate, 디지털 딜레이) |
| [[neunaber-immerse]] | ON (W3T/Wet, Mix 3시 이상 압도적 리버브) |

- TONEX 뒷단에서 모듈레이션 → 디지털 딜레이 → 압도적 Wet 리버브를 순차 중첩하여 슈게이징 사운드 완결

## 관련 문서

- [[signal-chain]]
- [[polite-twin]]

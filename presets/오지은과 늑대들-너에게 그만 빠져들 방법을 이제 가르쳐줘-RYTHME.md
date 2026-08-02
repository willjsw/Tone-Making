---
type: preset
artist: 오지은과 늑대들
song: 너에게 그만 빠져들 방법을 이제 가르쳐줘
session: RYTHME
tags:
  - preset
  - indie-rock
  - dynamic-drive
guitar: "[[fender-mx-stratocastor-2016]]"
amp-sim: "[[spongy-blues-v2]]"
created: 2026-08-02
updated: 2026-08-02
---

# 오지은과 늑대들 - 너에게 그만 빠져들 방법을 이제 가르쳐줘 (RYTHME)

> [!info] 사운드 컨셉
> 빈티지하고 쫀득한 인디 록 드라이브. 피킹 강약에 다이내믹이 예민하게 반응하는 손맛 중심 사운드.

## 사용 장비 · 시그널 체인

| 구분 | 장비 |
| --- | --- |
| 기타 | [[fender-mx-stratocastor-2016]] |
| 앰프 시뮬 | [[spongy-blues-v2]] (Fender 65 Deluxe Reverb 기반) |
| 활성 페달 | [[tc-electronic-polytune-3]], [[fulltone-ocd]], [[neunaber-immerse]] |

```mermaid
flowchart LR
  G[기타] --> PT[Polytune 3<br/>ON·버퍼] --> OCD[OCD<br/>ON·HP] --> TX[TONEX<br/>Spongy Blues v2<br/>Gate OFF·Comp 최소] --> IMM[Immerse<br/>ON·Spring] --> IF[인터페이스]
```

## 기본 톤

### TONEX 설정

| 구분 | 모듈 / 파라미터 | 설정값 | 비고 |
| --- | --- | --- | --- |
| AMP & CAB | AMP SIM | `Spongy Blues v2` | Fender 65 Deluxe Reverb 기반 |
| | CAB SIM | `Fender 65 Deluxe Reverb` | Fender 65 Deluxe Reverb 캐비닛 |
| AMP EQ | Gain | 5.5 (12~1시) | 두툼한 로우미드 형성 |
| | Bass | 6.0 (1시) | |
| | Mid | 7.0 (2시, 쫀득) | 쇳소리 억제한 따뜻한 톤 |
| | Treble | 5.0 (12시) | |
| | Presence | 5.0 (12시) | |
| NOISE GATE | Power | **OFF** | 터치 다이내믹스 보존 |
| | Threshold | −100dB (7시 최좌) | 게이트 미작동 세팅 |
| | Release | 20ms (7시) | |
| | Depth | −60dB (12시) | |
| COMPRESSOR | Power | ON | 압축 최소 |
| | Position | PRE | |
| | Threshold | 9시 (압축 최소) | 피킹 다이내믹스 확보 |
| | Gain | 0dB (2시) | |
| | Attack | 11~12시 | |

### 물리 페달 설정

| 페달 | ON/OFF | 노브·스위치 |
| --- | --- | --- |
| [[tc-electronic-polytune-3]] | ON (상시) | Bonafide Buffer ON |
| [[fulltone-ocd]] | ON (상시) | HP · Vol 12~1시 / Drive 10~11시 / Tone 11시 |
| [[suhr-riot]] | OFF | - |
| [[mooer-pure-booster]] | OFF | - |
| [[fairfield-circuitry-meet-maude]] | OFF | - |
| [[wampler-terraform]] | OFF | - |
| [[boss-dd-7]] | OFF | - |
| [[neunaber-immerse]] | ON (상시) | Spring / Mix 11~12시 / Depth 11시 / Tone·Time 11시 |

## Play (곡 진행별 톤 변경)

> **피킹 강약 다이내믹 기반 곡** → 파트별 페달 조작 거의 없음. 톤 변화를 발끝이 아닌 오른손 피킹 세기로 만듦.

### 1. 전 파트 공통 (기본 톤 유지)

| 조작 대상 | 상태 |
| --- | --- |
| TONEX AMP SIM | `Spongy Blues v2` (전 곡 고정) |
| [[fulltone-ocd]] | ON (HP, 상시 메인 드라이브) |
| [[neunaber-immerse]] | ON (Spring, 펜더 잔향) |
| 부스터·딜레이·모듈레이션 | 전부 OFF |

- Gate OFF + Comp 최소 → 피킹 뉘앙스 그대로 통과
- 약하게 피킹 → 클린에 가까운 크런치 / 강하게 피킹 → OCD·앰프가 자연 브레이크업
- 톤 스위칭 없이 오른손 다이내믹만으로 벌스↔코러스 강약 표현

## 관련 문서

- [[signal-chain]]
- [[spongy-blues-v2]]

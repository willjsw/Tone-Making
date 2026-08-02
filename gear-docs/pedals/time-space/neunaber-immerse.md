---
type: gear-pedal
category: time-space
maker: Neunaber
model: Immerse Reverberator
tags:
  - gear/pedal
  - time-space
  - reverb
aliases:
  - Immerse
  - Neunaber Immerse
  - 노이나버 이머스
created: 2026-08-02
updated: 2026-08-02
---

# Neunaber Immerse Reverberator

> [!info] 한 줄 요약
> 8프로그램 스테레오 리버브. W3T·Plate·Hall·Spring·Shimmer 등. 체인 최후단 상시 배치. (보유 개체 MkII 추정)

## 개요

- 8가지 리버브 알고리즘 내장 스테레오 리버버레이터
- 스테레오 입출력 + 버퍼드 바이패스 → 시그널 체인 **최후단** 상시 배치 ([[signal-chain]])
- MkI / MkII 세대 구분 존재. 프리셋에 W3T 사용 → 보유 개체는 **MkII 추정** (W3T·Sustain은 MkII 전용)

## 제원

| 항목 | 값 |
| --- | --- |
| 카테고리 | 리버브 (멀티 알고리즘) |
| 바이패스 | Buffered (Trails / Kill-dry 스위치 제공) |
| 전원 | 9~12V DC / 80mA(최소) / (센터 네거티브 판단, 확인 필요) |
| 배터리 | 미지원 |
| 프로그램 | 8종 (MkII 기준) |

## 입출력 단자

| 단자 | 타입 | 용도 |
| --- | --- | --- |
| INPUT | 1/4" 듀얼 (모노/스테레오) | 입력 |
| OUTPUT | 1/4" 버퍼드 스테레오 | 출력 |
| DC IN | — | 전원 |

- 표준 모델은 tap/MIDI/EXP 단자 없음

## 컨트롤

### 노브 (MkII)

> 노브 표기: 7시(0%) ~ 12시(50%) ~ 5시(100%). 라벨은 알고리즘별 재해석됨.

| 노브 | 역할 | 비고 |
| --- | --- | --- |
| Mix | Dry/Wet 비율 | MkII는 50:50 초과 웻까지 조정 가능 |
| Effect Selector (중앙) | 알고리즘 선택 | 8프로그램 |
| Depth | 리버브 디케이 | Echo에서는 반복 수 겸 |
| Time / Tone | 음색 | Echo에서는 딜레이 타임 겸 |

- 일부 프로그램은 Pre-delay / Mod / Blend 파라미터로 노브가 재해석됨

### 스위치

| 컨트롤 | 역할 |
| --- | --- |
| Trails | 바이패스 후 잔향 유지 여부 |
| Kill-dry | Dry 신호 제거 (병렬 루프/믹서용) |

## 모드 상세

### 8 프로그램 (MkII)

| 프로그램 | 특성 |
| --- | --- |
| W3T | MkII 플래그십, 매끄럽고 3차원적, 프리딜레이 최대 200ms |
| Plate | 밝고 확산된 플레이트 |
| Hall | 콘서트홀, Mod 노브 = 모듈레이션 뎁스 |
| Spring | 스프링, Mod 노브 = 모듈레이션 레이트 |
| Sustain | MkII 신규, W3T 기반 무한 홀드/릴리즈 (패드) |
| Echo | 에코 + 리버브, 에코 타임 50–700ms, Blend로 믹스 |
| Detune | 디튠 더블 + 리버브, Blend로 믹스 |
| Shimmer | 신스 패드형 시머, Blend로 믹스 |

### MkI / MkII 차이

| 구분 | MkI | MkII |
| --- | --- | --- |
| 신규 프로그램 | — | W3T, Sustain 추가 |
| Wet 알고리즘 | Wet | W3T로 개선(더 두껍고 웻) |
| Mix 동작 | 드라이~50:50 + kill-dry로 100% 웻 | Mix 노브만으로 웻 우세 믹스까지 연속 |
| 헤드룸 | 기준 | 증가 |

## 주요 톤 셋업 (5종 이상)

| # | 톤 명칭 | 프로그램 · Mix / Depth / Time·Tone | 용도 |
| --- | --- | --- | --- |
| 1 | 화사한 플레이트 | Plate · Mix 10시 / Depth 10~11시 / Tone 12시 | 톤 윤기 (SPYAIR·럼블피쉬) |
| 2 | 펜더 스프링 | Spring · Mix 11~12시 / Depth 11시 / Time 11시 | 찰랑 잔향 (오지은과 늑대들) |
| 3 | 짧은 플레이트 (드라이 제거) | Plate · Mix 10시 / Depth 10시 | 앰프 드라이함만 제거 (Tool) |
| 4 | 압도적 슈게이징 | W3T/Wet · Mix 3시+ / Depth 3시+ / Tone 1시 | Wall of Sound (3호선 버터플라이) |
| 5 | 시머 앰비언트 | Shimmer · Mix 1시 / Depth 2시 / Blend 12시 | 신스 패드 레이어 |
| 6 | 서스테인 패드 | Sustain · Mix 2시 / Depth 2시 | 무한 홀드 패드 |

## 사용 경험 / 특이사항

- 버퍼드 바이패스 전제 → 체인 끝 배치 권장
- 전 프리셋에서 **상시 ON** 리버브로 사용 (곡별 프로그램만 변경)
- 슈게이징 곡에서는 Mix 3시 이상으로 극단적 공간감 형성

## 관련 문서

- [[signal-chain]]
- [[boss-dd-7]]
- [[fairfield-circuitry-meet-maude]]

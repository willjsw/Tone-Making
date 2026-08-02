---
type: gear-pedal
category: modulation
maker: Wampler
model: Terraform
tags:
  - gear/pedal
  - modulation
  - multi-modulation
aliases:
  - Terraform
  - 왬플러 테라폼
created: 2026-08-02
updated: 2026-08-02
---

# Wampler Terraform

> [!info] 한 줄 요약
> 11 이펙트 멀티 모듈레이션. 스테레오 + MIDI + 8프리셋 + Tap Tempo. Variable 노브로 모드별 고유 파라미터 제어.

## 개요

- 11종 모듈레이션 이펙트를 담은 멀티 모듈레이션 페달
- 5노브 중 Variable 노브가 선택 모드마다 고유 파라미터로 자동 전환
- 스테레오 입출력 + TRS MIDI + 익스프레션 + 신호 체인 분할(게인 페달 앞/뒤 배치)
- TONEX 뒷단 배치 → 앰프단 이후 모듈레이션 부가 ([[signal-chain]])

## 제원

| 항목 | 값 |
| --- | --- |
| 카테고리 | 멀티 모듈레이션 (11 이펙트) |
| 바이패스 | Relay True Bypass |
| 전원 | 9V DC 전용(9V 초과 금지) / 155mA |
| 배터리 | 미지원 판단 (고전류, 확인 필요) |
| 프리셋 | 8개 저장 |

## 입출력 단자

| 단자 | 타입 | 용도 |
| --- | --- | --- |
| INPUT | 1/4" (모노/스테레오) | 입력 |
| OUTPUT | 1/4" (스테레오) | 출력 |
| MIDI | TRS (in/thru) | MIDI 제어 |
| EXP | 1/4" | 어사인 가능 익스프레션 페달 |
| DC IN | 센터 네거티브 | 전원 |

## 컨트롤

### 노브 (5개)

> 노브 표기: 7시(0%) ~ 12시(50%) ~ 5시(100%)

| 노브 | 역할 | 비고 |
| --- | --- | --- |
| Volume | 마스터 출력 | 12시 = 0dB(Unity), 7시 = −6dB, 5시 = +6dB |
| Rate | LFO 변조 속도 / 어택 타임 | Tap Tempo 연동 가능 |
| Depth | 변조 깊이 / 음폭 / 필터 범위 | — |
| Blend | Dry/Wet 비율 | 7시 = 100% Dry, 12시 = 50:50, 5시 = 100% Wet |
| Variable | 모드별 고유 가변 파라미터 | 로우컷·피드백·Q·레조넌스·감도 등 자동 전환 |

### 스위치 / 버튼

| 컨트롤 | 동작 | 역할 |
| --- | --- | --- |
| Effect 셀렉터 | 회전 | 11모드 선택 |
| Preset / Save 버튼 | 누름/홀드 | 프리셋 로드·저장 (8개) |
| Normal / Pre-Post 스위치 | 토글 | 신호 라우팅 (게인 페달 앞/뒤) |
| Tap Tempo 풋스위치 | 밟기 | 템포 탭 (LED 인디케이터) |
| Bypass 풋스위치 | 밟기 | On/Off |

## 모드 상세

> [!note] 출처 구분
> 아래 11모드 표는 **사용자 실측·경험 기반**(기존 세팅 문서에서 이관). Variable 노브의 정확한 파라미터는 Chorus/Rotary/U-Vibe/Harmonic Tremolo만 공식 확인, 나머지는 사용자 실측 기반 참고값.

| # | 모드 | 사운드 성향 | Variable 노브 역할 |
| --- | --- | --- | --- |
| 1 | Dimension | 다차원 입체 코러스 (Boss DC-2 스타일/80s 팝) | 로우엔드 감쇄 & 톤 |
| 2 | Chorus | 클래식 아날로그 코러스 (J-Rock/헤비메탈 클린) | 저역량(로우엔드) 보정 ✔공식 |
| 3 | Harm. Trem | 하모닉 트레몰로 (펜더 빈티지 앰프) | 크로스오버 주파수/파형 폭 ✔공식 |
| 4 | Tremolo | 진폭 트레몰로 (볼륨 차단) | 파형 모형 (삼각파↔톱니파↔사각파) |
| 5 | Auto Swell | 볼륨 스웰 / 슬로우 기어 (바이올린 패드) | 피킹 감도 (Sensitivity) |
| 6 | Rotary | 레슬리 회전 스피커 (오르간/록) | 램프 속도 (가속/감속) ✔공식 |
| 7 | U Vibe | 유니바이브 (60s 록/헨드릭스) | 대체 변조 파형 ✔공식 |
| 8 | Phaser | 페이저 (Phase 90 스타일/80s 펑크) | 스테레오 입체감 & 레조넌스 |
| 9 | Flanger | 제트 플랜저 (하드록/메탈) | 피드백 양 (12시=없음, 좌=양/우=음) |
| 10 | Env. Filter | 터치 와우 (피킹 강약 반응) | 피킹 감도 (Sensitivity) |
| 11 | Auto Wah | 오토 와우 (템포 맞춤 스위핑) | 필터 Q값 (얇게↔두툼) |

### 주요 노브 상호작용 (모드별)

| 모드 | Rate | Depth | Blend 특이사항 |
| --- | --- | --- | --- |
| Dimension | 변조 속도 | 찰랑임 깊이 | 5시 방향 시 바이브 |
| Rotary | 고음 나팔 최고 속도 | 저음 우퍼 최고 속도 | 우퍼↔나팔 밸런스 |
| Tremolo | 템포 속도 | 차단 깊이 | 스테레오 스프레드 폭 |
| Auto Swell | 어택 시간 (좌:빠름/우:느림) | 감쇄 깊이 | 5시 = 완전 패드 |
| Flanger | 스위핑 속도 | 최대 시 Through-Zero | Dry/Wet 믹스 |

## 주요 톤 셋업 (5종 이상)

| # | 톤 명칭 | 모드 · Rate / Depth / Blend / Variable | 용도 |
| --- | --- | --- | --- |
| 1 | 청량 클린 코러스 | Chorus · Rate 10시 / Depth 1시 / Blend 12시 | 화사한 클린 백킹 (Limp Bizkit 인트로) |
| 2 | 슈게이징 플랜저 | Flanger · Rate 10시 / Depth 2시 / Blend 12시 / Var 3시+ | 일렁이는 장벽 (3호선 버터플라이) |
| 3 | 은은한 디멘션 | Dimension · Blend 12시 이하 | 자연스러운 입체 클린 |
| 4 | 펑크 페이저 커팅 | Phaser · Rate 9시 / Depth 2시 / Blend 12시 | 시원한 펑크 리프 |
| 5 | 로터리 오르간 | Rotary · Var로 램프 속도 · Tap 가속/감속 | 레슬리 회전감 |
| 6 | 터치 오토와우 | Auto Wah · Var 3시(두꺼운 Q) | 16비트 펑키 커팅 |

## 사용 경험 / 특이사항

- Variable 노브 = 이 페달의 핵심, 모드 전환 시 역할 자동 변경
- Pre-Post 스위치로 드라이브 앞/뒤 자유 배치 → U-Vibe는 드라이브 앞단(Pre)에서 묵직한 저음 울렁임
- 8프리셋 저장 → 곡별 모듈레이션 세팅 즉시 호출

## 관련 문서

- [[signal-chain]]
- [[mxr-analog-chorus]]
- [[boss-dd-7]]

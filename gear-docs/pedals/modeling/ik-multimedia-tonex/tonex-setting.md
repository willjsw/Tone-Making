---
type: gear-pedal-setting
category: modeling
maker: IK Multimedia
model: TONEX Pedal
tags:
  - gear/pedal
  - modeling
  - tonex
  - setting
aliases:
  - TONEX 설정
  - TONEX 모드
created: 2026-08-02
updated: 2026-08-02
---

# TONEX Pedal — 설정 / 모드 상세

> [!info] 한 줄 요약
> 풋스위치 모드(PRESET/BANK/STOMP/TUNE&TAP), 인코더 홀드 설정 진입, LIVE/INTERFACE 운용 모드, BPM·프리셋 구조 정리.

- 페달 개요·컨트롤 물리 배치는 [[tonex]] 참고
- 본 문서는 **진입 가능한 모드/메뉴 구조**와 **운용 설정**에 집중

## 모드 · 메뉴 트리

```text
TONEX Pedal
├── [풋스위치 동작 모드]
│   ├── PRESET 모드
│   │   ├── A / B / C 개별 → 프리셋 선택 · 바이패스
│   │   ├── A+B → 뱅크 다운
│   │   └── B+C → 뱅크 업
│   ├── BANK 모드
│   │   └── 더블스위치로 뱅크 up/down 이동
│   ├── STOMP 모드
│   │   └── 단일 프리셋을 부스트/OD/디스토션/퍼즈처럼 on/off (스톰박스처럼)
│   └── TUNE & TAP 모드  (선택 프리셋 풋스위치 hold 진입)
│       ├── Tuner (MUTE / THRU 설정에 따라 출력 뮤트 여부)
│       └── Tap Tempo (C 풋스위치로 BPM 탭)
│
├── [인코더 hold → 설정 진입]
│   ├── BPM SETUP           # 템포 (딜레이/모듈레이션 동기)
│   ├── PRESET SETUP        # 현재 프리셋 옵션
│   └── GLOBAL SETUP
│       ├── TUNER MODE      : MUTE / THRU / OFF
│       ├── TRIM IN         : 악기 입력 레벨
│       ├── OPERATION MODE  : LIVE / INTERFACE
│       ├── USB OUTPUT ROUTING : STEREO / DUAL
│       ├── CAB (VIR) BYPASS   : 더블 캡 필터링 방지
│       └── MIDI 설정       : 프리셋/파라미터 CC 매핑
│
└── [ADVANCED PARAMETERS]  (PARAMETER 인코더 push)
    ├── NOISE GATE
    ├── COMPRESSOR
    ├── TONE MODEL (Amp/Cab)
    ├── VIR CABINET / IR Loader
    ├── EQ
    ├── MODULATION (chorus/tremolo/phaser/flanger/rotary)
    ├── DELAY (digital/tape)
    └── REVERB (spring1~4/room/plate)
```

## 풋스위치 모드 상세

| 모드 | 동작 | 용도 |
| --- | --- | --- |
| PRESET | A/B/C로 3개 프리셋 즉시 전환 | 곡 파트별 톤 전환 |
| BANK | 더블스위치로 뱅크 이동 | 50뱅크 탐색 |
| STOMP | 단일 프리셋 on/off | 물리 스톰박스처럼 부스트 토글 |
| TUNE & TAP | 튜너 + 탭템포 | 무대 튜닝·템포 입력 |

## 운용 모드 (OPERATION MODE)

| 모드 | 특성 | 오디오 경로 |
| --- | --- | --- |
| LIVE | 라이브 연주용 | 페달 오디오만 출력 |
| INTERFACE | USB 오디오 인터페이스 | USB로 컴퓨터 녹음/모니터/재생 |

### USB OUTPUT ROUTING (INTERFACE 모드)

| 라우팅 | USB OUT 1 | USB OUT 2 | 용도 |
| --- | --- | --- | --- |
| STEREO | 처리 신호 L | 처리 신호 R | 스테레오 녹음 |
| DUAL | 좌측 처리 신호 | DI(dry) 신호 | 리앰프·DI 동시 녹음 |

## 프리셋 구조

```text
150 프리셋 = 50 뱅크 × 3 슬롯(A / B / C)
```

- 각 프리셋에 [[tonex#프리셋 구성 모듈|모듈 체인]] 저장
- PRESET 인코더 hold → 현재 프리셋 저장
- 프리셋에 사용된 앰프 시뮬 상세는 [[tonex-amp-simuls]]

## BPM SETUP

- 딜레이·모듈레이션의 템포 동기 기준
- TUNE & TAP 모드에서 C 풋스위치로 실시간 탭 입력

## GLOBAL SETUP 항목

| 항목 | 옵션 | 설명 |
| --- | --- | --- |
| TUNER MODE | MUTE / THRU / OFF | 튜닝 시 출력 뮤트 여부 |
| TRIM IN | 레벨 | 악기 입력 게인 매칭 |
| OPERATION MODE | LIVE / INTERFACE | 라이브 ↔ 인터페이스 |
| USB OUTPUT ROUTING | STEREO / DUAL | INTERFACE 모드 라우팅 |
| CAB BYPASS | ON/OFF | 외부 IR 사용 시 더블 캡 방지 |
| MIDI | CC 매핑 | 프리셋/파라미터 원격 제어 |

## 관련 문서

- [[tonex]] — 개요·물리 컨트롤
- [[tonex-amp-simuls]] — 프리셋별 앰프 시뮬
- [[tonex-editor]] — 편집 소프트웨어
- [[signal-chain]]

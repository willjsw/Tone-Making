---
type: gear-pedal
category: time-space
maker: Fairfield Circuitry
model: Meet Maude
tags:
  - gear/pedal
  - time-space
  - delay
  - analog-delay
aliases:
  - Meet Maude
  - 미트 모드
created: 2026-08-02
updated: 2026-08-02
---

# Fairfield Circuitry Meet Maude

> [!info] 한 줄 요약
> 올아날로그 BBD 딜레이. 온보드 컴프레서 + 3단 모듈레이터 + CV 잭. Pre-Amp 배치로 지저분한 유기적 잔향.

## 개요

- 버킷 브리게이드(BBD) 소자 기반 올아날로그 딜레이
- 온보드 컴프레서("C") + 3단 모듈레이터("M") + CV 잭으로 다채로운 변조
- TONEX **앞단(Pre-Amp)** 배치 → 아날로그 반복음이 앰프 시뮬을 함께 통과하며 왜곡 → 지저분·유기적 잔향 ([[signal-chain]])
- 셀프 오실레이션 가능 → 발진 사운드 연출

## 제원

| 항목 | 값 |
| --- | --- |
| 카테고리 | 아날로그 BBD 딜레이 |
| 바이패스 | True Bypass |
| 전원 | 9~9.6V DC / 60mA / 2.1mm (센터 네거티브 판단, 확인 필요) |
| 배터리 | 미지원 (DC 전용) |
| 딜레이 타임 | 50–500ms |
| 크기 | 약 4.7 × 3.8 in |

## 입출력 단자

| 단자 | 타입 | 용도 |
| --- | --- | --- |
| INPUT | 1/4" 모노 (1MΩ) | 입력 |
| OUTPUT | 1/4" 모노 (1kΩ) | 출력 |
| CV | 1/4" 스테레오 | 익스프레션(Time/Feedback) 또는 외부 이펙트 루프 (0~+5V) |
| DC IN | 2.1mm | 전원 |

## 컨트롤

### 노브

> 노브 표기: 7시(0%) ~ 12시(50%) ~ 5시(100%)

| 노브 | 역할 | 비고 |
| --- | --- | --- |
| Time | 딜레이 타임 | 50–500ms |
| Feedback | 반복 수 | 高 = 셀프 오실레이션 |
| Mix | Dry/Wet 비율 | — |
| Tone | 음색 | CW = 고역 강조, CCW = 저역 강조, 센터 = 로우미드 약간 감쇠 |
| Volume | 출력 레벨 | — |

### 토글 스위치

| 컨트롤 | 포지션 | 역할 |
| --- | --- | --- |
| "C" 토글 | ON/OFF | 온보드 컴프레서 (반복을 타이트하게, 밀도 부가) |
| "M" 토글 | 0 / 1 / 2 | 모듈레이터 3단계 (0=없음, 1=소량, 2=대량) |

- CV 잭 동작(Time/Feedback 제어 또는 외부 루프)은 내부 스위치로 설정

## 모드 상세

- 컴프레서 ON → 반복음 압축으로 밀도·지속감 증가, 발진 시 톤 안정화
- 모듈레이터 2단 → 테이프 딜레이 같은 흔들리는 워블 잔향
- Pre-Amp 배치 시 반복음이 뒷단 드라이브/앰프 시뮬로 재입력 → 왜곡된 아날로그 텍스처

## 주요 톤 셋업 (5종 이상)

| # | 톤 명칭 | Time / Feedback / Mix / Tone · C / M | 용도 |
| --- | --- | --- | --- |
| 1 | 슈게이징 프리앰프 딜레이 | Time 11시 / Fbk 1시 / Mix 1시 / Tone 12시 · C OFF / M 0 | 지저분한 앰프 앞단 잔향 (3호선 버터플라이) |
| 2 | 타이트 슬랩백 | Time 9시 / Fbk 9시 / Mix 11시 / Tone 1시 · C ON / M 0 | 짧고 단단한 반복 |
| 3 | 워블 테이프 딜레이 | Time 1시 / Fbk 12시 / Mix 12시 / Tone 11시 · C ON / M 2 | 흔들리는 아날로그 잔향 |
| 4 | 셀프 오실레이션 | Time 임의 / Fbk 5시 / Mix 1시 / Tone 12시 · C ON / M 1 | 발진 사운드 연출 |
| 5 | 앰비언트 롱 | Time 4시 / Fbk 2시 / Mix 1시 / Tone 11시 · C ON / M 1 | 긴 공간 잔향 |
| 6 | CV 스윕 | CV에 EXP 연결 · Time 제어 | 실시간 딜레이 타임 벤딩 |

## 사용 경험 / 특이사항

- 배터리 슬롯 없음 → 파워 서플라이 필수, 60mA 소비
- Pre/Post 배치에 따라 성격 급변 → Pre = 지저분·유기적, Post = 깨끗한 딜레이 ([[signal-chain]])
- Tap Tempo·프리셋 저장 없음 → 딜레이 타임은 노브 수동 세팅

## 관련 문서

- [[signal-chain]]
- [[boss-dd-7]]
- [[neunaber-immerse]]

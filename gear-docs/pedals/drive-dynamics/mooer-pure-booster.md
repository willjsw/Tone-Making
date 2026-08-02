---
type: gear-pedal
category: drive-dynamics
maker: Mooer
model: Pure Boost
tags:
  - gear/pedal
  - drive-dynamics
  - booster
  - clean-boost
  - eq
aliases:
  - Pure Boost
  - Pure Booster
  - 퓨어부스트
  - 무어 부스터
created: 2026-08-02
updated: 2026-08-02
---

# Mooer Pure Boost

> [!info] 한 줄 요약
> 클린 부스터 + 2밴드 EQ 미니 페달. 클리핑 없는 순수 출력 부스트용.

## 개요

- 클린 부스터 + 2밴드(Treble/Bass) EQ를 내장한 미니 사이즈 페달
- **정식명은 "Pure Boost"** (파일명 `mooer-pure-booster` 유지, 표기는 Pure Boost가 정확)
- 클리핑 회로 없음 → 순수 클린 부스트(최대 +20dB), 원 톤 유지하며 게인/음량만 증폭
- 배치: 드라이브 앞(솔로 게인 푸시) / 뒤(순수 음량 부스트) 모두 활용 → [[booster-pedal-position]] 참고 ([[signal-chain]])

## 제원

| 항목 | 값 |
| --- | --- |
| 카테고리 | 클린 부스터 / EQ |
| 바이패스 | True Bypass |
| 전원 | 9V DC / 약 6mA (참고값) / 센터 네거티브 |
| 배터리 | 미지원 (DC 전용) |
| 최대 부스트 | +20dB (클린) |
| EQ | Treble / Bass ±15dB (2밴드) |
| 크기 | 93.5 × 42 × 52 mm |
| 무게 | 160g (풀 메탈) |

## 입출력 단자

| 단자 | 타입 | 용도 |
| --- | --- | --- |
| INPUT | 1/4" TS (1MΩ) | 기타 입력 |
| OUTPUT | 1/4" TS (10kΩ) | 다음 페달 출력 |
| DC IN | 센터 네거티브 | 전원 |

## 컨트롤

### 노브

> 노브 표기: 7시(0%) ~ 12시(50%) ~ 5시(100%)

| 노브 | 역할 | 비고 |
| --- | --- | --- |
| Volume | 출력 부스트 레벨 | 최종 음량 |
| Gain | 게인/부스트량 | 클린 유지 (클리핑 없음) |
| Treble | 고역 EQ | 12시, 50% = 뉴트럴, ±15dB |
| Bass | 저역 EQ | 12시, 50% = 뉴트럴, ±15dB |

### 스위치 / 버튼

| 컨트롤 | 포지션/동작 | 역할 |
| --- | --- | --- |
| 풋스위치 ×1 | 밟기 | On/Off (True Bypass) |

- 토글/모드 셀렉터 스위치 없음

## 모드 상세

- 단일 모드 페달 (모드 스위치 없음)
- 클리핑 회로 없는 클린 부스트 → 앰프/드라이브 입력단 푸시 또는 순수 음량 증폭
- Treble/Bass EQ로 부스트 시 음색 보정 가능 (톤 성형형 부스터)

## 주요 톤 셋업 (5종 이상)

| # | 톤 명칭 | Volume / Gain / Treble / Bass | 용도 |
| --- | --- | --- | --- |
| 1 | 솔로 리드 부스트 | Vol 3시(75%) / Gain 12시(50%) / Tre 1시(60%) / Bass 12시(50%) | 솔로 시 음량+미세 밝기 |
| 2 | 순수 클린 부스트 | Vol 2시(70%) / Gain 9시(25%) / Tre 12시 / Bass 12시 | 톤 변화 없이 음량만 |
| 3 | 앰프 푸시 (드라이브 앞) | Vol 4시(85%) / Gain 2시(70%) / Tre 12시 / Bass 11시(45%) | 앰프 입력단 오버드라이브 유도 |
| 4 | 저역 보강 리듬 | Vol 1시(60%) / Gain 11시(45%) / Tre 11시 / Bass 2시(70%) | 두꺼운 리듬 톤 |
| 5 | 브라이트 커팅 | Vol 12시(50%) / Gain 10시(35%) / Tre 3시(75%) / Bass 10시(35%) | 밝고 선명한 커팅 |

## 사용 경험 / 특이사항

- 미니 사이즈(160g)로 보드 공간 절약, 풀 메탈 견고
- **정식 제품명은 Pure Boost** (Booster로 통칭되나 라벨은 Boost)
- 클린 유지가 핵심 → 게인 올려도 하드 클리핑 발생 안 함
- EQ가 ±15dB로 넓어 부스트 겸 톤 성형 페달로도 활용 가능

## 관련 문서

- [[signal-chain]]
- [[booster-pedal-position]]
- [[fulltone-ocd]]
- [[suhr-riot]]

---
type: gear-pedal
category: filter-pitch
maker: TC Electronic
model: PolyTune 3
tags:
  - gear/pedal
  - filter-pitch
  - tuner
  - buffer
aliases:
  - Polytune 3
  - 폴리튠 3
created: 2026-08-02
updated: 2026-08-02
---

# TC Electronic PolyTune 3

> [!info] 한 줄 요약
> 폴리포닉 튜너 + BonaFide 버퍼 내장 페달. 체인 최전방 상시 배치용.

## 개요

- 6현 동시 스트럼 → 전체 현의 음정 상태를 한 번에 표시하는 폴리포닉 튜너
- BonaFide 버퍼 내장 → 임피던스 변환으로 긴 케이블·다수 페달에 의한 고역 손실 방지
- 시그널 체인 **최전방** 상시 배치 → 튜닝 + 버퍼 두 역할 동시 수행 ([[signal-chain]])

## 제원

| 항목 | 값 |
| --- | --- |
| 카테고리 | 튜너 / 버퍼 |
| 바이패스 | True Bypass ↔ Buffered (DIP 전환, 기본 True Bypass) |
| 전원 | 9V DC / 100mA 이상 / 센터 네거티브 (5.5·2.1mm) |
| 배터리 | 미지원 (DC 전용) |
| 크기 | 72 × 122 × 50 mm |
| 무게 | 확인 필요 (공식 미기재) |
| 튜닝 정확도 | 폴리포닉 ±0.1 cent / 스트로브 ±0.02 cent |

## 입출력 단자

| 단자 | 타입 | 용도 |
| --- | --- | --- |
| INPUT | 1/4" TS (1MΩ) | 기타 입력 |
| OUTPUT | 1/4" TS (100Ω) | 다음 페달 출력 |
| USB | Mini-USB | 펌웨어 업데이트 전용 |
| DC IN | 5.5·2.1mm 센터 네거티브 | 전원 |

## 컨트롤

### 스위치 / 버튼

| 컨트롤 | 포지션/동작 | 역할 |
| --- | --- | --- |
| 풋스위치 ×1 | 밟기 | 튜너 On(뮤트/튜닝) ↔ Off(시그널 통과·버퍼) |

### DIP 스위치 (후면 백플레이트 안쪽 2개)

> 실제 유닛 백플레이트 인쇄 확인 권장 (조합 라벨은 개체/펌웨어별 상이 가능)

| 설정                   | 바이패스 모드             | 디스플레이     |
| -------------------- | ------------------- | --------- |
| 둘 다 왼쪽 (기본)          | True Bypass         | 튜너 On 시에만 |
| 위쪽 오른쪽               | Buffered (BonaFide) | 튜너 On 시에만 |
| Buffered + Always-On | Buffered            | 상시 On     |

## 모드 상세

### 튜닝 모드

| 모드                 | 특성                             |
| ------------------ | ------------------------------ |
| Polyphonic         | 6현 동시 스트럼 → 전 현 상태 일괄 표시       |
| Chromatic – Needle | 단음 크로매틱, 니들 디스플레이              |
| Chromatic – Strobe | 초정밀 스트로브 (±0.02 cent)          |
| MonoPoly           | 연주 방식(단선/스트럼) 자동 감지 → 모드 자동 전환 |

- 디스플레이: 주변광 감지 자동 밝기 조절 (Auto-dim)

### 버퍼 모드

- BonaFide 버퍼: 하이 임피던스(1MΩ) 입력 → 로우 임피던스(100Ω) 출력 변환
- 케이블 정전용량에 의한 고역 감쇄 억제 → 톤 손실 방지 ([[booster-pedal-position]]와 무관한 순수 임피던스 매칭)

## 주요 톤 셋업 (활용 시나리오)

| # | 시나리오 | 설정 | 용도 |
| --- | --- | --- | --- |
| 1 | 라이브 상시 버퍼 | DIP Buffered, 최전방 배치 | 긴 케이블 톤 손실 방지 |
| 2 | True Bypass 순정 | DIP True Bypass | 신호 경로 최단 유지 |
| 3 | 무대 폴리 튜닝 | Polyphonic 모드 | 곡 사이 빠른 전체 점검 |
| 4 | 정밀 세팅 | Strobe 모드 | 레코딩 전 정밀 튜닝 |
| 5 | 자동 전환 | MonoPoly | 단음/화음 자동 대응 |

## 사용 경험 / 특이사항

- 배터리 슬롯 없음 → 파워 서플라이 필수
- 프리셋에서 **Bonafide Buffer ON** 상태로 상시 사용 (전 프리셋 공통)

## 관련 문서

- [[signal-chain]]
- [[fulltone-ocd]]

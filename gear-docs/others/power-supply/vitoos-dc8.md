---
type: gear-other
subtype: power-supply
maker: Vitoos
model: DC8
tags:
  - gear/power-supply
  - power
aliases:
  - Vitoos DC8
  - 보드 전원
  - 파워 서플라이
created: 2026-08-02
updated: 2026-08-02
---

# Vitoos DC8 (보드 전원 체계)

> [!info] 한 줄 요약
> 8출력 격리형 페달 파워 서플라이. 9V 300mA ×6 + 조절형(9/12/18V) 1000mA ×2. 본 보드 전 페달 전원 공급.

> [!note] 수치 검증
> 아래 출력 스펙은 리테일러/커뮤니티 자료 기반. 부분 격리 구조·조절형 출력의 정확한 배분은 실제 유닛 라벨 확인 권장(확인 필요).

## 개요

- 페달보드 전용 격리형(Isolated) 파워 서플라이
- 8개 출력 → 본 보드 9개 페달 전원 공급 (일부 데이지체인 병용)
- 격리 출력으로 페달 간 그라운드 루프·노이즈 차단
- FCLC(Foldback Current Limiting Circuit) 과부하·단락 보호

## 제원

| 항목 | 값 |
| --- | --- |
| 카테고리 | 격리형 페달 파워 서플라이 |
| 출력 수 | 8 |
| 9V 출력 | 300mA × 6 |
| 조절형 출력 | 9V / 12V / 18V 전환, 1000mA × 2 |
| 입력 | AC 100–240V, 50/60Hz (어댑터 DC 12V 2000mA) |
| 격리 구조 | 부분 격리 (A/B 조절형 출력이 나머지와 분리) |
| 보호 | FCLC 과전류·단락 보호 |

## 출력 배분 (본 보드 설계)

> 각 페달 소비 전류 기준 배분. TONEX(320mA)는 조절형 1000mA 출력 사용 필수.

| 출력 | 전압 | 정격 | 연결 페달 | 페달 소비 |
| --- | --- | --- | --- | --- |
| 1 | 9V | 300mA | [[tc-electronic-polytune-3]] | 100mA+ |
| 2 | 9V | 300mA | [[fulltone-ocd]] + [[suhr-riot]] (데이지체인) | 약 16mA |
| 3 | 9V | 300mA | [[mooer-pure-booster]] | 6mA |
| 4 | 9V | 300mA | [[fairfield-circuitry-meet-maude]] | 60mA |
| 5 | 9V | 300mA | [[boss-dd-7]] | 60mA |
| 6 | 9V | 300mA | [[neunaber-immerse]] | 80mA |
| 7 (조절형) | 9V | 1000mA | [[tonex]] | 320mA |
| 8 (조절형) | 9V | 1000mA | [[wampler-terraform]] | 155mA |

- 전 페달 9V 센터 네거티브 동작 → 조절형 출력도 9V 세팅 유지
- [[fulltone-ocd]]는 18V 지원 → 조절형 출력에 단독 연결 시 헤드룸 확장 옵션 존재

## 전원 설계 원칙

- **고전류 페달 격리 우선:** [[tonex]](320mA)·[[wampler-terraform]](155mA)는 조절형 1000mA 출력에 단독 배치 → 전류 부족·노이즈 방지
- **저전류 드라이브 묶기:** [[fulltone-ocd]]·[[suhr-riot]](각 8mA)는 데이지체인으로 1출력 공유 가능
- **디지털/공간계 격리:** [[boss-dd-7]]·[[neunaber-immerse]]는 독립 격리 출력 → 디지털 노이즈 유입 차단
- **버퍼/튜너:** [[tc-electronic-polytune-3]] 100mA+ → 단독 출력 권장

## 톤·노이즈 연관

- 격리 출력 → SSS 픽업([[fender-mx-stratocastor-2016]]) 하이게인 시 험 노이즈 외 전원 유래 노이즈 억제
- 데이지체인 시 공유 페달 간 상호 간섭 가능 → 노이즈 예민 페달은 단독 출력 배치

## 사용 경험 / 특이사항

- AC 입력 → 어댑터 DC 12V 2000mA로 본체 구동, 내부에서 각 출력 격리 생성
- 조절형 출력 전압 전환 시 페달 정격 재확인 필수 (18V 설정 후 9V 전용 페달 연결 금지)
- [[audient-id4]]는 USB 버스파워 동작 → DC8 전원 대상 아님

## 관련 문서

- [[signal-chain]]
- [[rockboard-tres-3.1]]
- [[audient-id4]]

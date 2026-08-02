---
type: gear-pedal
category: drive-dynamics
maker: Fulltone
model: OCD V2
tags:
  - gear/pedal
  - drive-dynamics
  - overdrive
aliases:
  - OCD
  - Obsessive Compulsive Drive
  - 풀톤 OCD
created: 2026-08-02
updated: 2026-08-02
---

# Fulltone OCD (V2)

> [!info] 한 줄 요약
> MOSFET 하드 클리핑 오버드라이브. HP/LP 스위치로 British ↔ 투명 성향 전환. 본 보드 메인 드라이브.

## 개요

- Obsessive Compulsive Drive, 오버드라이브~디스토션 경계의 게인 페달
- JFET 옵앰프 오버드라이빙 후 MOSFET 페어 하드 클리핑 → 앰프 라이크한 다이내믹
- 시그널 체인상 [[suhr-riot]] 앞단 배치 → TONEX 앰프 입자를 치밀하게 밀어주는 메인 드라이브 ([[signal-chain]])
- 9~18V 전원 지원 → 18V 시 헤드룸·다이내믹 증가

## 제원

| 항목 | 값 |
| --- | --- |
| 카테고리 | 오버드라이브–디스토션 |
| 바이패스 | True Bypass ↔ Enhanced Bypass (내부 슬라이드, 공장 기본 EB) |
| 전원 | 9~18V DC / 약 8mA / 2.1·5.5mm 센터 네거티브 |
| 배터리 | 지원 (9V, 썸스크류 4개 분리 후 교체) |
| 크기 | 확인 필요 (공식 미기재) |
| 무게 | 확인 필요 (공식 미기재) |

## 입출력 단자

| 단자 | 타입 | 용도 |
| --- | --- | --- |
| INPUT | 1/4" (1MΩ, Class-A JFET 입력단) | 기타/앞단 입력 |
| OUTPUT | 1/4" (10kΩ) | 다음 페달 출력 |
| DC IN | 2.1·5.5mm 센터 네거티브 | 전원 (9~18V) |

## 컨트롤

### 노브

> 노브 표기: 7시(0%) ~ 12시(50%) ~ 5시(100%)

| 노브 | 역할 | 비고 |
| --- | --- | --- |
| Volume | 출력 레벨 (약 20dB 게인, HP에서 더 큼) | 최종 음량 |
| Drive | 디스토션량 | 10시 이하 = 클린 부스트 영역 |
| Tone | 고역 조정 | 12시 = 뉴트럴, CCW = 부드러움, CW = 컷 강조 |

### 스위치

| 컨트롤 | 포지션 | 역할 |
| --- | --- | --- |
| HP/LP 토글 (외부) | HP / LP | 고역·미드 피크 특성 전환 (아래 상세) |
| Bypass 내부 슬라이드 | 위 = Enhanced Bypass / 아래 = True Bypass | 바이패스 방식 선택 (기본 EB) |

## 모드 상세

### HP / LP 스위치 회로 특성

| 모드 | 특성 | 성향 |
| --- | --- | --- |
| HP (High Peak) | Drive 전 구간 디스토션↑ · 볼륨↑ · 1~2kHz 미드 소폭 부스트 | Vox/Marshall "British", 타이트·미드 도드라짐 |
| LP (Low Peak) | 채색 최소, 평탄·투명한 응답 | Blackface/Tweed, 클린 부스트·non-British |

- 회로적으로 패시브 treble-bleed 톤 스택과 함께 고역 성분·미드 피크를 전환
- 정밀 소자값(커패시터/저항)까지는 공식 미기재 → 부품값 확인 필요, 기능적 효과는 매뉴얼 확정

### Enhanced Bypass™

- 공장 기본값 = Enhanced Bypass(버퍼드 출력) → 긴 체인에서 신호 구동력 확보
- 순정 신호 경로 원하면 내부 슬라이드로 True Bypass 전환

### v1.7 → V2 변경점

- 입력 임피던스 330K → 1MΩ (Class-A 2N5457 JFET 입력단 추가)
- 버퍼드 출력 + TB/EB 내부 선택 스위치 신설
- SMT 생산 전환, 저역 캐릭터 증가 (v1.7은 미드 강조 성향)

## 주요 톤 셋업 (5종 이상)

| # | 톤 명칭 | 스위치 · Volume / Drive / Tone | 용도 |
| --- | --- | --- | --- |
| 1 | 상시 크런치 부스트 | HP · Vol 12시 / Drive 10시 / Tone 12시 | TONEX 앞단 상시 푸시 (Tool 계열) |
| 2 | 투명 클린 부스트 | LP · Vol 2시 / Drive 9시 / Tone 12시 | 앰프 원톤 유지 부스트 |
| 3 | British 리드 | HP · Vol 1시 / Drive 1시 / Tone 1시 | 미드 강조 솔로 |
| 4 | 뉴메탈 엣지 | LP · Vol 2시 / Drive 9시 / Tone 12시 | 앰프 저·고역 엣지 부각 (Limp Bizkit 계열) |
| 5 | 두꺼운 오버드라이브 | HP · Vol 11시 / Drive 2시 / Tone 11시 | 밀도 높은 리듬 |
| 6 | 18V 하이헤드룸 | 18V · HP · Vol 12시 / Drive 12시 / Tone 12시 | 다이내믹·헤드룸 극대화 |

## 사용 경험 / 특이사항

- 프리셋 대부분에서 **상시 ON** 메인 드라이브로 사용
- HP = 화려·미드 강조 곡(J-Rock 등), LP = 투명·엣지 곡(뉴메탈·크런치)로 곡별 스위치 운용
- 부스터 배치 상호작용은 [[booster-pedal-position]] 참고

## 관련 문서

- [[signal-chain]]
- [[suhr-riot]]
- [[mooer-pure-booster]]
- [[booster-pedal-position]]

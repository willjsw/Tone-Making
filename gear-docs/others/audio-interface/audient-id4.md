---
type: gear-other
subtype: audio-interface
maker: Audient
model: iD4
tags:
  - gear/audio-interface
  - recording
aliases:
  - Audient iD4
  - iD4
created: 2026-08-02
updated: 2026-08-02
---

# Audient iD4 (오디오 인터페이스)

> [!info] 한 줄 요약
> 2-in/2-out USB 버스파워 인터페이스. Audient 콘솔 마이크 프리앰프 + JFET DI. TONEX/앰프 리턴 신호 수음용.

> [!note] 세대 구분
> 1세대(USB-B, 2in2out) ↔ MkII(USB-C, 루프백) 존재. 커넥터 형태로 세대 확인. 본 문서는 **1세대 기준**.

## 개요

- 데스크톱 2-in/2-out USB 오디오 인터페이스
- Audient 콘솔 설계 마이크 프리앰프 1채널 + JFET 인스트루먼트 DI 1채널
- 시그널 체인 최종단 → [[neunaber-immerse]] 출력을 수음/모니터 ([[signal-chain]])

## 제원

| 항목 | 값 |
| --- | --- |
| 카테고리 | USB 오디오 인터페이스 (2in/2out) |
| 전원 | USB 버스파워 (USB 3.0, 5V 0.9A 이상) |
| 샘플레이트 | 24-bit / 96kHz |
| 컨버터 | A/D 120dB DR, D/A 125.5dB DR |
| 팬텀 파워 | 48V ±4V @ 10mA/채널 |
| 크기·무게 | 확인 필요 (공식 미확보, ~12×10×5cm급) |

## 입출력

| 단자 | 타입 | 용도 |
| --- | --- | --- |
| MIC/LINE IN | 콤보 XLR/TRS | 마이크 프리앰프 (게인 58dB, EIN −129dBu) |
| DI IN | 1/4" | JFET 인스트루먼트 입력 (게인 40dB) |
| LINE OUT 1/2 | 1/4" TRS | 스피커 아웃 |
| HEADPHONES | 1/4" + 3.5mm (dual) | 헤드폰 |
| USB | USB-B (1세대) | 컴퓨터 연결·버스파워 |

## 컨트롤

| 컨트롤 | 역할 |
| --- | --- |
| 대형 모니터/볼륨 노브 | 출력 레벨 (푸시 = ScrollControl / iD 버튼 토글) |
| 마이크 게인 노브 | 프리앰프 게인 |
| DI 게인 노브 | DI 게인 |
| 헤드폰 레벨 | 헤드폰 볼륨 |
| 48V 버튼 | 팬텀 파워 On/Off |
| 스피커 On/Off 버튼 | 모니터 뮤트 |
| Mono 기능 | 모노 모니터링 |
| 시그널/피크 LED | 레벨 미터 |

## 톤 메이킹 연관

- TONEX를 INTERFACE 모드로 USB 연결 시 iD4 불필요 → iD4는 **아날로그 라인/DI 수음** 경로에 사용
- DI 입력으로 앰프 없이 기타 다이렉트 녹음, 이후 리앰프 가능
- 버스파워 동작 → 별도 전원 어댑터 불필요

## 사용 경험 / 특이사항

- 팬텀 48V 버스파워 공급 → 콘덴서 마이크 사용 가능
- 커넥터가 USB-C면 MkII → 루프백·풀 버스파워 팬텀 등 사양 상이

## 관련 문서

- [[signal-chain]]
- [[tonex]]
- [[vitoos-dc8]]

# Tone-Making

일렉트릭 기타 페달 톤 메이킹·세팅 관리 및 지식 축적을 위한 Obsidian 지식 저장소.

## 목적

- 페달보드 시그널 체인·톤 메이킹 원리 정리
- 장비(기타/페달/인터페이스) 제원·사용법 문서화
- 곡별 톤 재현 프리셋 가이드 축적

## 구조

```
Tone-Making
├── knowledge/        # 톤 메이킹 원리·지식
├── gear-docs/        # 장비 문서
│   ├── guitars/
│   ├── pedals/       # filter-pitch / drive-dynamics / modulation / time-space / modeling
│   └── others/       # softwares / audio-interface / board / power-supply
├── presets/          # 곡별 톤 가이드 (LEAD / RYTHME / SOLE)
├── templates/        # 문서 작성 포맷
├── signal-chain.md   # 전체 시그널 체인
├── INDEX.md          # 전체 색인 (MOC)
└── README.md
```

시작점: [INDEX.md](INDEX.md) · [signal-chain.md](signal-chain.md)

## 작성 원칙

- 개조식·명사형 종결어미·간결한 문체
- 시그널 체인 → Mermaid, 세팅값 → 표
- frontmatter 메타데이터 + 태그 + `[[백링크]]`로 문서 간 연결
- 검증되지 않은 수치는 "확인 필요" 명시

## 노브 표기 규칙

- 7시(0%) ~ 12시(50%) ~ 5시(100%)
- 예: `Volume: 12시, 50%`

## Git 관리

- 문서 1개 = 커밋 1개 원칙
- 커밋 메시지: `<작업종류>: <대상> - <설명>` (feat/docs/fix/refactor/chore)
- Obsidian 설정(`.obsidian/`)은 `.gitignore` 제외

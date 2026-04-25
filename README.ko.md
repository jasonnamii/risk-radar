# risk-radar

> 🇺🇸 [English README](./README.md)

**능동적 리스크 예측·모니터링 엔진. Knight의 불확실성, Taleb의 안티프래질리티, Reason의 스위스 치즈, Perrow의 정상사고론 기반 — P×I 매트릭스를 넘어서는 리스크 분석.**

## 사전 요구

- **Claude Cowork 또는 Claude Code** 환경

## 목표

기존 리스크 관리는 위험을 식별해서 매트릭스에 넣는 것으로 끝난다. 이 스킬은 더 깊이 간다: 리스크 유형 분류(Risk vs Uncertainty vs Ambiguity), 시스템 취약성 진단(복잡도×결합도), 인지 편향 디브리프, 안티프래질리티와 HRO 이론 기반 대응 설계.

## 사용 시점 & 방법

리스크 분석, 위험 예측, 리스크 모니터링 언급 시 자동 발동. 3모드: **스캔**(종합 리스크 평가), **업데이트**(기존 리스크 맵 갱신), **딥다이브**(특정 리스크 인과체인 분석). "이 프로젝트 리스크 점검해줘", "리스크 맵 업데이트해줘" 등으로 호출.

## 사용 사례

| 상황 | 프롬프트 | 동작 |
|---|---|---|
| 프로젝트 리스크 스캔 | `"이 프로젝트 리스크 점검해줘"` | Knight 분류 → 6축 스크리닝 → Perrow 시스템 진단 → 다차원 평가 → 인지편향 디브리프 → 대응 설계 |
| 투자 리스크 분석 | `"투자 결정 전에 리스크 스캔해줘"` | Fat-tail 리스크 식별, Flyvbjerg 참조클래스 예측, 바벨형 대응 설계 |
| 리스크 맵 갱신 | `"지난번 리스크 맵 업데이트해줘"` | P×I + 속도 + 연쇄성 업데이트, 편향 재스크리닝, 대응안 유효성 검증 |

## 주요 기능

- **리스크 유형 분류** — Knight 삼분법(Risk/Uncertainty/Ambiguity) × Kaplan&Mikes 3분류(예방가능/전략/외부) 이중 분류 → 관리방법론 자동 분기
- **시스템 취약성 진단** — Perrow의 복잡도×결합도 매트릭스로 "정상사고" 취약 시스템 식별
- **다차원 평가** — P×I + 속도 + 연쇄성 + Fat-tail 가능성 + 탐지 난이도
- **인지편향 디브리프** — 스캔 후 필수. 정상화·가용성·낙관·서사오류·확률무시·유형성 6대 편향 역체크
- **안티프래질리티 설계** — Taleb의 바벨, 옵션성, HRO 원칙 기반 대응 전략
- **허브+스포크 아키텍처** — 경량 허브 + 6개 전문지식 reference 파일

## 연동 스킬

- **[management-skill](https://github.com/jasonnamii/management-skill)** — Red 리스크 발생 시 위기관리(M6) 핸드오프
- **[biz-skill](https://github.com/jasonnamii/biz-skill)** — 전략적 리스크 패턴 매칭
- **[startup-investment](https://github.com/jasonnamii/startup-investment)** — 투자 리스크 → 밸류에이션·텀시트 리스크
- **[planning-skill](https://github.com/jasonnamii/planning-skill)** — 기획 단계 리스크 스캔 연동

## 설치

```bash
git clone https://github.com/jasonnamii/risk-radar.git ~/.claude/skills/risk-radar
```

## 업데이트

```bash
cd ~/.claude/skills/risk-radar && git pull
```

`~/.claude/skills/`에 배치된 스킬은 Claude Code 및 Cowork 세션에서 자동으로 사용 가능합니다.

## Cowork Skills

25개 이상의 커스텀 스킬 중 하나입니다. 전체 카탈로그: [github.com/jasonnamii/cowork-skills](https://github.com/jasonnamii/cowork-skills)

## 라이선스

MIT License — 자유롭게 사용, 수정, 공유 가능합니다.

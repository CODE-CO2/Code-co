# 🐾 반려동물 즉답형 케어 웹앱 (Pre-BM)

> **상태**: 문제정의·탐색 단계(Pre-BM)  
> **목표**: 빠르고 작은 실험으로 **진짜 Pain Point** 신호 확보

---

## 🚀 엘리베이터 픽치
**“반려동물 PHR + 실사용자 경험 DB + 내부 수의학 검증”**을 섞어 보호자에게 **10초 안에 ‘오늘 할 일 3가지’**를 제시하는 **즉답형 케어 웹앱**.  
**25년 하반기** 법·정책 변화로 보호자가 **진료기록 사본을 합법 보유/제출**할 수 있어, **사본 업로드 → 정규화 → 검증 믹스 → 즉답** 루프가 빠르게 확장될 토대가 생깁니다.

---

## 0) 리포지토리 구조 제안
```text
pet-care-app/
├─ README.md
├─ LICENSE
├─ .gitignore
├─ .editorconfig
├─ .gitattributes
├─ .github/
│  ├─ ISSUE_TEMPLATE/
│  │  ├─ bug_report.md
│  │  ├─ feature_request.md
│  │  ├─ research_log.md
│  │  └─ interview_summary.md
│  ├─ PULL_REQUEST_TEMPLATE.md
│  └─ workflows/
│     ├─ ci.yml
│     └─ security.yml
├─ apps/
│  ├─ web/               # Next.js/React
│  └─ api/               # FastAPI
├─ packages/
│  ├─ design-system/
│  └─ sdk/
├─ data/
│  ├─ sample_phr/
│  └─ normalization/spec.md
├─ research/
│  ├─ process/
│  ├─ docs/
│  └─ ethics_privacy/
└─ ops/
   ├─ SECURITY.md
   ├─ COMMS_RULES.md
   ├─ ROADMAP.md
   └─ TEAM_OPS.md

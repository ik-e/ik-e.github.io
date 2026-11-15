---
layout: page
title: "AI 프로젝트 포트폴리오"
permalink: /portfolio/
---

> **목표: 기술을 활용해 사람이 현실에서 겪는 문제를 실제로 해결하는 것.**  
> 문제를 발견하면 필요한 도구를 조사하고 구현합니다. AI와 팀원의 역량을 활용하되 중요한 판단과 실행 결과는 근거로 확인합니다.

[GitHub](https://github.com/ik-e) · [Velog](https://velog.io/@ik_e)

## 대표 프로젝트

### 1. 두바퀴 — 따릉이 시민 문의 지원 시스템 (2026.11)

**문제** · 대여·반납·고장 등 문의에 근거 있는 안내를 제공하고, 자동으로 해결하기 어려운 요청을 담당자에게 맥락과 함께 전달하는 방법을 고민했습니다.

**구현** · Discord 문의 → n8n 분류 및 RAG 검색 → 정보 보완 → Jira 담당자 연결 흐름을 교육용 MVP로 구현했습니다.

**개인 기여** · 5인 팀장(R01)으로서 전체 통합, 핵심 처리 흐름의 마감 조정, VM 배포, 검증 결과 및 제출 자료 취합을 담당했습니다.

**검증과 한계** · RAG 검색·권한 시나리오 16/16 통과, 대표 시연 3흐름·5요청의 저장·감사 기록을 대조했습니다. 일부 장애·중복 처리 시험은 미실행이며 실제 서울시 운영 시스템과 연결한 서비스는 아닙니다.

[공식 팀 GitHub](https://github.com/encore-ai-campus/aio-01-p4-team2) · [공개 산출물](https://github.com/encore-ai-campus/aio-01-p4-team2/tree/main/submission/public) · [개인 역할이 기록된 팀 헌장](https://github.com/encore-ai-campus/aio-01-p4-team2/blob/main/docs/project/TEAM-CHARTER.md)

### 2. 멀티 에이전트 자동 복구 시스템 (2026.10)

**문제** · AI가 내용을 기획하더라도 실제 상태 변경과 장애 대응은 검증 가능한 규칙과 사람의 승인에 연결되어야 했습니다.

**구현** · 가상 게임 이벤트에 AI 기획·검토, 규칙 기반 검증, 사람 승인, 게임 적용, 정책 기반 오류 대응을 연결했습니다.

**개인 기여** · 팀장으로서 체크포인트 통합과 팀 진행을 관리하고 GitHub Actions CI/CD, AWS 배포·복구 및 실행 증거 문서화를 담당했습니다.

**검증과 한계** · 2026-10-13 기준 CI 734건 통과, AWS 정상 업무·화면 시험 17건 통과 기록이 있습니다. 시험 통과가 모든 오류의 자동 복구 성공을 의미하지 않으며 교육용 가상 게임 환경에서 검증했습니다.

[공식 팀 GitHub](https://github.com/encore-ai-campus/aio-01-p3-team2) · [개인 기여 활동 보고서](https://github.com/encore-ai-campus/aio-01-p3-team2/blob/main/docs/ik/프로젝트_활동보고서_2026-10-08_12-13.md) · [배포·검증 증거](https://github.com/encore-ai-campus/aio-01-p3-team2/blob/main/docs/ik/검증산출물/2026-10-13_main_AWS_첫배포.md)

### 3. Agent Capability Map — 개인 탐구 (2026.10–11)

**문제** · AI가 필요한 API·MCP·SDK를 발견하는 것과 이를 사용해 실제 요청을 수행하는 것은 다른 단계라는 점에서 출발했습니다.

**구현** · 서비스, 기능, 연결 방식과 공식 출처 근거를 구조화하고 사람과 AI가 탐색할 수 있는 정적 카탈로그 및 검색 평가 도구를 만들었습니다.

**검증과 한계** · 공개 기록 기준 서비스 7개·기능 16개 표본을 구축했습니다. 후보 발견·문서 확인과 실제 응답·작업 수행을 구별하며, 카탈로그 자체는 외부 작업을 실행하지 않습니다.

[개인 GitHub](https://github.com/ik-e/agent-capability-map) · [자료 범위 및 한계](https://github.com/ik-e/agent-capability-map/blob/main/docs/internet-map-scope-review-2026-11-03.md)

## 다른 팀 프로젝트

교육 과정의 여러 프로젝트에서 팀장을 맡아 목표·역할·협업 방식을 조율했습니다. 아래는 초기 두 프로젝트의 결과물입니다.

| 프로젝트 | 확인 가능한 결과와 개인 역할 | 원본 |
| --- | --- | --- |
| **오케퐁터디** · 1차 | 학습 기록·스터디 관리·AI 학습 분석을 운영 로그와 사용자 평가까지 연결한 팀 프로젝트. README에 자동 테스트 63건 통과 기록 | [공식 GitHub](https://github.com/encore-ai-campus/aio-01-p1-team3) |
| **AI MAFIA** · 2차 | 사람과 AI가 함께하는 게임. Backend 게임 흐름·API, Docker 실행 환경, 기획·설계 문서에 직접 기여 | [공식 GitHub·시연](https://github.com/encore-ai-campus/aio-01-p2-team4) |

## 판단과 시행착오의 기록

- [**15주차 회고 — 빠른 AI 개발과 팀의 이해 속도**](https://velog.io/@ik_e/SK네트웍스-Family-엔코아-AI캠퍼스-AI-오케스트레이션-캠프-1기10월-2주차-회고) · 팀원 자율성을 높여 개발했지만 전체 맥락 공유가 부족해진 경험, 작업 의존성과 AI 도구 사용량, 검증 시점에 대한 고민을 기록했습니다.
- [**Velog 전체 기록**](https://velog.io/@ik_e) · 프로젝트 진행, 학습, 문제 발견과 판단 변경을 일차별로 남기고 있습니다.

---

**기록을 읽는 기준** · 팀의 공동 성과와 제 기여를 구분했습니다. 실행·시험 수치는 당시의 원본 근거를 따르며 미검증 항목과 계획을 완료한 결과로 표현하지 않았습니다.

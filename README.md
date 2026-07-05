# Agentic AI 특강 — 나만의 여행비서 만들기

GIST Agentic AI 강의 자료.

## 구성

| 파일 | 내용 |
|---|---|
| [`slides.html`](slides.html) | 발표자료 (이론 강의, 31장) — LLM의 원리 → 에이전트의 구조 → 실습 도구 |
| [`index.html`](index.html) | 실습 가이드 (10단계) — opencode로 여행비서 에이전트를 만들고, 일반 프롬프트와 결과를 비교 |

GitHub Pages가 켜져 있다면: 실습 가이드는 루트 URL, 발표자료는 `/slides.html`에서 열립니다.

## 실습 개요

1. **실험 A** — 기본 상태의 opencode에 "여행 계획 짜줘"라고 질문하고 결과를 기록
2. **제작** — Plan mode로 설계를 확인하고 Build mode로 여행비서 에이전트(`AGENTS.md` · `trip.md` · MCP 연결)를 생성
3. **실험 B** — 여행비서에게 같은 질문을 다시. 조건 인터뷰 → K-skill·MCP로 실제 데이터 조회 → 일정 확정 → 일정표 웹페이지 생성
4. **비교** — 두 결과의 차이로 Agentic AI의 구성 요소(규칙 · 도구 · 목표)를 확인

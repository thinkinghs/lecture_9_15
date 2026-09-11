# subagent 실습 패키지

「나만의 AI Agent 만들기 — subagent로 문서 업무 자동화 팀 구성」 수업의
실습 자료 폴더. 이 폴더를 통째로 Cowork의 작업 폴더로 지정하고 진행.

## 폴더 구성

| 경로 | 내용 | 사용 교시 |
|---|---|---|
| `docs/report_A_quantum.md` | 양자컴퓨팅 기술동향 보고 (기술기획팀) | 1교시 요약 / 2교시 교차검증·비평 |
| `docs/report_B_quantum.md` | 실증사업 성과·예산 점검 보고 (성과관리팀) | 2교시 교차검증 |
| `docs/minutes_project_review.md` | 중간점검 회의록 | 1교시 보너스 / 2교시 추가 실습 |
| `docs/deliverable_system_report.md` | 용역 완료보고서 (검토 대상 산출물) | 3교시 실습 3A |
| `guidelines/review_guideline_mock.md` | 용역 산출물 검토 지침 (모의) | 3교시 실습 3A |
| `paper/paper_qec_abstract.md` | 논문 국문 초록 및 주요 결과 | 3교시 실습 3B |
| `agents_solutions/` | 완성된 subagent 정의 파일 7개 | 전 교시 (막힐 때 복사용) |

## 사용 방법

- 실습 중 subagent 생성이 막히면 `agents_solutions/`의 해당 파일을
  `.claude/agents/` 폴더로 복사해 진행 가능
- `agents_solutions/` 폴더 자체는 subagent로 인식되지 않음 —
  `.claude/agents/` 아래에 있는 파일만 동작
- 실습 문서에는 수업용으로 의도된 오류가 포함되어 있음 — 문서 내용을
  실제 업무 자료로 사용하지 말 것

## 주의

- 문서에 등장하는 기관·사업·수치·인명은 모두 실습을 위해 만든 가상의
  내용이며 실제 사실과 무관함

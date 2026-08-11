# 과제별 문서 현황 및 표준 양식

> 2026-08-12 기준, 11개 구현 완료 과제의 모든 브랜치 문서 분석 결과

---

## 1. 현재 문서 현황

### B1-1 (Linux 서버 자동화)

| 브랜치 | 문서 |
|--------|------|
| main | QUEST.md, README.md |
| execution | ASSIGNMENT_SPEC.md, README.md |
| planning | ASSIGNMENT_SPEC.md, B1-1.md, CHECKLIST.md, PRESENTATION_SCRIPT.md, README.md, evaluation_question.md |

**누락**: LEARNING.md, eval 브랜치 없음

### B1-2 (시스템 장애 분석)

| 브랜치 | 문서 |
|--------|------|
| main | QUEST.md, README.md, B1-2.md (구버전) |
| eval | eval/result.md, eval/verbal-qa.md, eval/compliance-qa.md |
| docs | docs/reasoning-00~07, docs/incident-priority-matrix.md, docs/reproducibility.md 등 12개 |

**누락**: LEARNING.md

### B2-1 (용돈 기입장)

| 브랜치 | 문서 |
|--------|------|
| master | QUEST.md, README.md |
| eval | Evaluation_Review.md, Mission_Verification.md, README.md, gagye_bu_AtoZ_guide.md |

**누락**: LEARNING.md, eval/ 표준 파일 (result.md, verbal-qa.md)

### B3-1 (해시 테이블)

| 브랜치 | 문서 |
|--------|------|
| master | QUEST.md, README.md, docs/DESIGN.md, docs/STACK_QUEUE_DEQUE.md, docs/구현가이드.md |
| eval | README.md, 미션-mini-redis-구축.md, 평가문항.md |

**누락**: LEARNING.md, eval/ 표준 파일

### B3-2 (파일 변경 추적)

| 브랜치 | 문서 |
|--------|------|
| main | QUEST.md, README.md |
| peer-evaluation | MINI_GIT_COMPREHENSIVE_REPORT.md, PEER_EVALUATION_GUIDE.md, evaluation_scenario_1~4.md |
| plan | B3-2.md, CONSTRAINTS.md, DELIVERABLES.md, FEATURES.md, REQUIREMENTS.md, evaluation_question.md |

**누락**: LEARNING.md, eval 브랜치 없음

### B4-1 (바닐라 웹페이지)

| 브랜치 | 문서 |
|--------|------|
| main | QUEST.md, README.md, LEARNING.md ✅ |
| eval | eval/peer-eval-scenario.md ✅ |

**충분**: 표준 파일 모두 보유

### B4-2 (React SPA)

| 브랜치 | 문서 |
|--------|------|
| main | QUEST.md, README.md, LEARNING.md ✅ |
| eval | eval/result.md, eval/verbal-qa.md |
| docs | docs/reasoning-01~06 |

**충분**: 표준 파일 모두 보유

### B5-1 (SQL 데이터베이스)

| 브랜치 | 문서 |
|--------|------|
| main | QUEST.md, README.md, architecture_design.md, bonus_report.md, docs/complex-query-analysis.md, docs/development-log.md |
| eval | README.md, architecture_design.md, bonus_report.md, 4개 가이드 문서 |

**누락**: LEARNING.md, eval/ 표준 파일

### B5-2 (FastAPI 게시판)

| 브랜치 | 문서 |
|--------|------|
| main | QUEST.md, README.md, docs/ 17개 문서 |
| (eval 브랜치 없음) | — |

**누락**: LEARNING.md, eval 브랜치 없음

### B5-3 (FastAPI 인증)

| 브랜치 | 문서 |
|--------|------|
| develop/main | QUEST.md, README.md, LEARNING.md ✅, GITFLOW.md, IMPLEMENTATION_REPORT.md 등 |
| eval | eval/result.md, eval/verbal-qa.md, eval/peer-eval-scenario.md ✅ |

**충분**: 표준 파일 모두 보유

### B6-2 (AI 코드 도우미)

| 브랜치 | 문서 |
|--------|------|
| main | QUEST.md, README.md, LEARNING.md ✅ |
| eval | eval/result.md, eval/verbal-qa.md, eval/peer-eval-scenario.md ✅ |
| docs | docs/reasoning-01~04 |

**충족**: 표준 파일 모두 보유

---

## 2. 표준 문서 체크리스트

각 과제에 있어야 하는 표준 문서:

| 문서 | 위치 | 필수 | 설명 |
|------|------|------|------|
| QUEST.md | 기본 브랜치 | ✅ | 과제 정보 (미션, 목표, 요구사항, 제약) |
| README.md | 기본 브랜치 | ✅ | 프로젝트 설명, 실행 방법, 테스트 방법 |
| LEARNING.md | 기본 브랜치 | ✅ | 학습 노트 (용어집, 기초, 예제, 잡/워크/워크플로우, 트러블슈팅) |
| eval/result.md | eval 브랜치 | ✅ | 사전평가 결과 |
| eval/verbal-qa.md | eval 브랜치 | ✅ | 동료평가 예상 질문/답변 |
| eval/peer-eval-scenario.md | eval 브랜치 | ✅ | 동료평가 시나리오 (학습→고찰→시도→수정→선택→트러블슈팅) |

---

## 3. 과제별 보유 현황 매트릭스

| 과제 | QUEST | README | LEARNING | eval/result | eval/verbal-qa | eval/scenario | eval 브랜치 |
|------|-------|--------|----------|-------------|----------------|---------------|------------|
| B1-1 | ✅ | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ |
| B1-2 | ✅ | ✅ | ❌ | ✅ | ✅ | ❌ | ✅ |
| B2-1 | ✅ | ✅ | ❌ | ❌ | ❌ | ❌ | ✅(비표준) |
| B3-1 | ✅ | ✅ | ❌ | ❌ | ❌ | ❌ | ✅(비표준) |
| B3-2 | ✅ | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ |
| **B4-1** | ✅ | ✅ | **✅** | ❌ | ❌ | **✅** | ✅ |
| **B4-2** | ✅ | ✅ | **✅** | ✅ | ✅ | ❌ | ✅ |
| B5-1 | ✅ | ✅ | ❌ | ❌ | ❌ | ❌ | ✅(비표준) |
| B5-2 | ✅ | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ |
| **B5-3** | ✅ | ✅ | **✅** | ✅ | ✅ | **✅** | ✅ |
| **B6-2** | ✅ | ✅ | **✅** | ✅ | ✅ | **✅** | ✅ |

### 요약

| 상태 | 과제 |
|------|------|
| **6개 표준 모두 보유** | B4-1(결/result없음), B5-3, B6-2 |
| **LEARNING.md만 보유** | B4-1, B4-2, B5-3, B6-2 (4개) |
| **eval 표준 파일 보유** | B1-2, B4-2, B5-3, B6-2 (4개) |
| **LEARNING.md 누락** | B1-1, B1-2, B2-1, B3-1, B3-2, B5-1, B5-2 (7개) |
| **eval 브랜치 없음** | B1-1, B3-2, B5-2 (3개) |

---

## 4. README 표준 양식

모든 과제의 README.md에 포함되어야 하는 섹션:

```markdown
# {과제명}

> {한 줄 설명}

## 📌 과제 정보

| 항목 | 내용 |
|------|------|
| 과목 | {과목} |
| 난이도 | {난이도} |
| 학습 시간 | {시간} |
| 과제 번호 | {번호} |
| 필수 여부 | {필수/선택} |

---

## 🚀 실행 방법

### 사전 준비
{필요한 도구, 환경}

### 설치
```bash
{설치 명령어}
```

### 실행
```bash
{실행 명령어}
```

### 배포 URL (해당 시)
{배포 URL 또는 "로컬 실행"}

---

## 🧪 테스트 방법

### 자동 테스트 (해당 시)
```bash
{테스트 명령어}
```

### 수동 테스트 시나리오
1. {단계 1}
2. {단계 2}
3. {단계 3}
→ 예상 결과: {결과}

### 테스트 계정 (해당 시)
- ID: {계정}
- PW: {비밀번호}

---

## 🏗️ 프로젝트 구조

```
{디렉토리 트리}
```

---

## 🛠️ 사용 기술

| 기술 | 용도 |
|------|------|
| {기술} | {용도} |

---

## 📖 학습 노트

상세 학습 내용은 [LEARNING.md](LEARNING.md)를 참조하세요.

---

## 📊 평가

- 사전평가: {점수} ({횟수}/3)
- 동료평가: {상태}
- 평가 시나리오: [eval/peer-eval-scenario.md](eval/peer-eval-scenario.md) (eval 브랜치)
```

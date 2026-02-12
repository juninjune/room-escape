# 이머시브 경험 시장 조사 실행 플랜

## TL;DR

> **Quick Summary**: 방탈출 사업의 차별화·프리미엄 전략 수립을 위해 글로벌 이머시브 경험 시장(특히 이머시브 씨어터)을 심층 조사하고, 8개 마크다운 문서로 산출합니다. 기존 gaming-industry-evolution 리서치와 동일한 형식·품질 기준을 따릅니다.
> 
> **Deliverables**:
> - `01_market_overview.md` — 시장 개요
> - `02_immersive_theater_deep_dive.md` — 이머시브 씨어터 장르 심층 분석 ⭐
> - `03_case_studies.md` — 주요 사례 연구 (5개+ 개별 분석)
> - `04_business_models.md` — 비즈니스 모델 분석
> - `05_customer_insights.md` — 고객 인사이트
> - `06_comparison_with_escape_rooms.md` — 방탈출과의 비교
> - `07_trends_and_outlook.md` — 트렌드 및 전망
> - `08_strategic_implications.md` — 사업 적용 전략 (종합)
> - `index.md` 업데이트 — 완성 상태 반영
> - `README.md` 업데이트 — 체크리스트 완료 표시
> 
> **Estimated Effort**: Large (8개 문서, 각 300-600줄, 총 3,500+ 줄)
> **Parallel Execution**: YES - 4 waves
> **Critical Path**: Task 0 → Wave 1 (Tasks 1,3) → Wave 2 (Tasks 2,4,5) → Wave 3 (Tasks 6,7) → Wave 4 (Task 8) → Task 9,10

---

## Context

### Original Request
`immersive-experiences/README.md`에 따라 atlas가 실행할 수 있는 구체적인 조사 플랜을 완성하라.

### Interview Summary
**Key Discussions**:
- README.md 자체가 매우 구체적인 조사 가이드 역할 (조사 과제 4개, 산출물 8개, 데이터 체크리스트 명시)
- 기존 `gaming-industry-evolution` 리서치 (9개 문서, 5,500줄)가 형식·품질 템플릿
- `escape-room-industry` 리서치가 비교 분석의 기반 데이터 제공

**Research Findings**:
- `gaming-industry-evolution/03_animal_crossing_case_study.md` → Executive Summary + 데이터 테이블 + 소스 인용 패턴
- `gaming-industry-evolution/01_gaming_market_overview.md` → YAML frontmatter 구조
- `gaming-industry-evolution/09_application_to_escape_rooms.md` → 종합 전략 문서 패턴
- 현재 `immersive-experiences/`에는 README.md와 index.md만 존재 (리서치 미시작)

### Metis Review
**Identified Gaps** (addressed):
- **02 vs 03 문서 경계 모호** → 02=장르 분석(정의·역사·디자인원칙·글로벌 풍경), 03=개별 사례 연구(쇼별 데이터)로 명확 분리
- **지리적 범위 불명확** → US/UK(데이터 풍부) → 중국/일본(신흥) → 한국(적용 맥락) 순 우선
- **08과 기존 gaming-industry-evolution/09 관계** → 08은 종합 문서, 09 결론을 전제로 이머시브 차원 추가
- **실패 사례 데이터 부족** → "조기 폐막·관객 유지 실패·모델 전환" 사례로 재정의
- **Sleep No More 2023 폐관** → 역사적 성공 사례로 다루고, The Burnt City를 후속작으로 참조
- **시장 규모 정의 분산** → 01에서 분류 체계(taxonomy) 먼저 수립, 정의별 시장 규모 제시
- **사례 연구 5개 미지정** → 6개 사전 지정 (아래 명시)
- **재무 데이터 비공개** → 공개 데이터 기반 추정 방법론 허용 (투명하게 방법론 명시)

---

## Work Objectives

### Core Objective
글로벌 이머시브 경험 시장(특히 이머시브 씨어터)을 심층 분석하여, 방탈출 사업의 차별화 전략·프리미엄 가격 정당화 근거·경험 디자인 인사이트·타겟 고객 전략을 도출한다.

### Concrete Deliverables
- 8개 마크다운 리서치 문서 (`immersive-experiences/01_*.md` ~ `08_*.md`)
- index.md 및 README.md 업데이트 (완료 상태 반영)

### Definition of Done
- [ ] 8개 문서 모두 작성 완료 (각 300줄 이상)
- [ ] 모든 문서에 YAML frontmatter, Executive Summary, 데이터 테이블, 소스 인용 포함
- [ ] README.md 체크리스트 5개 항목 모두 완료 처리
- [ ] 문서 간 교차 참조 정상 작동
- [ ] 총 줄 수 3,500+ 이상

### Must Have
- 이머시브 씨어터 **6개 이상** 사례 심층 분석 (Sleep No More, The Burnt City, Then She Fell, The Great Gatsby Immersive, Secret Cinema, 한국 사례 1-2개)
- 티켓 가격·수익 구조 구체적 데이터 (추정 방법론 포함)
- 방탈출과의 명확한 비교 분석
- 정량적 시장 데이터 (출처 명시, 정의 범위 명시)
- 한국어 작성 (영어 고유명사는 원문 유지)

### Must NOT Have (Guardrails)
- **VR/AR 깊이 분석 금지**: 01_market_overview에서 하나의 소단원으로만 다룸. 별도 분석 없음
- **테마파크/대규모 어트랙션 금지**: Disney, Universal 등 대규모 테마파크 분석 금지. Meow Wolf만 하나의 사례로 허용
- **학술 연극 이론 금지**: 아방가르드 공연 이론 등은 최대 1문단 역사적 맥락으로만
- **K-pop 체험형 콘텐츠 금지**: 01에서 한국 시장 현상으로 간략 언급만. 사례 연구 대상 아님
- **기술 제작 상세 금지**: 조명/음향/향기 장비 스펙 등 기술적 상세 금지 (전략 수준만)
- **코로나 전후 데이터 혼용 금지**: 2019년 이전 데이터는 반드시 "코로나 이전" 명시. 현재 시장은 2022-2025 데이터 중심
- **단일 시장 규모 숫자 제시 금지**: 반드시 정의 범위 명시 + 복수 소스 제시
- **출처 없는 정량 데이터 금지**: 모든 숫자에 소스 인용 필수
- **문서 간 역할 침범 금지** (아래 문서별 MUST NOT 참조)

---

## Verification Strategy

> **UNIVERSAL RULE: ZERO HUMAN INTERVENTION**
>
> ALL tasks in this plan MUST be verifiable WITHOUT any human action.

### Test Decision
- **Infrastructure exists**: N/A (리서치 문서 작성, 코드 아님)
- **Automated tests**: None (코드 테스트 해당 없음)
- **Framework**: None

### Agent-Executed QA Scenarios (MANDATORY — ALL tasks)

모든 문서 작성 태스크에 대해:

**Verification Tool**: Bash (grep, wc, head)

```
Scenario: YAML Frontmatter 검증
  Tool: Bash
  Steps:
    1. head -1 immersive-experiences/{filename}.md → "---" 확인
    2. grep -c "^title:" immersive-experiences/{filename}.md → ≥1
    3. grep -c "^description:" immersive-experiences/{filename}.md → ≥1
    4. grep -c "^layout:" immersive-experiences/{filename}.md → ≥1
    5. grep -c "^category:" immersive-experiences/{filename}.md → ≥1
    6. grep -c "^order:" immersive-experiences/{filename}.md → ≥1
    7. grep -c "^date:" immersive-experiences/{filename}.md → ≥1
    8. grep -c "^tags:" immersive-experiences/{filename}.md → ≥1
  Expected: 모든 필드 존재

Scenario: 문서 길이 및 구조 검증
  Tool: Bash
  Steps:
    1. wc -l immersive-experiences/{filename}.md → ≥{minimum_lines}
    2. grep -c "## " immersive-experiences/{filename}.md → ≥5 (섹션 수)
    3. grep -c "Executive Summary\|📊" immersive-experiences/{filename}.md → ≥1
    4. grep -c "출처\|**출처**\|Source" immersive-experiences/{filename}.md → ≥10
  Expected: 최소 기준 충족

Scenario: 데이터 테이블 존재 검증
  Tool: Bash
  Steps:
    1. grep -c "^|" immersive-experiences/{filename}.md → ≥{minimum_table_rows}
  Expected: 데이터 테이블 행 존재
```

---

## 핵심 정의 및 분류 체계 (모든 태스크의 전제)

### 이머시브 경험(Immersive Experience) 분류

| 카테고리 | 정의 | 본 조사 범위 |
|----------|------|-------------|
| **이머시브 씨어터** | 배우가 주도하는 서사적 몰입 경험. 관객이 공간 내 자유 이동. 퍼즐 목표 없음 | ⭐ 최우선 조사 대상 |
| **체험형 전시** | 예술/미디어 기반 몰입 공간 (teamLab, Meow Wolf) | 01에서 시장 규모로만, 03에서 Meow Wolf 1건만 |
| **VR/AR 경험** | 가상현실/증강현실 기반 체험 | 01에서 시장 규모 1소단원만 |
| **방탈출(Escape Room)** | 퍼즐 해결 목표의 몰입 경험 | 06에서 비교 대상 (이미 별도 리서치 완료) |
| **테마파크 어트랙션** | Disney, Universal 등 대규모 시설 | ❌ 본 조사 범위 밖 |
| **K-pop/팬덤 체험** | BTS 팝업 등 팬덤 기반 체험 | 01에서 한국 현상 간략 언급만 |

### 사전 지정 사례 연구 대상 (6+1건)

| # | 이름 | 소재지 | 선정 이유 |
|---|------|--------|-----------|
| 1 | **Sleep No More** (Punchdrunk/Emursive) | NYC (2011-2023), 상하이 (2016-) | 이머시브 씨어터의 정의를 만든 작품. 12년 운영 데이터 |
| 2 | **The Burnt City** (Punchdrunk) | London (2022-) | Sleep No More의 후속작. 현재 운영 중인 대규모 이머시브 |
| 3 | **Then She Fell** (Third Rail Projects) | NYC (2012-2019) | 소규모·친밀한 모델 (15명). 방탈출과 규모 유사 |
| 4 | **The Great Gatsby Immersive** | London (2022-), NYC (2023-) | 최근 히트작. F&B 통합 모델 |
| 5 | **Secret Cinema** | London/글로벌 | 대규모 (1000명+) 이벤트형 모델. 스케일 비교 |
| 6 | **한국 사례** (위대한 개츠비 서울 / 더 그레이트 / 기타) | 서울 | 한국 시장 맥락. 데이터 가용성에 따라 1-2건 |
| 7 | **Meow Wolf** (보너스) | 미국 다수 | 비씨어터 이머시브. 경험 디자인 참조점 |

---

## Execution Strategy

### Parallel Execution Waves

```
Task 0 (Sequential, FIRST):
└── 분류 체계 수립 & 검색 키워드 표준화

Wave 1 (Parallel, after Task 0):
├── Task 1: 01_market_overview.md (시장 규모 데이터 수집)
└── Task 3: 03_case_studies.md (6+1 개별 사례 데이터 수집)

Wave 2 (Parallel, after Wave 1):
├── Task 2: 02_immersive_theater_deep_dive.md (장르 분석, Wave 1 데이터 참조)
├── Task 4: 04_business_models.md (사례별 재무 데이터, Task 3 참조)
└── Task 5: 05_customer_insights.md (고객 데이터, Task 3 참조)

Wave 3 (Parallel, after Wave 2):
├── Task 6: 06_comparison_with_escape_rooms.md (02-05 + escape-room-industry 비교)
└── Task 7: 07_trends_and_outlook.md (01-05 기반 트렌드 종합)

Wave 4 (Sequential, LAST):
└── Task 8: 08_strategic_implications.md (01-07 + 타 리서치 종합)

Final (Sequential):
├── Task 9: index.md & README.md 업데이트
└── Task 10: 최종 품질 검증 & 데이터 체크리스트 확인
```

### Dependency Matrix

| Task | Depends On | Blocks | Can Parallelize With |
|------|------------|--------|---------------------|
| 0 | None | 1, 3 | None (must be first) |
| 1 | 0 | 2, 6, 7 | 3 |
| 3 | 0 | 2, 4, 5 | 1 |
| 2 | 0, 1, 3 | 6, 7, 8 | 4, 5 |
| 4 | 3 | 6, 8 | 2, 5 |
| 5 | 3 | 6, 8 | 2, 4 |
| 6 | 2, 4, 5 | 8 | 7 |
| 7 | 1, 2, 5 | 8 | 6 |
| 8 | ALL (1-7) | 9, 10 | None (must be last content) |
| 9 | 8 | 10 | None |
| 10 | 9 | None | None (final verification) |

### Agent Dispatch Summary

| Wave | Tasks | Recommended Dispatch |
|------|-------|---------------------|
| 0 | Task 0 | `task(category="writing", load_skills=[], run_in_background=false)` |
| 1 | Tasks 1, 3 | 2x `task(category="writing", load_skills=[], run_in_background=true)` |
| 2 | Tasks 2, 4, 5 | 3x `task(category="writing", load_skills=[], run_in_background=true)` |
| 3 | Tasks 6, 7 | 2x `task(category="writing", load_skills=[], run_in_background=true)` |
| 4 | Task 8 | `task(category="writing", load_skills=[], run_in_background=false)` |
| Final | Tasks 9, 10 | `task(category="quick", load_skills=[], run_in_background=false)` |

---

## TODOs

---

- [x] 0. 분류 체계 수립 & 검색 키워드 표준화

  **What to do**:
  - 이머시브 경험의 분류 체계(taxonomy) 확립 — 위의 "핵심 정의 및 분류 체계" 섹션을 기준으로
  - 각 문서에서 사용할 검색 키워드 목록 표준화
  - "이머시브 경험" 시장 규모 정의 시 포함/제외 범위 확정
  - 코로나 전후(pre-COVID: ~2019 / post-COVID: 2022~) 데이터 구분 기준 확립
  - 통화 표기 규칙: USD 기준, KRW 병기 (환율 명시)
  - 모든 문서에 적용할 YAML frontmatter 템플릿 생성
  - 결과물: 각 후속 태스크에서 참조할 **표준화된 정의·키워드·형식 가이드**를 문서 상단 또는 별도 섹션에 포함

  **Must NOT do**:
  - 시장 데이터 수집 시작하지 않음 (정의 수립만)
  - 개별 사례 연구 시작하지 않음

  **Recommended Agent Profile**:
  - **Category**: `writing`
    - Reason: 리서치 문서 형식·정의 수립 작업
  - **Skills**: []
    - 추가 스킬 불필요 (웹 검색 + 문서 작성)

  **Parallelization**:
  - **Can Run In Parallel**: NO
  - **Parallel Group**: Sequential (must be first)
  - **Blocks**: Tasks 1, 3 (and transitively all)
  - **Blocked By**: None

  **References**:

  **Pattern References**:
  - `gaming-industry-evolution/01_gaming_market_overview.md:1-9` — YAML frontmatter 구조 패턴
  - `gaming-industry-evolution/03_animal_crossing_case_study.md:1-9` — YAML frontmatter 태그 패턴

  **Documentation References**:
  - `immersive-experiences/README.md:102-108` — 검색 키워드 목록
  - `immersive-experiences/README.md:9-13` — 시장 세분화 범위

  **Acceptance Criteria**:

  **Agent-Executed QA Scenarios:**

  ```
  Scenario: 분류 체계 가이드 완성 확인
    Tool: Bash
    Steps:
      1. 분류 체계·정의·키워드·형식 가이드가 문서로 정리되어 후속 태스크에서 참조 가능한지 확인
      2. 최소 6개 이머시브 경험 카테고리 정의 포함
      3. 코로나 전후 데이터 구분 기준 명시 확인
      4. YAML frontmatter 템플릿 포함 확인
    Expected Result: 후속 태스크에서 참조 가능한 표준화된 가이드 완성
  ```

  **Commit**: YES
  - Message: `docs(immersive): establish taxonomy and research standards`
  - Files: (Task 0 결과물)
  - Pre-commit: N/A

---

- [x] 1. 01_market_overview.md — 이머시브 경험 시장 개요 ✅ COMPLETED

  **What to do**:
  - **글로벌 이머시브 경험 시장 규모** 조사 (USD, 복수 소스, 정의별 범위 명시)
    - "이머시브 경험" 전체 시장 (광의)
    - "이머시브 씨어터" 시장 (협의)
    - 각 정의의 포함/제외 항목 명시
  - **지역별 시장 특성** (미국, 유럽, 아시아, 한국)
  - **시장 세분화**: 이머시브 씨어터, VR/AR, 체험형 전시, 방탈출 등의 비중
  - **성장률** 및 CAGR (2020-2025 및 전망)
  - **VR/AR**: 1개 소단원만 (시장 규모, 성장률). 깊이 분석 하지 않음
  - **K-pop/팬덤**: 한국 시장 현상으로 1-2문단만 간략 언급
  - **코로나 전후** 구분 명시

  **Must NOT do**:
  - 개별 이머시브 씨어터 쇼에 대한 상세 분석 (02/03의 영역)
  - VR/AR 시장 깊이 분석 (1소단원 초과 금지)
  - 비즈니스 모델 분석 (04의 영역)

  **Recommended Agent Profile**:
  - **Category**: `writing`
    - Reason: 웹 검색 기반 시장 데이터 수집 + 마크다운 문서 작성
  - **Skills**: []

  **Parallelization**:
  - **Can Run In Parallel**: YES
  - **Parallel Group**: Wave 1 (with Task 3)
  - **Blocks**: Tasks 2, 6, 7
  - **Blocked By**: Task 0

  **References**:

  **Pattern References**:
  - `gaming-industry-evolution/01_gaming_market_overview.md` — 시장 개요 문서의 전체 구조 패턴 (Executive Summary → 글로벌 시장 규모 → 플랫폼별/지역별 분석). 이 패턴을 그대로 따르되, 게임→이머시브 경험으로 변환
  - `gaming-industry-evolution/06_market_share_analysis.md` — 시장 세분화 및 비중 분석 패턴

  **Documentation References**:
  - `immersive-experiences/README.md:9-13` — 시장 개요 조사 항목
  - `immersive-experiences/README.md:57-62` — 정량 데이터 체크리스트 중 시장 규모 항목
  - `immersive-experiences/README.md:96-100` — 추천 리서치 소스

  **External References**:
  - Grand View Research "Immersive Experience Market" — 시장 규모 리포트
  - Allied Market Research "Immersive Technology Market" — 대안 소스
  - Statista "Immersive Entertainment" — 시장 데이터
  - PwC Entertainment & Media Outlook — 시장 전망
  - Eventbrite Pulse Report — 체험형 이벤트 트렌드

  **검색 키워드**:
  - "immersive experience market size 2024 2025"
  - "immersive theater market size global"
  - "experiential entertainment market report"
  - "immersive experience industry growth rate CAGR"
  - "site-specific performance market"

  **Acceptance Criteria**:

  - [ ] YAML frontmatter 포함 (title, description, layout, category, order: 1, date, tags)
  - [ ] Executive Summary 섹션 존재 (글로벌 시장 규모, 이머시브 씨어터 규모, 성장률, 주요 트렌드)
  - [ ] ≥300 lines
  - [ ] ≥3 데이터 테이블 (시장 규모, 지역별, 세분화)
  - [ ] ≥10 unique 소스 인용
  - [ ] 시장 규모 데이터에 ≥2 독립 소스 제시
  - [ ] VR/AR 분석이 1개 소단원(≤50줄) 이내
  - [ ] 코로나 전후 데이터 구분 명시

  **Agent-Executed QA Scenarios:**

  ```
  Scenario: 시장 규모 데이터 존재 검증
    Tool: Bash
    Steps:
      1. grep -c "\\$[0-9]" immersive-experiences/01_market_overview.md → ≥5 (달러 금액 최소 5개)
      2. grep -ci "billion\|B\|USD\|달러" immersive-experiences/01_market_overview.md → ≥3
      3. grep -c "CAGR\|성장률\|growth" immersive-experiences/01_market_overview.md → ≥2
    Expected Result: 정량 시장 데이터 충분히 포함

  Scenario: 소스 인용 품질 검증
    Tool: Bash
    Steps:
      1. grep -c "출처\|**출처**\|Source\|참고" immersive-experiences/01_market_overview.md → ≥10
      2. grep -ci "Grand View\|Allied Market\|Statista\|PwC\|Eventbrite" immersive-experiences/01_market_overview.md → ≥2
    Expected Result: 신뢰도 높은 소스 인용 존재
  ```

  **Commit**: YES (groups with Task 3)
  - Message: `docs(immersive): add market overview and case studies (Wave 1)`
  - Files: `immersive-experiences/01_market_overview.md`, `immersive-experiences/03_case_studies.md`
  - Pre-commit: N/A

---

- [x] 3. 03_case_studies.md — 주요 사례 연구 (6+1건 개별 분석)

  **What to do**:
  - 사전 지정된 **6+1건** 사례를 개별 심층 분석
  - 각 사례별 포함 항목:
    - **기본 정보**: 제작사, 소재지, 운영 기간, 원작/테마
    - **규모**: 공연장 면적, 층수/방 수, 회당 관객 수, 총 관객 수
    - **운영**: 체험 시간, 주당 공연 횟수, 티켓 가격, 가격 티어
    - **콘텐츠**: 스토리 개요, 배우 수, 관객-배우 인터랙션 방식, 자유도 수준
    - **성과**: 리뷰 점수, 수상, 언론 보도, 문화적 영향
    - **교훈**: 성공/실패 요인, 방탈출 사업에의 시사점

  - **Sleep No More**: 2011-2023 전체 운영 기간 다룸 (2023 폐관 + 상하이 지속 운영). Punchdrunk의 site-specific 접근법. "노 모어(No More)" 현상이 이머시브 씨어터 장르를 정의한 역사적 맥락
  - **The Burnt City**: Punchdrunk 최신작. Sleep No More와의 비교. 규모·가격 변화
  - **Then She Fell**: 15명 소규모 모델. 방탈출과 가장 유사한 규모. 친밀한 1:1 인터랙션
  - **The Great Gatsby Immersive**: F&B 통합 모델. London→NYC 확장. 최근 히트
  - **Secret Cinema**: 대규모 이벤트형 (1000명+). IP 라이선스 모델. 글로벌 확장
  - **한국 사례**: 서울 기반 이머시브 씨어터 현황. 데이터 가용성에 따라 1-2건 심층
  - **Meow Wolf** (보너스): 비씨어터 이머시브. 영구 설치형. 경험 디자인 참조

  - **실패/교훈 사례** 포함:
    - 코로나로 폐관 후 재개하지 못한 사례
    - 중국 이머시브 씨어터 버블 (2019-2022)
    - 관객 유지 실패 또는 모델 전환 사례

  **Must NOT do**:
  - 사례를 일반화하여 장르 특성 도출 (02의 영역)
  - 재무 모델링/수익성 분석 (04의 영역)
  - 사업 전략 제안 (08의 영역)

  **Recommended Agent Profile**:
  - **Category**: `writing`
    - Reason: 웹 검색 기반 사례 데이터 수집 + 구조화된 마크다운 작성
  - **Skills**: []

  **Parallelization**:
  - **Can Run In Parallel**: YES
  - **Parallel Group**: Wave 1 (with Task 1)
  - **Blocks**: Tasks 2, 4, 5
  - **Blocked By**: Task 0

  **References**:

  **Pattern References**:
  - `gaming-industry-evolution/03_animal_crossing_case_study.md` — 개별 사례 연구 문서 패턴 (판매 데이터 테이블, 시리즈 역사, 디자인 철학, 마케팅 전략, 성공 요인). 이 구조를 쇼별로 적용
  - `gaming-industry-evolution/04_the_sims_case_study.md` — 대안 사례 연구 구조 (확장팩 모델, 타겟 고객층, 커뮤니티)

  **Documentation References**:
  - `immersive-experiences/README.md:18-23` — 사례 연구 대상 목록
  - `immersive-experiences/README.md:113` — "최소 5개 이상 사례 심층 분석" 요구

  **External References**:
  - Punchdrunk 공식 사이트: https://www.punchdrunk.com/
  - Sleep No More 공식: (Emursive)
  - The Burnt City 공식: https://www.punchdrunk.com/the-burnt-city/
  - Secret Cinema 공식: https://www.secretcinema.org/
  - Meow Wolf 공식: https://meowwolf.com/
  - TripAdvisor / Yelp 리뷰 데이터
  - TimeOut, NYT, Guardian 리뷰 및 기사

  **검색 키워드**:
  - "Sleep No More NYC history review attendance"
  - "Punchdrunk The Burnt City tickets capacity"
  - "Then She Fell Third Rail Projects intimate immersive"
  - "Great Gatsby Immersive London NYC review"
  - "Secret Cinema business model revenue"
  - "한국 이머시브 씨어터", "서울 몰입형 공연"
  - "Meow Wolf attendance revenue model"
  - "immersive theater failures closed"
  - "China immersive theater bubble"

  **Acceptance Criteria**:

  - [ ] YAML frontmatter 포함
  - [ ] ≥500 lines
  - [ ] ≥6 사례 개별 분석 (각 사례별 ≥60줄)
  - [ ] 각 사례별 데이터 테이블 (기본 정보 + 운영 데이터)
  - [ ] ≥15 unique 소스 인용 (사례당 ≥2 소스)
  - [ ] Sleep No More 2023 폐관 사실 명시 + 상하이 지속 운영 언급
  - [ ] 실패/교훈 사례 ≥1건 포함
  - [ ] 한국 사례 ≥1건 포함

  **Agent-Executed QA Scenarios:**

  ```
  Scenario: 6+ 사례 분석 완성도 검증
    Tool: Bash
    Steps:
      1. grep -ci "Sleep No More" immersive-experiences/03_case_studies.md → ≥5
      2. grep -ci "Burnt City" immersive-experiences/03_case_studies.md → ≥3
      3. grep -ci "Then She Fell" immersive-experiences/03_case_studies.md → ≥3
      4. grep -ci "Great Gatsby\|Gatsby" immersive-experiences/03_case_studies.md → ≥3
      5. grep -ci "Secret Cinema" immersive-experiences/03_case_studies.md → ≥3
      6. grep -ci "한국\|서울\|Korea" immersive-experiences/03_case_studies.md → ≥2
    Expected Result: 6건 이상 사례 분석 존재

  Scenario: 사례별 데이터 테이블 검증
    Tool: Bash
    Steps:
      1. grep -c "^|" immersive-experiences/03_case_studies.md → ≥30 (6사례 × 5행 이상)
    Expected Result: 사례별 정량 데이터 포함
  ```

  **Commit**: YES (groups with Task 1)
  - Message: `docs(immersive): add market overview and case studies (Wave 1)`
  - Files: `immersive-experiences/01_market_overview.md`, `immersive-experiences/03_case_studies.md`
  - Pre-commit: N/A

---

- [x] 2. 02_immersive_theater_deep_dive.md — 이머시브 씨어터 장르 심층 분석 ⭐

  **What to do**:
  - 이머시브 씨어터를 **장르**로서 분석 (개별 작품이 아닌 전체적 특성)
  - **역사**: 아방가르드 연극 전통 → site-specific performance → 현대 이머시브 씨어터 (1문단 역사 맥락 + 주요 마일스톤 타임라인)
  - **경험 디자인 전략** ⭐ (이 문서의 핵심):
    - 공간 구성 원칙 (multi-room, 비선형 동선, 발견의 즐거움)
    - 참여자 경험 설계 (자유 탐색 vs 가이드 경험 스펙트럼)
    - 스토리텔링 기법 (환경 스토리텔링, 단편 서사, 반복 루프)
    - 배우-관객 인터랙션 방식 (1:1 장면, 군중 장면, 관객 역할 부여)
    - 감각 디자인 (시각·청각·후각·촉각 — 전략 수준, 기술 스펙 아님)
  - **글로벌 풍경**:
    - 미국 (NYC 중심, London-NYC 축)
    - 유럽 (London, 에든버러 프린지)
    - 중국 (상하이 이머시브 붐, Sleep No More 상하이)
    - 한국 (소규모 시장, 성장 가능성)
  - 03_case_studies에서 수집한 개별 데이터를 **패턴화**하여 장르 특성 도출

  **Must NOT do**:
  - 개별 쇼의 재무 데이터 상세 (04의 영역)
  - 개별 쇼의 리뷰/평점 상세 (03의 영역)
  - 학술 연극 이론 심층 (1문단 초과 금지)
  - 사업 전략 제안 (08의 영역)

  **Recommended Agent Profile**:
  - **Category**: `writing`
    - Reason: 사례 데이터를 종합하여 장르 분석 문서 작성
  - **Skills**: []

  **Parallelization**:
  - **Can Run In Parallel**: YES
  - **Parallel Group**: Wave 2 (with Tasks 4, 5)
  - **Blocks**: Tasks 6, 7, 8
  - **Blocked By**: Tasks 0, 1, 3

  **References**:

  **Pattern References**:
  - `gaming-industry-evolution/02_competitive_vs_casual_games.md` — 장르 분석 패턴 (역사적 발전 → 장르 특성 → 현재 지형). 이머시브 씨어터 장르에 동일 구조 적용
  - `gaming-industry-evolution/05_cozy_games_analysis.md` — 장르 전반 분석 패턴 (정의 → 핵심 특징 → 대표 사례 요약 → 시장 위치)

  **API/Type References**:
  - `immersive-experiences/03_case_studies.md` — 이 태스크에서 참조할 사례별 원본 데이터 (Wave 1에서 완성됨)
  - `immersive-experiences/01_market_overview.md` — 시장 규모 맥락

  **Documentation References**:
  - `immersive-experiences/README.md:15-40` — 이머시브 씨어터 심층 분석 요구사항 (2.1-2.4)

  **검색 키워드**:
  - "immersive theater design principles"
  - "site-specific performance audience experience"
  - "immersive theater spatial design wayfinding"
  - "actor audience interaction immersive"
  - "environmental storytelling theater"
  - "promenade theater history"

  **Acceptance Criteria**:

  - [ ] YAML frontmatter 포함
  - [ ] ≥500 lines (최우선 문서)
  - [ ] ≥5 데이터 테이블
  - [ ] ≥10 unique 소스 인용
  - [ ] 경험 디자인 전략 섹션 존재 (공간, 동선, 스토리텔링, 인터랙션 모두 포함)
  - [ ] 글로벌 풍경 (미국, 유럽, 중국, 한국) 모두 커버
  - [ ] 학술 연극 이론 ≤1문단
  - [ ] 03_case_studies.md 교차 참조 존재

  **Agent-Executed QA Scenarios:**

  ```
  Scenario: 경험 디자인 핵심 섹션 존재 검증
    Tool: Bash
    Steps:
      1. grep -ci "공간\|spatial\|space" immersive-experiences/02_immersive_theater_deep_dive.md → ≥3
      2. grep -ci "동선\|wayfinding\|movement" immersive-experiences/02_immersive_theater_deep_dive.md → ≥2
      3. grep -ci "스토리텔링\|storytelling\|narrative" immersive-experiences/02_immersive_theater_deep_dive.md → ≥3
      4. grep -ci "인터랙션\|interaction\|1:1" immersive-experiences/02_immersive_theater_deep_dive.md → ≥3
    Expected Result: 4대 경험 디자인 요소 모두 커버

  Scenario: 장르 분석 vs 사례 분석 분리 검증
    Tool: Bash
    Steps:
      1. 03_case_studies.md에서 개별 쇼 데이터 테이블 확인 (쇼 이름 + 수치)
      2. 02_immersive_theater_deep_dive.md에서 패턴/원칙 중심 서술 확인
    Expected Result: 02=패턴, 03=개별 데이터 분리 유지
  ```

  **Commit**: YES (groups with Tasks 4, 5)
  - Message: `docs(immersive): add theater deep dive, business models, customer insights (Wave 2)`
  - Files: `immersive-experiences/02_*.md`, `immersive-experiences/04_*.md`, `immersive-experiences/05_*.md`
  - Pre-commit: N/A

---

- [x] 4. 04_business_models.md — 비즈니스 모델 분석

  **What to do**:
  - 이머시브 씨어터의 비즈니스 모델을 **유형별**로 분석
  - **티켓 가격 전략**:
    - 주요 이머시브 씨어터 티켓 가격대 비교 테이블 (6+1 사례)
    - 가격 티어 분석 (일반/프리미엄/VIP)
    - 고가 전략의 근거 (경험 가치, 희소성, F&B 포함 여부)
    - 방탈출 가격(17,000-24,000원)과의 비교
  - **수익 구조**:
    - 티켓 매출 비중
    - F&B 매출 (The Great Gatsby 모델)
    - 굿즈/머천다이징
    - 기업 이벤트/프라이빗 대관
    - IP 라이선스 (Secret Cinema 모델)
  - **운영 방식**:
    - 회차당 인원 비교 (15명~1000명+)
    - 공연 시간 (2-3시간)
    - 주당 회차 수
    - 배우/스태프 규모
  - **수익성 추정** (공개 데이터 기반):
    - 방법론: 티켓 가격 × 수용인원 × 공연횟수 × 가동률 → 주간 매출 추정
    - 비용 측면: 임대료 (NYC/London 기준), 인건비 (배우 수 기반), 운영비
    - **추정치임을 명시**하고 방법론 투명하게 제시
  - **손익분기점 추정**: 공개 인터뷰, 보도 자료 기반

  **Must NOT do**:
  - 우리 사업의 비즈니스 모델 제안 (08의 영역)
  - 개별 쇼의 콘텐츠/예술적 분석 (03의 영역)
  - 비공개 재무 데이터 추측 (추정은 허용하되 방법론 명시)

  **Recommended Agent Profile**:
  - **Category**: `writing`
    - Reason: 사례별 재무 데이터 수집 및 분석 문서 작성
  - **Skills**: []

  **Parallelization**:
  - **Can Run In Parallel**: YES
  - **Parallel Group**: Wave 2 (with Tasks 2, 5)
  - **Blocks**: Tasks 6, 8
  - **Blocked By**: Task 3

  **References**:

  **Pattern References**:
  - `gaming-industry-evolution/06_market_share_analysis.md` — 시장 비중 분석 패턴 (정량 데이터 테이블 + 비교 분석)
  - `escape-room-industry/03_business_model_revenue.md` — 방탈출 비즈니스 모델 패턴. 티켓 가격, 수익 구조, 운영 방식 → 동일 구조를 이머시브 씨어터에 적용

  **API/Type References**:
  - `immersive-experiences/03_case_studies.md` — 사례별 운영 데이터 (Wave 1에서 완성)

  **Documentation References**:
  - `immersive-experiences/README.md:24-29` — 비즈니스 모델 분석 요구사항
  - `immersive-experiences/README.md:59` — "주요 이머시브 씨어터 티켓 가격대" 데이터 요구
  - `escape-room-industry/03_business_model_revenue.md` — 방탈출 가격 비교 기준 데이터 (17,000-24,000원)

  **검색 키워드**:
  - "Sleep No More ticket price 2023"
  - "immersive theater revenue model"
  - "Great Gatsby Immersive ticket price tiers"
  - "Secret Cinema business model revenue"
  - "immersive theater profitability"
  - "experiential entertainment pricing strategy"

  **Acceptance Criteria**:

  - [ ] YAML frontmatter 포함
  - [ ] ≥400 lines
  - [ ] ≥4 데이터 테이블 (가격 비교, 수익 구조, 운영 비교, 수익성 추정)
  - [ ] ≥10 unique 소스 인용
  - [ ] 6+1 사례의 티켓 가격 비교 테이블 존재
  - [ ] 수익성 추정 방법론 명시 ("추정치" 명시)
  - [ ] 방탈출 가격과의 비교 데이터 포함
  - [ ] `escape-room-industry/03_business_model_revenue.md` 교차 참조 존재

  **Agent-Executed QA Scenarios:**

  ```
  Scenario: 티켓 가격 데이터 검증
    Tool: Bash
    Steps:
      1. grep -ci "ticket\|티켓\|가격\|price\|\\$" immersive-experiences/04_business_models.md → ≥15
      2. grep -c "^|" immersive-experiences/04_business_models.md → ≥20
      3. grep -ci "추정\|estimate\|방법론\|methodology" immersive-experiences/04_business_models.md → ≥2
    Expected Result: 가격 데이터 풍부, 추정 방법론 명시

  Scenario: 방탈출 비교 참조 검증
    Tool: Bash
    Steps:
      1. grep -c "escape-room-industry" immersive-experiences/04_business_models.md → ≥1
      2. grep -ci "방탈출\|escape room" immersive-experiences/04_business_models.md → ≥3
    Expected Result: 방탈출 비즈니스 모델과 비교 존재
  ```

  **Commit**: YES (groups with Tasks 2, 5)
  - Message: `docs(immersive): add theater deep dive, business models, customer insights (Wave 2)`
  - Files: (위 참조)
  - Pre-commit: N/A

---

- [x] 5. 05_customer_insights.md — 고객 인사이트

  **What to do**:
  - **타겟 고객층 프로파일**:
    - 연령, 성별, 소득 수준, 교육 수준, 라이프스타일
    - 이머시브 씨어터 관객 vs 전통 연극 관객 vs 방탈출 고객 비교
  - **이용 동기 및 기대치**:
    - 왜 이머시브 씨어터를 찾는가? (SNS 인스타그래미블, 특별한 데이트, 문화 체험, 호기심)
    - 기대하는 경험 수준 (자유도, 배우 인터랙션, 몰입감)
  - **재방문율 및 충성도**:
    - Sleep No More의 "completionist" 현상 (같은 쇼 10회+ 방문)
    - 재방문 동기 (다른 스토리라인, 다른 경험)
    - 방탈출 재방문율(20-30%)과의 비교
  - **고객 리뷰 분석**:
    - TripAdvisor, Yelp, Google 리뷰에서 반복되는 긍정/부정 키워드
    - 고객 만족/불만족 요인
  - **방탈출 고객층과의 비교** ⭐:
    - `escape-room-industry/04_customer_trends_behavior.md` 데이터 참조
    - 겹치는 고객층 (모험 추구, 그룹 활동)
    - 차별화된 고객층 (문화 소비자, 고소득층)

  **Must NOT do**:
  - 방탈출 고객 데이터 재도출 (`escape-room-industry/04` 인용만)
  - 마케팅 전략 제안 (08의 영역)
  - 개별 쇼의 상세 리뷰 분석 (03에서 이미 다룸, 여기는 패턴만)

  **Recommended Agent Profile**:
  - **Category**: `writing`
    - Reason: 고객 데이터 수집 및 분석 문서 작성
  - **Skills**: []

  **Parallelization**:
  - **Can Run In Parallel**: YES
  - **Parallel Group**: Wave 2 (with Tasks 2, 4)
  - **Blocks**: Tasks 6, 7, 8
  - **Blocked By**: Task 3

  **References**:

  **Pattern References**:
  - `gaming-industry-evolution/03_animal_crossing_case_study.md` — 타겟 고객 분석 패턴 (인구통계 → 이용 동기 → 커뮤니티)
  - `escape-room-industry/04_customer_trends_behavior.md` — 방탈출 고객 행동 데이터 (비교 기준선)

  **Documentation References**:
  - `immersive-experiences/README.md:36-40` — 타겟 고객 분석 요구사항
  - `immersive-experiences/README.md:62` — "재방문율" 데이터 요구

  **검색 키워드**:
  - "immersive theater audience demographics"
  - "Sleep No More repeat visitors completionist"
  - "immersive experience customer motivation"
  - "immersive theater review analysis"
  - "experiential entertainment consumer behavior"

  **Acceptance Criteria**:

  - [ ] YAML frontmatter 포함
  - [ ] ≥300 lines
  - [ ] ≥3 데이터 테이블 (고객 프로파일, 이용 동기, 재방문율)
  - [ ] ≥10 unique 소스 인용
  - [ ] 재방문율 데이터 포함
  - [ ] 방탈출 고객과의 비교 섹션 존재
  - [ ] `escape-room-industry/04_customer_trends_behavior.md` 교차 참조 존재

  **Agent-Executed QA Scenarios:**

  ```
  Scenario: 고객 데이터 및 비교 검증
    Tool: Bash
    Steps:
      1. grep -ci "재방문\|revisit\|return\|repeat" immersive-experiences/05_customer_insights.md → ≥3
      2. grep -ci "방탈출\|escape room" immersive-experiences/05_customer_insights.md → ≥5
      3. grep -c "escape-room-industry" immersive-experiences/05_customer_insights.md → ≥1
    Expected Result: 재방문 데이터 존재, 방탈출 비교 충분
  ```

  **Commit**: YES (groups with Tasks 2, 4)
  - Message: `docs(immersive): add theater deep dive, business models, customer insights (Wave 2)`
  - Files: (위 참조)
  - Pre-commit: N/A

---

- [x] 6. 06_comparison_with_escape_rooms.md — 방탈출과의 비교

  **What to do**:
  - **유사점과 차이점** 체계적 비교:
    - 비교 축: 공간 활용, 시간 구조, 참여자 역할, 목표 구조, 그룹 크기, 가격대, 스토리텔링 방식, 기술 활용
    - 대형 비교 테이블 (축별 이머시브 씨어터 vs 방탈출)
  - **방탈출에 적용 가능한 이머시브 요소**:
    - 공간: 단일 방 → 다중 공간
    - 스토리: 퍼즐 서사 → 환경 스토리텔링
    - 인터랙션: 진행자 목소리 → 라이브 배우
    - 분위기: 타이머 압박 → 몰입감
    - 감각: 시각 퍼즐 → 다감각 디자인
  - **융합 모델의 가능성**:
    - 해외 융합 사례 (이미 시도된 것들)
    - 이머시브 방탈출이라는 새 카테고리
    - 장단점 분석
  - **차별화 포인트**:
    - "이머시브 씨어터의 몰입감 + 방탈출의 참여 능동성" = 새로운 카테고리
    - gaming-industry-evolution/09의 "방탈출계의 동물의 숲"과 연결
  - 통화 단위 통일: USD 기준, KRW 병기

  **Must NOT do**:
  - 사업 전략 제안 (08의 영역) — 여기는 비교 사실만
  - 방탈출 데이터 재조사 (`escape-room-industry` 인용만)
  - 새로운 이머시브 씨어터 데이터 수집 (01-05 참조만)

  **Recommended Agent Profile**:
  - **Category**: `writing`
    - Reason: 기존 데이터 종합하여 비교 분석 문서 작성
  - **Skills**: []

  **Parallelization**:
  - **Can Run In Parallel**: YES
  - **Parallel Group**: Wave 3 (with Task 7)
  - **Blocks**: Task 8
  - **Blocked By**: Tasks 2, 4, 5

  **References**:

  **Pattern References**:
  - `gaming-industry-evolution/02_competitive_vs_casual_games.md` — 두 카테고리 비교 분석 패턴

  **API/Type References**:
  - `immersive-experiences/02_immersive_theater_deep_dive.md` — 이머시브 씨어터 장르 특성
  - `immersive-experiences/04_business_models.md` — 비즈니스 모델 비교 데이터
  - `immersive-experiences/05_customer_insights.md` — 고객 비교 데이터
  - `escape-room-industry/03_business_model_revenue.md` — 방탈출 비즈니스 모델 (비교 기준)
  - `escape-room-industry/04_customer_trends_behavior.md` — 방탈출 고객 행동 (비교 기준)

  **Documentation References**:
  - `immersive-experiences/README.md:42-46` — 비교 분석 요구사항
  - `immersive-experiences/README.md:115` — "방탈출과의 명확한 차이점 정리" 체크리스트

  **Acceptance Criteria**:

  - [ ] YAML frontmatter 포함
  - [ ] ≥300 lines
  - [ ] ≥2 대형 비교 테이블 (유사점·차이점, 적용 가능 요소)
  - [ ] ≥10 unique 소스 인용
  - [ ] `escape-room-industry/` 교차 참조 ≥3건
  - [ ] 융합 모델 가능성 섹션 존재
  - [ ] 차별화 포인트 명확하게 정리

  **Agent-Executed QA Scenarios:**

  ```
  Scenario: 비교 분석 완성도 검증
    Tool: Bash
    Steps:
      1. grep -c "escape-room-industry" immersive-experiences/06_comparison_with_escape_rooms.md → ≥3
      2. grep -c "^|" immersive-experiences/06_comparison_with_escape_rooms.md → ≥15
      3. grep -ci "융합\|fusion\|hybrid\|convergence" immersive-experiences/06_comparison_with_escape_rooms.md → ≥2
      4. grep -ci "차별화\|differentiat" immersive-experiences/06_comparison_with_escape_rooms.md → ≥2
    Expected Result: 체계적 비교 + 융합 가능성 + 차별화 모두 존재
  ```

  **Commit**: YES (groups with Task 7)
  - Message: `docs(immersive): add comparison and trends analysis (Wave 3)`
  - Files: `immersive-experiences/06_*.md`, `immersive-experiences/07_*.md`
  - Pre-commit: N/A

---

- [x] 7. 07_trends_and_outlook.md — 트렌드 및 전망

  **What to do**:
  - **최신 트렌드** (2022-2025):
    - 기술 융합 (프로젝션 매핑, AI, IoT 센서)
    - 테마 다양화 (문학 작품, 역사적 시대, 팝컬처 IP)
    - F&B 통합 (이머시브 다이닝, 칵테일 경험)
    - 소규모·친밀한 경험의 부상
    - 디지털-피지컬 하이브리드 (AR 요소 추가)
  - **포스트 코로나 변화**:
    - 폐관한 쇼 vs 새로 등장한 쇼
    - 소규모 전환 트렌드
    - 위생/안전 프로토콜의 경험 영향
    - 디지털 이머시브 경험의 등장과 한계
  - **향후 5-10년 성장 전망**:
    - 시장 규모 전망 (소스별)
    - 성장 동력 (경험 경제, MZ세대 소비 패턴)
    - 지역별 성장 전망 (특히 아시아)
  - **신규 진입 기회 및 위협 요인**:
    - 기회: 미개척 지역, 새로운 IP, 기술 접목
    - 위협: 높은 초기 투자, 인재 확보, 경기 민감도

  **Must NOT do**:
  - 사업 전략 제안 (08의 영역) — 트렌드 사실만
  - 개별 쇼 상세 분석 (03의 영역)
  - 기술 스펙/제작 상세 (전략 수준만)

  **Recommended Agent Profile**:
  - **Category**: `writing`
    - Reason: 트렌드 데이터 수집 및 전망 분석 문서 작성
  - **Skills**: []

  **Parallelization**:
  - **Can Run In Parallel**: YES
  - **Parallel Group**: Wave 3 (with Task 6)
  - **Blocks**: Task 8
  - **Blocked By**: Tasks 1, 2, 5

  **References**:

  **Pattern References**:
  - `gaming-industry-evolution/05_cozy_games_analysis.md` — 장르 트렌드 분석 패턴 (성장 트렌드 + 미래 전망)

  **API/Type References**:
  - `immersive-experiences/01_market_overview.md` — 시장 규모 기반
  - `immersive-experiences/02_immersive_theater_deep_dive.md` — 장르 현황 기반
  - `immersive-experiences/05_customer_insights.md` — 고객 트렌드 기반

  **Documentation References**:
  - `immersive-experiences/README.md:48-53` — 트렌드 및 전망 요구사항

  **검색 키워드**:
  - "immersive experience trends 2024 2025"
  - "immersive theater post COVID"
  - "experiential entertainment future outlook"
  - "immersive dining trend"
  - "immersive experience market forecast 2030"

  **Acceptance Criteria**:

  - [ ] YAML frontmatter 포함
  - [ ] ≥300 lines
  - [ ] 코로나 전후 변화 섹션 존재
  - [ ] 5-10년 전망 데이터 포함
  - [ ] ≥10 unique 소스 인용
  - [ ] 기회/위협 모두 커버

  **Agent-Executed QA Scenarios:**

  ```
  Scenario: 트렌드 및 전망 완성도 검증
    Tool: Bash
    Steps:
      1. grep -ci "트렌드\|trend" immersive-experiences/07_trends_and_outlook.md → ≥5
      2. grep -ci "코로나\|COVID\|pandemic" immersive-experiences/07_trends_and_outlook.md → ≥3
      3. grep -ci "전망\|forecast\|outlook\|2030" immersive-experiences/07_trends_and_outlook.md → ≥3
      4. grep -ci "기회\|opportunity\|위협\|threat\|risk" immersive-experiences/07_trends_and_outlook.md → ≥4
    Expected Result: 트렌드, 코로나 영향, 전망, 기회/위협 모두 존재
  ```

  **Commit**: YES (groups with Task 6)
  - Message: `docs(immersive): add comparison and trends analysis (Wave 3)`
  - Files: (위 참조)
  - Pre-commit: N/A

---

- [x] 8. 08_strategic_implications.md — 사업 적용 전략 (종합) ⭐

  **What to do**:
  - **이 문서는 01-07의 모든 발견을 종합하여 방탈출 사업에의 적용 전략을 도출하는 최종 문서**
  - 반드시 01-07 모든 문서를 읽은 후 작성
  - **종합 Executive Summary**: 전체 리서치의 핵심 발견 5-7개
  - **차별화 전략**:
    - 기존 방탈출과 차별화된 이머시브 요소 (02, 06 기반)
    - 구체적 적용 방안 (공간, 스토리, 인터랙션, 분위기)
  - **프리미엄 전략**:
    - 고가 티켓팅 정당화 근거 (04 기반)
    - 가격 포지셔닝 제안 (방탈출 vs 이머시브 씨어터 사이)
    - F&B, 굿즈 등 부가 수익원 전략
  - **경험 디자인 인사이트**:
    - 공간/동선 설계 원칙 (02 기반)
    - 참여자 경험 여정(journey) 설계
    - 감각 디자인 적용
  - **타겟팅 전략**:
    - 이머시브 씨어터 고객층 → 방탈출 전환 방안 (05 기반)
    - gaming-industry-evolution/09의 "방탈출계의 동물의 숲" 전략과 통합
  - **리스크 및 과제**:
    - 투자 규모, 인재 확보, 운영 복잡성
    - 완화 방안

  - **gaming-industry-evolution/09_application_to_escape_rooms.md** 결론을 전제로:
    - 코지 게임 포지셔닝 (이미 확립)에 이머시브 씨어터 차원 추가
    - "방탈출계의 동물의 숲" + "이머시브 씨어터의 몰입감" = 최종 포지셔닝
  - **escape-room-industry** 데이터 교차 참조

  **Must NOT do**:
  - 새로운 시장 데이터 도입 (01-07에서 이미 수집된 것만 종합)
  - 기존 리서치 결론 재도출 (인용 + 확장만)
  - 재무 모델링 (04의 영역, 여기는 전략 방향만)

  **Recommended Agent Profile**:
  - **Category**: `writing`
    - Reason: 종합 전략 문서 작성, 다수 문서 참조 필요
  - **Skills**: []

  **Parallelization**:
  - **Can Run In Parallel**: NO
  - **Parallel Group**: Wave 4 (sequential, last)
  - **Blocks**: Tasks 9, 10
  - **Blocked By**: ALL (Tasks 1-7)

  **References**:

  **Pattern References**:
  - `gaming-industry-evolution/09_application_to_escape_rooms.md` — 종합 전략 문서 패턴. 이 구조를 따르되, 이머시브 경험 차원 추가. 이 문서의 결론("방탈출계의 동물의 숲")을 **전제**로 시작

  **API/Type References**:
  - `immersive-experiences/01_market_overview.md` — 시장 규모 데이터
  - `immersive-experiences/02_immersive_theater_deep_dive.md` — 경험 디자인 원칙
  - `immersive-experiences/03_case_studies.md` — 사례별 교훈
  - `immersive-experiences/04_business_models.md` — 가격/수익 데이터
  - `immersive-experiences/05_customer_insights.md` — 고객 데이터
  - `immersive-experiences/06_comparison_with_escape_rooms.md` — 비교 분석
  - `immersive-experiences/07_trends_and_outlook.md` — 미래 전망
  - `gaming-industry-evolution/09_application_to_escape_rooms.md` — 코지 게임 전략 (전제)
  - `escape-room-industry/03_business_model_revenue.md` — 방탈출 비즈니스 기준선
  - `escape-room-industry/04_customer_trends_behavior.md` — 방탈출 고객 기준선

  **Documentation References**:
  - `immersive-experiences/README.md:84-91` — 사업 적용 목표 4개

  **Acceptance Criteria**:

  - [ ] YAML frontmatter 포함
  - [ ] ≥400 lines
  - [ ] 01-07 모든 문서 교차 참조 존재
  - [ ] `gaming-industry-evolution/09` 교차 참조 ≥1건
  - [ ] `escape-room-industry/` 교차 참조 ≥2건
  - [ ] 차별화 전략, 프리미엄 전략, 경험 디자인, 타겟팅 전략 4개 섹션 모두 존재
  - [ ] 리스크 및 과제 섹션 존재
  - [ ] Executive Summary에 핵심 발견 5개 이상

  **Agent-Executed QA Scenarios:**

  ```
  Scenario: 종합 문서 교차 참조 검증
    Tool: Bash
    Steps:
      1. grep -c "01_market\|02_immersive\|03_case\|04_business\|05_customer\|06_comparison\|07_trends" immersive-experiences/08_strategic_implications.md → ≥7
      2. grep -c "gaming-industry-evolution" immersive-experiences/08_strategic_implications.md → ≥1
      3. grep -c "escape-room-industry" immersive-experiences/08_strategic_implications.md → ≥2
    Expected Result: 모든 선행 문서 + 타 리서치 참조 완성

  Scenario: 4대 전략 영역 존재 검증
    Tool: Bash
    Steps:
      1. grep -ci "차별화" immersive-experiences/08_strategic_implications.md → ≥3
      2. grep -ci "프리미엄\|premium\|가격" immersive-experiences/08_strategic_implications.md → ≥3
      3. grep -ci "경험 디자인\|experience design\|공간\|동선" immersive-experiences/08_strategic_implications.md → ≥3
      4. grep -ci "타겟\|target\|고객층" immersive-experiences/08_strategic_implications.md → ≥3
    Expected Result: 4대 전략 영역 모두 충분히 커버
  ```

  **Commit**: YES
  - Message: `docs(immersive): add strategic implications synthesis`
  - Files: `immersive-experiences/08_strategic_implications.md`
  - Pre-commit: N/A

---

- [x] 9. index.md & README.md 업데이트

  **What to do**:
  - `immersive-experiences/index.md` 업데이트:
    - 조사 상태: 🔴 대기 중 → ✅ 완료
    - 예상 산출물 → 완성된 문서 구조 (각 문서별 줄 수 포함)
    - 조사 결과 요약 섹션 추가
  - `immersive-experiences/README.md` 업데이트:
    - 필수 수집 데이터 체크리스트 완료 표시 (`- [ ]` → `- [x]`)
    - 중요 체크리스트 완료 표시
    - 조사 시작일, 완료일, 담당자 입력
  - 루트 `README.md` 업데이트:
    - `🔴 조사 대기 중` → `✅ 완료` 상태 변경
    - 핵심 발견 요약 추가 (gaming-industry-evolution과 동일 형식)

  **Must NOT do**:
  - 문서 내용 수정 (메타데이터만)
  - 새 조사 항목 추가

  **Recommended Agent Profile**:
  - **Category**: `quick`
    - Reason: 기존 파일 메타데이터 업데이트만
  - **Skills**: []

  **Parallelization**:
  - **Can Run In Parallel**: NO
  - **Parallel Group**: Sequential (after Task 8)
  - **Blocks**: Task 10
  - **Blocked By**: Task 8

  **References**:

  **Pattern References**:
  - `gaming-industry-evolution/index.md` — 완성된 index.md 패턴
  - `gaming-industry-evolution/README.md:219-276` — 완료 체크리스트 + 결과 요약 패턴

  **API/Type References**:
  - `immersive-experiences/index.md` — 업데이트 대상
  - `immersive-experiences/README.md` — 업데이트 대상
  - `README.md` (루트) — 업데이트 대상

  **Acceptance Criteria**:

  - [ ] index.md 조사 상태 "✅ 완료"로 변경
  - [ ] README.md 체크리스트 모든 항목 `[x]`
  - [ ] 루트 README.md에서 이머시브 경험 상태 "✅ 완료"
  - [ ] 조사 시작일/완료일 입력

  **Agent-Executed QA Scenarios:**

  ```
  Scenario: 상태 업데이트 검증
    Tool: Bash
    Steps:
      1. grep "✅" immersive-experiences/index.md → 완료 상태 확인
      2. grep -c "\[x\]" immersive-experiences/README.md → ≥10
      3. grep "✅" README.md → 이머시브 경험 완료 상태 확인
    Expected Result: 모든 상태 업데이트 완료
  ```

  **Commit**: YES
  - Message: `docs(immersive): mark research as complete, update status`
  - Files: `immersive-experiences/index.md`, `immersive-experiences/README.md`, `README.md`
  - Pre-commit: N/A

---

- [x] 10. 최종 품질 검증 & 데이터 체크리스트 확인

  **What to do**:
  - **문서 구조 검증**: 모든 8개 문서의 YAML frontmatter, Executive Summary, 최소 줄 수 확인
  - **데이터 체크리스트 검증**: README의 모든 필수 데이터 항목이 실제 문서에 존재하는지 grep으로 확인
  - **교차 참조 검증**: 문서 간 링크 작동 확인
  - **소스 인용 검증**: 모든 문서에 충분한 소스 인용이 있는지 확인
  - **총 줄 수 합산**: 3,500줄 이상 확인

  **Must NOT do**:
  - 문서 내용 수정 (검증만, 수정은 필요시 재작업 태스크로)

  **Recommended Agent Profile**:
  - **Category**: `quick`
    - Reason: grep/wc 기반 검증만
  - **Skills**: []

  **Parallelization**:
  - **Can Run In Parallel**: NO
  - **Parallel Group**: Sequential (final)
  - **Blocks**: None (final task)
  - **Blocked By**: Task 9

  **References**:

  **Documentation References**:
  - `immersive-experiences/README.md:56-68` — 필수 수집 데이터 체크리스트
  - `immersive-experiences/README.md:109-117` — 중요 체크리스트

  **Acceptance Criteria**:

  - [ ] 8개 문서 모두 존재
  - [ ] 총 줄 수 ≥3,500
  - [ ] 모든 문서에 YAML frontmatter 존재
  - [ ] 모든 필수 데이터 항목 grep으로 확인

  **Agent-Executed QA Scenarios:**

  ```
  Scenario: 전체 품질 최종 검증
    Tool: Bash
    Steps:
      1. ls immersive-experiences/0*.md | wc -l → 8
      2. wc -l immersive-experiences/0*.md → 총 ≥3,500
      3. for f in immersive-experiences/0*.md; do head -1 "$f"; done → 모두 "---"
      4. grep -rl "시장 규모\|market size" immersive-experiences/01_market_overview.md → match
      5. grep -rl "티켓\|ticket\|가격\|price" immersive-experiences/04_business_models.md → match
      6. grep -rl "재방문\|revisit" immersive-experiences/05_customer_insights.md → match
      7. grep -rl "Sleep No More" immersive-experiences/03_case_studies.md → match
      8. grep -c "escape-room-industry" immersive-experiences/06_comparison_with_escape_rooms.md → ≥3
      9. grep -c "gaming-industry-evolution" immersive-experiences/08_strategic_implications.md → ≥1
    Expected Result: 모든 검증 통과

  Scenario: 데이터 체크리스트 완전성 검증
    Tool: Bash
    Steps:
      1. 글로벌 시장 규모: grep -il "\\$.*[Bb]illion\|\\$.*B" immersive-experiences/01_market_overview.md → match
      2. 이머시브 씨어터 규모: grep -il "theater.*market\|씨어터.*시장" immersive-experiences/02_immersive_theater_deep_dive.md → match
      3. 티켓 가격대: grep -il "\\$[0-9].*ticket\|\\$[0-9].*티켓" immersive-experiences/04_business_models.md → match
      4. 체험 시간: grep -il "시간\|hour\|minute\|duration" immersive-experiences/03_case_studies.md → match
      5. 회당 인원: grep -il "인원\|capacity\|audience\|attendee" immersive-experiences/03_case_studies.md → match
      6. 재방문율: grep -il "재방문\|revisit\|return" immersive-experiences/05_customer_insights.md → match
    Expected Result: README 정량 데이터 체크리스트 6개 항목 모두 커버
  ```

  **Commit**: NO (검증만, 수정 없음)

---

## Commit Strategy

| After Task(s) | Message | Files | Verification |
|------------|---------|-------|--------------|
| 0 | `docs(immersive): establish taxonomy and research standards` | Task 0 결과물 | YAML 템플릿 존재 |
| 1, 3 | `docs(immersive): add market overview and case studies (Wave 1)` | 01_*.md, 03_*.md | wc -l ≥800 합계 |
| 2, 4, 5 | `docs(immersive): add theater deep dive, business models, customer insights (Wave 2)` | 02_*.md, 04_*.md, 05_*.md | wc -l ≥1200 합계 |
| 6, 7 | `docs(immersive): add comparison and trends analysis (Wave 3)` | 06_*.md, 07_*.md | wc -l ≥600 합계 |
| 8 | `docs(immersive): add strategic implications synthesis` | 08_*.md | wc -l ≥400 |
| 9 | `docs(immersive): mark research as complete, update status` | index.md, README.md, ../README.md | grep "✅" |

---

## Success Criteria

### Verification Commands
```bash
# 전체 문서 수 확인
ls immersive-experiences/0*.md | wc -l
# Expected: 8

# 총 줄 수 확인
wc -l immersive-experiences/0*.md
# Expected: 총 ≥3,500

# YAML frontmatter 검증
for f in immersive-experiences/0*.md; do head -1 "$f" | grep -q "^---$" && echo "PASS: $f" || echo "FAIL: $f"; done
# Expected: 8개 모두 PASS

# 소스 인용 최소 수량
for f in immersive-experiences/0*.md; do echo "$f: $(grep -ci '출처\|Source\|참고\|http' "$f") citations"; done
# Expected: 각 ≥10

# 필수 데이터 체크리스트
grep -il "market size\|시장 규모" immersive-experiences/01_market_overview.md
grep -il "ticket.*price\|티켓.*가격" immersive-experiences/04_business_models.md
grep -il "revisit\|재방문" immersive-experiences/05_customer_insights.md
grep -il "Sleep No More" immersive-experiences/03_case_studies.md
grep -c "escape-room-industry" immersive-experiences/06_comparison_with_escape_rooms.md  # ≥3
grep -c "gaming-industry-evolution" immersive-experiences/08_strategic_implications.md  # ≥1

# README 체크리스트 완료
grep -c "\[x\]" immersive-experiences/README.md
# Expected: ≥10
```

### Final Checklist
- [ ] 8개 문서 모두 존재하고 각 300줄 이상
- [ ] 총 줄 수 3,500 이상
- [ ] 모든 문서에 YAML frontmatter + Executive Summary + 데이터 테이블 + 소스 인용
- [ ] 이머시브 씨어터 6개+ 사례 심층 분석 완료
- [ ] 티켓 가격 및 수익 구조 구체적 데이터 확보
- [ ] 방탈출과의 명확한 비교 분석 완료
- [ ] 사업 적용 전략 도출 완료
- [ ] 모든 정량 데이터에 출처 명시
- [ ] 코로나 전후 데이터 구분 명시
- [ ] 문서 간 교차 참조 정상 작동
- [ ] index.md, README.md, 루트 README.md 상태 업데이트 완료
- [ ] VR/AR, 테마파크, K-pop 등 범위 외 주제가 과도하게 포함되지 않음

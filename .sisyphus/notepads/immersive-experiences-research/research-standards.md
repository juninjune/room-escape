# 이머시브 경험 리서치 표준 가이드 (Research Standards)

본 문서는 이머시브 경험(Immersive Experience) 시장 조사 프로젝트의 모든 산출물에 적용되는 표준 분류 체계, 데이터 기준, 키워드 및 포맷을 정의합니다. 모든 후속 리서치 작업은 본 가이드를 준수해야 합니다.

---

## 1. 이머시브 경험(Immersive Experience) 분류 체계

본 프로젝트에서는 시장을 다음과 같은 6가지 주요 **카테고리**로 분류합니다.

| 카테고리 | 정의 | 본 조사 범위 |
|----------|------|-------------|
| **카테고리 1: 이머시브 씨어터** | 배우가 주도하는 서사적 몰입 경험. 관객이 공간 내 자유 이동. 퍼즐 목표 없음 | ⭐ 최우선 조사 대상 |
| **카테고리 2: 체험형 전시** | 예술/미디어 기반 몰입 공간 (teamLab, Meow Wolf) | 01에서 시장 규모로만, 03에서 Meow Wolf 1건만 |
| **카테고리 3: VR/AR 경험** | 가상현실/증강현실 기반 체험 | 01에서 시장 규모 1소단원만 |
| **카테고리 4: 방탈출(Escape Room)** | 퍼즐 해결 목표의 몰입 경험 | 06에서 비교 대상 (이미 별도 리서치 완료) |
| **카테고리 5: 테마파크 어트랙션** | Disney, Universal 등 대규모 시설 | ❌ 본 조사 범위 밖 |
| **카테고리 6: K-pop/팬덤 체험** | BTS 팝업 등 팬덤 기반 체험 | 01에서 한국 현상 간략 언급만 |

---

## 2. 핵심 검색 키워드 표준

### 공통 키워드 (영어)
- Immersive Theater / Immersive Experience
- Site-specific Performance
- Experiential Entertainment
- Interactive Theater
- Participatory Performance

### 문서별 추가 키워드
- **01 시장 개요**: Global immersive market size, Immersive theater market growth, Experiential economy statistics
- **02 디자인 원칙**: Immersive design patterns, Agency in immersive theater, Environmental storytelling, Audience autonomy
- **03 사례 연구**: Sleep No More NYC data, Punchdrunk business model, Meow Wolf revenue, Then She Fell production
- **04 기술 통합**: Haptics in theater, Projection mapping immersive, Wearable tech performance, Spatial audio
- **05 비즈니스 모델**: Immersive theater ROI, Ticketing strategies immersive, F&B integration theater, Ancillary revenue
- **06 방탈출 비교**: Escape room vs immersive theater, Puzzle design immersive, Gamification of theater
- **07 미래 트렌드**: AI in immersive theater, Metaverse physical experiences, Hybrid immersive events, Sustainability in immersive
- **08 결론 및 제언**: Immersive experience investment, Future of live entertainment, Strategic recommendations

---

## 3. 시장 규모 및 데이터 정의 기준

### 시장 규모 정의 (Scope)
- **광의 (Broad)**: 모든 몰입형 체험 포함 (씨어터 + VR/AR + 전시 + 방탈출 등)
- **협의 (Narrow)**: 배우 주도의 서사적 몰입 경험(이머시브 씨어터)에 한정
- **작성 원칙**: 데이터 인용 시 반드시 해당 수치가 어떤 범위를 의미하는지 명시할 것.

### COVID-19 데이터 표준
- **Pre-COVID**: 2019년 및 이전 데이터는 반드시 "코로나 이전 (pre-COVID)" 명시
- **Post-COVID**: 2022-2025 데이터를 현재 시장 기준으로 사용
- **주의**: 코로나 전후 데이터를 직접 비교할 때는 환경적 차이를 주석으로 부기하며, 혼용하지 않음.

### 화폐 및 수치 표기
- **기본 통화**: USD (미국 달러) 사용
- **보조 표기**: KRW 병기 시 환율 명시 (예: $100 ≈ 130,000원, 2024년 평균 환율 1,300원 기준)
- **단위**: "$[금액]B" (billion), "$[금액]M" (million) 형식 사용

---

## 4. 사례 연구 대상 (Case Studies)

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

## 5. 문서 포맷 (YAML Frontmatter Template)

본 프로젝트의 모든 8개 리서치 문서는 아래의 YAML 형식을 상단에 포함해야 합니다.

```yaml
---
title: "[문서 제목]"
description: "[문서 설명 - 1~2문장]"
layout: default
category: "[시장 분석 | 디자인 | 케이스 스터디 | 기술 | 비즈니스]"
order: [번호 1~8]
date: 2026-02-[날짜]
tags: ["태그1", "태그2", "태그3", "태그4"]
---
```

---

## 6. 검증 체크리스트
- [ ] 이머시브 씨어터 정의가 포함되었는가?
- [ ] 코로나 전후 데이터 구분 기준을 준수했는가?
- [ ] 화폐 표기 시 USD를 우선하였는가?
- [ ] 지정된 7개 사례 연구 대상이 포함되었는가?
- [ ] YAML 템플릿이 포함되었는가?

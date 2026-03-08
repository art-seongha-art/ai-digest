# 오늘의 논문 — 2026-03-08

## SkillNet: AI 기술 생성, 평가 및 연결
*SkillNet: Create, Evaluate, and Connect AI Skills*

**저자**: Yuan Liang; Ruobin Zhong; Haoming Xu; Chen Jiang; Yi Zhong 외 | **출처**: huggingface

### 추천 이유

스코어 기반 선정 (관련도: 0.74, 키워드: 0.00, LLM: 1.00)

### 요약

- 문제: AI 에이전트의 장기적인 발전을 저해하는 체계적인 스킬 축적 및 전이 메커니즘의 부재로 인해 에이전트가 기존 전략을 활용하지 못하고 반복적으로 솔루션을 재발견하는 문제가 있습니다.
- 방법: SkillNet은 200,000개 이상의 AI 스킬을 통합 온톨로지 내에 구조화하여 생성, 평가, 조직화하는 개방형 인프라로, Safety, Completeness, Executability, Maintainability, Cost-awareness 등 다차원 평가를 수행합니다.
- 결과: SkillNet은 ALFWorld, WebShop, ScienceWorld에서 에이전트 성능을 크게 향상시켜 평균 보상을 40% 개선하고 실행 단계를 30% 감소시켰습니다.
- 키워드: SkillNet, AI agents, skill ontology, multi-dimensional evaluation, skill repository

### 초록 (한국어)

현재 AI 에이전트(AI agent)는 유연하게 도구를 호출하고 복잡한 작업을 실행할 수 있지만, 기술의 체계적인 축적 및 전이(transfer) 부족으로 인해 장기적인 발전이 저해되고 있습니다. 기술 통합(consolidation)을 위한 통일된 메커니즘이 없으면 에이전트들은 이전 전략을 활용하지 않고 고립된 맥락에서 해결책을 재발견하며 빈번하게 "바퀴를 재발명"합니다. 이러한 한계를 극복하기 위해 우리는 AI 기술을 대규모로 생성, 평가 및 조직화하도록 설계된 개방형 인프라인 SkillNet을 소개합니다. SkillNet은 통일된 온톨로지(ontology) 내에서 기술을 구조화하며, 이 온톨로지는 이질적인(heterogeneous) 소스에서 기술을 생성하고, 풍부한 관계형 연결을 설정하며, 안전성(Safety), 완전성(Completeness), 실행 가능성(Executability), 유지보수성(Maintainability), 비용 인식(Cost-awareness)에 걸쳐 다차원적 평가를 수행하는 것을 지원합니다. 우리의 인프라는 200,000개 이상의 기술 저장소(repository), 대화형 플랫폼, 그리고 다용도 Python 툴킷(toolkit)을 통합합니다. ALFWorld, WebShop, ScienceWorld에 대한 실험적 평가는 SkillNet이 에이전트 성능을 크게 향상시켜, 여러 백본(backbone) 모델에 걸쳐 평균 보상(reward)을 40% 개선하고 실행 단계(execution step)를 30% 감소시킨다는 것을 보여줍니다. 기술을 진화하고 구성 가능한(composable) 자산으로 형식화함으로써, SkillNet은 에이전트가 일시적인 경험에서 영구적인 숙달(mastery)로 나아갈 수 있는 견고한 기반을 제공합니다.

### 링크

- 원문: https://huggingface.co/papers/2603.04448
- 캡처: `archive/2026-03-08/captures/huggingface_2603.04448.html`

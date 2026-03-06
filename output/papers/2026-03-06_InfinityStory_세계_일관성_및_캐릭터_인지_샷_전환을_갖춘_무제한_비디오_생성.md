# 오늘의 논문 — 2026-03-06

## InfinityStory: 세계 일관성 및 캐릭터 인지 샷 전환을 갖춘 무제한 비디오 생성
*InfinityStory: Unlimited Video Generation with World Consistency and Character-Aware Shot Transitions*

**저자**: Mohamed Elmoghany; Liangbing Zhao; Xiaoqian Shen; Subhojyoti Mukherjee; Yang Zhou 외 | **출처**: huggingface

### 추천 이유

스코어 기반 선정 (관련도: 0.71, 키워드: 0.00, LLM: 1.00)

### 요약

문제: 장편 스토리텔링 비디오 생성 시 배경 일관성, 다중 피사체 샷 간 전환의 매끄러움, 그리고 시간 단위 길이로의 확장이 주요 난제이다.
방법: InfinityStory는 배경 일관성을 유지하는 생성 파이프라인과 다중 피사체 진입/퇴장을 처리하는 전환 인식 비디오 합성 모듈을 제안하며, 10,000개의 다중 피사체 전환 시퀀스를 포함하는 합성 데이터셋을 구축했다.
결과: VBench에서 InfinityStory는 Background Consistency 88.94, Subject Consistency 82.11로 최고 점수를 달성했으며, 전체 평균 순위 2.80으로 향상된 안정성과 부드러운 전환을 입증했다.
키워드: Video Generation, World Consistency, Shot Transitions, Multi-subject, VBench

### 초록 (한국어)

일관된 시각적 내러티브를 가진 장편 스토리텔링 비디오를 생성하는 것은 비디오 합성(video synthesis) 분야에서 여전히 중대한 과제로 남아 있습니다. 본 논문에서는 샷(shot) 간 배경 일관성, 다중 피사체(multi-subject) 샷 간(shot-to-shot) 매끄러운 전환, 그리고 시간 단위 내러티브로의 확장성(scalability)이라는 세 가지 핵심적인 한계점을 해결하는 새로운 프레임워크, 데이터셋, 모델을 제시합니다. 우리의 접근 방식은 캐릭터 정체성과 공간 관계를 보존하면서 장면 전반에 걸쳐 시각적 일관성을 유지하는 배경 일관성 생성 파이프라인을 도입합니다. 또한, 다중 피사체가 프레임에 진입하거나 이탈하는 복잡한 시나리오를 위한 매끄러운 샷 전환을 생성하여 이전 연구의 단일 피사체(single-subject) 한계를 뛰어넘는 전환 인식 비디오 합성 모듈을 제안합니다. 이를 지원하기 위해, 충분히 다뤄지지 않았던 동적 장면 구성을 포함하는 10,000개의 다중 피사체 전환 시퀀스로 구성된 합성 데이터셋을 기여합니다. VBench에서 InfinityStory는 가장 높은 배경 일관성(Background Consistency)(88.94), 가장 높은 피사체 일관성(Subject Consistency)(82.11), 그리고 최고의 전체 평균 순위(2.80)를 달성하여 향상된 안정성, 더 매끄러운 전환, 더 나은 시간적 일관성(temporal coherence)을 보여줍니다.

### 링크

- 원문: https://huggingface.co/papers/2603.03646
- 캡처: `archive/2026-03-06/captures/huggingface_2603.03646.html`

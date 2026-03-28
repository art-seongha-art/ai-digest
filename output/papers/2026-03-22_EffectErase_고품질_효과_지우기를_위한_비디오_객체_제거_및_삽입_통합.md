# 오늘의 논문 — 2026-03-22

## EffectErase: 고품질 효과 지우기를 위한 비디오 객체 제거 및 삽입 통합
*EffectErase: Joint Video Object Removal and Insertion for High-Quality Effect Erasing*

**저자**: Yang Fu; Yike Zheng; Ziyun Dai; Henghui Ding | **출처**: huggingface

### 추천 이유

스코어 기반 선정 (관련도: 0.71, 키워드: 0.00, LLM: 1.00)

### 요약

문제: 기존 비디오 객체 제거 기법들은 객체뿐만 아니라 변형, 그림자, 반사와 같은 시각적 효과를 제거하고 일관된 배경을 복원하는 데 어려움이 있으며, 이를 위한 체계적인 대규모 데이터셋도 부족하다.
방법: 60K 비디오 쌍과 5가지 효과 유형을 포함하는 대규모 VOR 데이터셋을 구축하고, 비디오 객체 삽입을 역보조 작업으로 활용하는 상호 학습(reciprocal learning) 기반의 EffectErase를 제안한다. 이 모델은 영향 영역에 초점을 맞춘 task-aware region guidance와 삽입-제거 일관성(insertion-removal consistency) 목표를 포함한다.
결과: EffectErase는 VOR 데이터셋으로 훈련되어 광범위한 실험에서 기존 기법 대비 우수한 성능을 달성하며, 고품질 비디오 객체 효과 제거를 성공적으로 수행한다.
키워드: Video Object Removal, Video Object Insertion, Reciprocal Learning, VOR, EffectErase

### 초록 (한국어)

비디오 객체 제거 (Video object removal)는 동적인 목표 객체와 변형, 그림자, 반사와 같은 시각적 효과를 제거하고 매끄러운 배경을 복원하는 것을 목표로 한다. 최근의 확산 기반 비디오 인페인팅 (diffusion-based video inpainting) 및 객체 제거 방법은 객체를 제거할 수 있지만, 이러한 효과를 지우고 일관된 배경을 합성하는 데 어려움을 겪는 경우가 많다. 방법론적 한계 외에도, 훈련 및 평가를 위해 다양한 환경에서 일반적인 객체 효과를 체계적으로 포착하는 포괄적인 데이터셋의 부족으로 인해 발전이 더욱 저해되고 있다. 이를 해결하기 위해, 우리는 VOR (Video Object Removal)을 소개한다. VOR은 다양한 쌍을 이룬 비디오를 제공하는 대규모 데이터셋으로, 각 쌍은 목표 객체가 효과와 함께 존재하는 비디오 하나와 객체 및 효과가 없는 비디오 하나, 그리고 해당 객체 마스크 (object mask)로 구성된다. VOR은 캡처된 소스와 합성된 소스에서 얻은 60K개의 고품질 비디오 쌍을 포함하며, 다섯 가지 효과 유형을 다루고, 광범위한 객체 범주뿐만 아니라 복잡하고 동적인 다중 객체 장면을 포괄한다. VOR을 기반으로, 우리는 EffectErase를 제안한다. EffectErase는 비디오 객체 삽입을 상호 학습 방식 (reciprocal learning scheme) 내의 역 보조 작업으로 취급하는 효과 인식 비디오 객체 제거 방법이다. 이 모델은 영향을 받은 영역에 학습을 집중시키고 유연한 작업 전환을 가능하게 하는 작업 인식 영역 안내 (task-aware region guidance)를 포함한다. 다음으로, 상호 보완적인 행동과 효과 영역 및 구조적 단서 (structural cue)의 공유된 지역화를 장려하는 삽입-제거 일관성 목표 (insertion-removal consistency objective)를 포함한다. VOR로 훈련된 EffectErase는 광범위한 실험에서 우수한 성능을 달성하며, 다양한 시나리오에서 고품질 비디오 객체 효과 제거를 제공한다.

### 링크

- 원문: https://huggingface.co/papers/2603.19224
- 캡처: `archive/2026-03-22/captures/huggingface_2603.19224.html`

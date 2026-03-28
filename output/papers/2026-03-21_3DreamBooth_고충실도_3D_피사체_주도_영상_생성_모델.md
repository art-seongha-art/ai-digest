# 오늘의 논문 — 2026-03-21

## 3DreamBooth: 고충실도 3D 피사체 주도 영상 생성 모델
*3DreamBooth: High-Fidelity 3D Subject-Driven Video Generation Model*

**저자**: Hyun-kyu Ko; Jihyeon Park; Younghyun Kim; Dongheok Park; Eunbyung Park | **출처**: huggingface

### 추천 이유

스코어 기반 선정 (관련도: 0.73, 키워드: 0.00, LLM: 1.00)

### 요약

- 문제: 기존 subject-driven 비디오 생성 모델은 대상을 2D로 처리하여 3D 공간 사전 지식이 부족해 뷰 일관성이 결여되고, 멀티뷰 비디오 데이터 부족으로 임의의 디테일 생성 및 시간적 과적합 문제가 발생한다.
- 방법: 3DreamBooth는 1-프레임 최적화 패러다임을 통해 공간 기하학과 시간적 움직임을 분리하여 광범위한 비디오 훈련 없이 강력한 3D 사전 지식을 모델에 주입한다. 3Dapter는 비대칭 조건화 전략을 통해 미세한 텍스처를 강화하고 수렴 속도를 가속화한다.
- 결과: 제안된 3DreamBooth 및 3Dapter 프레임워크는 2D 방식의 한계와 데이터 희소성을 극복하며, 강력한 3D 사전 지식 임베딩과 텍스처 디테일 강화를 통해 고품질의 3D-aware 비디오 커스터마이징을 가능하게 한다.
- 키워드: 3DreamBooth, 3Dapter, 3D-aware, Video Generation, Subject-Driven

### 초록 (한국어)

맞춤형 피사체의 동적이고 시점 일관적인 비디오를 생성하는 것은 몰입형 VR/AR, 가상 프로덕션, 차세대 전자상거래를 포함한 광범위한 신흥 애플리케이션에서 매우 중요하게 여겨진다. 하지만 피사체 기반 비디오 생성 분야의 빠른 발전에도 불구하고, 기존 방법론들은 주로 피사체를 2D 개체로 취급하며, 단일 시점 시각적 특징이나 텍스트 프롬프트를 통해 정체성(identity)을 전송하는 데 중점을 둔다. 실제 피사체는 본질적으로 3D이기 때문에, 이러한 2D 중심 접근 방식을 3D 객체 맞춤화에 적용하면 근본적인 한계가 드러난다. 즉, 3D 형상(geometry)을 재구성하는 데 필요한 포괄적인 공간 사전 지식(spatial priors)이 부족하다. 결과적으로, 새로운 시점(novel views)을 합성할 때, 진정한 3D 정체성(identity)을 보존하기보다는 보이지 않는 영역에 대해 그럴듯하지만 임의적인 세부 사항을 생성하는 데 의존해야 한다. 다중 시점 비디오 데이터셋의 부족으로 인해 진정한 3D 인식(3D-aware) 맞춤화를 달성하는 것은 여전히 어렵다. 제한된 비디오 시퀀스에 대해 모델을 미세 조정(fine-tune)하려고 시도할 수 있지만, 이는 종종 시간적 과적합(temporal overfitting)으로 이어진다. 이러한 문제들을 해결하기 위해, 우리는 3DreamBooth와 3Dapter로 구성된 3D 인식(3D-aware) 비디오 맞춤화를 위한 새로운 프레임워크를 소개한다. 3DreamBooth는 1프레임 최적화 패러다임(paradigm)을 통해 공간 형상(spatial geometry)을 시간적 움직임(temporal motion)으로부터 분리한다. 공간 표현(spatial representations)에 대한 업데이트를 제한함으로써, 광범위한 비디오 기반 훈련 없이도 모델에 강력한 3D 사전 지식(3D prior)을 효과적으로 주입한다. 미세한 질감(fine-grained textures)을 향상시키고 수렴(convergence)을 가속화하기 위해, 우리는 시각적 조건화 모듈(visual conditioning module)인 3Dapter를 통합한다. 단일 시점 사전 훈련(single-view pre-training) 후, 3Dapter는 비대칭 조건화 전략(asymmetrical conditioning strategy)을 통해 주 생성 브랜치(main generation branch)와 함께 다중 시점 공동 최적화(multi-view joint optimization)를 거친다. 이러한 설계는 모듈이 동적 선택적 라우터(dynamic selective router) 역할을 하여, 최소한의 참조 세트(reference set)로부터 시점별 형상 힌트(view-specific geometric hints)를 질의할 수 있도록 한다.
Project page: https://ko-lani.github.io/3DreamBooth/

### 링크

- 원문: https://huggingface.co/papers/2603.18524
- 캡처: `archive/2026-03-21/captures/huggingface_2603.18524.html`

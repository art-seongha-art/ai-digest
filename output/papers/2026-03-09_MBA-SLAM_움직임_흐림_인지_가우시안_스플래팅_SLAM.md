# 오늘의 논문 — 2026-03-09

## MBA-SLAM: 움직임 흐림 인지 가우시안 스플래팅 SLAM
*MBA-SLAM: Motion Blur Aware Gaussian Splatting SLAM*

**저자**: Peng Wang; Lingzhe Zhao; Yin Zhang; Shiyu Zhao; Peidong Liu | **연도**: 2024 | **출처**: arxiv

### 추천 이유

스코어 기반 선정 (관련도: 0.75, 키워드: 0.16, LLM: 1.00)

### 요약

- 문제: 기존 NeRF 및 3D Gaussian Splatting 기반 SLAM 방법들은 모션 블러가 심한 입력 프레임에서 카메라 위치 추정 정확도와 맵 재구성 품질이 크게 저하되는 문제가 있다.
- 방법: MBA-SLAM은 모션 블러를 인지하는 트래커와 NeRF 또는 3D Gaussian Splatting 매퍼를 통합한 덴스 비주얼 디블러 SLAM 파이프라인이다. 이는 모션 블러 이미지의 물리적 생성 과정을 모델링하여 3D 장면 표현 학습과 노출 시간 동안의 카메라 로컬 궤적 추정을 동시에 수행, 능동적으로 블러를 보상한다.
- 결과: MBA-SLAM은 모션 블러가 있는 데이터셋에서 기존 최첨단 방법들을 능가하며, 카메라 위치 추정 및 맵 재구성 모두에서 우수한 성능을 입증했다.
- 키워드: Motion Blur, SLAM, 3D Gaussian Splatting, Neural Radiance Fields, Deblurring

### 초록 (한국어)

신경 방사 필드(Neural Radiance Fields, NeRF) 및 3D 가우시안 스플래팅(3D Gaussian Splatting, 3DGS)과 같은 새로운 3D 장면 표현(3D scene representations)은 특히 고품질 비디오 시퀀스를 입력으로 사용할 때 사실적인 렌더링(photo-realistic rendering)을 위한 동시 위치 추정 및 지도 작성(Simultaneous Localization and Mapping, SLAM)에서 그 효과를 입증했다. 그러나 기존 방법들은 저조도 또는 장노출 조건과 같은 실제 시나리오에서 흔히 발생하는 모션 블러 프레임(motion-blurred frames)에 어려움을 겪는다. 이는 종종 카메라 위치 추정 정확도(camera localization accuracy)와 지도 재구성 품질(map reconstruction quality) 모두에서 상당한 감소를 초래한다. 이 문제를 해결하기 위해, 우리는 심각한 모션 블러 입력(motion-blurred inputs)을 처리하고 이미지 디블러링(image deblurring)을 향상시키기 위한 밀집 시각 디블러 SLAM 파이프라인(dense visual deblur SLAM pipeline), 즉 MBA-SLAM을 제안한다. 우리의 접근 방식은 효율적인 모션 블러 인식 추적기(motion blur-aware tracker)를 신경 방사 필드 또는 가우시안 스플래팅 기반 매퍼(mapper)와 통합한다. 모션 블러 이미지의 물리적 이미지 형성 과정(physical image formation process)을 정확하게 모델링함으로써, 우리 방법은 3D 장면 표현을 동시에 학습하고 노출 시간(exposure time) 동안 카메라의 로컬 궤적(local trajectory)을 추정하여 카메라 움직임으로 인한 모션 블러에 대한 사전 보상(proactive compensation)을 가능하게 한다. 실험에서 우리는 MBA-SLAM이 카메라 위치 추정 및 지도 재구성 모두에서 이전 최첨단 방법(state-of-the-art methods)을 능가하며, 선명한 이미지와 모션 블러의 영향을 받은 이미지를 포함하는 합성 데이터셋(synthetic datasets) 및 실제 데이터셋(real datasets) 전반에 걸쳐 우수한 성능을 보여주어 우리 접근 방식의 다용성(versatility)과 강건성(robustness)을 강조한다. 코드는 https://github.com/WU-CVGL/MBA-SLAM에서 확인할 수 있다.

### 링크

- 원문: http://arxiv.org/abs/2411.08279v2
- PDF: `archive/2026-03-09/pdfs/arxiv_2411.08279v2.pdf`

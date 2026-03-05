# Paper Agent — 2026-03-05

## 3D 가우시안 스플래팅 및 2D 가우시안 스플래팅으로 지원되는 SfM 프로세스를 통한 투명 및 반사 표면의 3D 재구성
*3D Reconstruction of Transparent and Reflective Surfaces, Through the Use of SfM Processes Supported by 3D Gaussian-Splatting and 2D Gaussian-Splatting*

**저자**: Billi Dario; Caroti Gabriella; Piemonte Andrea | **연도**: 2025 | **출처**: crossref | **DOI**: 10.20944/preprints202505.2191.v1

### 추천 이유

스코어 기반 선정 (관련도: 0.73, 키워드: 0.08, LLM: 1.00)

### 요약

문제: 투명하고 반사율이 높은 표면의 정확한 3D 재구성은 기존 방법으로는 어려운 문제이다.
방법: 본 연구는 기존 포토그래메트리, 향상된 3D Gaussian Splatting, 그리고 혁신적인 평면 표현을 활용하는 새로운 2D Gaussian Splatting (2DGS)의 세 가지 접근 방식을 평가한다.
결과: 유리 공예품 사례 연구에서 2DGS는 기하학적 재구성 및 다중 뷰 일관성에서 우수한 성능을 보였으며, 향상된 3D Gaussian Splatting의 표면 아티팩트와 기존 포토그래메트리의 불충분함을 극복했으나, 더 높은 계산 요구량을 가진다.
키워드: 3D Reconstruction, Transparent Surfaces, Reflective Surfaces, 2D Gaussian Splatting, 3D Gaussian Splatting

### 초록 (한국어)

이 연구는 까다로운 투명 표면의 3D 재구성(3D reconstruction)을 위한 세 가지 고급 접근 방식, 즉 기존 사진 측량법(photogrammetry), 향상된 3D 가우시안 스플래팅(3D Gaussian Splatting), 그리고 새로운 2D 가우시안 스플래팅(2D Gaussian Splatting, 2DGS)을 평가한다. 유리 유물에 대한 상세 사례 연구를 통해, 본 연구는 2DGS가 혁신적인 평면 표현(planar representation)을 활용하여 미세 표면 디테일과 복잡한 내부 구조를 포착하는 데 있어 다른 방법들보다 뛰어난 기하학적 재구성(geometric reconstruction) 및 다중 시점 일관성(multi-view consistency) 성능을 보여줌을 입증한다. 향상된 3D 접근 방식은 시각적 렌더링(rendering) 품질에서 이점을 보이지만, 표면 아티팩트(artifacts)를 나타내며, 기존 사진 측량법은 완전한 재구성에 부적합한 것으로 드러났다. 비교 분석은 2DGS가 더 높은 계산 요구 사항(computational demands)이 따르지만, 구조적 정확도(structural accuracy)와 지각적 품질(perceptual quality)에서 균형 잡힌 능력을 가지고 있음을 강조한다. 이러한 결과는 2DGS가 문화유산 문서화(cultural heritage documentation), 특히 정밀한 디지털 보존(digital preservation)이 필요한 투명하고 반사되는 객체에 대한 중요한 진전임을 확립한다. 본 연구는 정확한 3D 문서화가 필수적인 유산 보존(heritage conservation) 및 원격 감지(remote sensing) 응용 분야에서 더 광범위한 채택을 촉진하기 위한 성능 최적화(performance optimization) 및 접근성 개선(accessibility improvements)을 포함한 향후 개발의 주요 방향을 제시한다.

### 링크

- 원문: https://doi.org/10.20944/preprints202505.2191.v1
- 캡처: `archive/2026-03-05/captures/doi_10.20944_preprints202505.2191.v1.html`

---

## AI 실감미디어 콘텐츠 다이제스트

## 📌 오늘의 이슈

안녕하세요! 오늘 AI 업계에서는 'AI 에이전트'로의 전환이 점점 더 현실로 다가오고 있다는 소식이 눈에 띄네요. 이제는 단순히 질문에 답하는 걸 넘어, AI가 스스로 도구를 사용하고 복잡한 작업을 처리하는 시대가 오고 있어요. 개발자 커뮤니티에서는 이런 AI 에이전트가 기존 소프트웨어를 잘 쓸 수 있도록, 기계가 이해하기 쉬운 형태로 프로그램을 바꿔야 한다는 구체적인 논의까지 시작됐어요. 더 이상 '프롬프트 엔지니어링'에만 매달릴 게 아니라, AI가 일하는 방식을 근본적으로 고민해야 할 때가 온 거죠.

한편, AI와 결합한 실감미디어는 우리 일상 공간으로 더 깊숙이 들어오고 있어요. 국내에서는 실감미디어 기술 기업인 **닷밀**이 강화도에 AI를 접목한 대규모 복합문화공간을 만든다는 반가운 소식이 있었고요. 중앙대학교에서는 실감미디어 국제 컨퍼런스를 열어 미래 인재 양성에 대한 비전을 공유하기도 했어요. 하지만 이런 기술 발전의 이면에는 고민할 지점도 생기네요. **Meta**의 스마트 안경 같은 XR 기기가 사생활을 침해할 수 있다는 우려가 제기되면서, 기술이 우리 삶에 들어올 때 어떤 사회적 합의가 필요한지 생각하게 만드는 하루였어요.

## 🌐 글로벌 AI

**'AI 에이전트'로의 전환 가속화와 AI 통제권 논란.**
최근 AI 업계의 화두가 '프롬프트 엔지니어링'에서 스스로 목표를 설정하고 작업을 수행하는 '에이전틱 AI(Agentic AI)'로 넘어가고 있다. 이는 AI가 단순 응답을 넘어 능동적으로 도구를 사용하고 복잡한 과업을 해결하는 패러다임의 전환을 의미한다. 이러한 흐름 속에서 **OpenAI**의 CEO 샘 알트만은 미 국방부(펜타곤)의 AI 사용을 회사가 통제할 수 없다고 인정하며, 강력한 AI 기술의 통제권과 윤리적 사용에 대한 사회적 논의가 더욱 중요해졌음을 시사하였다.

🔗 [Sam Altman admits OpenAI can't control Pentagon's use of AI](https://www.theguardian.com/technology/2026/mar/04/sam-altman-openai-pentagon)

## 🏛️ 국내정책

**중앙대, AI 융합 실감미디어 국제 컨퍼런스 개최.**
**중앙대학교**가 '실감미디어 국제 컨퍼런스 2026'을 성공적으로 개최하였다. 이번 행사는 AI 기술과 실감미디어의 융합을 주제로, 관련 분야의 학문적 발전과 미래 인재 양성을 위한 비전을 제시하는 자리가 되었다. 이는 국내 학계와 정책 기관이 AI와 XR 기술의 시너지를 중요한 미래 성장 동력으로 인식하고 있음을 보여주는 사례이다.

🔗 [중앙대, 실감미디어 국제 컨퍼런스 2026 성료…AI 융합 미래 제시](https://news.google.com/rss/articles/CBMia0FVX3lxTFBNNzdTR0FrdmlWa0NTZ1lYZklYczFibmlmRlVrZGNQZXprT3lEMVZyM3hoM3duWEIxZGFDTXNzN1pObWhPWUhMbjUtOEtIby1uNUNDQ01jMjd4Y29pbGo0NkV0eHZCVkY1dTVF?oc=5)

## 🏭 산업계

**국내 실감미디어 공간 사업 확장과 XR 기기 프라이버시 문제 대두.**
국내 실감미디어 기업 **닷밀**이 강화도에 AI 기술을 결합한 차세대 복합문화공간을 조성한다고 발표했다. 이는 몰입형 기술이 엔터테인먼트를 넘어 지역 관광 및 문화 사업의 핵심 요소로 자리 잡고 있음을 보여준다. 반면, **Meta**의 레이밴 스마트 안경과 같은 상용 XR 기기가 공공장소에서의 녹화 기능으로 심각한 사생활 침해 문제를 야기할 수 있다는 비판이 제기되었다. 이는 XR 기술의 대중화에 앞서 해결해야 할 중요한 사회적, 윤리적 과제를 드러낸다.

🔗 ['차은우 동생', 닷밀과 강화도에 AI 결합 차세대 실감미디어 복합문화공간 조성 - 아시아경제](https://news.google.com/rss/articles/CBMiYEFVX3lxTFAxdHN3bExzNFM3OTBWVFZxblRFclc3RFhKSVdrZFliRHlWb0RVZmpOSlZfMHU1cG5lSEVYN2pNbE5KUzBLU2IzeWl3cU1FLVhZX25QNmJOMHZySG44alJ1WQ?oc=5)

## 🔬 연구동향

해당 없음

## 💬 커뮤니티

**AI 에이전트 시대를 위한 기존 CLI(Command-Line Interface) 재설계 제안.**
개발자 커뮤니티에서 AI 에이전트가 기존 소프트웨어를 효과적으로 사용하기 위해서는 현재의 인간 친화적인 CLI를 재설계해야 한다는 논의가 활발하다. AI 에이전트는 인간이 읽기 편한 텍스트보다 JSON과 같이 정형화된 데이터를 선호하므로, CLI가 기계가 파싱하기 쉬운(machine-readable) 형태로 결과를 출력하도록 개선해야 한다는 것이다. 이는 AI 에이전트 워크플로우의 안정성과 효율성을 높이기 위한 실질적인 엔지니어링 과제를 제시한다.

🔗 [You need to rewrite your CLI for AI agents](https://justin.poehnelt.com/posts/rewrite-your-cli-for-ai-agents/)

## 🎨 생성형AI

**AI 활용 미디어아트 전시 'Hyper X Flow' 개최.**
생성형 AI를 활용한 미디어아트 그룹전 'Hyper X Flow'가 개최되었다. 이번 전시는 AI를 단순한 창작 도구가 아닌, 예술적 개념을 탐구하고 표현하는 핵심 매체로 사용하는 작가들의 작품을 선보인다. 이는 생성형 AI 기술이 현대 미술계에서 새로운 미학적 가능성을 열고 예술가들의 창작 과정에 깊이 통합되고 있음을 보여주는 사례이다.

🔗 [제3회 ‘행간애’ 'Hyper X Flow' - 아트코리아방송](https://news.google.com/rss/articles/CBMibkFVX3lxTE5kcnkwRnlNV3JjV2xYVkNJTmc5TlJLaGNXQzNTdG40MzNmUUJuQmpVMUdQTkNiMEtWXy1BTDlNWUdyVW9pbUFpbmhVZ002bDdkTU95OHB0bTNSQy1WZHZYZGl0MFRWUXFSRmdCNGlB?oc=5)

## 📢 공모지원

- **사업명**: 2026년 기업 데이터 연계ㆍ활용 지원사업
- **주관기관**: 과학기술정보통신부
- **내용**: 중소·벤처기업의 데이터 활용 및 AI 도입을 촉진하기 위해 데이터 구매·가공, AI 솔루션 도입, 컨설팅 비용 등을 지원
- **마감일**: 공고문 확인 필요

🔗 [「2026년 기업 데이터 연계ㆍ활용 지원사업」 공고](https://www.msit.go.kr/bbs/view.do?sCode=user&mId=311&mPid=121&bbsSeqNo=100&nttSeqNo=3186529)

## 🔑 오늘의 키워드

**AI 에이전트 (AI Agent)**: 단순히 주어진 명령에 응답하는 것을 넘어, 목표를 달성하기 위해 스스로 환경을 인식하고, 계획을 세우며, 도구를 사용하여 행동하는 AI 시스템이다. 최근 프롬프트 엔지니어링의 한계를 넘어 AI의 자율성과 문제 해결 능력을 극대화하는 방향으로 주목받고 있다.

**실감미디어 (Immersive Media)**: 가상현실(VR), 증강현실(AR), 혼합현실(XR) 등을 포괄하는 기술로, 사용자에게 높은 몰입감과 현실감을 제공한다. 오늘 동향에서는 AI와 결합하여 대규모 문화 공간을 조성하는 등 물리적 공간과 융합되는 사례가 나타났다.

**CLI (Command-Line Interface)**: 사용자가 텍스트 기반의 명령어를 입력하여 컴퓨터와 상호작용하는 인터페이스이다. AI 에이전트가 기존 소프트웨어를 안정적으로 제어하기 위해, 인간이 아닌 기계가 해석하기 용이한(예: JSON 출력) 형태로 CLI를 개선해야 한다는 논의가 등장하며 중요 키워드가 되었다.

---

<details>
<summary>실행 정보</summary>

- 실행 시각: 2026-03-05T16:07:28.504887+00:00
- Provider: gemini
- Model: gemini-2.5-flash
- 검색 결과: 204건
- 신규 후보: 202건
- pending 추가: 1건
- PDF 저장: 실패 (캡처로 대체)

</details>
# Paper Agent — 2026-03-05

## 조각 오브젝트 생성을 위한 창의적 AI 개발
*Developing Creative AI to Generate Sculptural Objects*

**저자**: Songwei Ge; Austin Dill; Eunsu Kang; Chun-Liang Li; Lingyao Zhang; Manzil Zaheer; Barnabas Poczos | **연도**: 2019 | **출처**: arxiv

### 추천 이유

스코어 기반 선정 (관련도: 0.72, 키워드: 0.08, LLM: 1.00)

### 요약

문제: DeepDream 기반 접근 방식에서 발생하는 3D 조형물 객체 생성 시 점 구름의 희소성 문제를 해결한다.
방법: Amalgamated DeepDream (ADD)는 DeepDream에서 발생하는 점 구름 희소성 문제를 해결하여 창의적이고 인쇄 가능한 3D 점 구름을 생성한다. Partitioned DeepDream (PDD)는 점 구름 클러스터링과 ADD를 결합하여 더 다양한 3D 객체 생성을 가능하게 한다.
결과: ADD와 PDD 알고리즘을 통해 희소성 문제를 해결하고, 창의적이며 인쇄 가능한 3D 조형물 객체를 성공적으로 생성하고 실제 예술 설치물에 통합했다.
키워드: DeepDream, 3D point cloud, Generative AI, Sculptural object, Clustering

### 초록 (한국어)

우리는 기계 학습(machine learning)을 통해 조형물(sculptural objects)을 생성함으로써 인간과 기계 창의성의 교차점을 탐구한다. 본 연구는 자동 예술 생성(automatic art generation)의 기술적 세부 사항과 예술가이자 예술의 관객으로서 AI와 사람 간의 상호작용 모두에 대한 질문을 제기한다. 우리는 3D 포인트 클라우드(point cloud) 생성을 위한 두 가지 알고리즘을 소개하고, 이들의 조형물로서의 구현(actualization)과 총체적 예술 설치(holistic art installation)로의 통합에 대해 논의한다. 구체적으로, Amalgamated DeepDream (ADD) 알고리즘은 순진한(naive) DeepDream 기반 접근 방식에 의해 야기되는 희소성 문제(sparsity problem)를 해결하고 창의적이며 인쇄 가능한 포인트 클라우드를 생성한다. Partitioned DeepDream (PDD) 알고리즘은 포인트 클라우드 클러스터링(clustering) 알고리즘과 ADD를 결합함으로써 더 다양한 3D 객체 생성을 탐구할 수 있도록 한다.

### 링크

- 원문: http://arxiv.org/abs/1908.07587v1
- PDF: `archive/2026-03-05/pdfs/arxiv_1908.07587v1.pdf`

---

## AI 실감미디어 콘텐츠 다이제스트

## 📌 오늘의 이슈

안녕하세요! 오늘 AI 업계의 가장 큰 화두는 단연 'AI 에이전트'로의 전환인 것 같아요. 이제는 단순히 지시를 잘 따르는 AI를 넘어, 스스로 목표를 설정하고 작업을 수행하는 자율적인 AI, 즉 '에이전트'를 만드는 데 모두가 집중하고 있네요. 커뮤니티에서는 '프롬프트 엔지니어링의 시대는 끝났다'는 말이 나올 정도예요. 개발자들은 이제 AI가 직접 사용할 수 있도록 기존의 개발 도구(CLI)를 다시 설계해야 한다는 논의까지 시작했어요.

이런 흐름 속에서 국내에서는 AI와 실감미디어가 우리 일상 공간으로 빠르게 스며들고 있다는 소식이 들려왔어요. 실감미디어 전문기업 **닷밀**이 강화도에 AI를 결합한 대규모 복합문화공간을 짓는다고 발표했고요, **중앙대학교**에서는 실감미디어의 미래를 논하는 국제 컨퍼런스를 성공적으로 마쳤다고 해요. AI가 단순히 화면 속에 머무는 게 아니라, 우리가 직접 체험하고 즐기는 공간과 콘텐츠로 진화하는 모습이 정말 인상적이네요!

## 🌐 글로벌 AI

**AI 에이전트를 위한 CLI(Command Line Interface) 재설계 논의 활발**
AI 에이전트가 개발 도구를 직접 사용할 수 있도록 기존의 CLI를 재설계해야 한다는 주장이 제기되었다. 현재의 CLI는 인간 사용자를 위해 설계되어 텍스트 출력이 비정형적이고 길어 AI가 파싱하기 어렵다. 따라서 AI 에이전트가 안정적으로 사용할 수 있도록 JSON과 같은 구조화된 데이터를 출력하는 'AI 우선' CLI의 필요성이 강조되고 있다. 이는 AI 에이전트가 개발 워크플로우에 더 깊숙이 통합되기 위한 중요한 기술적 전환을 의미한다.

🔗 [You need to rewrite your CLI for AI agents](https://justin.poehnelt.com/posts/rewrite-your-cli-for-ai-agents/)

## 🏛️ 국내정책

**중앙대, AI 융합 실감미디어 국제 컨퍼런스 개최**
**중앙대학교**가 실감미디어 분야의 최신 기술과 미래를 조망하는 '실감미디어 국제 컨퍼런스 2026'을 성공적으로 개최하였다. 이번 컨퍼런스는 AI 기술과 실감미디어의 융합을 핵심 주제로 다루며, 학계와 산업계 전문가들이 모여 미래 비전을 공유하는 장이 되었다. 이는 국내 대학이 AI와 XR 등 미래 기술 분야의 연구 및 인재 양성을 주도하고 있음을 보여주는 사례이다.

🔗 [중앙대, 실감미디어 국제 컨퍼런스 2026 성료…AI 융합 미래 제시 - 서울타임즈뉴스](https://news.google.com/rss/articles/CBMia0FVX3lxTFBNNzdTR0FrdmlWa0NTZ1lYZklYczFibmlmRlVrZGNQZXprT3lEMVZyM3hoM3duWEIxZGFDTXNzN1pObWhPWUhMbjUtOEtIby1uNUNDQ01jMjd4Y29pbGo0NkV0eHZCVkY1dTVF?oc=5)

## 🏭 산업계

**닷밀, 강화도에 AI 기반 실감미디어 복합문화공간 조성**
실감미디어 콘텐츠 제작사 **닷밀**이 강화도에 AI 기술을 접목한 차세대 실감미디어 복합문화공간을 조성한다고 밝혔다. 이는 기술과 문화가 결합된 대규모 프로젝트로, 관람객에게 새로운 차원의 몰입형 경험을 제공하는 것을 목표로 한다. 이번 사업은 국내 실감미디어 산업이 단순 전시를 넘어, 지역 관광과 연계된 대규모 상업 공간으로 확장되고 있음을 보여주는 중요한 사례이다.

🔗 ['차은우 동생', 닷밀과 강화도에 AI 결합 차세대 실감미디어 복합문화공간 조성 - 아시아경제](https://news.google.com/rss/articles/CBMiYEFVX3lxTFAxdHN3bExzNFM3OTBWVFZxblRFclc3RFhKSVdrZFliRHlWb0RVZmpOSlZfMHU1cG5lSEVYN2pNbE5KUzBLU2IzeWl3cU1FLVhZX25QNmJOMHZySG44alJ1WQ?oc=5)

## 🔬 연구동향

**AGI 달성을 위한 '연속 학습'의 필요성에 대한 논쟁**
Hacker News 커뮤니티에서 AGI(인공일반지능) 개발에 '연속 학습(Continual Learning)'이 필수적인지에 대한 논의가 이루어졌다. 현재 **OpenAI**와 같은 선두 연구소들은 새로운 데이터가 쌓이면 주기적으로 모델 전체를 재학습시키는 방식을 사용하고 있다. 이는 인간처럼 지속적으로 새로운 정보를 배우고 통합하는 연속 학습과는 다른 접근법으로, 현재의 스케일링 법칙 기반 접근법이 AGI에 도달하기에 충분한지에 대한 연구계의 고민을 보여준다.

🔗 [We don't need continual learning for AGI. What top labs are currently doing](https://news.ycombinator.com/item?id=47259384)

## 💬 커뮤니티

**'프롬프트 엔지니어링' 시대의 종말과 '에이전트 AI'의 부상**
Reddit 커뮤니티를 중심으로 '프롬프트 엔지니어링'의 중요성이 감소하고, 자율적으로 작업을 수행하는 '에이전트 AI'가 부상할 것이라는 예측이 확산되고 있다. 사용자들은 이제 완벽한 프롬프트를 만드는 것보다, 명확한 목표를 부여하고 AI 에이전트가 스스로 문제를 해결하도록 하는 방식으로 패러다임이 전환될 것으로 보고 있다. 이는 AI 활용 방식이 인간의 지시를 정교화하는 단계에서 AI의 자율성을 극대화하는 단계로 넘어가고 있음을 시사한다.

🔗 [Are we finally done with "Prompt Engineering"? The shift to Agentic AI in 2026 is getting real.](https://www.reddit.com/r/DeepSeek/comments/1rll5q0/are_we_finally_done_with_prompt_engineering_the/)

## 🎨 생성형AI

**미디어 아티스트 그룹 '행간애', 생성형 AI 활용 전시 개최**
미디어 아티스트 그룹 **'행간애'**가 생성형 AI를 활용한 미디어아트 전시 'Hyper X Flow'를 개최하였다. 이번 전시는 인간의 의식과 AI의 상호작용을 탐구하며, AI가 만들어내는 예측 불가능한 이미지와 텍스트를 통해 새로운 예술적 경험을 제공한다. 이는 생성형 AI가 단순한 도구를 넘어, 현대 예술가들에게 새로운 창작의 매체이자 영감의 원천으로 자리 잡고 있음을 보여준다.

🔗 [제3회 ‘행간애’ 'Hyper X Flow' - 아트코리아방송](https://news.google.com/rss/articles/CBMibkFVX3lxTE5kcnkwRnlNV3JjV2xYVkNJTmc5TlJLaGNXQzNTdG40MzNmUUJuQmpVMUdQTkNiMEtWXy1BTDlNWUdyVW9pbUFpbmhVZ002bDdkTU95OHB0bTNSQy1WZHZYZGl0MFRWUXFSRmdCNGlB?oc=5)

## 📢 공모지원

- **사업명**: 2026년 기업 데이터 연계ㆍ활용 지원사업
- **주관기관**: 과학기술정보통신부
- **내용**: 기업이 보유한 데이터와 외부 데이터를 연계하여 새로운 비즈니스 모델이나 서비스를 창출할 수 있도록 컨설팅, 데이터 가공, 기술 등을 지원하는 사업
- **마감일**: 공고문 참조

🔗 [「2026년 기업 데이터 연계ㆍ활용 지원사업」 공고](https://www.msit.go.kr/bbs/view.do?sCode=user&mId=311&mPid=121&bbsSeqNo=100&nttSeqNo=3186529)

## 🔑 오늘의 키워드

**AI Agent (에이전트 AI)**: 특정 목표를 달성하기 위해 환경을 인식하고, 스스로 판단하여 자율적으로 행동하는 AI 시스템이다. 단순한 질의응답을 넘어 복잡한 작업을 위임받아 처리할 수 있어, '프롬프트 엔지니어링' 이후의 차세대 AI 패러다임으로 주목받고 있다.

**실감미디어 (Immersive Media)**: 가상현실(VR), 증강현실(AR), 혼합현실(XR) 등을 포괄하는 기술로, 사용자에게 높은 몰입감과 현실감을 제공하여 가상과 현실의 경계를 허무는 콘텐츠를 의미한다. 최근 AI 기술과 결합하여 상업 공간, 문화, 예술 등 다양한 분야로 빠르게 확산되고 있다.

**연속 학습 (Continual Learning)**: AI 모델이 기존에 학습한 지식을 잊어버리지 않으면서 새로운 데이터를 순차적으로 학습하는 능력이다. 이는 인간의 학습 방식과 유사하며, 변화하는 환경에 실시간으로 적응해야 하는 AI 시스템을 위한 핵심 연구 분야 중 하나이다.

---

<details>
<summary>실행 정보</summary>

- 실행 시각: 2026-03-05T16:13:18.195806+00:00
- Provider: gemini
- Model: gemini-2.5-flash
- 검색 결과: 203건
- 신규 후보: 200건
- pending 추가: 1건
- PDF 저장: 성공

</details>
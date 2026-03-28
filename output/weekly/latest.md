# 주간 AI 웹진 — 2026-03-29

> 이번 주 AI판, 속도전보다 워크플로 싸움이 더 뜨거웠습니다.

> 기간: 2026-03-22 ~ 2026-03-29
> 수집 건수: 15

## 이번 주 판세 요약

**이번 주는 새 모델이 튀어나온 것보다, 이미 있던 도구들이 어디까지 실무를 먹어치우는지가 더 또렷하게 보인 한 주였습니다.**

영상 생성 쪽에선 기존 세대 종료와 후속 경험 기본 전환이 공식화됐습니다. 중요한 건 특정 제품명보다도, 생성 툴들이 버전 교체를 더 빠르게 밀어붙이기 시작했다는 흐름입니다. 음악 생성 쪽에선 Suno가 입력, 리스타일링, 스타일 고정 기능을 한꺼번에 밀어 넣으면서 '한 곡 뽑기'보다 '내 작업물을 바로 이어 쓰기' 경쟁으로 판을 돌렸습니다.

### 세 줄 요약

- 이번 주 핵심은 신모델 공개보다 기존 워크플로를 갈아끼우는 변화였습니다.
- 음악·영상 생성 툴은 프롬프트 경쟁보다 내 소스와 자산을 바로 붙여 쓰는 쪽으로 움직였습니다.
- LLM 쪽은 성능 과시보다 도구 연결, 평가, 장기 실행 같은 실무 체력 강화가 더 선명했습니다.

## LLM

이번 주 LLM은 성능표보다 운영표가 더 중요해진 주간이었습니다.

### 1. Gemini 3.1 Flash Live: Making audio AI more natural and reliable

`2026-03-26 | 공식 발표 | Google | update`

![Gemini 3.1 Flash Live: Making audio AI more natural and reliable](images/2026-03-29_gemini-3-1-flash-live-making-audio-ai-more-natural-and-reliable_0ccccf36e2b1.png)

Google은 Gemini 3.1 Flash Live를 선보이며, 음성 모델의 정확도를 높이고 응답 지연 시간을 대폭 단축했습니다. 이는 사용자에게 더욱 유연하고 자연스러운 실시간 대화 경험을 제공합니다.

> 엔진 출력표보다, 자주 타는 차에 자동변속기를 달아 놓은 쪽에 더 가깝습니다.

[원문 보기](https://blog.google/innovation-and-ai/models-and-research/gemini-models/gemini-3-1-flash-live/)

### 2. Search Live is expanding globally

`2026-03-26 | 공식 발표 | Google | update`

![Search Live is expanding globally](images/2026-03-29_search-live-is-expanding-globally_f72d49ec37eb.png)

Google은 'Search Live' 기능을 통해 AI 모드에서 음성 및 카메라를 활용한 대화형 다중 모드 검색을 전 세계 200개 이상의 국가로 확장했습니다. 이는 사용자들이 텍스트 입력의 제약 없이 말하고 보여주면서 정보를 탐색할 수 있게 함으로써, 검색 경험을 보다 직관적이고 자연스러운 대화 형태로 근본적으로 변화시키는 중요한 전환점을 마련합니다.

> 이제 검색은 질문을 받아 적는 비서가 아닌, 눈을 마주하고 대화하는 친구가 되었습니다.

[원문 보기](https://blog.google/products-and-platforms/products/search/search-live-global-expansion/)

### 짧게 보고 갈 것

- Claude Code auto mode: a safer way to skip permissions (Anthropic)
- Lyria 3 Pro: Create longer tracks in more Google products (Google)
- Build with Lyria 3, our newest music generation model (Google)
- Harness design for long-running application development (Anthropic)
- Find out what’s new in the Gemini app in March's Gemini Drop. (Google)
- Make the switch: Bring your AI memories and chat history to Gemini (Google)
- 3 new Gemini features are coming to Google TV (Google)

## 영상 생성

영상 생성은 거창한 신기능 발표보다 버전 전환과 기존 작업 자산을 어떻게 이어갈지가 더 크게 보인 주간이었습니다.

### 1. Sora 1 Sunset – FAQ

`2026-03-17 | 공식 발표 | OpenAI | update`

![Sora 1 Sunset – FAQ](images/2026-03-29_sora-1-sunset-faq_b77ba89a005a.png)

OpenAI는 2026년 3월 13일부로 미국 내 Sora 1 서비스를 공식 종료하고, 이제 모든 사용자가 Sora 2를 기본 환경으로 이용하게 되었습니다. 기존 Sora 1에서 생성한 콘텐츠는 영구 삭제 전까지 제한된 기간 동안 데이터 내보내기가 가능합니다. 이는 사용자들이 더 이상 두 가지 버전 사이에서 혼란을 겪을 필요 없이, 최신 기술이 집약된 Sora 2의 단일화된 환경에서 더욱 효율적이고 일관된 영상 생성 경험을 할 수 있게 됨을 의미합니다.

> 마치 구형 내비게이션 대신 최신 지도와 기능이 통합된 하나의 시스템을 쓰는 것과 같습니다.

[원문 보기](https://help.openai.com/en/articles/20001071-sora-1-sunset-faq)

## 음악 생성

음악 생성 쪽은 이번 주에 유독 방향이 선명했습니다. 프롬프트 한 줄 받아 곡을 뽑는 데서 끝나는 게 아니라, 내 파일과 스타일을 바로 들고 들어오게 만드는 쪽으로 확실히 꺾였습니다.

### 1. Introducing Covers

`2026-03-29 | 공식 발표 | Suno | update`

![Introducing Covers](images/2026-03-29_introducing-covers_beee26a5330f.jpg)

Suno가 내 오디오를 다른 결로 다시 입히는 `Covers` 베타를 공개했습니다. 이건 프롬프트 한 줄 경쟁보다, 내 소스와 스타일을 바로 가져다 쓰는 워크플로 경쟁으로 넘어갔다는 뜻입니다.

> 빈 악보에 부탁하는 게 아니라, 내 작업 파일을 통째로 스튜디오에 들고 들어간 느낌입니다.

[원문 보기](https://suno.com/blog/covers)

### 2. Introducing Suno Scenes

`2026-03-29 | 공식 발표 | Suno | update`

![Introducing Suno Scenes](images/2026-03-29_introducing-suno-scenes_e25644658548.jpg)

Suno는 'Suno Scenes'라는 새로운 기능을 선보였습니다. 이제 사용자들이 카메라로 찍은 사진이나 영상에서 곧바로 자신만의 노래를 만들 수 있게 되었습니다.

> 멜로디 하나 얻는 수준이 아니라, 세션 파일에 자주 쓰는 악기 체인을 저장한 느낌입니다.

[원문 보기](https://suno.com/blog/introducing-suno-scenes)

### 짧게 보고 갈 것

- Ensuring Content Integrity: Suno Partners with Audible Magic for User Uploads (Suno)
- Audio Inputs (Suno)
- Introducing Personas (Suno)

## 이미지 생성

이번 주는 공식 채널 기준으로 굵직한 업데이트가 없었습니다.

## 편집/제작

이번 주는 공식 채널 기준으로 굵직한 업데이트가 없었습니다.

## 3D

이번 주는 공식 채널 기준으로 굵직한 업데이트가 없었습니다.

## 에이전트/자동화

이번 주는 공식 채널 기준으로 굵직한 업데이트가 없었습니다.

## XR/Spatial

이번 주는 공식 채널 기준으로 굵직한 업데이트가 없었습니다.

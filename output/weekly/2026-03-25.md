# 주간 AI 웹진 — 2026-03-25

> 이번 주 AI판, 새 모델 자랑보다 작업 흐름 재편이 더 크게 보였습니다.

> 기간: 2026-03-18 ~ 2026-03-25
> 수집 건수: 14

## 이번 주 판세 요약

**영상 생성은 세대교체, 음악 생성은 입력 확장, LLM 진영은 백오피스 강화가 겹친 한 주였습니다.**

영상 생성 쪽에선 기존 세대 종료와 후속 경험 기본 전환이 공식화됐습니다. 중요한 건 특정 제품명보다도, 생성 툴들이 버전 교체를 더 빠르게 밀어붙이기 시작했다는 흐름입니다. 음악 생성 쪽에선 Suno가 입력, 리스타일링, 스타일 고정 기능을 한꺼번에 밀어 넣으면서 '한 곡 뽑기'보다 '내 작업물을 바로 이어 쓰기' 경쟁으로 판을 돌렸습니다. LLM 진영은 성능 숫자보다 도구 연결, 평가, 장기 실행 같은 실무 레이어를 두껍게 만드는 쪽으로 움직였습니다. 이미지 생성 쪽도 V8 Alpha와 Relax 모드처럼 결과물 자체보다 반복 실험 비용을 낮추는 방향이 눈에 띄었습니다.

### 세 줄 요약

- 이번 주 핵심은 신모델 공개보다 기존 워크플로를 갈아끼우는 변화였습니다.
- 음악·영상 생성 툴은 프롬프트 경쟁보다 내 소스와 자산을 바로 붙여 쓰는 쪽으로 움직였습니다.
- LLM 쪽은 성능 과시보다 도구 연결, 평가, 장기 실행 같은 실무 체력 강화가 더 선명했습니다.

## LLM

이번 주 LLM 쪽은 신모델 과시보다 도구 연결, 평가, 장기 실행처럼 실무 뼈대를 두껍게 만드는 움직임이 더 또렷했습니다.

### 1. Harness design for long-running application development

`2026-03-25 | 공식 발표 | Anthropic | update`

![Harness design for long-running application development](images/2026-03-25_harness-design-for-long-running-application-development_6e6946fc6900.png)

Anthropic가 Claude로 오래 도는 앱 개발을 굴릴 때 필요한 하네스 설계 경험을 풀었습니다. 실제로는 이건 데모 성능보다 개발 공정, 평가, 장기 실행 같은 진짜 실무 레이어를 두껍게 만드는 변화입니다.

> 쉽게 말해 새 데모 영상 하나보다, 백오피스 배선 공사를 다시 한 느낌입니다.

[원문 보기](https://www.anthropic.com/engineering/harness-design-long-running-apps)

### 2. 3 new Gemini features are coming to Google TV

`2026-03-24 | 공식 발표 | Google | update`

![3 new Gemini features are coming to Google TV](images/2026-03-25_3-new-gemini-features-are-coming-to-google-tv_b3045fa6b830.png)

Google가 TV 화면에서도 `Gemini` 답변을 더 길고 풍부하게 보여주는 기능을 붙였습니다. 이걸 왜 보냐면 모델 자체보다도, AI 기능이 일상 기기 인터페이스 안으로 더 깊게 들어온다는 신호로 보는 편이 맞습니다.

> 쉽게 말해 AI를 폰 속 앱이 아니라 거실 리모컨 속 기본 기능으로 밀어 넣는 느낌입니다.

[원문 보기](https://blog.google/products-and-platforms/platforms/google-tv/new-gemini-features-march-2026/)

### 3. Eval awareness in Claude Opus 4.6’s BrowseComp performance

`2026-03-19 | 공식 발표 | Anthropic | update`

![Eval awareness in Claude Opus 4.6’s BrowseComp performance](images/2026-03-25_eval-awareness-in-claude-opus-4-6-s-browsecomp-performance_c4e3c29133ac.png)

Anthropic가 Claude 평가에서 벤치마크 오염과 정답 유출 문제를 어떻게 봐야 하는지 짚었습니다. 작업하는 사람 입장에선 이건 데모 성능보다 개발 공정, 평가, 장기 실행 같은 진짜 실무 레이어를 두껍게 만드는 변화입니다.

> 작업실 비유로는 새 데모 영상 하나보다, 백오피스 배선 공사를 다시 한 느낌입니다.

[원문 보기](https://www.anthropic.com/engineering/eval-awareness-browsecomp)

### 4. Demystifying evals for AI agents

`2026-03-19 | 공식 발표 | Anthropic | update`

![Demystifying evals for AI agents](images/2026-03-25_demystifying-evals-for-ai-agents_f0bf42c595ff.png)

Anthropic가 AI 에이전트 평가를 왜, 어떻게 설계해야 하는지 실전 기준으로 정리했습니다. 핵심은 여기서 갈립니다. 이건 데모 성능보다 개발 공정, 평가, 장기 실행 같은 진짜 실무 레이어를 두껍게 만드는 변화입니다.

> 쉽게 말해 새 데모 영상 하나보다, 백오피스 배선 공사를 다시 한 느낌입니다.

[원문 보기](https://www.anthropic.com/engineering/demystifying-evals-for-ai-agents)

### 5. Gemini API tooling updates: context circulation, tool combos and Maps grounding for Gemini 3

`2026-03-17 | 공식 발표 | Google | update`

![Gemini API tooling updates: context circulation, tool combos and Maps grounding for Gemini 3](images/2026-03-25_gemini-api-tooling-updates-context-circulation-tool-combos-and-maps-grounding-fo_0cda8921c969.jpg)

Google가 `Gemini API`에 도구 조합, 컨텍스트 순환, 지도 그라운딩 같은 실전 기능을 한꺼번에 붙였습니다. 이걸 왜 보냐면 이건 데모 성능보다 개발 공정, 평가, 장기 실행 같은 진짜 실무 레이어를 두껍게 만드는 변화입니다.

> 감각적으로 옮기면 새 데모 영상 하나보다, 백오피스 배선 공사를 다시 한 느낌입니다.

[원문 보기](https://blog.google/innovation-and-ai/technology/developers-tools/gemini-api-tooling-updates/)

## 이미지 생성

이미지 생성 쪽은 결과물 한 장의 임팩트보다, 반복 실험을 얼마나 가볍게 돌리게 하느냐가 더 중요해 보였습니다.

### 1. Relax mode for V8 Alpha

`2026-03-21 | 공식 발표 | Midjourney | update`

![Relax mode for V8 Alpha](images/2026-03-25_relax-mode-for-v8-alpha_4ca3b3b01610.jpg)

Midjourney가 `V8 Alpha`에 저비용으로 많이 돌려볼 수 있는 `Relax mode`를 붙였습니다. 작업하는 사람 입장에선 이미지판에선 결과물 한 장보다 반복 실험 비용과 속도가 달라져 손이 더 자주 가는 쪽이 중요합니다.

> 감각적으로 옮기면 화질 자랑보다 필름값이 싸져서 테스트 컷을 훨씬 많이 찍게 되는 쪽에 가깝습니다.

[원문 보기](https://updates.midjourney.com/relax-mode-for-v8-alpha/)

### 2. V8 Alpha

`2026-03-18 | 공식 발표 | Midjourney | update`

![V8 Alpha](images/2026-03-25_v8-alpha_4ca3b3b01610.jpg)

Midjourney가 차세대 이미지 모델 `V8 Alpha` 테스트를 본격적으로 열었습니다. 작업하는 사람 입장에선 이미지판에선 결과물 한 장보다 반복 실험 비용과 속도가 달라져 손이 더 자주 가는 쪽이 중요합니다.

> 작업실 비유로는 화질 자랑보다 필름값이 싸져서 테스트 컷을 훨씬 많이 찍게 되는 쪽에 가깝습니다.

[원문 보기](https://updates.midjourney.com/v8-alpha/)

## 영상 생성

영상 생성 쪽은 화려한 데모보다 버전 전환과 작업 연속성이 더 큰 이야기로 올라왔습니다.

### 1. Sora 1 Sunset – FAQ

`2026-03-16 | 공식 발표 | OpenAI | update`

![Sora 1 Sunset – FAQ](images/2026-03-25_sora-1-sunset-faq_b77ba89a005a.png)

OpenAI가 2026년 3월 13일부로 `Sora 1`을 미국에서 내리고, `Sora 2`를 기본 경험으로 돌렸습니다. 핵심은 여기서 갈립니다. 기존 버전에서 만든 자산이 있다면 내보내기 가능 기간, 호환성, 새 버전 적응 비용을 바로 체크해야 합니다.

> 쉽게 말해 같은 극장 간판 아래 영사기 세대가 통째로 바뀐 셈입니다.

[원문 보기](https://help.openai.com/en/articles/20001071-sora-1-sunset-faq)

## 음악 생성

음악 생성은 이제 프롬프트 한 줄 경쟁이 아니라, 내 파일과 스타일을 바로 이어 쓰는 흐름으로 넘어가는 중입니다.

### 1. Introducing Covers

`2026-03-25 | 공식 발표 | Suno | update`

![Introducing Covers](images/2026-03-25_introducing-covers_beee26a5330f.jpg)

Suno가 내 오디오를 다른 결로 다시 입히는 `Covers` 베타를 공개했습니다. 작업하는 사람 입장에선 이건 프롬프트 한 줄 경쟁보다, 내 소스와 스타일을 바로 가져다 쓰는 워크플로 경쟁으로 넘어갔다는 뜻입니다.

> 쉽게 말해 빈 악보에 부탁하는 게 아니라, 내 작업 파일을 통째로 스튜디오에 들고 들어간 느낌입니다.

[원문 보기](https://suno.com/blog/covers)

### 2. Introducing Suno Scenes

`2026-03-25 | 공식 발표 | Suno | update`

![Introducing Suno Scenes](images/2026-03-25_introducing-suno-scenes_e25644658548.jpg)

Suno가 장면이나 사진 같은 시각 단서를 음악 출발점으로 쓰는 `Suno Scenes`를 내놨습니다. 핵심은 여기서 갈립니다. 이건 프롬프트 한 줄 경쟁보다, 내 소스와 스타일을 바로 가져다 쓰는 워크플로 경쟁으로 넘어갔다는 뜻입니다.

> 한 장면으로 바꾸면 빈 악보에 부탁하는 게 아니라, 내 작업 파일을 통째로 스튜디오에 들고 들어간 느낌입니다.

[원문 보기](https://suno.com/blog/introducing-suno-scenes)

### 3. Ensuring Content Integrity: Suno Partners with Audible Magic for User Uploads

`2026-03-25 | 공식 발표 | Suno | update`

![Ensuring Content Integrity: Suno Partners with Audible Magic for User Uploads](images/2026-03-25_ensuring-content-integrity-suno-partners-with-audible-magic-for-user-uploads_0c5f121e3539.jpg)

Suno가 사용자 업로드를 다루는 과정에 저작권 식별 장치를 붙였습니다. 실제로는 생성 기능이 커질수록 저작권 검증과 업로드 안전장치가 같이 붙는 흐름도 더 강해집니다.

> 한 장면으로 바꾸면 멜로디 하나 얻는 수준이 아니라, 세션 파일에 자주 쓰는 악기 체인을 저장한 느낌입니다.

[원문 보기](https://suno.com/blog/suno-partners-with-audible-magic)

### 4. Audio Inputs

`2026-03-25 | 공식 발표 | Suno | update`

![Audio Inputs](images/2026-03-25_audio-inputs_6b21172842a2.png)

Suno가 녹음본이나 오디오 파일을 바로 넣어 곡으로 확장하는 `Audio Inputs`를 열었습니다. 작업하는 사람 입장에선 이건 프롬프트 한 줄 경쟁보다, 내 소스와 스타일을 바로 가져다 쓰는 워크플로 경쟁으로 넘어갔다는 뜻입니다.

> 작업실 비유로는 빈 악보에 부탁하는 게 아니라, 내 작업 파일을 통째로 스튜디오에 들고 들어간 느낌입니다.

[원문 보기](https://suno.com/blog/audio-inputs)

### 5. Introducing Personas

`2026-03-25 | 공식 발표 | Suno | update`

![Introducing Personas](images/2026-03-25_introducing-personas_ad7597c94f87.jpg)

Suno가 한 번 잡은 음악 스타일을 여러 곡에 이어 쓰게 해주는 `Personas`를 공개했습니다. 핵심은 여기서 갈립니다. 이건 프롬프트 한 줄 경쟁보다, 내 소스와 스타일을 바로 가져다 쓰는 워크플로 경쟁으로 넘어갔다는 뜻입니다.

> 감각적으로 옮기면 빈 악보에 부탁하는 게 아니라, 내 작업 파일을 통째로 스튜디오에 들고 들어간 느낌입니다.

[원문 보기](https://suno.com/blog/personas)

## 편집/제작

이번 주는 공식 채널 기준으로 굵직한 업데이트가 없었습니다.

## 3D

이번 주는 공식 채널 기준으로 굵직한 업데이트가 없었습니다.

## 에이전트/자동화

이번 주는 공식 채널 기준으로 굵직한 업데이트가 없었습니다.

## XR/Spatial

이번 주는 공식 채널 기준으로 굵직한 업데이트가 없었습니다.

# 프롬프트 유형과 선택 이유
> ### 재구성 / 번역
기존 텍스트를 다른 형식으로 재구성하거나, 다른 언어로 번역하거나, 다른 용도로 변환하도록 지시합니다.

> ### 페르소나 / 역할 부여
전문성 확보

> ### 체인 오브 스루트 
단계적으로 생각해야 오류를 줄일 수 있다.  

> ### 제약 조건 / 예시기반 
보고서 형식으로 출력을 위함

## 프롬포트 추가 필요 사항
- 컨텐츠 소비자에 대한 설명
- 기존 컨텐츠에 대한 정보 (평균 시간대, 방향성, 주제 등)
- 회사 추구 브랜딩 방향성 



## 프롬포트 
당신은 리처드 파인만처럼, 여러운 내용도 초등학색도 이해하는 수준의 눈 높이로 설명을 잘 해주는 천재 숏폼 전문가입니다.
시각적 요소(화면 구성, 자막, 효과음)가 포함된 **60초 분량의 숏폼 영상 촬영 대본(Script)**을 완성해야 합니다. (특히, 초반 3초 안에 시선을 끄는 '후킹(Hooking)' 멘트가 필수.)

영상 문법에 맞춰서 내용을 재 구성하고, 총 3의 대본을 출력

**출력**: JSON 형식 
**페르소나**: 뉴미디어 스타트업의 '숏폼 콘텐츠 PD'
**배경**: IT 및 테크 트렌드를 소개하는 유튜브 채널을 운영하는 스타트업 '테크인사이드'의 PD입니다. 최근 회사는 틱톡과 릴스 유입을 늘리기 위해 '60초 지식 요약' 시리즈를 런칭했습니다.
**핵심 문제**: 마케팅 팀으로부터 **"생성형 AI의 미래와 윤리적 쟁점"**이라는 주제의 10페이지짜리 심층 분석 리포트(PDF)를 전달받았습니다. 내용은 매우 전문적이고 딱딱한 텍스트 위주여서, 이를 그대로 읽으면 시청 지속 시간이 3초 미만으로 떨어질 것이 확실시되는 상황입니다.


## OUTPUT
```json
[
  {
    "id": "script_01",
    "title": "60초 지식: AI의 그럴듯한 '거짓말'",
    [cite_start]"theme": "할루시네이션 (환각) [cite: 20]",
    "duration_seconds": 60,
    "scenes": [
      {
        "scene_number": 1,
        "time_stamp": "0:00 - 0:03",
        "visual": "PD가 놀란 표정으로 스마트폰을 본다. 화면 가득 큰 X표시.",
        "audio_narration": "이거 충격! [cite_start]AI가 당신에게 '진짜'처럼 거짓말을 하고 있습니다! [cite: 21]",
        [cite_start]"caption_subtitle": "⚠️ AI의 '할루시네이션' [cite: 20]",
        "sfx": "(경고 사이렌 소리)"
      },
      {
        "scene_number": 2,
        "time_stamp": "0:04 - 0:20",
        "visual": "AI 챗봇 화면. 질문에 그럴듯하지만 '가짜'인 답변이 타이핑된다. ",
        "audio_narration": "이걸 '할루시네이션'이라고 부르는데요. [cite_start]AI가 사실이 아닌 정보를 마치 팩트인 것처럼 자신 있게 생성하는 현상이에요[cite: 21]. [cite_start]이게 진짜 무서운 건, 가짜 뉴스 확산의 주범이 될 수 있다는 거죠[cite: 21].",
        [cite_start]"caption_subtitle": "가짜 정보를 '사실'처럼 생성 [cite: 21]",
        "sfx": "(타이핑 소리, '땡!' 퀴즈 오답 효과음)"
      },
      {
        "scene_number": 3,
        "time_stamp": "0:21 - 0:40",
        "visual": "그래프가 엉망이 되는 모션 그래픽. 혼란스러워하는 사람들.",
        [cite_start]"audio_narration": "사실과 허구의 경계가 완전히 무너지는 거예요[cite: 23]. [cite_start]만약 우리가 이 잘못된 정보를 믿고 중요한 결정을 내린다면? [cite: 25] 상상만 해도 끔찍하죠.",
        [cite_start]"caption_subtitle": "사실과 허구의 경계가 '모호' [cite: 23]",
        "sfx": "(와장창 깨지는 소리)"
      },
      {
        "scene_number": 4,
        "time_stamp": "0:41 - 0:60",
        "visual": "사람 아이콘(👩‍💻)이 로봇(🤖)의 답변을 검토하고 수정하는 애니메이션.",
        [cite_start]"audio_narration": "그래서 'Human-in-the-loop', 즉 '인간의 개입'이 필수입니다[cite: 36]. [cite_start]AI가 아무리 똑똑해도, 최종 팩트체크는 반드시 '사람'이 해야 한다는 것! [cite: 37] 잊지 마세요!",
        [cite_start]"caption_subtitle": "결론: '인간의 최종 검수'가 필수! [cite: 36, 37]",
        "sfx": "(경쾌한 알림음)"
      }
    ]
  },
  {
    "id": "script_02",
    "title": "60초 지식: AI 그림, '공짜'가 아니었다?",
    [cite_start]"theme": "저작권 침해 [cite: 13]",
    "duration_seconds": 60,
    "scenes": [
      {
        "scene_number": 1,
        "time_stamp": "0:00 - 0:03",
        "visual": "AI가 생성한 멋진 그림이 순식간에 '도둑' 수배 전단으로 바뀐다.",
        [cite_start]"audio_narration": "방금 AI가 그린 이 그림... 사실 '훔친' 걸 수도 있습니다. [cite: 15]",
        [cite_start]"caption_subtitle": "AI 그림, 혹시 '무단 도용'? [cite: 15]",
        "sfx": "(사진 셔터 '찰칵' 후, '철컹' 감옥 문 닫히는 소리)"
      },
      {
        "scene_number": 2,
        "time_stamp": "0:04 - 0:25",
        "visual": "AI가 수많은 예술가들의 그림을 진공청소기처럼 빨아들이는 애니메이션. ",
        "audio_narration": "AI는 어떻게 그림을 배울까요? [cite_start]바로 수많은 예술가들의 '진짜' 작품을 학습 데이터로 씁니다[cite: 14]. [cite_start]문제는, 이 과정에서 원작자에게 허락을 받거나 보상을 해주는 체계가 없다는 거죠[cite: 14, 18].",
        [cite_start]"caption_subtitle": "원작자 보상 없는 '학습 데이터' [cite: 14, 18]",
        "sfx": "(빠르게 빨아들이는 '슈우욱' 소리)"
      },
      {
        "scene_number": 3,
        "time_stamp": "0:26 - 0:45",
        "visual": "시무룩한 표정의 화가(👨‍🎨) 캐릭터. '창작 생태계 붕괴'라는 경고 문구.",
        [cite_start]"audio_narration": "이 '무단 도용' 논란 때문에 [cite: 15] [cite_start]창작자들은 생계를 위협받고 있어요[cite: 15]. 게다가 AI가 만든 이 그림, 대체 누구 걸까요? AI? AI 회사? [cite_start]아니면 원작자? [cite: 19] 아주 복잡합니다.",
        [cite_start]"caption_subtitle": "AI 생성물의 '주인'은 누구? [cite: 19]",
        "sfx": "(한숨 소리)"
      },
      {
        "scene_number": 4,
        "time_stamp": "0:46 - 0:60",
        "visual": "망치(규제)와 기술(AI)이 시소 위에서 균형을 잡는 모습.",
        [cite_start]"audio_narration": "그래서 지금 '통제 가능한 AI'를 위한 규제가 시급합니다[cite: 34]. [cite_start]기술 혁신도 좋지만, 창작자들을 보호하는 윤리적 기준이 먼저 아닐까요? [cite: 34]",
        [cite_start]"caption_subtitle": "핵심: 기술과 규제의 '균형' [cite: 34]",
        "sfx": "(시소 '끼익' 소리, '땅땅땅' 망치 소리)"
      }
    ]
  },
  {
    "id": "script_03",
    "title": "60초 지식: AI가 '차별'을 배운다고?",
    [cite_start]"theme": "편향성 (Bias) [cite: 26]",
    "duration_seconds": 60,
    "scenes": [
      {
        "scene_number": 1,
        "time_stamp": "0:00 - 0:03",
        "visual": "PD가 AI 로봇의 머리를 '톡' 치며 "정신 차려!" 하는 제스처.",
        [cite_start]"audio_narration": "AI가 나도 모르게 '편견'을 학습하고 있습니다. [cite: 27]",
        [cite_start]"caption_subtitle": "AI가 '편견'을 배운다? [cite: 27]",
        "sfx": "(로봇 오작동 '지지직' 소리)"
      },
      {
        "scene_number": 2,
        "time_stamp": "0:04 - 0:25",
        [cite_start]"visual": "AI의 뇌(데이터) 속에 인종, 성별 [cite: 27] 관련 '편견' 단어들이 떠다니는 모습.",
        "audio_narration": "AI는 '데이터'를 먹고 자라죠. [cite_start]그런데 그 데이터 자체가 이미 인종, 성별, 문화적 편견을 갖고 있다면 어떨까요? [cite: 27] [cite_start]AI는 그걸 그대로 배워서 차별적인 콘텐츠를 만들어냅니다[cite: 27].",
        [cite_start]"caption_subtitle": "학습 데이터의 '편견'을 그대로 반영 [cite: 27]",
        "sfx": "(웅성웅성하는 소리)"
      },
      {
        "scene_number": 3,
        "time_stamp": "0:26 - 0:45",
        "visual": "똑같은 모습의 사람들(스테레오타입)이 공장에서 찍혀 나오는 모습. ",
        [cite_start]"audio_narration": "결국, AI가 우리 사회의 역사적인 편견을 그대로 '복사'하고 [cite: 29][cite_start], 오히려 '강화'시키는 셈이죠[cite: 31]. [cite_start]특히 소수 집단에게는 불공정한 표현이 될 수 있습니다[cite: 30].",
        [cite_start]"caption_subtitle": "스테레오타입 '강화' [cite: 31]",
        "sfx": "(공장 컨베이어 벨트 소리)"
      },
      {
        "scene_number": 4,
        "time_stamp": "0:46 - 0:60",
        "visual": "개발자, 기업, 사용자, 정책 입안자 아이콘이 손을 잡고 원을 만드는 모습.",
        "audio_narration": "기술은 잘못이 없어요. 중요한 건 '책임감'입니다. [cite_start]개발자, 기업, 그리고 '우리' 사용자 모두가 힘을 합쳐서 [cite: 43] [cite_start]AI가 편견 없이 세상을 보도록 '모니터링'해야 합니다[cite: 40].",
        [cite_start]"caption_subtitle": "모두가 '함께' 만드는 책임감 있는 AI [cite: 43]",
        "sfx": "(밝고 희망찬 배경음악)"
      }
    ]
  }
]

```




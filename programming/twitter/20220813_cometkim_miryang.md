# Twitter

## 1

@MiryangJung
유튜브 React, GraphQL, Relay 관련 추천 스레드

## 2

먼저 리액트 그림을 따라가봅시다.

전설이 시작된 JSConfUS 2013 의 리액트 첫 공개에선 가장 초기의 핵심 컨셉(Markup Generation, Reconcilation, Escape Hatch)과 배경 이야기에 대해 조금 들을 수 있습니다.

<https://youtu.be/GW0rj4sNH2w>

## 3

그 당시의 리액트도 센세이셔널 했지만, 지금의 리액트와는 다른 물건이라고 할 수 있습니다. 이걸 구분 짓는 기준이 되는 Fiber를 이해하는게 리액트를 이해하는데 도움이 됩니다.

2016년에 소개한 React Fiber, 스케줄링의 필요성을 역설합니다.

<https://youtu.be/aV1271hd9ew>

## 4

동시성 스케줄링을 이해하는게 리액트를 이해하는데 필요한 핵심임은 아무리 강조해도 지나치지 않습니다. 2016년 이후 리액트 컨퍼런스의 단골 주제이기도 합니다.

개인적으로 가장 잘 설명한 발표로는 ReactEurope 2019 의 이 세션을 뽑습니다.

<https://youtu.be/Iyrf52cwxQI>

## 5

Fiber 기반 아키텍처와 프로그래밍 모델에 대해 조금 더 자세한 설명이 포함된 세션

<https://www.youtube.com/watch?v=7GcrT0SBSnI&ab_channel=ReactRally>

## 6

Fiber 아키텍처는 확실히 흔치 않은 디자인 결정이며, 오늘날 성장하는 다른 프론트엔드 프레임워크 대비 리액트가 상대적으로 무겁고 복잡해 보이게 만드는 주원인이기도 합니다.

## 7

리액트는 아니지만 Rethinking Reactivity 도 아주 좋은 발표인데

<https://youtu.be/AdNJ3fydeao>

위 영상들을 번갈아 보면 Svelte의 철학으로 뽑는 "Radical Simplicity"와 React의 "성능만이 UX를 결정하지 않는다" 사이의 온도 차이를 느낄 수 있습니다.

## 8

이렇게 과도한 복잡성을 쌓아 도대체 무엇을 달성했는가는 Suspense와 Relay를 빼놓고서는 도저히 설명할 수가 없습니다.

2016년부터 떡밥이 난무하던 Facebook F5 프로젝트(웹 클라이언트 리디자인)의 결과 발표는 조금 충격적일만큼 기술격차를 느끼게 합니다.

<https://youtu.be/KT3XKDBZW7M>

## 9

릴레이 팟캐스트 같은거 듣다보면 2021년 이후는 더 아득히 먼 곳으로 간 것 같은데.... 팟캐는 아카이빙을 안해서 찾기가 어렵군요

## 10

GraphQL과 Relay 얘기를 좀 해보겠습니다. 이들은 분명 밖에서는 독립적으로 발전해왔는데 저렇게 잘 통합되어 굴러간다니 놀라운 일입니다.

사실 거의 역사를 함께 한 물건이기 때문에 React 프랙티스가 쌓여있는 것 만큼이나 GraphQL 프랙티스가 쌓여있습니다.

## 11

GraphQL은 N+1 문제에 대한 일반 해결책과 함께 소개됩니다. 사실상의 한몸 이라고 할 수 있는 DataLoader 를 이해하는 것이 정말 중요합니다.

<https://youtu.be/OQTnXNCDywA>

영상 초반에 흥미로운 탄생스토리가 담겨있고 후반엔 구현 디테일을 설명합니다.

## 12

GraphQL은 공개된 시점 직후부터 업계에서 꽤나 활발하게 사용되었기 때문에 오늘날에도 베스트 프랙티스라고 부르는 것들은 대부분 2015년 ~ 2016년 발표를 찾아보면 많이 엿볼 수 있습니다.

이런거라던가:

<https://youtu.be/1Fg_QtzI7SU>

## 13

이런거:

<https://youtu.be/zVNrqo9XGOs>

## 14

GraphQL 얼리어답터로 손꼽히는 빅테크 엔지니어들이 각자 생각하는 방식으로 GraphQL을 소개하는 짧은 영상입니다

<https://youtu.be/mRgvbtNuCZY>

## 15

React 와 GraphQL 의 대통합인 Relay 역시 역사를 함께합니다.

코어 컨셉은 이 영상에서 엿볼 수 있습니다.

<https://youtu.be/oPSuvaYmXBY>

## 16

뭔가 독립적으로 성장한 것 같은 두 기술이 잘 맞아 떨어지는 것 처럼 보이는 것은 우연이 아닙니다. React 와 GraphQL은 실제로 있는 거대한 문제를 함께 해결(개밥)하면서 성장해온 실용적인 기술입니다.

제 최애 발표에서 그것들의 배경 철학을 살짝 엿볼 수 있습니다.

<https://youtu.be/vG8WpLr6y_U>

## 17

GraphQL과 Relay는 실제 클라이언트의 어려운 문제들을 허탈하리만치 쉽게 해결해줍니다.

하지만 실제로 사용해보셨다면 그걸 위한 API 디자인이 얼마나 중요한지도 느낄겁니다.

GraphQL 스키마 디자인에는 정답이 없습니다만, 경험에 기반한 다양한 원칙들이 소개됩니다.

<https://youtu.be/pJamhW2xPYw>

## 18

유연한 스키마 설계에 대해서도 자주 얘기하는 편이고요

<https://youtu.be/fBkmlFfwRu0>

## 19

에러 디자인도 상당히 중요한 주제입니다

<https://youtu.be/RDNTP66oY2o>

## 20

API 이야기를 하는데 거버넌스 얘기가 빠질 수 없죠. 조직이 커지면 항상 API 거버넌스 문제를 함께 고민해야 합니다. GraphQL은 조직이 채택하기 좋은 기술일까요?

GraphQL에 대규모 투자를 쏟은 넷플릭스의 사례에서 그 결과(희망편)를 엿볼 수 있습니다.

<https://youtu.be/QrEOvHdH2Cg>

## 21

하지만 Federation 전략이 성공하려면 상당한 수준의 조직적인 투자가 필요한 것으로 보입니다.

많은 팀들이 지지하고 인프라와 교육적인 투자가 이루어져서 가능하다고 들었습니다.

대안으로 더 자주보이는 BFF 혼합 패턴에 대해 소개합니다.

<https://youtu.be/YnZr-qeiGO0>

## 22

GraphQL은 JS 클라이언트에서나 유용한거 아닌가요? 라고하면 전혀 아닌게... GraphQL 이 등장이 더 빨라고 첫 지원 타겟은 (RN이 아닌) iOS 앱이였습니다.

이 세션은 GraphQL 클라이언트 아키텍처를 독립적으로 잘 설명합니다

<https://youtu.be/vQkGO5q52uE>

## 23

React 도 그래요. 리액트를 안쓰거나 안쓰게 된다 하더라도 React 에서 시도한 컨셉과 프로그래밍 모델들이 다른 생태계에도 많은 영향을 미쳤다는 것은 부정할 수 없습니다.

배움을 바탕으로 더 나은 프레임워크를 만드는데 유효하게 활용할 수 있겠죠.

<https://youtu.be/K3JqNaw0-Us>

## 24

다 좋은데 데이터 패칭과 리액티비티 문제를 잘 해결해도 여전히 자체적으로 복잡한 UI가 있습니다.

이런 상황에서 추천하고 싶은 영상은 이것입니다

<https://youtu.be/VU1NKX6Qkxc>

## 25

더 직접적으로 리액트 코드베이스를 기반한 설명이 포함된 이 발표도 추천합니다

<https://youtu.be/sZg3DoTfHLQ>

## 26

위에 iOS GraphQL 클라이언트 아키텍처 영상에서 뭔가 빼먹은듯한 느낌이 들어서 찾아옴. Apollo 버전도 좋습니다

현대적인 웹 클라이언트 모델이 뭔지 보여주는 파트

<https://youtu.be/EDqw-sGVq3k?t=1790>

## 27

이것도 재밌어요 ㅋㅋㅋ

<https://youtu.be/wNUg1jpj9T0>

## 28

좀 일반적인 클라이언트 아키텍처 얘기를 하려면 Elm 이랑 Cycle.js 를 들고와야하거든요...? 디테일 한 건 글감으로 쟁여두고

특히나 리액트 생태계에서 Elm이 언급되는 경우가 잦은데 이 발표에서 둘 사이의 연관성을 얘기합니다

<https://youtu.be/jl1tGiUiTtI>

## 29

음 유튜브나 팟캐는 아카이빙할 리소스로써 별로 선호하지 않아서 재생목록이 이 정도 밖에 없네요. 심심하거나 자극이 필요할 때 하나씩 틀어보면 좋습니다.
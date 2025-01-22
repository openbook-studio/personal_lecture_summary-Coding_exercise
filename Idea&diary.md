# 2025.1.22
파이썬, 오류, 문법에 대한 부분들 거의 모두 찾을 수 있는 프로그램 및 서비스들은 github copilot, perplexity 등의 AI 도구들 통해서 충분히 searching 가능하고 일단 쉬운 레벨에서는 굉장히 친절하게 알려준다.  변수의 설정조차도 모를 때는 굉장히 유용하다고 생각되어진다.

# 2025.1.22(화)
머릿속에 있는 것을 표현할 때 좀 더 reliable 하고 일관성 있는 방법으로 코딩하고 소통할 수 있는 방법은 무엇이 있을까? 고민이 됨. 
유튜브 찾아보니 tool 보다는 전반적인 방법론을 많이 제시하고 있고 코딩 초기에 전체 청사진, 구조를 그려보는 것에 대한 이야기는 별로 없었음. 질문을 조금 더 고쳐보니
Q. for perflexity 파이썬 코드 작성시 머릿속에 있는 개념들을 명시화하는 좋은 방법으로 다이어그램 그리기 같은 것도 사용하는가?
Lucidchart / Draw.io 웹 기반 도구로 플로우차트, UML, 데이터 흐름 다이어그램 등을 쉽게 생성 가능.  vs code에서 draw.io설치하니 아무 문제 없이 바로 설치할 수 있었음. 
PlantUML - 텍스트 기반 UML 다이어그램 생성 도구로 버전 관리와 통합이 용이 / 설치가 어려워서 거의 1시간 헤매다가 포기함.
PyCharm / Visual Studio Code - PyCharm은 UML 클래스 다이어그램과 의존성 그래프를 제공하며, Visual Studio Code는 다양한 플러그인으로 시각화를 지원


draw.io 차트는 하나씩 그려 줘야만 하긴 한데 설치는 간단히 끝이 났다. 그러나 plantuml 플러그인은 거의 두 시간을 써서 해결했는데
"No valid diagram found here!" 

커서 위치 문제인 것이라고 생각되어졌는데, 그 이전에 java 와 graphviz 설치를 완전히 해 버리는 바람에 정확히 뭐가 문제였는지는 모르겠다. 여튼 커서 위치 문제는 항상 주의해서 
@startuml 과 @enduml 사이에 잘 위치할 수 있도록 꼭 하자!

다이어그램 종류에 따라서 https://plantuml.com/ko/sequence-diagram 사이트에 예시가 잘 나와있다. 

그리고 또 내가 문제를 만들었는데 vs code에 있는 설정을 뭔가 건드렸더니 원래 떠 있던 아이콘들이 사라져서 너무 불편해져버렸다...ㅜㅠ 이런 거 찾는데 또 1시간씩 쓸 생각을 하니 너무 머리가 아프고 절망적이다...  https://velog.io/@shn0322/VS-code-python-%EC%8B%A4%ED%96%89-%EB%B2%84%ED%8A%BC-%EC%82%AC%EB%9D%BC%EC%A7%90-%EB%AC%B8%EC%A0%9C  ai 도움으로 거의 30분만에? 찾긴 했다?! 다행인가?! ㅜㅠ  시간 마다 해야 할 과업들은 요원하네..ㅜㅠ
여튼 alt+d 를 하면 여튼 preview current diagram 을 볼 수 있음. 
https://www.youtube.com/watch?v=e6HMqKnJcdg 채널에서도 설명 해 줌.

다이어그램 추천 사이트: https://www.codesee.io/learning-center/code-visualization#uml

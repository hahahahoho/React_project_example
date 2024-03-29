# REACT!

------

안녕하세요? 오랬만에 깃허브에 커밋하게 되네요.

오늘은 리액트에 대해서 얘기해보고자 합니다. 그 전에 리액트에 대한 기본적인 설명과 간단한 사용에 대해서 올렸었습니다. 이번에는 실제 제가 프로젝트에 적용하는 과정에서 느낀 리액트에 대해서 이야기 해보고자 합니다.

리액트, javascript라이브러리죠? 실제 돔을 조작하는 것이 아닌 가상돔을 조작하고 상태를 관리함으로써 우리는 돔조작에서 자유로워지고 조금 더 객체지향적인 프로그래밍을 할 수 있도록 도와준다. 이게 바로 제가 느낀 리액트입니다.

react는 런닝커브가 크다. 라는 말이 있습니다. 실제로도 그렇다고 느꼈습니다. vue에 비해서 알아야 할 것들이 굉장히 많았습니다. es6, redux, styled-component, router, lifecycle, webpack, babel, 코드 스플리팅, 비동기통신 처리방법, props, state 등 등... 중요한 단어는 이 정도가 될 거 같네요.

그럼 어떻게 리액트를 사용하여야, 정말 제대로 사용하고 효율적으로 사용하는 것일까? 프로젝트를 진행하면서 스스로에게 가장 많이 던진 질문입니다. 이전에 웹페이지를 만들 때 list를 뿌려주면 페이지에 맡게 스크립트를 짜서 데이터를 불러와 각 각의 html태그에 넣어주면 끝이었던 거에 비해, 리액트를 사용하면서는 앞의 질문에 대한 해답을 찾기 위해 컴포넌트의 재활용성과 유지보수의 비용을 절감할 수 있는 방법을 고민하였습니다. 하나의 리스트를 짜더라도 다음에 사용하면 좀 더 쉽게, 그리고 좀 더 편리하게 유지보수를 하기 위해 코드를 작성하다보니, 기존 리스트를 짜는데에 비해 훨~씬 많은 시간을 잡아먹었습니다. 물론 처음이니까 더욱 그렇겠지요.

아직, 완벽한 해답은 찾지 못하였습니다. 아직도 코드는 계속 수정되고 있습니다. 일단 지금에서의 최종적인 목적은   

 첫째, 컴포넌트를 호출할 때, rest API를 호출하기 위해 tableName과 그리고 몇가지 옵션을 props로 데이터를 넘겨주어 자동으로 db데이터의 필드와 데이터를 뿌려주어, 한 개의 컴포넌트를 다른 곳에서도 쓸 수 있도록 재활용성을 높이는것. 

그리고 둘째, 생성된 컴포넌트와 관련된 하위 컴포넌트들도 자동적으로 상위 컴포넌트의 옵션에 맞게 적용되어 유지보수의 비용을 절감하는 것.

마지막으로, 컴포넌트 별로 style옵션을 다르게 받을 수 있도록 하여, 재활용 할 수 있는 반응형 컴포넌트를 만드는 것을 목적으로 하고 있습니다.

지금까지 만든 코드는 아직 프로젝트의 핵심 내용을 담고 있지 않고 보편적으로 볼 수 있는 부분만을 위의 목적에 맞게 만들고 있었던 코드이기에 모두 올려 놓겠습니다. 도움이 되었으면 너무나 좋을 것 같지만, 비효율적인 부분도 분명히 많기에 조언해주신다면 매우 감사히 받겠습니다.

아마 당분간은 이제 실제 진행중인 프로젝트를 만드는 것에 집중하게 될 것 같습니다. 프로젝트를 마치거나 혹시 중간에 다른 내용으로 공유하고자 하는 것이 생기면 다시 돌아와 커밋하겠습니다 ^^. 



 
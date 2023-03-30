# 1-1 REACT - 라이브러리? 프레임워크?
- 공식문서를 보면 스스로를 도구모음(라이브러리)라고 소개하고 있다. 반면에 엥귤러는 프레임워크(공장)이다. 즉 사용자가 덜 엄격한 규격의 제안을 받는다. 

1. 생태계
- 사람들이 많이 사용한다는 점에서, 정보에 접근하는 것이 이롭다는 이점이 있습니다. 
- stackoverflow 를 보면 2억 개의 정보가 쌓여 있습니다. 뷰(100만)

2. 리액트와 라이브러리(2강에서 20가지 이상의 라이브러리들을 살펴볼 것이다.)
- 가상돔, JSX, FLUX, 함수형 프로그래밍
- https://velog.io/@huurray/React%EC%9D%98-%ED%83%84%EC%83%9D%EA%B3%BC-Flux-%ED%8C%A8%ED%84%B4%EC%97%90-%EB%8C%80%ED%95%98%EC%97%AC

# 1-2 DOM : Document Object Model : 문서 노드 트리
- www.w3shcools.com
- 바닐라(순수) 자바스크립트를 보겠습니다. HTML 의 요소들을 하나의 돔이라고 부릅니다. 
- 코드샌드박스(리댁트 등에 대한 다양한 환경이 세팅되어 있습니다. 알쥐알쥐)
- prac - index.html

- CDN : 웹에서 사용되는 다양한 컨텐츠(리소스)를 저장하여 제공하는 시스템
- react documents CDN
  <script crossorigin src="https://unpkg.com/react@18/umd/react.development.js"></script>
  <script crossorigin src="https://unpkg.com/react-dom@18/umd/react-dom.development.js"></script>

- 이 CDN을 붙여 놓으면, 바닐라 자바스크립트로 리액트를 구현할 수 있다. 
- https://ko.reactjs.org/docs/react-api.html#createelement 

    React.createElement(
      type,
      [props],
      [...children]
    )

- 인자로 주어지는 타입에 따라 새로운 React 엘리먼트를 생성하여 반환합니다. type 인자로는 태그 이름 문자열('div' 또는 'span' 등), React 컴포넌트 타입, 또는 React Fragment 타입 중 하나가 올 수 있습니다.

- JSX로 작성된 코드는 React.createElement()를 사용하는 형태로 변환됩니다. JSX를 사용할 경우 React.createElement()를 직접 호출하는 일은 거의 없습니다. 자세한 정보는 JSX 없이 React 사용하기 문서에서 확인할 수 있습니다.

# 1-8 이벤트 리스너
https://www.w3schools.com/js/tryit.asp?filename=tryjs_event_onclick1

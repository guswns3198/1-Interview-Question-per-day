# Day 28 Question



## :memo: state변경 시 왜 setState, useState를 사용하나요?

state는 컴포넌트 렌더링에 영향을 주는 데이터를 갖고 있는 객체이며 이것을 업데이트 하기위해 setState, useState가 필요합니다. 직접 state를 수정하면 리액트는 render 함수를 호출하지 않아서 렌더링이 일어나지 않고 setState를 호출하여 state를 변경하면 리액트 엔진이 render 함수를 이용해서 렌더링을 실행하기 때문입니다.


:rocket:


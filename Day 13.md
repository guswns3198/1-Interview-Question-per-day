# Day 13 Question



## :memo: useEffect의 dependency array에 대해서 설명해주세요.

useEffect는 첫번째 인자로 콜백 함수를 받고 두번째 인자로 dependency array를 받습니다.
컴포넌트가 화면 맨 처음 렌더링 될 때만 실행되고 업데이트가 있을 때에는 실행하고 싶지 않다면 빈 배열을, 특정 값이 업데이트 될 때만 실행하고 싶다면 배열 안에 해당 특정 값을 넣어주고 모든 상태가 변경될 때 마다 렌더링 시키고 싶다면 두번째 인자에 아무것도 넣지 않으면 됩니다.


:rocket:

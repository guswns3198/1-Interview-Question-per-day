# Day 17 Question



## :memo: Redux의 주요 개념들과 연결 관계를 설명해주세요

Redux의 주요 개념으로 Action, Dispatch, Reducer, Store가 있습니다. 상태 변경이 필요한 이벤트가 발생 시 Action 객체가 생성되며 이는 Dispatch 함수의 인자로 전달되고 Dispatch 함수는 Action 객체를 Reducer 함수로 전달하게 됩니다. Reducer 함수는 전달받은 Action 객체에 따라 상태를 변경시킨 후 Store에 저장합니다.

:rocket:


## flex


#### ⧭ flex container : flex가 선언된 요소
```
display, flex-flow, flex-direction, flex-wrap, justify-content, align-content, align-items
```

#### display
  - flex : 블록 요소와 같이 Flex Container 정의 -> 최대화됨
  - inline-flex : 인라인 요소와 같이 Flex Container 정의 -> 최소화됨

#### flex-direction
  - row : 행 축 (좌 -> 우) 정렬
  - row-reverse : 행 축 (우 -> 좌) 정렬
  - column : 열 축 (위 -> 아래)
  - column-reverse : 열 축 (아래 -> 위)

#### flex-wrap
  - nowrap : 묶음(줄 바꿈) 없음 (무조건 한줄에 표시 하려고 함)
  - wrap : 여러 줄로 묶음 (영역이 작으면 줄 바꿈해줌)
  - wrap-reverse : wrap의 반대 방향으로 묶음

#### justify-content
  - flex-start : Flex items를 시작점으로 정렬
  - flex-end : Flex items를 끝점으로 정렬
  - center : Flex items를 가운데 정렬

#### align-content (여러줄 정렬)
  - stretch : Flex items를 시작점을 정렬
  - flex-start : Flex items를 시작점으로 정렬
  - flex-end : Flex items를 끝점으로 정렬
  - center : Flex items를 가운데 정렬

#### align-items (한줄 정렬)
  - stretch : Flex items를 교차 축으로 늘림
  - flex-start : Flex items를 각 줄의 시작점으로 정렬
  - flex-end : Flex items를 각 줄의 끝점으로 정렬
  - center : Flex items를 각 줄의ㅏ 가운데 정렬
<br>

#### ⧭ flex items : 그 자식 요소들
```
order, flex, flex-grow, flex-shrink, flex-basis, align-self
```

#### order
  - 0 : 순서 없음
  - 숫자 : 숫자가 작을 수록 먼저 (정렬 index가 됨)

#### flex-grow
  - 0 : 증가 비율 없음
  - 숫자 : 증가 비율

#### flex-shrink
  - 1 : Flex Container 너비에 따라 감소 비율 적용
  - 숫자 : 감소 비율

#### flex-basis
  - auto : 요소의 Content 너비 (글자의 길이 비례해서 늘어남)
  - 단위 : px, em, rem 등의 단위로 지정



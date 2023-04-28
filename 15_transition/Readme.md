## transition

transition: 속성명 지속시간 타이밍함수 대기시간;
- transition-property 
    all : 모든 속성에 적용
    속성이름 : 전환 효과를 사용할 속성 이름 명시
- transition-duration
    0s : 전환 효과 없음
    시간 : 지속시간(s) 지정
- transition-timing-function
    ease : 느리게-빠르게-느리게 = cubic-bezier(0.25, 0.1, 0.25, 1)
    linear : 일정하게 = cubic-bezier(0, 0, 1, 1)
    ease-in : 느리게-빠르게 = cubic-bezier(0.42, 0, 1, 1)
    ease-out : 빠르게-느리게 = cubic-bezier(0, 0, 0.58, 1)
    ease-in-out : 느리게-빠르게-느리게 = cubic-bezier(0.42, 0, 0.58, 1)
- transition-delay
    0s : 대기 시간 없음
    시간 : 대기시간(s) 지정
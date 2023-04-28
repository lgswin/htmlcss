## transform

transform: 변환함수1 변환함수2 변환함수3 ...;
transform: 원근법 이동 크기 회전 기울임;

### 2D 변환함수
    translate(x,y) : 이동 (x축, y축)
    translateX(x,y) : 이동 (x축)
    translateY(x,y) : 이동 (y축)
    scale(x,y) : 크기 (x축, y축)
    scaleX(x,y) : 크기 (x축)
    scaleY(x,y) : 크기 (y축)
    rotate(degree) : 회전 (각도)
    skew(x,y) : 기울임 (x축)
    skewX(x,y) : 기울임 (x축)
    skewY(x,y) : 기울임 (y축)
    matrix(n,n,n,n,n,n) : 2차원 변환 효과

### 3D 변환함수
    translateZ(z) : 이동 (z축)
    translate3d(x,y,z) : 이동 (x축, y축, z축)
    scaleZ(z) : 크기 (z축)
    scale3d(x,y,z) : 크기 (x축, y축, z축)
    rotateX(x) : 회전 (x축)
    rotateY(y) : 회전 (y축)
    rotateZ(z) : 회전 (z축)
    rotate3d(x,y,z,a) : 회전 (x축, y축, z축, 각도)
    perspective(n) : 원근법(거리)
    matrix3d(n,n,n,n,n,n,n,n,n,n,n,n,n,n,n,n) : 3차원 변환 효과

#### perspective : 하위 요소를 관찰하는 원근 거리를 지정 (속성)
    단위 : px 등 단위로 지정

- perspective 속성과 함수 차이점
    perspective:600px; - [관찰대상의 부모에 원근거리를 지정함] - perspective-origin
    tranform: perspective(600px) - [관찰대상에 원근거리를 지정함] - transform-origin

#### backface-visibility : 3D 변환으로 회전된 요소의 뒷면 숨김 여부
    visible : 뒷면 보임
    hidden : 뒷면 숨김

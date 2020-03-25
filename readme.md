# Web project_0315

## 어려웠던 부분

### 1. nav 구현

* 로고 이미지를 상단 바에 넣는 것과 로고 이미지에 a 태그를 넣는것이 어려웠음

### 2. footer 구현

* 없음

### 3. Home 구현

* 창의 너비가 줄어듬에 따라 하단 section에 들어가는 이미지의 크기가 가변적으로 변하게 하는 것이 어려웠음

### 4. Community 구현

* inline 속성을 띄는 span 태그들을 한번에 오른쪽 정렬시키는 것이 어려웠음



## 학습한 내용

### 1. nav 구현

* ul tag 는 기본적으로 margin과 padding 값을 갖고 있으므로 margin: 0; padding:0 을 통해 속성값을 변경시켜야한다
* position: fixed; top: 0; 을 통해 상단바를 고정시킬 수 있음
* display :flex; flex: 1; 을 통해 모든 메뉴 항목을 동일한 너비로 만들 수 있음
* li: hover: a{} 를 통해 포인터를 갖다대었을 때 속성이 변하게 할 수 있음

### 2. Footer 구현

* position: fixed; bottom: 0; 을 통해 상단바를 고정시킬 수 있음

### 3. Home 구현

* 사진을 background-image로 설정할 수 있음
* background-size 속성을 cover로 설정하면, 이미지 크기 비율을 그대로 유지한 상태에서 이미지가 들어있는 가로 또는 세로에 이미지를 맞출 수 있음(가로와 세로 중 큰 값에 맞춘다).
* border-radius: 10px; 를 통해 버튼의 모서리를 둥글게 만들 수 있음
* button{ border: 0; outline: 0;} 을 통해 버튼 클릭 시 나타나는 테두리를 없앨 수 있음
* button{curson: pointer;}을 통해 버튼에 커서를 올렸을 때 포인터를 바꿀 수 있음
* image의 크기를 vw, vh 로 설정하면 스크린의 크기에 맞춰 이미지의 크기가 가변적으로 변함
* flex 내부의 요소는 margin: 0 auto; 를 통해 중앙정렬을 만들 수 있음

### 4. Community 구현

* hr의 색상 및 넓이를 border: solid red 와 같이 한번에 설정할 수 있음
* article{border-bottom: 3px solid lightgrey}와 같이 테두리 속성을 한번에 설정할 수 있음
* 부모가 div 태그로 block 형태를 띄고, 자식이 span 태그로 inline 형태를 띌 때 inilie 형태를 수평정렬하기 위해서는 부모태그에 text-align 속성을 변경하면 된다.
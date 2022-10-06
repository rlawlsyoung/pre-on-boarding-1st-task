# 플레이키보드 프리온보딩 프론트 1팀

##  배포 링크

https://playkeyboard-front-team-1.netlify.app/

## 팀 노션
https://www.notion.so/1-b2d8f038c91c41aa9c2153b9c656c680

## 적용 기술 및 구현 기능

### 적용 기술 
+ Front-end : React.js styled component, hangul_js, React-Router-Dom

###  구현 기능

#### 박예선
- 구현한 기능 : 
- 설명 : 

       
#### 김진영
- 구현한 기능 : 키보드 체험하기, detail 페이지 이모티콘 및 텍스트 박스
- 설명 : hangul-js 라이브러리를 통해 한글 및 영어 키보드를 구현했습니다.<br/>
useState를 통해 inputValue라는 state를 관리하고 키보드 상단 input의 value를 inputValue state로 설정해주어 키 값을 입력할 때마다 상태값이 업데이트 되도록 구현했습니다.
또 detail 페이지에서 데이터를 받아와 isLiveTheme가 true인 경우에만 이모티콘과 텍스트 박스를 출력하도록 설정했습니다.
 
#### 이기완
- 구현한 기능 : 카테고리 페이지 테마부분 레이아웃 구현 및 스타일링
- 설명 : 
  - ES7부터 제공하는 async/await 키워드를 이용하여 api 데이터를 fetch 하였습니다. 기존 fetch에서 이용되는 then() 메서드가 길어지게 될시 코드의 가독성이 떨어진다는 문제점이 있기 때문에, 가독성 측면에서 좀 더 깔끔하게 보여지는 async/await 키워드를 택하였습니다. 
  - 마지막으로 각 테마 클릭시, react-router-dom에서 제공하는 useNavigate 훅을 이용하여, 세부 디테일을 볼수있는 페이지인 detail/:themeId로 넘어가게끔 구현하였습니다. 유저가 각 테마를 클릭할시 onClick 이벤트와 화살표함수를 이용하여 해당되는 테마 아이디 값을 useNavigate 훅에 담아 링크를 바꾸어주었습니다.
  - 스타일링의 경우 grid 레이아웃을 사용하여 카테고리 테마부분에 보여지는 전체적인 레이아웃을 잡았습니다. flex대신 grid를 택한 이유는 추후에 column이 추가되거나 레이아웃 전체 틀이 바뀔시 grid를 사용하는것이 유지보수 차원에서 더 좋다고 생각하여 택하였습니다. 
  
#### 이혜림 
- 구현한 기능 : 
- 설명 : 

#### 김정연
- 구현한 기능 : 클릭시 이모티콘 카운트 증가, style 변화
- 설명 : 이모티콘 count 값이 클릭한것만 증가하는 기능을 구현하였습니다.
useState로 count배열 상태값 관리하였고 배열을 모두 0으로 만들고 클릭한것만 count +1이 되고 style이 변하도록 구현하였습니다.

  
---

## Reference

- 이 프로젝트는 비영리목적으로 playkeyboard의 기업협업과제용으로 제작한 프로젝트입니다.
- 실무수준의 프로젝트이지만 학습용으로 만들었기 때문에 이 코드를 활용하여 이득을 취하거나 무단 배포할 경우 법적으로 문제될 수 있습니다.

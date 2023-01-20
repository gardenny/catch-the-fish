![fish](https://user-images.githubusercontent.com/110226567/213706360-87de7b9a-53ff-42d0-94ed-a0df788f815d.png)

# 🐟 Catch the fish!

물고기를 잡아라! 게임 👉 [Demo](https://imjone.github.io/catch-the-fish/)
<br><br>

## 📢 프로젝트 소개

### [성게를 피해 물고기를 클릭하는 게임]

- 주어진 시간 안에 성게를 피해 물고기를 클릭하여 모두 없애는 게임
- ▶️ 버튼을 누르면 게임이 시작되고, 시작한 이후에 ⏸ 버튼을 누르면 게임 일시정지
- 일시정지한 이후에 나오는 팝업창의 ↩️ 버튼을 누르면 게임이 처음부터 재시작
- 시간이 0초가 될 때까지 물고기를 모두 클릭하지 못하면 패배
<br><br>

## 🗨️ 사용 기술

![HTML](https://img.shields.io/badge/HTML-e34f26?style=flat-square&logo=HTML5&logoColor=white)
![css](https://img.shields.io/badge/CSS-1572b6?style=flat-square&logo=CSS3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-f7df1e?style=flat-square&logo=JavaScript&logoColor=white)
<br><br>

## 📋 주요 기능

### 1. 게임시작

- 시작 버튼 클릭 시 정지 버튼으로 변경
- 타이머 및 남은 물고기 수 카운트 시작
- 랜덤한 x, y 위치에 물고기 && 성게 이미지 배치

### 2. 게임 진행

- 물고기 클릭 시 해당 요소가 삭제되고 카운트 1씩 감소
- 성게 클릭 시 게임 종료와 동시에 lost 팝업창 노출

### 3. 게임 종료

- pause 버튼 클릭 시 타이머 및 카운트 일시정지
- replay 팝업창 노출

### 4. 팝업창 노출

- win : 시간 내에 물고기를 모두 클리어한 경우
- lost : 성게 클릭 || Timeout인 경우

### 5. 사운드 출력

- 게임 시작 시 배경 음악 재생
- 물고기 및 성게 클릭 시 해당 상황에 맞는 효과음 재생
- 게임 승리 및 패배 시 해당 상황에 맞는 효과음 재생
<br><br>

## 😊 나의 회고록

### 💧 어려웠던 점 및 개선 사항

물고기 잡기 게임은 나의 첫 번째 토이 프로젝트였다.
그렇기 때문에 함수를 어떻게 작성해야 할지 감이 잘 잡히지 않아 머리를 많이 싸맸다.
특히나 클래스, 모듈화 같은 부분들은 아직 익숙하지 않은 탓인지 코드를 매끄럽게 작성하기가 어려웠다...
중간에 this 바인딩 이슈로 하루를 통으로 날려 먹기도 했고.. 참 힘들었다.
시간적 여유가 생긴다면 메인 화면, 난이도 설정, 배치된 이미지들이 동적으로 움직이는 등의 추가적인 기능들까지 구현해보고 싶다.

### 🔥 배운 점 및 느낀 점

이번 프로젝트를 진행하면서 모듈화의 중요성에 대해 알게 되었다.
지금까지는 단순히 메인 페이지와 서브 페이지를 기준으로 js 파일을 나누어 작성했었는데,
이렇게 각각의 기능들을 클래스별로 분류하여 모듈화하니 main.js 코드가 훨씬 간결하고 깔끔해졌다.
또한 디자인 패턴이나 데이터 타입을 보장하는 방법 등 조금 더 기술적인 부분들에 대해 큰 틀을 익힐 수 있어서 좋았다.
비록 쉽지 않은 프로젝트였지만, 그래도 꾸준히 공부하면서 코드를 많이 짜다 보면
확실하게 내 것으로 만들 수 있으리라고 나는 믿는다. 앞으로도 쉬지 않고 계속해서 열심히 달려야겠다!
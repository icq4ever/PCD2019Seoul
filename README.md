# PCD 2019 Seoul
Processing Community Day 2019 @Seoul
프로세싱 커뮤니티 

----------
# p5 가지고 놀기

Lauren McCarthy 에 의해 제공

## Setup (10분)
1. p5.js 웹 에디터를 사용해 시작해보려 합니다. <a href="http://alpha.editor.p5js.org" target="blank">http://alpha.editor.p5js.org</a> 에서 사용할 수 있습니다.
2. 계정을 생성해 등록하고, 여러분의 첫 프로젝트의 이름을 선택하여 저장하세요.
3. p5.js를 시작할 준비가 되었습니다!

## 실험하기(45-90분)
p5.js를 시작하는 한가지 방법은, 그냥 가지고 놀면서 어떤 변화가 있는지 살펴보는 것입니다.

1. `setup()`과 `draw()`라고 되어있는 부분에 아래에 적혀있는 몇줄의 코드를 추가해보세요. 아래에 보이는 코드라인중 하나를 작성하되, 핑크색부분의 알파벳을 숫자로 바꿔 작성해보세요. 플레이버튼을 눌러 코드를 실행해봅니다. 각각의 라인이 무슨 역할을 하는지  알아차릴 수 있으신가요 ?
2. 숫자를 바꿔보면서 어떤 변화가 있는지 살펴보세요. 숫자를 바꿀때마다 플레이버튼을 눌러 코드를 다시 실행해줘야합니다. 각 문자들이 무엇을 의미하는지 아시겠어요 ?
3. 코드를 `setup()`과 `draw()` 에 넣었을 때, 어떤 차이점이 있는지 설명할 수 있을까요 ?


``` java
createCanvas(w, h);
ellipse(x, y, w, h);
rect(x, y, w, h);
line(x1, y1, x2, y2);
triangle(x1, y1, x2, y2, x3, y3);
fill(g);
fill(r, g, b, a);
stroke(r, g, b, a);
strokeWeight(w);
background(r, g, b, a);
print(s);

// 아래의 문자들은 위에 언급된 함수의 입력값으로 사용될 수 있습니다.
mouseX
mouseY
random(max);
second();
```

한동안 각자 실험을 해본 뒤, 다른사람과 함께 팀을 꾸려 실행을 해보면서, 여러분이 얻은 경험을 함께 나눠보세요.<br/>
마지막으로, 그룹 전체와 함께 라인 한줄 한줄을 훑어보세요. 진행자는 참가자의 컴퓨터를 프로젝터에 연결하도록 도와줄 수도 있습니다.


----------
## 스케치하기 (30분 이상)

앞의 순서에서 익힌것을 가지고, 여러분만의 스케치를 작성해보세요. <br/>
매 시도마다, 아래의 내용을 추가해보세요:

1. 프로그램을 실행할 때마다 바뀌는 한 요소
2. 마우스에 따라 변경되는 한 요소
3. 시간이 변함에 따라 변경되는한  요소

아래의 자료들이 도움이 될 것입니다:

- [p5js.org](http://p5js.org) - p5.js 웹사이트입니다. 라이브러리와, 레퍼런스, 예제 그리고 튜토리얼을 볼 수 있습니다.
- [p5js.org/reference](http://p5js.org/reference) - p5.js 레퍼런스


----------
## 다른 아이디어들
- 여러분의 친구들을 그려보세요. `arc(), curve(), elliipse(), line(), point(), quad(), rect(), triangle()`과 같은  2D  기본 도형과, `background(), colorMode(), fill(), noFill(), noStroke(), stroke()`과 같은 색 함수들을 사용해보세요. 캔버스의 크기를 지정하기 위해 `createCanvas()`를 사용해야 한다는 점을 기억하세요.
- 잠시 산책을 하면서 호기심을 주거나 영감을 주는 사물을 찾아보세요. 그리고 그것을 코드로 옮겨보세요. 그것은 사실적일수도 있고, 추상적일 수도 있을겁니다. 스케치를 실행할때마다 서로 다른 것들을 포함시켜보세요.
- 함께 그려보세요. 한 사람이 빈 캔버스를 만든 뒤, 한줄의 코드를 추가하고 실행한 뒤, 옆사람에게 전달하세요. 다름 사람은 다른 한줄의 코드를 추가한 뒤, 실행하여 다시 옆사람에게 전달합니다. 참여자 모두가 참여할때까지 이를 반복하세요.  한대 이상의 노트북을 이용해 동시에 이를 수행할 수도 있을겁니다. 이를 위해 참석자들의 좌석을 원형으로 배치하면 도움이 될 수도 있을겁니다. 참여자들은 원형으로 천천히 돌면서 스케치의 변화를 살펴볼 수 있을겁니다.


## 더 나아가서

아래는 p5.js와 코딩에 대해 보다 더 많은 도움이 되는 자료들입니다.
[](https://discourse.processing.org/c/p5js)
- [p5.js 포럼](https://discourse.processing.org/c/p5js) - p5.js 프로그래밍에 관해 질문하는 곳입니다
- [Daniel Shiffman의 코딩 연습 강좌 시리즈](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA) - p5.js 비디오 튜토리얼
- [Getting Started with p5.js](https://www.amazon.com/Make-Interactive-Graphics-JavaScript-Processing/dp/1457186772) - Lauren McCarthy, Casey Reas, Ben Fry 작성
- [Intro to programming for the visual arts with p5.js](https://www.kadenze.com/courses/introduction-to-programming-for-the-visual-arts-with-p5-js/info) - 무료로 등록가능한 온라인 강좌
- [Open Processing](https://www.openprocessing.org/) - p5.js 스케치를 공유하는 웹사이트.


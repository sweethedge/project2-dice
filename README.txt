# JS
0926
script: 
1. <head> 영역에
2. <body> 영역 어디든 가능.
3. 외부에서 import도 가능.
인라인 스타일 js call
<button class="bt1" onclick="funPrint();">버튼1</button>

function 함수명(매개변수) {
  명령;
}
함수명(매개변수1, 2, 3, ...)

여기까지 옛날 얘기.

"오늘 배운 JS 코드의 구조를 통째로 외워라"

/* function funPrint() {
console.log("외부 자바스크립트");
}
console.log("버튼"+1);
옛날 방식 */

// ES6+ : 화살표 함수
const funPrint = (n) => {
// console.log(n);
console.log(`버튼${n}`)
} 

0927.
let bt. "bt는 바뀔 수 있다"
요소 찾기 by tag, id, class, query.
"DOMContentloaded" 뒤에 요소 실행
"생각을 하고 코딩을 해라"
"JS는 타 언어와 달리 매개변수 자리에 함수가 들어간다"

조급하게 생각하지 마라. 편하게 생각해라. 맨날 하면 느는 거지.
"어쨌든 문제를 해결할 수 있는 능력이 필요하고, 그거를 늘려야 한다"
"미션을 받았을 때 어떤 입력>처리>출력을 원하는지 니가 먼저 생각을 하고, 그게 맞는지 물어봐라"
"어떤 걸 입력할까요?"
"어떤 걸 출력할까요?
"그 기능은 달라서 추가금이 필요한데요?"
"그건 개발자가 할 수 없는 일인데요?"
  "그러니까 A를 넣으면 A1이 나오면 되냐고 물어봐라"
  "기본적인 알고리즘은 flowchart다. 그거를 짜기 전에 입력-처리-출력을 어떻게 할지 생각해라"
"문법보다는 자바의 틀을 더 생각해야 한다"
"니가 짠 코드의 활용도 생각해야 한다"

블록 주석 shift alt a

0928.
html 태그 내에 id 라는 게 들어있는 줄은 
document.querySelector("#id").innerHTML = "니가 바꾸고 싶은 단어, 함수, 값"
으로 바꿀 수 있다.

ex. 
<section id="msg"> msg 섹션.
const msgDiv = document.querySelector('#msg').innerHTML = tag
<p id="total">확인을 눌러봐라.</p>
document.querySelector("#total").innerHTML = " 주사위값 = " + (i);

0929
form 에서 type이랑 name은 있어야 한다.
validationcheck는 js로 할 것이 아니고 하는 방법이 있다.

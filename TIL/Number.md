# Number

숫자를 나타내는 자료형
64bit로 실수와 정수 모두 표현 가능 
정상적이지 않은 숫자나 표현할 수 없는 범위의 수를 표시하는 NaN,Infinity

parseInt,parseFloadt 명령어
문자열 "1"과 1은 다름
명령어 뒤에 따라오는 괄호 안에 있는 문자열의 앞에서부터 Number를 인식함
```javascript
var height = prompt("키를 입력하세요");  //180.3입니다 입력
console.log(height, typeof(height));
//180.3입니다. string
var height_int = parseInt(height);
console.log(height_int, typeof(height_int));
//180 "number"
var height_float = parseFloat(height);
console.log(height_float,typeof(height_float));
//180.3 "number"
var height = prompt("키를 입력하세요"); //제 키는 180.3이면 좋겠습니다 입력
//제 키는 180.3이면 좋겠습니다. string
//NaN "number"  parseInt  문자열의 시작부터 인식 가능한 숫자를 인식하기 때문에 
//NaN "number"  parseFloat 문자열의 시작부터 인식 가능한 숫자를 인식하기 때문에 
var a=1/0;
//Infinity
```

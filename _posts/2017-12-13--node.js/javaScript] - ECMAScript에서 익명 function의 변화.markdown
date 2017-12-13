##### 오늘 공부한 내용

- ECMAScript6에서 JavaScript의 익명 함수(Function) 의 변화

##### 출처

- https://www.youtube.com/watch?v=9ueu3z2yu-k&list=PL9kzervdzKxy-c7UQgZbnZIr14DCPM87j&index=3 모던 웹을 위한 Node.js 3판 - 3강



#####  사용 예시

1. ECMAScript6 이전

   ```javascript
   const testFunction = function () {
     return "A";
   }
   ```

   ​

2. ECMAScript6 이후

   ```javascript
   //ECMAscript6에서는 익명 함수에는 => (화살표)를 사용할 수 있다.
   const testFunction2 = () => {
     return "B";
   }

   //추가적으로 화살표 함수는 화살표 뒤에 한 줄로 사용도 가능하다.
   const testFunction3 = () => "C";

   ```

   ​

필자는 JavaScript를 제대로 배우지 않고 node.js에 들어가서 다소 생소했지만, 다행이 람다를 조금 공부하고 있어서 해당 부분의 변화를 보고 람다식과 비슷하다는 생각을 했다.

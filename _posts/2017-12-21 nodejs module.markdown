---
layout: post
title:  "Node.js - 모듈 만들기"
date:   2017-12-21 16:22:59
author: 박성훈
categories: JavaScript

---

##### 오늘 공부한 내용

- 모듈 exports

##### 출처

- [Node.js 프로그래밍 5강 npm을 이용한 모듈 관리 | T아카데미](https://www.youtube.com/watch?v=bLKgL5TrUzo)

##### 사용

1. Module 만들기

   ```javascript
   function Exercise(){ //클래스 생성

   }

   Exercise.prototype.run = function (){
       console.log('run!');
   }
   module.exports = Exercise; //모듈로용하겠다
   ```

   ​

2. Module 불러오기

   ```javascript
   const Exercise = require('./exercise.js'); //module 불러오기
   const exerciseObj = new Exercise(); //객체 생성

   exerciseObj.run();

   ```

   ​

모듈을 분리함으로써 자바의 클래스와 비슷하게 사용할 수 있다. 

중요한 기능이니 숙지해야겠다.

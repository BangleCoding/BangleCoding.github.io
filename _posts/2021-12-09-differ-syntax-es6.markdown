---
layout: post
tags: [js, javascript, es6]
title: "ES6 문법 특징, 기존 문법에서 변한 부분"
date: 2021-12-07 18:16:14 +0900
categories: plugins
---

- 기존의 방법처럼 병합 연산자로 문자열과 문자열, 혹은 문자열과 변수를 연졀할 필요가 없어졌다.
- 템플릿 문자열을 사용할 때 작은따옴표('')가 아닌 백틱 (`) 문자열을 사용한다.
- 템플릿 문자열에 특수기호 '$' 를 사용하여 변수 또는 식을 포함할 수 있다.

```js
//기존 방법
var string1 = "hello";
var string2 = "greeting";
var string3 = string1 + " " + string2;
// hello greeting

var value1 = 1;
var value2 = 2;
var boolValue = 1 < 2;
var operator1 = "if you multiply them, " + value1 * value2 + " is the result.";
var operator2 =
  "if you print boolValue, " +
  (boolValue ? "true" : "false") +
  " is the result";
// if you multiply them, 2 is the result
// if you print boolValue, false is the result;
```

```js
//ES6 방법
let string1 = "hello";
let string2 = "greeting";
let string3 = `${string1} ${string2}`;
//hello greeting

let value1 = 1;
let value2 = 2;
let boolValue = 1 < 2;
let operator1 = `if you multiply them, ${value1 * value2} is the result.`;
let operator2 = `if you print boolValue, ${
  boolValue ? "true" : "false"
} is the result`;

// if you multiply them, 2 is the result
// if you print boolValue, false is the result;
```

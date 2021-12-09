---
layout: post
tags: [reactjs, prettier, visual studio code]
title: "prettier.js 확장 플러그인 attribute 설명"
date: 2021-12-07 18:16:14 +0900
categories: plugins
---

- visual studio code 의 유명한 extension인 prettier.js의 attribute 요점 정리.
- node.js 기반 프로젝트 최상단에 .prettierrc 파일을 만들고 JSON형태로 입력한다.

"useTabs": false, // 탭을 사용할 때 빈칸으로 채움
"printWidth": 100, //파일 최대 길이를 100칸으로 지정
"tabWidth": 2, //탭의 빈 칸을 두칸으로 지정
"trailingComma": "all", //나열항목의 마지막에 항상 쉼표(,)를 붙임
"semi": true, //실행 줄 마지막에 항상 세미콜론(;)을 붙임
"singleQuote": true //문자 따옴표를 작은따옴표('')로 통일

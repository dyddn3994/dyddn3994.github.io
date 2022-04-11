---
title: ref:\ DOM에 이름 달기
author: dyddn
date:  +0900
categories: [Front-end, React, 리액트를 다루는 기술]
tags: [DOM]
---

일반 HTML에서 DOM 요소에 이름을 달 때는 id를 사용한다. JSX에서도 동일하게 사용할 수 있지만 컴포넌트를 여러번 사용한다면 중복 id를 가진 DOM이 여러 개 생기는 문제가 발생할 수 있다. 이러한 문제를 피하기 위해 리액트 프로젝트 내부에서 DOM에 이름을 다는 방법이 ref(reference) 개념이다.

ref에 대해 이해도가 부족하여 차후에 작성
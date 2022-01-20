---
layout: single
title:  "could not find or load main class"
excerpt: "에러 해결"

categories:
  - error
tags:
  - [cmd]

toc: false
toc_sticky: false
 
date: 2021-05-14
last_modified_at: 2021-05-14
---

Error: Could not find or load main class HelloJava

Caused by: java.lang.ClassNotFoundException: HelloJava



- 위치 : 내 PC > 속성 > 설정 변경 > 고급 > 환경 변수
- 시스템 변수 : CLASSPATH > %JAVA_HOME%\lib;.

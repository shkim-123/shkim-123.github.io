---
layout: single
title:  "[운영체제] 프로세스 상태"
excerpt: ""

categories:
  - 운영체제
tags:
  - [운영체제]

toc: false
toc_sticky: false
 
date: 2021-05-16
last_modified_at: 2021-05-16

---
프로그램: 파일 시스템에 존재하는 실행파일

프로세스: 메모리에 적재되어 CPU에서 실행중인 프로그램

#### 프로세스 상태
![image](https://user-images.githubusercontent.com/82145134/118383062-ad2f1d00-b635-11eb-8112-32dff60e6bfc.png)


New : 프로세스가 생성중인 상태

Ready : 프로세스가 CPU를 기다리는 상태

Running : 프로세스가 CPU를 할당받아 명령어를 수행중인 상태

Blocked(sleep, wait) : 프로세스가 CPU를 할당 받아도 당장 실행할 수 없는 상태

Termianted : 프로세스의 실행 종료

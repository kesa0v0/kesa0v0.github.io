---
tags: 
  - Programming
  - Python
  - Web
categories: 
  - Programming
date: 2020-08-19 23:30:00
#description:
title: '개인용 Send Anywhere'
comments: true
---

## 계기

Send Anywhere가 참 편리하다. 코드 6자리를 통해 쉽게 파일을 주고 받을 수 있다. 구글 클라우드 같은거 쓰려면 로그인 해야하고 또 유선은 선이 필요한데 그런 것 필요없이 바로 파일 전송이 가능하다.

그런데 학교 컴퓨터에는 이 Send Anywhere을 막아 놓았다.

그래서 직접 만들어보자! 라는 생각이 들었다.


## 내용

파이썬에서 flask를 사용해 만들었다.

index에 접속하면 파일 업로드와 코드 입력하는 부분이 있다.

---

파일 1개 이상을 업로드 하고 전송 버튼을 누르면, 서버로 파일들을 받아오게 된다.

그 뒤 랜덤하게 코드 16진수 6자리를 만들고 이 코드를 이름으로 해서 받아온 파일들을 포함한 zip파일을 만든다.

코드를 리턴한다.

---

코드를 받으면 zip 파일을 다운로드 시킨다. 그 뒤 zip 파일을 지우는데 이 지우는 기능 깜빡하고 안 만들었다.

자고 일어나서 만들어야겠다.


## 개선점

랜덤하게 생성된 코드가 겹칠 수 있는데 고치는거 깜빡했다.

보안 문제가 있을 수 있을 꺼 같은데 개인용이라서 어차피 괜찮지 않을까 하는 생각이 든다.

UI 디자인. 근데 HTML 디자인 하는 법을 모른다. 흠...터레스팅...

## GITHUB

[Github](https://github.com/kesa0v0/CloudStorage)
---
tags: 
  - Programming
  - Python
categories: 
  - Programming
date: 2020-08-19 22:30:00
#description:
title: '단축 링크 생성기'
comments: true
---

파이썬에서 flask로 단축 링크 생성기를 만들었다.

sqlite3으로 DB를 만들었다.

DB는 번호, url, 단축url 의 구조를 가진다.

DB에 들어오는 순서대로 번호를 매긴다.

그 번호를 62개의 문자로 바꾼다.

```
0 -> "0"

1 -> "1"

...

61 -> "z"

62 -> "01"

...
```

이제 (주소)/link/(코드) 를 입력하면 db에 저장된 url로 리다이렉트 해준다.

로컬서버에서 잘 돌아가는건 확인했는데, flask는 진짜 서버로 사용하려면 다른게 필요하다고 한다. 흠터레스팅...

[Github](https://github.com/kesa0v0/short-uri)

---
tags: # 태그 사용
    - tag1
    - tag2

categories: #카테고리
  - category a  #only english

author_profile: true / false #작성자 프로필 출력여부
read_time: false # read_time을 출력할지 여부 1min read 같은것!

toc: true #Table Of Contents 목차 보여줌
toc_label: "My Table of Contents" # toc 이름 정의
toc_icon: "cog" #font Awesome아이콘으로 toc 아이콘 설정
toc_sticky: true # 스크롤 내릴때 같이 내려가는 목차

gallery: #이미지 갤러리
  - url: /assets/images/unsplash-gallery-image-1.jpg
    image_path: /assets/images/unsplash-gallery-image-1-th.jpg
    alt: "placeholder image 1"
    title: "Image 1 title caption"
  - url: /assets/images/unsplash-gallery-image-2.jpg
    image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Image 2 title caption"
#다음과 같이 본문에서 사용한다.
{% include gallery caption="This is a sample gallery with **Markdown support**." %}

header:  # 헤더에 유튜브 비디오 삽입
  video:
    id: XsxDH4HcOWA
    provider: youtube


link: https://github.com # Direct Link 만들기
---

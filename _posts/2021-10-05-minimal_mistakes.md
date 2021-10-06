---
title: minimal_mistakes 구조
tag: [blog]
---


jekyll 디렉토리 구조
나만 알아볼 수 있게 정리함


# _layouts
페이지 레이아웃 지정되어 있는 폴더


# _posts
작성한 포스트들 저장하는 폴더 (연-월-일-제목.md 지켜야함)

# _pages
날짜 관련 없는 포스트들 저장하는 폴더

# _site
명령어를 통해 빌드된 사이트. 로컬호스트에서 볼 수 있다.  
.gitignore에 해당 폴더 작성되어 있어 깃에 올라가지 않음  
github page에서 블로그를 빌드하고, 만약 본인이 직접 빌드하고 관리하고 싶은 경우 _site 파일 내용을 저장소에 올린다

# _includes
페이지에 include 할 수 있는 것들 (footer, header, toc...)이 정의되어 있음

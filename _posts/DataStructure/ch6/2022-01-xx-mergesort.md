---
title: 병합 정렬
excerpt: Doit 자료구조와 알고리즘 입문_6장
category: Data_Structure
---



파이썬에서 제공하는 병합 정렬.

방법1. list(sorted(a+b))    장점 : 배열이 정렬되지 않아도 사용 가능 단점:속도가 느림
방법2. heapq 모듈의 .merge 메소드 사용 list(heapq.merge(a,b)) 속도가 방법1보다 빠름


## 시간복잡도

병합정렬의 시간복잡도는 **O(nlogn)**이다.  
---
title:  "jekyll post add error" 
date:   2022-08-04 15:04:23
categories: [error]
tags: [error]
---

새로운 post를 올리기 위해 _posts 파일에 ex.md 파일을 추가하여 글을 쓰려 했는데 글이 올라가지 않는 상황이 발생했다.
1시간동안 이것저것 수정해 본 끝에 date를 현재 내가 글을 올린 시간에 맞추면 글이 올라가지 않는다는걸 찾았다.

--요약--

문제: jekyll post 추가가 되지않는 현상  
문제 원인: date  
문제 해결: date의 시점 시간이 한국이랑 다르기 때문, 이를 맞추려면 config 자체의 타이머 시간을 한국과 맞추거나 해당 시간을 감안  


[error]:      https://wocksl.github.io/#blog/error

---
title:  "intellij github contributors error"
date:   2022-08-05 02:13:00
categories: [error 모음]
tags: [error]
---

git push를 하고나서 github를 들어가보니 contributors가 내가 아닌 다른사람으로 올라가는 경우가 생겼다
error 원인을 찾아보니 나의 Intellij에서 github에 연동된 계정이 내가 아닌 다른사람이여서 수정했다

문제: git push 이후 contributors가 다른 사용자
문제 원인: Intellij에 다른 사용자가 로그인
문제 해결: git config를 확인 후 user, email을 수정 

``` ruby
$ git config --global --list
$ git config --global user.name 'your_name'
$ git config --global user.email 'your_email@example.com'
```
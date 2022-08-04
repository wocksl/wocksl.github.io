---
title:  "intellij github contributors error"
date:   2022-08-05 02:13:00
categories: [error 모음]
tags: [error]
---

git push를 하고나서 github를 들어가보니 contributors가 내가 아닌 다른사람으로 올라가는 경우가 생겼다.
원인을 찾아보다 보니 나의 Intellij

``` ruby
$ git config --global --list
$ git config --global user.name 'your_name'
$ git config --global user.email 'your_email@example.com'
```
---
layout: post
title:  0611 링크 에러(Fixed)
date:   2017-06-11 00:10:00
comments: false
categories: Homepage
---

작성자: 최아영

## 에러 증상
블로그 카테고리 클릭 후 해당 포스트 클릭 시 사이트 링크에서 '/126B'가 빠져 링크 오류 발생

이미지 삽입 시 동일한 증상이 나타난다.

## 원인 및 수정
원인은 _config.yml 파일에서 site 변수를 설정되어 있지 않아  '/126B'가 빠진 디폴트 주소로 설정되어 있었기 때문에, 
계속 링크 오류가 나는 것이었다.

[지킬 메뉴얼](https://jekyllrb.com/docs/variables/)을 통해 이를 알 수 있었으며, 
site 변수를 제대로 설정하여 이 에러를 고칠 수 있었다.

> site: https://17-1-skku-oss.github.io/126B/
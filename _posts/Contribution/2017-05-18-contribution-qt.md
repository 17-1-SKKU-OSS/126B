---
layout: post
title:  0518 Qt linquist
date:   2017-05-18
comments: false
categories: Contribution
---

작성자: 최아영

## Qt

Qt는 컴퓨터 프로그래밍에서 GUI 프로그램 개발에 널리 쓰이는 크로스 플랫폼 프레임워크이다.

Tiled는 이 Qt를 사용하여 만들어진 프로그램이다.

## Qt linguist
![linguist](https://17-1-skku-oss.github.io/126B/images/linguist.png)

[다운로드](http://www.softpedia.com/get/Others/Home-Education/Qt-Linguist.shtml)

Qt에 쓰이는 문자열을 ts파일로 모아, Qt linquist라는 유틸리티를 통해 번역할 수 있다.

원본 텍스트가 보이고 그 아래에 다국어로 번역할 수 있도록 되어 있어 편리하게 번역을 진행할 수 있다.

Tiled는 번역 기여시 이 Qt linquist를 이용해 tiled_en.ts 파일을 번역하여 PR 해줄 것을 요청하고 있다.

### 번역 방법
* Qt Linguist에서 `translations/tiled_en.ts`를 연다.
* `Edit -> Translation File Settings...`에서 Target Language를 바꾼다.

![lin1](https://17-1-skku-oss.github.io/126B/images/lin1.png)
* 파일을 `tiled_ko.ts`로 저장한다.
* 문자열을 번역하고 업데이트한다.
![lin2](https://17-1-skku-oss.github.io/126B/images/lin2.png)

### 번역 상태

![linguist](https://17-1-skku-oss.github.io/126B/images/icon.png)

번역 상태는 번역 완료/번역 미완료/번역 안 됨의 3가지로 나눌 수 있으며 텍스트 왼쪽 아이콘으로 상태를 알 수 있다.

#### 번역 완료

![linguist](https://17-1-skku-oss.github.io/126B/images/icon_finished.png)

* 번역이 완료된 상태

#### 번역 미완료

![linguist](https://17-1-skku-oss.github.io/126B/images/icon_unfinished.png)

* 번역하였으나 완료는 아님

#### 번역 안됨

![linguist](https://17-1-skku-oss.github.io/126B/images/icon_not.png)

* 번역되지 않은 상태

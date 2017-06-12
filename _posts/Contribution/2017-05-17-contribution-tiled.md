---
layout: post
title:  0517 기여 프로젝트 확정-Tiled
date:   2017-05-17
comments: false
categories: Contribution
---

작성자: 최아영

## Tiled 프로젝트에 대해

기여할 프로젝트에 대해 생각해보던 중 대외활동에서 사용했던 "Tiled" 툴을 떠올렸다.

깃허브에서 오픈소스로 개발되고 있으며 아직 한글화 번역이 안 된 프로그램이었기에

실습 때 정했던 Beets 프로젝트 대신, Tiled 프로젝트에 기여하기로 확정하였다.

![Tiled](https://17-1-skku-oss.github.io/126B/images/tiled.png)

[홈페이지](http://www.mapeditor.org/)

[깃허브 페이지](https://github.com/bjorn/tiled)

Tiled는 Tile Map 게임의 맵 디자인을 할 수 있는 툴이다. 

여러 Tile Set을 불러와 그 Tile들을 이용해 맵을 만들 수 있다.

또한 Pygame, Unity3D, GameMaker 등 여러 툴에 적용 가능하다.

## 프로젝트 기여 방안

현재 여러 언어로 프로그램이 번역되어 있으나, 한국어가 없어 이를 번역하며 프로젝트에 기여하기로 하였다.

Tiled는 Qt 기반의 프로그램이며, Qt는 GUI 프로그램 개발에 널리 쓰이는 크로스 플랫폼 오픈소스 프레임워크이다.

Qt 프로그램은 Qt Linguist라는 툴을 이용하여 다국어 번역을 할 수 있다.

우리 팀은 이 Qt Linguist 툴을 이용해 tiled_en.ts을 tiled_ko.ts 파일로 번역하여 프로그램 내부를 한글화 하기로 결정하였다.

[번역 기여관련 위키](https://github.com/bjorn/tiled/wiki/Translating-Tiled)

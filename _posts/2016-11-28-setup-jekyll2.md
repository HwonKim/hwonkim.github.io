---
layout: post
title:  "Jekyll 설치하기(2) - 필수 파일 설치"
date:   2016-11-28 09:00:13
categories: setup
permalink: /setup/jekyll/2
---
**Jekyll을 Window7에 설치하여 Github 블로그 작성하는 방법을 알아보자!**

## 1. Railsinstaller 설치

**Jekyll을 사용하려면 Ruby, DevKit, Git등 다양한 툴이 필요한데 Railsinstaller하나로 이 모든 것을 한번에 설치 할 수 있다.**  
**타 블로그를 참고하며 하나하나 설치도 해봤지만 이 방법이 제일 편한 것 같다**

![이미지](/image/setup/jekyll-win-5.png)  

**[Railsinstaller](http://railsinstaller.org/en)에 접속해서 Windows 버전을 다운받아 설치한다.**  

![이미지](/image/setup/jekyll-win-6.png)  

**Railsinstaller 설치!**  
**Install Git과 Add executables for Ruby, Devkit and Git 설정을 체크!**  

## 2. Jekyll 설치
**RailsInstaller 설치 후 Command 창에서 다음과 같이 입력한다**
> cd : C:\RailsInstaller\DevKit  
> gem install jekyll  

**운이 좋으면 에러 없이 설치 되겠지만 필자는 다음과 같은 에러를 겪었다.**  

![이미지](/image/setup/jekyll-win-7.png)  


참고 : [WhaTap Tech Blog](http://tech.whatap.io/2015/09/11/install-jekyll-on-windows/) Jekyll 윈도우에 설치해서 사용하기
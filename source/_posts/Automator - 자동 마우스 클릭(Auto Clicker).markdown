---
layout: post
title:  "Automator 마우스 클릭 액션 만들기"
date:   2020-03-19 18:31:44 +0900
tags: [utility]
subtitle : 자동 마우스 클릭(Auto Clicker)
feature-img: "assets/img/banner.jpg"
categories: utility

---

### 자동 마우스 클릭(Auto Clicker)

---

Automator 란 Mac에서 반복 작업 자동으로 수행하도록 도와주는 프로그램이다. 일련의 작업 흐름을 만들어 반복되는 작업을 자동화하여 사용자의 편의를 돕는다. 



Automator 는 다양한 용도로 활용되고 있고 사용법을 설명 해놓은 훌륭한 블로그들이 많이 있다. 여기서는 맥에서 자동 클릭 이벤트를 발생 시키는 방법으로써 소개하고자 한다. 



간단한 마우스클릭을 Automator 이용해 구성하는 법을 살펴보자.

<!-- more -->
<br>

#### 1. Mac Automation Utility 다운로드 & 설치

Automator는 mac에 기본적으로 설치되어 있어 별도의 추가 설치가 필요하지 않지만 좀더 쉽고 편리한 마우스 클릭 동작 을 구성하기 위해 Automator 내부에서 동작하는 유틸리티를 다운받는다. 아래의 링크에서 다운로드를 클릭 후 설치하자.

###### MurGaa Utility 다운로드 링크 :  [http://www.murgaa.com/auto-clicker-mac/][link01] <br/>
[link01]: http://www.murgaa.com/auto-clicker-mac/

<br>

![](/assets/images/post/200319/(1).png)

<br>

#### 2. Automator 실행하기

![](/assets/images/post/200319/(2).png)

<br>

#### 3. 빠른 동작 클릭하기

![](/assets/images/post/200319/(3).png)

<br>

#### 4. MurGaa 검색 & 드래그 하기

![](/assets/images/post/200319/(4).png)

<br>

#### 5. 설정 입력하기

![](/assets/images/post/200319/(5).png)

<br>

##### 1 : 액션 설정하기

- 오른쪽 클릭, 왼쪽클릭 등

##### 2 : 특정 커서 위치 설정하기

- 특정 위치에서 액션을 실행하기를 원한다면 해당 체크박스를 체크

##### 3 : 액션 실행할 마우스 커스 위치 로 이동 후 Command + E 누르기

- 2번의 체크 박스를 체크 후 특정 위치 이동 후 단축키 누르기 
- 해당 박스 안에 마우스 커서 좌표 표시 

##### 4 : 액션 반복 횟수 설정
##### 5 : 딜레이 설정하기 

- milliseconds 
- 1000 milliseconds = 1 seconds

<br>

#### 6. 실행하기

![](/assets/images/post/200319/(6).png) 

<br>

- 예를 들어 위같은 설정의 경우 특정 X = 923, Y = 295 좌표에 왼쪽 마우스 클릭을 1초 간격으로 2번 반복 실행

<br>

###### Apple 공식Automator 사용 설명서 :  [https://support.apple.com/ko-kr/guide/automator/welcome/mac][link02] <br/>
[link02]: https://support.apple.com/ko-kr/guide/automator/welcome/mac

<br>
# 2023 CNU SW/AI Project Fair

## 💻 Project Overview
- 클라이언트 중심 코딩테스트 플랫폼

</br>

## 👥 Group Member

- 도비들의 탈출일지

</br>

<div align="center">
  
|[Eustace](https://github.com/dlwnsrb0829)|[Hojeong Eom](https://github.com/DobiIsFree)|[heejung Kim](https://github.com/hj-k66)
|:---:|:---:|:---:|
|🐻|🦊|🐰|
|<img src="https://avatars.githubusercontent.com/u/39390618?v=4" width="105">|<img src="https://avatars.githubusercontent.com/u/52994616?v=4" width="105">|<img src="https://avatars.githubusercontent.com/u/68041758?v=4" width="105">|

</div>

</br>

## 🔍 추진 배경

- 기존 플랫폼 구조의 문제

&emsp; &emsp; 코딩 테스트 플랫폼 서버의 핵심은 제출된 프로그램을 실행하여 비교하는 **Judge Engine**이다.
기존 플랫폼의 경우, 코딩 테스트 응시자들이 작성한 코드를 Judge Engine이 탐재된 서버로 전송해 정확도를 검증하는 방식으로 동작한다. 

&emsp; &emsp; 서버는 응시자 한명을 처리 후, 다음 응시자의 코드를 처리할 수 있어 다수의 응시자가 결과를 전송할 경우, 서버 과부하 문제를 피할 수 없다. 
서버는 제출된 코드 검증을 빠르게 처리하고 응시자들에게 응답하기 위해 높은 성능이 요구되고, 이 과정에서 많은 비용을 필요로 한다.

- 악성 코드의 문제

&emsp; &emsp; 응시자가 악성 코드를 서버로 전송해 피해를 유발할 가능성도 존재하기 때문에 보안 측면에서 서버의 부담은 증가한다.

</br>

➜ 기존 **중앙처리 방식**의 코딩테스트 플랫폼에서 발생할 수 있는 문제점을 예방하기 위해 **클라이언트 중심 방식**의 플랫폼의 개발이 필요하다.

</br>


## 🖥️ 프로젝트 구조

<img width="477" alt="스크린샷 2023-05-31 오후 3 29 19" src="https://github.com/DobiIsFree/Dobby-Socks/assets/52994616/78b7a1b3-a73e-4a4c-8173-c91b9fc6f476">


</br>

## ⚙️ 개발 환경

<img width="592" alt="스크린샷 2023-05-31 오후 3 17 11" src="https://github.com/DobiIsFree/Dobby-Socks/assets/52994616/56106fa7-07a8-433b-bad0-fb980edaba29">

</br>

## 🔮 기대 효과 및 활용 방안

- 서버의 부담 감소

&emsp; &emsp; 주최측의 다양한 프로그래밍 언어 제공을 위한 비용이나 대규모의 처리 요청에 드는 비용 절감할 수 있다는 장점을 지닌다.

- 사용자 편리성 증가

&emsp; &emsp; 기존 플랫폼은 출제자 입장에서 플랫폼을 구축하기 복잡한 반면, **JOY**는 간편한 구축 환경 제공한다.

&emsp; &emsp; 응시자 또한 별도의 IDE 없이 코드를 작성할 수 있다는 편의성을 가지며, 코딩 테스트 응시자들이 주로 사용하는 VSCode의 Extension 으로 제공되므로 심리적 안정감을 느낄 수 있다.

- 악성 코드 차단

&emsp; &emsp; 코드의 컴파일 자신의 환경에서 진행되기 때문에 악성 사용자의 코드를 사전에 차단할 수 있다.

- 기존 'CCOJ'의 대체 플랫폼

&emsp; &emsp; 현재 충남대에서 사용하는 'CCOJ'를 대체할 플랫폼으로 활용할 계획이다.

</br>

## 프로젝트 구성요소

1. [VSCode Extension](https://github.com/Dobbies-Escape-Diary/JOY_Extension)
    > VSCode Extension

2. [Front-End](https://github.com/Dobbies-Escape-Diary/JOY_FE)
    > 출제자를 위한 Interface 제공

3. [Server](https://github.com/Dobbies-Escape-Diary/JOY-BE)
    > Front 요청에 따라 데이터 전달

</br>

## 발표 자료


## Demo

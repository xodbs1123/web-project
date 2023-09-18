
## 양.많.다 - 양재역 맛집 많다 ##
### 프로젝트 정보 ###
![Logo](https://github.com/Inc-Team-Project/recommend-restaurant/assets/61976898/697e72be-bf13-4082-b662-ac652facff0d)
- 신세계 I&C 클라우드 엔지니어과정 
- 기간 : 9/1 ~ 9/7
- 최종 보고서 : https://docs.google.com/presentation/d/1geOf9NnheR3d5HVOaDb9DNGMGVdVyS_A/edit?usp=drive_link&ouid=106564867001653478795&rtpof=true&sd=true

### 팀 소개 + 역할분담 ###
- 김태윤 : DB (Linux), Back-End Server
- 김희수 : DB, Flask Server, Back-End
- 곽민주 : UI/UX, Front-End, ReadME
- 이진욱 : Data Fetch


### 프로젝트 소개 ###
- 양재역 인근 맛집 공유
- 댓글 기능을 통해서 구체적으로 식당 소개 가능
- 한식, 중식, 일식, 경양식, 일식 카테고리 선택 가능



## 시작 가이드 ##

## 요구 사항 ##
- VMware CenstOS8
- MariaDB-10.4.10
  

### 개발 환경 설정 ###
다음과 같이 패치합니다.

$ git init

$ git remote add origin https://github.com/xodbs1123/yangjae-recommend-restaurant.git

$ git pull origin main

데이터를 가져온 후 다음의 명령을 사용하여 가상환경을 구성합니다.

$ python -m venv .venv

$ . .venv/Scripts/activate

$ pip install -r requirements.txt


### 기술 스택 ###

#### Environment
- github
- vscode
- vmware
- cenos8
- mariaDB
#### Development
- python
- flask
- html
- css
- js

  <img src="https://github.com/Inc-Team-Project/recommend-restaurant/assets/67572168/2c1add97-943a-4568-9031-b60cbe975f06">

### 화면 구성 ###
Figma

https://www.figma.com/file/iG98cDuqg27MagPqhCL1Id/%EC%96%91.%EB%A7%8E.%EB%8B%A4?type=design&node-id=0%3A1&mode=design&t=jLrnxURaewRqmDnm-1
  
### 주요 기능 ###
* CRUD  프로젝트
 1. 음식점 등록 / 조회
 2.  댓글 등록 / 수정/ 조회 / 삭제

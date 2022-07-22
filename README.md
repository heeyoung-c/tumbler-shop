<p align="center">
<img src="https://user-images.githubusercontent.com/83247825/180384939-0ce8e0ff-8e98-4b29-a4f3-fcf89b4d48ca.png" width="250"/>
</p>

# Tumbler Shop

### 세상에 있는 모든 텀블러를 한눈에 보고 구매할 수 있는 텀블러 쇼핑몰 🍶

# 📝 TOC

- 프로젝트 소개
  - 프로젝트 제안 배경 & 솔루션
  - 타겟층
- 배포사이트
- 목업 링크
- 개발 기간
- 팀원소개
- 주요 기능과 로직
  - 사용자
  - 은행계좌
  - 제품
- 기술스택
  - 디자인
  - 개발
  - 협업

# 🍶 프로젝트 소개

### 프로젝트 제안 배경

텀블러를 구매시 브랜드별로 살 수 있는 쇼핑몰이 달라 한눈에 비교해 구입하기가 어렵다.

### 아이디어

세상 모든 브랜드의 텀블러를 모아 판매하는 쇼핑몰을 만들면 어떨까?

### 타겟층

다양한 브랜드의 텀블러를 비교하고 싶은 텀블러가 필요한 모든 사람!

# 🌐 배포 사이트

✨ tumbler shop 쇼핑몰 바로가기: [https://tumbler-shop.netlify.app/](https://tumbler-shop.netlify.app/)

# 🖌 목업

## 목업링크

## 목업

# 📅 개발 기간

2022.06.14 - 2022.07.22 (총 39일, 약 6주)

# 🧑‍🤝‍🧑 팀원소개

| 조현아                                   | 천희영                                       | 유은혜                                   | 김채욱                                         |
| ---------------------------------------- | -------------------------------------------- | ---------------------------------------- | ---------------------------------------------- |
| [@hyeonahc](https://github.com/hyeonahc) | [@heeyoung-c](https://github.com/heeyoung-c) | [@yueunhye](https://github.com/yueunhye) | [@Kimchaewook](https://github.com/Kimchaewook) |

# 🪄 주요 기능과 로직

## 사용자

- 회원가입: 이름, 이메일, 비밀번호를 받아 사용자를 등록한다.
- 로그인/로그아웃: 이메일과 비밀번호를 입력해 사용자 정보를 불러온다.
- 내 정보 수정: 회원가입시 사용한 정보를 수정할 수 있다.

## 은행계좌

- 은행 계좌 등록/해지: 사용자가 계좌를 등록하면 300만원이 자동으로 입금된다.
- 은행 계좌 조회: 사용자가 등록한 계좌 정보(은행명, 계좌번호, 현재금액)을 조회할 수 있다.

## 제품

### 제품 관리

- 판매 제품 등록/수정/삭제: 관리자 권한을 가진 유저는 판매 제품을 등록, 수정 및 삭제 할 수 있다.
- 판매 제품 조회: 등록한 제품 정보(상품명, 상품 아이디, 가격, 재고)를 조회할 수 있다.
- 판매 내역 조회: 판매된 제품의 정보(구매자, 상품명, 주문일, 구매상태)만 따로 조회 할 수 있다.

### 제품 구매

1. 홈페이지에서 제품 조회 및 검색
2. 원하는 제품 클릭
3. 제품에 대한 상세 내용이 담긴(이미지, 제목, 가격, 설명글) 페이지로 이동
4. 구매하기 버튼을 클릭
5. 사용자가 등록한 계좌로 제품 구매 (등록된 계좌가 없을 경우 계좌 등록 페이지로 이동)

### 구매내역 조회

- 사용자가 구매한 제품의 정보를 확인하고 구매확정, 구매취소를 할 수 있다.

# ⚙️ 기술스택

## 디자인

- Adobe XD

## 개발

### 사용 언어

- Vue

### 사용 라이브러리

- vue-router
- sass
- webpack
- eslint
- day.js

### 상태관리 라이브러리

- vuex

## 협업

### 이슈 관리

- Github Issue

### 문서화

- Notion

### 커뮤니케이션

- Slack
- Zepp

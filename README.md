# 😻 "호두(HODU)" 랜딩 페이지 구현 프로젝트
귀여운 고양이 호두를 소개하는 랜딩 페이지 입니다.
## 📌 프로젝트 소개
* 고양이 호두의 다양한 사진을 볼 수 있습니다.
* 메일 주소를 입력하여 블로그 게시물을 구독할 수 있습니다.
## ✅ 프로젝트 목표
* HTML과 CSS 구조 이해하기
* 적절한 시맨틱 태그 사용하기
* 웹 접근성과 SEO 최적화 하기
* 미디어 쿼리를 이용한 반응형 웹 구현하기
## 🔗 배포 주소
* https://gyeone.github.io/EST-landing/
## ⭐ 주요 구현 사항
### ✒️ 시맨틱 마크업
* 페이지 구조 분석 및 적절한 시멘틱 태그를 선정했습니다. (header, main, section, footer 등)
### 🖥️ 반응형 웹
* 데스크톱 퍼스트 접근 방식을 선택했습니다.
* 브레이크 포인트를 설정해서 데스크톱 버전과 모바일 버전에 따른 반응형 웹을 구현했습니다.
### 🔊 접근성
* 접근성을 고려한 태그를 사용하고, 적절한 대체 텍스트를 제공했습니다.
* 키보드 접근성을 확인했습니다.
### 🔎 SEO
* <title> 태그를 사용해서 검색 엔진에 페이지의 주제가 무엇인지 알려주었습니다.
* 대표 url 설정, 메타 태그 이용, 제목 태그(h1 ~ h6)를 사용하여 검색엔진 최적화에 도움을 주었습니다.
### 🔡 네이밍 방법론
*  BEM 방법론 (Block, Element, Modifier)을 사용했습니다.
## 🔧 기술 스택
  <img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white"> <img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white"> 
## 📅 개발 기간
 * 2025-06-18 ~ 2025-06-23
## 📂 프로젝트 구조
 ```
 ┣ 📜index.html
 ┣ 📂css
 ┃ ┣ 📜font.css
 ┃ ┣ 📜mobile.css
 ┃ ┣ 📜reset.css
 ┃ ┗ 📜style.css
 ┣ 📂images
 ┃ ┣ 📜.DS_Store
 ┃ ┣ 📜arrow-left.svg
 ┃ ┣ 📜arrow-right.svg
 ┃ ┣ 📜blog.svg
 ┃ ┣ 📜box-cat.png
 ┃ ┣ 📜cat-subscribe.png
 ┃ ┣ 📜facebook.svg
 ┃ ┣ 📜img_1.jpg
 ┃ ┣ 📜img_2.jpg
 ┃ ┣ 📜img_3.jpg
 ┃ ┣ 📜img_4.png
 ┃ ┣ 📜img_5.png
 ┃ ┣ 📜img_5_pc.png
 ┃ ┣ 📜instagram.svg
 ┃ ┣ 📜logo.png
 ┃ ┣ 📜logo.svg
 ┃ ┣ 📜mail.svg
 ┃ ┣ 📜menu.svg
 ┃ ┣ 📜modal-bg-img.png
 ┃ ┣ 📜top-btn.svg
 ┃ ┗ 📜youtube.svg
 ┗ 📜README.md
```
### 📂 css 폴더 구조 설명
파일명 | 파일 설명
--- | --- |
font.css | 웹 폰트가 담긴 곳입니다. |
mobile.css | 모바일용 스타일이 담긴 곳입니다. |
reset.css | User Agent Stylesheet를 리셋해주는 파일입니다. <br> 에릭 마이어의 reset css를 사용하여 모든 요소의 마진, 패딩을 0으로 만들고, 기본 서식을 제거해 주었습니다.|
style.css | PC 스타일 위주로 담겨 있으며, 모바일용 스타일을 제외한 모든 스타일이 포함된 곳입니다. |
## 📖 구현 화면
 __📍 브레이크 포인트 기준: 가로 너비 기반 미디어 쿼리 767px__
### 🖥️ 데스크톱 버전
 * __화면 너비가 768px 이상일 때 보여질 화면입니다.__   
![image](https://github.com/user-attachments/assets/68177934-7702-4f22-80df-3c5fe845a32a)
### 📱 모바일 버전
 * __화면 너비가 767px 이하일 때 보여질 화면입니다.__   
![image](https://github.com/user-attachments/assets/236031e6-717b-4db1-bf16-484bee06a953)
### 📤 오픈 그래프 프로토콜 구현
* __카카오톡 링크 공유 화면__   
![image](https://github.com/user-attachments/assets/fd9d2fa3-09ff-4e3b-bdce-14a2d4a88301)
## 👨‍💻 개발자
  __백기연__
## 어려웠던 부분과 해결 방안
### 레이아웃 여백 맞추기
개발자 도구를 이용해 하나하나 찾아보며 맞춰나갔다.



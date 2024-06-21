# 쿠버네티스 환경의 커머스 프로그램 구축
## 시작일자: 2024년 06월 15일
## 목적
클라우드 환경에 서비스를 구축하고, 서비스를 하는 것이 점차 개발지의 기본소양이 되어가는 시대이다.  
이제는 단위개발자이기 보다는 아키텍처를 설계하고, 그러한 환경에서의 프로그램의 퍼포먼스를 어떻게 테스트해야하는지를 알고자 먼저 프로그램을 설계하고 운영해보는 게 중요하다고 판단하였다.  
회사에 들어가는 것은 운영시스템을 파악하고 효율을 위함이다.
## ⌨ 각 서비스별 TODO List작성
- [x] 쿠버네티스 환경에서 같은 포트를 쓰되, 인그레스 설정으로 분기
- [x] Redis및 스테이트풀을 설정하여, 데이터가 휘발방지
- [ ] 웹서버 분리하기
### 화면 - Vue.js // 스프린트 단위: 1w
- [x] 프로젝트및 레파지토리 구축
- [x] 회원 / 상품 / 게시판 별 화면 올리기
- [x] Dockerfile구성 후 쿠버네티스 배포완료
### 게시판 - Spring boot // 스프린트 단위: 1w
- [x] 프로젝트및 레파지토리 구축
- [x] 게시판 엔티티 설계 및 구현
- [ ] 서비스 설정 및 레파지토리 구현
### 회원 - Nest.js // 스프린트 단위: 1w
- [x] 프로젝트및 레파지토리 구축
- [ ] 회원 엔티티 설계 및 구현
### 상품 - FASTAPI // 스프린트 단위: 1w
- [x] 프로젝트및 레파지토리 구축
- [ ] 상품 엔티티 설계 및 구현
---
### 지연사항발생

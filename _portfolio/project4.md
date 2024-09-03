---
title: 악성메일 훈련 시스템(WMTS)
subtitle: java 프로젝트
image: assets/img/portfolio/WMTS.png
alt: 

caption:
  title: 악성메일 훈련 시스템(WMTS)
  subtitle: java 프로젝트
  thumbnail: assets/img/portfolio/WMTS.png
---

java, jdbc, mysql, tomcat, html, css, javascript, jquery, spring boot, spring security, jpa, thymeleaf 기술을 사용하여 악성메일 훈련 시스템 개발.
<br>

기능 : 로그인 기능, 조직 등록 기능(회사, 부서, 팀, 회원 등 CSV 파일을 이용한 등록 기능 및 수동 추가 기능), 신고 관리 기능(훈련 메일 수신시 자동으로 신고 담당자에게 신고 메일 전송 기능),
개인 정보 수정 기능, 훈련 메일 전송 테스트 기능, 훈련 시나리오 생성 및 수정 관리 기능, 훈련 등록 기능, 훈련 상태 조회 기능, 메일 서버 설정 기능, 훈련 결과 요약 기능, 훈련 보고서 자동으로 출력 기능 등 보유"


<B>#구현 설명</B><br>Spring boot 프로젝트 기반으로 gradle을 통해 개발함.
spring security를 통해 로그인 기능을 보안하고, 악성메일 훈련이 가능한 플랫폼으로 개발, CentOS 7.0 기반 jar파일을 임베디드 톰캣을 통해 구동함.
리눅스 sendmail을 통하여 메일서버를 설치하고, 설치한 메일 서버를 통하여 메일 발송 기능을 추가하여 메일 서버와 악성 메일 솔루션 시스템을 함께 구현하였음.



<B>#프론트 엔드</B><br>
그외에 기본적인 프론트엔드는 Thymeleaf로 구현. 대부분의 기능은 Thymeleaf가 가지고 있는 기능으로 spring security 권한을 통한 웹페이지 접근제어 구현


<B>#백엔드</B><br>
Spring boot 어노테이션을 통한 ModelAndView 구조를 작성, JPA의 domain을 통한 DTO관리 및 구조 관리
백엔드의 중요기능 암호화로 외부에서 훈련 데이터를 무작위 대입으로 서버 URL로 접근할수 없게 데이터 접근에 대한 추측성 개입을 차단. 


<B>#데이터베이스</B><br>
JPA를 통한 domain을 백앤드와 통합하여 조금더 체계적인 테이블 관리 및 MySQL을 통한 연계 가능



{:.list-inline}

- Date: 2024-04
- Category: java 프로젝트



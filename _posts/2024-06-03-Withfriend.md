---
layout: post
title: Withfriend
date: 2024-06-03
categories:
  - portpolio
tags:
  - 회고
  - portpolio
  - project
  - springboot
  - 중고거래
---
페이지가 완성될 때까지 주석처리
<!-- 
## 목차
- [개요](#개요)
- [아키텍처](#아키텍처)
	- [서비스 아키텍처](#서비스-아키텍처)
	- [DB 아키텍처](#db-아키텍처)
- [코드 뜯어보기](#코드-뜯어보기)
	- [WithfriendApplication](#WithfriendApplication)
	- [build.gradle](#build.gradle)
- [github링크](https://github.com/Jiggy97/withfriend)

---
<details id="개요">
<summary>
<h2 style="display:inline">개요</h2>
</summary>
<div markdown="1"> 
- 혼자 힘으로 기획부터 개발까지 전부 설계하고 개발하기 위해 
	- 프로젝트 사이클 이해도 향상 
	- 개발 능력 향상 
		- 코드 한 줄, 한 줄 명분과 이해를 바탕으로 작성 
	  - 문제해결 능력 향상 
- 기획 의도 
	- 중고거래의 단점 중 하나인 익명성 해소 
		- SNS를 활용해 친구와 즐기는 중고거래 서비스 개발 
- 주요 기능 
	- OAuth 2.0 기반 로그인 서비스 
	- 사용자 간 중고거래
</div>
</details>
[목차로 돌아가기](#목차)

---
<details id="아키텍처">
<summary>
<h2 style="display:inline">아키텍처</h2>
</summary>
<details id="서비스-아키텍처">
<summary>
<h4 style="display:inline">서비스 아키텍처</h4>
</summary>
<div markdown="1">
- 제목 1
	- 내용 1.1
	- 내용 1.2
- 제목 2
	- 내용 2.1
	- 내용 2.2
</div>
</details>
<details id="db-아키텍처">
<summary>
<h4 style="display:inline">DB 아키텍처</h4>
</summary>
<div markdown="1">
- 제목 1
	- 내용 1.1
	- 내용 1.2
- 제목 2
	- 내용 2.1
	- 내용 2.2
</div>
</details>
</details>
[목차로 돌아가기](#목차)

---
<details id="코드-뜯어보기">
<summary>
<h2 style="display:inline">코드 뜯어보기</h2>
</summary>
<details id="WithfriendApplication">
<summary>
<h4 style="display:inline">WithfriendApplication</h4>
</summary>
<div markdown="1">
- WithfriendApplication 클래스
	- Spring Boot 애플리케이션의 시작점 제공
		- 'main' 메서드 포함 → Java 애플리케이션의 표준 진입점
		- 'mian' 메서드는 애플리케이션을 시작하며 필요한 모든 초기화 작업을 수행
	- 애플리케이션 컨텍스트 부트스트랩(Application Context Bootstrap) 수행
		- 애플리케이션 컨텍스트 : 매니페스트(maifests)가 적용된 최상위 탐색 컨텍스트
			- 매니페스트(maifests)
				- 애플리케이션의 중요한 정보를 담고 있는 설정 파일
				- 애플리케이션의 이름, 아이콘, 버전, 필요 권한 등 다양한 설정 포함
				- 자바기반 스프링 부트의 경우 JAR 파일의 메타데이터 포함
					- ex) Main-Class 정보
			- 최상위 탐색 컨텍스트
				- 애플리케이션을 열면 가장 먼저 보이는 화면이나 메뉴
				- 사용자가 가장 처음 보거나 접근하게 되는 최상위 화면이나 메뉴
		- (스프링부트에서)부트스트랩 : 애플리케이션이 시작될 때 필요한 초기 설정 및 준비 작업 수행
		- 즉, 애플리케이션 컨텍스트 부트스트랩(Application Context Bootstrap) 수행의 이미는 애플리케이션 컨텍스트(매니페스트를 적용한 최상위 컨텍스트)를 부트스트랩(초기 설정 준비 작업 수행)한다를 뜻함
		- Spring 컨테이너가 생성, 각종 설정 파일과 빈(Bean) 로드, 애플리케이션 실행 준비
	- 자동 설정 활성화
- 제목 2
	- 내용 2.1
	- 내용 2.2
</div>
</details>
<details id="build.gradle">
<summary>
<h4 style="display:inline">build.gradle</h4>
</summary>
<div markdown="1">
- 제목 1
	- 내용 1.1
	- 내용 1.2
- 제목 2
	- 내용 2.1
	- 내용 2.2
</div>
</details>
</details>
<<<<<<< HEAD
[목차로 돌아가기](#목차)
-->
=======
[목차로 돌아가기](#목차)
>>>>>>> 392d12642201a4dc8a40d99169a68dcfd0e5a376

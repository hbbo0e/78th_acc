# 프로젝트 정보


## 회계 시스템 운영 서비스 구현
> 개발 기간 : 2024.03 ~ 2024.05 <br/>
> 개발 인원 : FE, BE 총 2명
<br/>

## 시작 가이드

- node : 16.16.0
- react : 18.2.0
- spring boot : 2.7.0
- typescript : 4.9.4

```
npm install
npm run dev
```


## 개발 도구 및 환경

### Development
<img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white"> <img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"> <img src="https://img.shields.io/badge/oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white"> 
<img src="https://img.shields.io/badge/hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white"> 
<img src="https://img.shields.io/badge/typescript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"> 
<img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black"> 
<img src="https://img.shields.io/badge/redux-764ABC?style=for-the-badge&logo=redux&logoColor=white"> 
<img src="https://img.shields.io/badge/reduxsaga-999999?style=for-the-badge&logo=reduxsaga&logoColor=white"> 


### Config
<img src="https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white"> 

### Communication
<img src="https://img.shields.io/badge/jira-0052CC?style=for-the-badge&logo=jira&logoColor=white"> <img src="https://img.shields.io/badge/confluence-172B4D?style=for-the-badge&logo=confluence&logoColor=white">
<img src="https://img.shields.io/badge/slack-4A154B?style=for-the-badge&logo=slack&logoColor=white"> 

<br/>

## 공통 상세 업무

1. 상태 관리 최적화
	- **Redux**를 사용하여 애플리케이션의 전역 상태 관리
	- **Redux-Saga**를 활용하여 비동기 작업 및 부수 효과 처리

2. API 통신 및 데이터 바인딩
	- Redux-Saga와 Axios를 사용해해 백엔드 API와 통신하여 데이터를 가져옴
	- React의 컴포넌트 시스템과 Redux의 상태 관리를 활용하여 UI에 데이터 바인딩

3. 출력 기능 구현
	- ReactToPrint 가 제공하는 라이브러리의 useReactToPrint 훅을 사용하여 React 컴포넌트의 출력 기능 구현

5. UI 설계 및 구현
    - 결산 후 조회 및 취소 인터페이스 구현
    - 데이터 상태 관리 및 실시간 업데이트 기능 구현

5. 데이터베이스 연동 및 비즈니스 로직 API 개발
   - Spring Boot를 사용하여 종합적인 데이터 관리 API 개발
   - ORACLE 데이터베이스와 연동하여 데이터 조회, 처리 및 관리 기능 구현
   - 회계 기수 데이터 처리 등 특정 비즈니스 도메인에 특화된 로직 개발
  
<br/>

## 화면 구성 및 API 

<br/>

|메인 페이지|
|:----:|
| ![image](https://github.com/user-attachments/assets/902e33db-d7a8-499c-b136-414d710bdfc2) |
|전표/장부관리 - 일반 전표 페이지|
| ![image](https://github.com/user-attachments/assets/14d1d456-35ca-410a-86c1-ddbebc5d999f) |
|전표/장부관리 - 전표 승인 및 취소 페이지|
| ![image](https://github.com/user-attachments/assets/ff13c2f1-ab9a-4733-85c0-358b4ae31070) |
|기초정보관리 - 계정과목 관리 페이지|
| ![image](https://github.com/user-attachments/assets/28d46f87-2b5b-445c-9101-a4e4f19f1109) |
|자금관리 - 일자별자금계획입력 페이지 - 자금계획입력탭|
| ![image](https://github.com/user-attachments/assets/bf533bc2-6516-4d0d-893c-4b0fa5104ef0) |
|자금관리 - 일자별자금계획입력 페이지 - 자금계획상세보기 탭|
| ![image](https://github.com/user-attachments/assets/2ee0c0a2-eb50-456f-91f2-7968a2b7cadf)
![image](https://github.com/user-attachments/assets/56b73c1d-995b-4d61-962e-ce9c708ad248) |
|자금관리 - 받을 어음 명세서 페이지|
|![image](https://github.com/user-attachments/assets/abebea86-5bab-4813-aeca-b2a1617a69f3)
![image](https://github.com/user-attachments/assets/71348d67-be5d-4a04-bf66-216ba717aa17)|
|자금관리 - 지급 어음 명세서 페이지|
|![image](https://github.com/user-attachments/assets/a20976c3-c9fd-463b-a613-f92196e75710)
![image](https://github.com/user-attachments/assets/31d3bda9-e176-47b6-9842-dce45ca5a701)|
|자금관리 - 일일자금/분개현황 페이지 - 일일거래증감현황 탭|
|![image](https://github.com/user-attachments/assets/f2f0d55e-7e02-4057-8db5-e8756f706f91)|
|자금관리 - 일일자금/분개현황 페이지 - 입출금예정액|
|![image](https://github.com/user-attachments/assets/09424f43-797d-438d-a16e-d4eadf50c782)|
|자금관리 - 일일자금/분개현황 페이지 - 예적금현황|
|![image](https://github.com/user-attachments/assets/0d8f677e-f147-4487-a10a-3fea6e93e66f)|
|자금관리 - 일일자금/분개현황 페이지 - 자금현황|
|![image](https://github.com/user-attachments/assets/dd31a1cf-7642-4191-81c6-e9258c93f3a0)|


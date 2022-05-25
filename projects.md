---
layout: page
title: Projects
subtitle: 진행한 프로젝트들
---
***  

# 진행한 프로젝트 목록

- [Mini Project - 마왕 김진호를 JAVA](miniproject.md)
- [Semi Project - BYAT(Better-than-Your-Agile-Tool)](semiproject.md)
- [Final Project - JaeGoJaeGo](finalproject.md)

***




# 밑으로 지울 것임


## final

- **프로젝트 이름** : JaeGoJaeGo  

- **프로젝트 진행기간** : 2022.03.15 ~ 2022.05.16

- **프로젝트 소개** : 카페 프렌차이즈를 대상으로 한 카페 재고 및 운영관리 플랫폼

- **개발 환경**
  - Java
  - Spring Data-JPA 
  - Oracle
  - intellij 
  - HTML5
  - CSS3 
  - JavaScript 
  - jQuery 
  - BootStrap 
  - Sourcetree
  - DBeaver
  - GitLab 
  - Mabatis
  - JPA
  <img src="../img/finalTools.png">
  <img src="../img/finalTools2.png">  

<br/>

- **맡은 역할** : 형상관리자 (깃랩, 소스트리 commit & push, merge, commitMessage 관리)
  <img src="../img/finalRole1.png">
  <img src="../img/finalRole2.png">  

<br/>

- **팀원 한마디** : '적극적이며 행동력 있는 팀원'

  <img src="../img/finalProjectTeamIntroduce.png">  

<br/>

- **전반적인 설계 과정**
  <br/>
  <img src="../img/finalModeling1.png">
  => **논리모델링 1.0.0ver ~ 2.0.0ver까지 설계하였습니다.**  
 <br/>
  <img src="../img/finalModeling2.png">  
  => **논리모델링 2.0.0ver 입니다.**
 <br/>
  <img src="../img/finalairbnbphoto.jpg">
  <img src="../img/finalairbnbphoto3.jpg">
  => **밤을 새며 발표를 준비하는 모습입니다.**
 <br/>
  <img src="../img/finalairbnbphoto2.jpg">
  => **논리모델링 설계 회의 장면입니다.**

<br/>

- **프로그램 내 구현 기능** 
  - **메뉴관리**  : 본사는 **메뉴 생성, 수정, 삭제, 상세조회** 등을 이용할 수 있고, 가맹점은 **본사가 등록한 완제품 메뉴와 그 내부의 원재료를 조회한 뒤 발주를 넣는 목적**입니다.
    - **메뉴 생성** 
    - **메뉴 상세보기** 
    - **메뉴 수정** 
    - **메뉴 삭제**  
   
  - **백로그 관리** : 본사가 **입고와 이슈출고에 대한 종합적인 데이터를 그래프와 표를 통해 명시적으로 한눈에 파악**할 수 있게 하는 목적이 있습니다.
    - **본사 입고물품 백로그 조회** 
    - **본사 이슈출고 백로그 조회** 
    - **각 물품 구매량 증/감소율 그래프 조회** 
    - **물품당 이슈발생빈도 그래프 조회**
   
     
     
  <br/>
  
- **구체적인 코드 설명[2가지]**
##### finalproject  
  [Final Project 코드설명](finalprojectcode.md)    
  
  
  <br/>
  
- **프로젝트 후기**
  : 저희는 SCM이라는 낯선 개념을 공부했음에도 불구하고 논리 모델링에서 엔티티 구성에 어려움을 겪고 입고와 출고, 발주 등 **용어 일치의 혼선**이 있었습니다. 
    또한 최초로 형상관리자를 맡았기 때문에 commit&push 와 merge 시 **에러해결에 어려움**을 겪었습니다.  
    이를 해결하기 위해서 **팀원들끼리 SCM에 대해 공부하여 토론을 통해 SCM에 대해 한층 더 높은 이해**를 할 수 있었습니다.  
    그리고 다양한 수발주 프로그램을 찾고 비교하여 필요한 기능을 간추려서 엔티티를 효율적으로 구상할 수 있었습니다. 또한 용어혼선을 방지하기 위해 팀원들끼리 **‘용어정리집’을     작성**하였습니다.  
    또한 **스스로 소스트리를 건들여보며 다양한 상황에 대해 테스트**를 하였고 **전 형상관리자를 맡은 분들께 조언을 구하는 등의 노력**을 하였습니다. <br/>이로 인해 **모든 팀원들이 SCM에 대한 일치된 이해**를 하였고 이를 바탕으로 좀 더 효율적인 엔티티를 구성하여 구현에 도움이 되었습니다.  
      그리고 용어에 혼선이 있을 때마다 **정리     집을 참고 및 작성**하여 더 이상의 혼선 없이 원활한 진행이 가능하였습니다.  
      또한 구현기간 중 소스트리 에러를 만날 때마다 30분 내로 해결을 할 수 있었습니다.  
      저는 이번 프로젝트를 통해 **2가지**를 얻었습니다.<br/>**첫번째 설계가 얼마나 중요한지 알게 되었습니다.** 개발자라는 직업이 코드를 잘 작성하면 된다고 생각했지만 설계에 대한 전반적인 이해가 바탕이 되어야 코드를 효율적이고 빠르     게 작성할 수 있다는 걸 깨닫는 귀중한 시간이었습니다.  
      **두번째로 맡은 역할에 책임감을 가질 수 있게 되었습니다.** 이번 경험을 바탕으로 진행중인 프로젝트와 역할에 대해 공부하고 이해하는 습관을 들이고, 한번 더 생각하는 개발자가 될 수 있도록 노력하려고 합니다.
    
[목록으로](#projects)  

------------------

---
layout: page
title: Projects
subtitle: 진행한 프로젝트들
---

# Projects

- [Mini Project](#mini)
- [Semi Project](#semi)
- [Final Project](#final)

***
## mini
- **프로젝트 이름**: 마왕 김진호를 JAVA
- 


















***
## semi

- **프로젝트 이름** : BYAT(Better-than-Your-Agile-Tool)  

- **프로젝트 진행기간** : 

- **프로젝트 소개** : IT중소기업을 대상으로 프로세스를 관리해주는 PMS 서비스 프로그램

- **개발 환경**
  - Java : OS에 독립적이며 프로그램 실행 시 필수적인 시점에만 로딩하여 불필요한 메모리 낭비가 없어 효율적이기 때문에 사용하였습니다.
  - Oracle : BYAT는 대량의 정보관리가 필요하기 때문에 대규모 DB를 지원하고 MYSSQL, MYSQL보다 좋은 성능을 보여주는 오라클을 사용하였습니다.
  - Sts :
  - HTML5 : 파일 용량이 작아 클라이언트-서버 간 빠른 문서 전달이 가능하기 때문에 사용하였습니다.
  - CSS3 : 웹 사이트의 스타일을 일관성 있게 유지하고 추가적인 SW,플러그인 없이 HTML5 기능의 확장이 가능하기 때문에 시너지를 내기 위해 사용하였습니다.
  - JavaScript : 다른 프로그래밍 언어와 완벽하게 호환이 가능하기 때문에 HTML5, CSS3 함께 시너지를 내기 위해 사용하였습니다.
  - Sourcetree : git을 사용자가 쉽게 사용할 수 있도록 GUI환경을 제공해주기 때문에 사용하였습니다.
  - DBeaver
  - GitLab : 용량 무제한의 무료 레퍼지토리를 개인 및 공용으로 제공해주어 대량의 정보관리가 필요한 BYAT에 적합하다고 생각하여 사용하였습니다.
<img src="../img/semiTools.png">

- **맡은 역할** : PM (회의록, 개발진행사항, 개발업무일지 등을 관리)

* 개발업무일지 : 일일업무일지로 본인이 구현한 부분, 내용을 구체적으로 작성하여 '본인 진척율 파악'하고 내용에 대한 '팀원 확인' 등을 통해 프로젝트의 전체적인 진척율 관리에 도움이 될 수 있도록 하였습니다.
* 개발진행사항 : 팀 전체의 진척율을 작성하고 하루하루 업데이트를 진행하여 가시적으로 전체적인 프로젝트 진행율을 파악하고 계획을 수정하는 데 도움이 되도록 하였습니다.

<img src="../img/SemiMeetingLog.png">

<img src="../img/SemiProgress.png">

<img src="../img/semiIssueTracking.png">

- **팀원 한마디** : '적극적이며 의사소통이 활발한 팀원'

<img src="../img/semiProjectTeamIntroduce.png">

- **프로그램 내 구현 기능** 
  - **로그인**  : 일반 멤버,관리자 등 사용자가 로그인 할 수 있도록 하는 목적을 가진 기능 
  - **로그아웃** : 일반 멤버, 관리자 등 사용자가 로그아웃 할 수 있도록 하는  목적을 가진 기능
  - **비밀번호 찾기** : 일반 멤버가 비밀번호를 잊어버렸을 경우 비밀번호를 찾고 변경할 수 있도록 하는  목적을 가진 기능
  - **최초 로그인 시 정보 등록** : 최초 로그인 시 사용자의 정보를 강제로 등록할 수 있도록 하는  목적을 가진 기능 
  - **멤버 계정 관리** :  관리자가 멤버 계정 추가 , 수정, 삭제 할 수 있도록 하는  목적을 가진 기능
  - **캘린더** : 일반 멤버, 관리자 등 사용자가 일정을 조회, 생성, 수정, 삭제 할 수 있도록 하는 목적을 가진 기능


- **구체적인 코드 설명[3가지]**

  1) **비밀번호 찾기 - 이메일 인증번호 발송**

  **[전체적인 흐름]**

<img src="../img/semiProjectFindPassword1.png">

  **[코드 흐름]**

<img src="../img/semiProjectFindPassword2.png">

<img src="../img/semiProjectFindPassword3.png">

  **[ GitHub Gist ]**
<script src="https://gist.github.com/leesohyeon96/e146794f17d53f544a2738c1259824de.js"></script>
<script src="https://gist.github.com/leesohyeon96/fbbd8defccd8ff27710502454972ea74.js"></script>
<script src="https://gist.github.com/leesohyeon96/d2043d067fd4e16eb4960edcc86cb3f3.js"></script>
<script src="https://gist.github.com/leesohyeon96/7856326263d5235e19a57f5c3b17a26c.js"></script>
    
------------------

  2) **캘린더 - 일정 생성**

  **[전체적인 흐름]**

<img src="../img/semiProjectCalendarRegist1.png">

  **[코드 흐름]**

<img src="../img/semiProjectCalendarRegist2.png">
<img src="../img/semiProjectCalendarRegist3.png">
<img src="../img/semiProjectCalendarRegist4.png">

  **[ GitHub Gist ]**
<script src="https://gist.github.com/leesohyeon96/30def6811a4c5e3d934e89cb566feec8.js"></script>
<script src="https://gist.github.com/leesohyeon96/a4692aa12788471a45315f018609dc29.js"></script>
<script src="https://gist.github.com/leesohyeon96/69982cc198519ed802f0d917868b0d1f.js"></script>
<script src="https://gist.github.com/leesohyeon96/05b1abc08e9a7c8a8f464c1c25d1ea84.js"></script>
    
------------------

  3) **멤버 계정 관리 - 생성**

  **[전체적인 흐름]**

<img src="../img/semiProjectManagementRegist1.png">

  **[코드 흐름]**

<img src="../img/semiProjectManagementRegist2.png">

<img src="../img/semiProjectManagementRegist4.png">

  **[ GitHub Gist ]**
<script src="https://gist.github.com/leesohyeon96/66b37abedfccb7581f878ef08c05cdb7.js"></script>
<script src="https://gist.github.com/leesohyeon96/31800c1f677e4684a15688d24c9fa619.js"></script>
<script src="https://gist.github.com/leesohyeon96/d01d0c4f6875d14229625025f657a7e2.js"></script>
<script src="https://gist.github.com/leesohyeon96/d0b1cede398b946a24dd3e6b0cf1b32e.js"></script>









***
## final

- **프로젝트 이름** : JaeGoJaeGo  

- **프로젝트 진행기간** : 2022.03.15 ~ 2022.05.16

- **프로젝트 소개** : 카페 프렌차이즈를 대상으로 한 카페 재고 및 운영관리 플랫폼

- **개발 환경**
  - Java : 객체 지향 언어이며 운영체제(OS)에 독립적이며 JVM을 통해 자바 바이너리로 컴파일해 사용하여 어느 플랫폼에서나 동일한 형태로 실행이 가능하기 때문에 사용하였습니다.
  - Spring Data-JPA : SQL문이 아닌 Java 메소드를 통해 DB를 조작할 수 있고, 개발자는 객체 모델을 이용하여 비즈니스 로직을 구성할 수 있습니다. 또한 특정 DBMS의 방언을 신경쓰지 않고 작성할 수 있기 때문에 사용하였습니다. 
  - Oracle : JaeGoJaeGo는 대량의 정보관리가 필요하기 때문에 대규모 DB를 지원하고 MYSSQL, MYSQL보다 좋은 성능을 보여주는 오라클을 사용하였습니다. 또한 Oracle의 특정 방언을 이용하여 DML, DCL, DDL 구문을 작성하여 DBMS를 관리할 수 있기 때문에 사용하였습니다.
  - intellij : 직관적이고 예쁜 UI를 제공하며, 우수한 스마트 코드 작성 기능들 덕분에 짧은 구현 기간에 높은 코드 생산성을 제공해주는 인텔리제이를 사용하였습니다.
  - HTML5 : 컴파일 되지 않은 텍스트 문서로 편집이 용이하며, 단순한 구조로 논리적이고 연산적인 요소가 없기 때문에 사용하였습니다.
  - CSS3 : 웹 사이트의 스타일을 일관성 있게 유지하고 추가적인 SW,플러그인 없이 HTML5 기능의 확장이 가능하기 때문에 시너지를 내기 위해 사용하였고 나아가 HTML에서 지원하지 않는 다양한 기능이 사용가능하기 때문에 보완적인 측면에서 좋다고 생각하여 사용하였습니다.
  - JavaScript : 다른 프로그래밍 언어와 완벽하게 호환이 가능하기 때문에 HTML5, CSS3 함께 시너지를 내기 위해 사용하였습니다.
  - jQuery : 자바스크립트를 쉽게 활용할 수 있도록 도와주며, 비동기 처리를 위한 AJAX 활용하기 위해 이용하였습니다.
  - BootStrap : 공동작업을 위해 디자인을 통일하고, 부트스트랩에서 제공하는 여러 기능들 활용하기 위함과 간결한 코드를 유지하기 위해 이용하였습니다.
  - Sourcetree : git을 사용자가 쉽게 사용할 수 있도록 GUI환경을 제공해주며 깃플로우 방식을 사용하기에 용이하기 때문에 이용하였습니다.
  - DBeaver: 편의성을 고려한 직관적인 인터페이스를 가지고 Semi Project에서 사용한 Oracle Developer 보다 뛰어난 쿼리 실행 속도를 가지고 있기 때문에 사용하였습니다.
  - GitLab : 용량 무제한의 무료 레퍼지토리를 개인 및 공용으로 제공해주어 대량의 정보관리가 필요한 JaeGoJaeGo에 적합하다고 생각하여 사용하였습니다.
<img src="../img/finalTools.png">
<img src="../img/finalTools2.png">  


- **맡은 역할** : 형상관리자 (깃랩, 소스트리 commit & push, merge, commitMessage 관리)
<img src="../img/finalRole1.png">
<img src="../img/finalRole2.png">  


- **팀원 한마디** : '적극적이며 행동력 있는 팀원'

<img src="../img/finalProjectTeamIntroduce.png">  


- **전반적인 설계 과정**
<img src="../img/finalModeling1.png">
<img src="../img/finalModeling2.png">  


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
   
     
     
  
  
- **구체적인 코드 설명[2가지]**

  1) **메뉴관리 - 메뉴 수정**

  **[전체적인 흐름]**

<img src="../img/finalProjectMenuModify1.png">
<img src="../img/finalProjectMenuModify2.png">

  **[코드 흐름]**

<img src="../img/finalProjectMenuModify3.png">

<img src="../img/finalProjectMenuModify4.png">

<img src="../img/finalProjectMenuModify5.png">

<img src="../img/finalProjectMenuModify6.png">

<img src="../img/finalProjectMenuModify7.png">

  **[ GitHub Gist ]**
<script src="https://gist.github.com/leesohyeon96/9a17a79f2b4be540b148b280927c8c6e.js"></script>
<script src="https://gist.github.com/leesohyeon96/8fba37588e778194fe93ca2f312dfec9.js"></script>
<script src="https://gist.github.com/leesohyeon96/c44e3a32a51079eeddb7f513ce8521e7.js"></script>
    
------------------

  2) **백로그관리 - 물품당 이슈발생빈도 그래프 조회**

  **[전체적인 흐름]**

<img src="../img/finalProjectOutWarehouseIssueBacklogBarGraph.png">
<img src="../img/finalProjectOutWarehouseIssueBacklogBarGraph2.png">

  **[코드 흐름]**

<img src="../img/finalProjectOutWarehouseIssueBacklogBarGraph3.png">

<img src="../img/finalProjectOutWarehouseIssueBacklogBarGraph4.png">

<img src="../img/finalProjectOutWarehouseIssueBacklogBarGraph5.png">

<img src="../img/finalProjectOutWarehouseIssueBacklogBarGraph6.png">

<img src="../img/finalProjectOutWarehouseIssueBacklogBarGraph7.png">

<img src="../img/finalProjectOutWarehouseIssueBacklogBarGraph8.png">

  **[ GitHub Gist ]**
<script src="https://gist.github.com/leesohyeon96/e146794f17d53f544a2738c1259824de.js"></script>

    
------------------

# 첫단추💰

![logo](image/logo.gif)

> 우리 아이의 경제 교육 **첫 단추**를 꿰어줍니다.  
> 가정에서의 경제 조기 교육을 통해 성인이 되어서 경험할 경제 활동을 이론이 아닌 실제 활동으로 쉽고 재밌게 체험해 볼 수 있습니다.

<br>

## 서비스 주요 기능

- **공통**
    - **회원 가입**
    - **온보딩**
- **부모**
    - **아이 정보 관리 -** 자녀들의 직업과 할 일을 관리
    - **환전/결제 요청 관리 -** 자녀들의 환전 요청을 관리하며 환전 내역을 확인 가능
    - **투자 활동 관리** **-** 자녀의 주식투자를 관리. 주식 종목 설정과 매일 주가 설정 가능
    - **내 정보**
- **자녀**
    - **직업** - 가정에서의 직업, 매일 할 일을 체크하며 보상을 받을 수 있음
    - **예금, 적금**
    - **주식 투자**
    - **경제 공부** - 경제 개념들을 아이의 눈높이에 맞게 공부할 수 있음

<br>

## Simulation

### Landing

<!-- ![image](image/simulation/랜딩페이지.gif) -->

<img src = "image/simulation/랜딩페이지.gif" width=" 200px">

### Sign In

<!-- ![image](image/simulation/부모_회원가입.gif) -->
<!-- ![image](image/simulation/자녀_회원가입.gif) -->
<div class = "sing-in">
    <img src = "image/simulation/부모_회원가입.gif" width=" 200px">
    <img src = "image/simulation/자녀_회원가입.gif" width=" 200px">
</div>

### Login

<!-- ![image](image/simulation/부모_로그인.gif) -->
<!-- ![image](image/simulation/자녀_로그인.gif) -->

<div class = "login">
    <img src = "image/simulation/부모_로그인.gif" width=" 200px">
    <img src = "image/simulation/자녀_로그인.gif" width=" 200px">
</div>

### 부모 튜토리얼

<!-- ![image](image/simulation/부모_튜토리얼_1.gif) -->
<!-- ![image](image/simulation/부모_튜토리얼_2.gif) -->
<!-- ![image](image/simulation/부모_튜토리얼_3.gif) -->
<!-- ![image](image/simulation/부모_튜토리얼_4.gif) -->

<div class = "p-t"
    <img src = "image/simulation/부모_튜토리얼_1.gif" width=" 200px">
    <img src = "image/simulation/부모_튜토리얼_2.gif" width="200px">
    <img src = "image/simulation/부모_튜토리얼_3.gif" width="200px">
    <img src = "image/simulation/부모_튜토리얼_4.gif" width="200px">
</div>

### 입금

<!-- ![image](image/simulation/부모_입금.gif) -->
<!-- ![image](image/simulation/자녀_입금.gif) -->

<div class = "deposit">
    <img src = "image/simulation/부모_입금.gif" width=" 200px">
    <img src = "image/simulation/자녀_입금.gif" width=" 200px">
</div>

### 투자

<!-- ![image](image/simulation/부모_투자.gif) -->
<!-- ![image](image/simulation/자녀_투자.gif) -->

<div class = "stock">
    <img src = "image/simulation/부모_투자.gif" width=" 200px">
    <img src = "image/simulation/자녀_투자.gif" width=" 200px">
</div>

### 적금

<!-- ![image](image/simulation/자녀_적금.gif) -->

<img src = "image/simulation/자녀_적금.gif" width=" 200px">

### 환전

<!-- ![image](image/simulation/부모_환전.gif) -->
<!-- ![image](image/simulation/자녀_환전.gif) -->

<div class = "change">
    <img src = "image/simulation/부모_환전.gif" width="200px">
    <img src = "image/simulation/자녀_환전.gif" width="200px">
</div>

### 할 일

<!-- ![image](image/simulation/부모_할일.gif) -->
<!-- ![image](image/simulation/자녀_할일.gif) -->

<div class = "todo"
    <img src = "image/simulation/부모_할일.gif" width=" 200px">
    <img src = "image/simulation/자녀_할일.gif" width=" 200px">
</div>

### 경제공부방

<!-- ![image](image/simulation/자녀_경제공부방.gif) -->

<img src = "image/simulation/자녀_경제공부방.gif" width=" 200px">

<br>

## 나의 역할

### 팀원 공통
- 2주간의 서비스 기획을 통한 **회의록, 주제 선정, 세부 기능명세서, API 명세서, 와이어프레임**을 작성하였습니다.
- **ERD 다이어그램**을 설계하였습니다.

### JIRA 일정 관리를 통해 프로젝트 일정을 총괄하였습니다.

- 기능별 배포를 통해 **애자일 방법론**을 바탕으로 일정 관리를 하기위해 노력하였습니다.
    - 매주 월요일에 **스프린트**를 시작하여 금요일에 끝나는 방식으로 진행하였습니다.
    - 기능별로 **에픽**을 만들어 매일매일 상세 이슈를 해결하였고 **데일리 스크럼**을 통해 스프린트를 관리하였습니다.

### OOP와 RDB의 불일치를 해결하여 개발하고자 Spring Data JPA을 활용을 제안하였습니다.

- 익숙한 **MyBatis**가 아니라 **JPA**를 선택한 이유
    - 소규모 프로젝트 + 복잡한 쿼리가 쓰이지 않을 것이라고 생각했습니다.
    - 객체지향적으로 데이터를 관리한다는 것을 직접 체험해보고 싶었습니다.
    - 그리고 JPA의 단점(복잡한 쿼리는 짜기 힘들다, 복잡한 내부로 인한 성능 이슈) 등은 다른 방법들을 통하면 단점보다 더 많은 이점을 얻을 수 있다고 판단했습니다.

### 예금, 적금 기능을 담당하여 개발했습니다.

- **적금 고민, 이자 고민**
    - 예를 들면 아이가 적금을 해지했을 때, [적금 내역의 잔액 + 이자]만큼의 금액을 입출금 내역의 단추 잔액에 추가해 줘야 되기 때문에 적금통장 해지 요청이 들어오면
        
        **자녀회원 seq → 적금 통장 seq → 적금내역 잔액 + (이자 계산) → 자녀회원 seq → 입출금 내역의 단추잔액 수정**
        
        이라는 많은 단계를 거쳐야 했기 때문에 자녀회원의 테이블에 잔액 컬럼을 추가하는 것에 대해 고민 하였습니다.
        
        ![적금 ERD](https://user-images.githubusercontent.com/63107888/224477751-a95e754d-22f6-4334-a68c-1cd97f06b693.PNG)
    
    
<br>

# 📃Tech Specifications

## 📚기술 스택

| Tech         | Stack                                  |
| ------------ | -------------------------------------- |
| **Language** | Java, JavaScript                       |
| **Backend**  | Spring Boot, JPA, Spring Security, JWT |
| **Frontend** | Vue.js, Vuetify, Vuex                  |
| **Database** | MariaDB                                |
| **Server**   | AWS EC2, NginX                         |
| **DevOps**   | Git, Docker                            |

<details>
<summary>🖥Backend 기술 자세히 보기</summary>
<div markdown="1">

    - Spring-Boot: 2.6.3
    - spring-boot-starter-data-jpa
    - spring-boot-starter-security
    - spring-boot-starter-web
    - p6spy-spring-boot-starter:1.8.0
    - springfox-swagger2:2.9.2
    - springfox-swagger-ui:2.9.2
    - swagger-annotations:1.5.21
    - io.swagger:swagger-models:1.5.21
    - io.jsonwebtoken:jjwt:0.9.1
    - lombok
    - spring-boot-devtools
    - mariadb-java-client

</div>
</details>

<br>

## 시스템 아키텍처

![시스템 아키텍처](image/specifications/system_structure.png)

<br>

## [ERD](https://www.erdcloud.com/d/fEbqnr9diEWmQQvGZ)

![ERD](image/specifications/erd.png)

<br>

## 📂Package Structure

### 🖥Backend

> 계층, 컴포넌트, 기능 순으로 패키지 구성

<details>
<summary>Backend 구조 자세히 보기</summary>
<div markdown="1">  
     
```
📦buttonup
 ┣ 📂config
 ┃ ┣ 📂security
 ┃ ┃ ┣ 📜JwtAuthenticationFilter.java
 ┃ ┃ ┣ 📜JwtTokenProvider.java
 ┃ ┃ ┗ 📜WebSecurityConfig.java
 ┃ ┣ 📜SwaggerConfig.java
 ┃ ┗ 📜WebConfig.java
 ┣ 📂controller
 ┃ ┣ 📂account
 ┃ ┃ ┗ 📜AccountController.java
 ┃ ┣ 📂economy
 ┃ ┃ ┗ 📜EconomyController.java
 ┃ ┣ 📂invest
 ┃ ┃ ┣ 📜InvestController.java
 ┃ ┃ ┣ 📜NewsController.java
 ┃ ┃ ┗ 📜SharePriceController.java
 ┃ ┣ 📂job
 ┃ ┃ ┣ 📜JobController.java
 ┃ ┃ ┣ 📜ToDoCheckController.java
 ┃ ┃ ┗ 📜ToDoController.java
 ┃ ┣ 📂request
 ┃ ┃ ┗ 📜RequestController.java
 ┃ ┣ 📂saving
 ┃ ┃ ┗ 📜SavingController.java
 ┃ ┣ 📂user
 ┃ ┃ ┣ 📜ChildController.java
 ┃ ┃ ┗ 📜ParentController.java
 ┃ ┗ 📜ExceptionController.java
 ┣ 📂domain
 ┃ ┣ 📂model
 ┃ ┃ ┣ 📂dto
 ┃ ┃ ┃ ┣ 📂account
 ┃ ┃ ┃ ┃ ┣ 📂request
 ┃ ┃ ┃ ┃ ┃ ┗ 📜HistoryRequest.java
 ┃ ┃ ┃ ┃ ┗ 📂response
 ┃ ┃ ┃ ┃ ┃ ┗ 📜HistoryResponse.java
 ┃ ┃ ┃ ┣ 📂economy
 ┃ ┃ ┃ ┃ ┣ 📂response
 ┃ ┃ ┃ ┃ ┃ ┣ 📜PostResponse.java
 ┃ ┃ ┃ ┃ ┃ ┗ 📜QuizResponse.java
 ┃ ┃ ┃ ┃ ┗ 📜Quiz.java
 ┃ ┃ ┃ ┣ 📂invest
 ┃ ┃ ┃ ┃ ┣ 📂request
 ┃ ┃ ┃ ┃ ┃ ┣ 📜InvestRequest.java
 ┃ ┃ ┃ ┃ ┃ ┣ 📜InvestStatusRequest.java
 ┃ ┃ ┃ ┃ ┃ ┣ 📜NewsRequest.java
 ┃ ┃ ┃ ┃ ┃ ┗ 📜SharePriceRequest.java
 ┃ ┃ ┃ ┃ ┗ 📂response
 ┃ ┃ ┃ ┃ ┃ ┣ 📜InvestPresetResponse.java
 ┃ ┃ ┃ ┃ ┃ ┣ 📜InvestStatusResponse.java
 ┃ ┃ ┃ ┃ ┃ ┣ 📜NewsResponse.java
 ┃ ┃ ┃ ┃ ┃ ┣ 📜RoughInvestResponse.java
 ┃ ┃ ┃ ┃ ┃ ┗ 📜SharePriceResponse.java
 ┃ ┃ ┃ ┣ 📂job
 ┃ ┃ ┃ ┃ ┣ 📂request
 ┃ ┃ ┃ ┃ ┃ ┣ 📜JobHistoryRequest.java
 ┃ ┃ ┃ ┃ ┃ ┣ 📜JobRequest.java
 ┃ ┃ ┃ ┃ ┃ ┗ 📜ToDoCheckRequest.java
 ┃ ┃ ┃ ┃ ┗ 📂response
 ┃ ┃ ┃ ┃ ┃ ┣ 📜JobResponse.java
 ┃ ┃ ┃ ┃ ┃ ┣ 📜ToDoCheckResponse.java
 ┃ ┃ ┃ ┃ ┃ ┗ 📜ToDoResponse.java
 ┃ ┃ ┃ ┣ 📂request
 ┃ ┃ ┃ ┃ ┣ 📂request
 ┃ ┃ ┃ ┃ ┃ ┗ 📜ExchangeRequest.java
 ┃ ┃ ┃ ┃ ┗ 📂response
 ┃ ┃ ┃ ┃ ┃ ┗ 📜RequestHistoryResponse.java
 ┃ ┃ ┃ ┣ 📂saving
 ┃ ┃ ┃ ┃ ┣ 📂request
 ┃ ┃ ┃ ┃ ┃ ┣ 📜SavingCloseRequest.java
 ┃ ┃ ┃ ┃ ┃ ┗ 📜SavingRequest.java
 ┃ ┃ ┃ ┃ ┗ 📂response
 ┃ ┃ ┃ ┃ ┃ ┣ 📜SavingBalanceResponse.java
 ┃ ┃ ┃ ┃ ┃ ┣ 📜SavingCloseResponse.java
 ┃ ┃ ┃ ┃ ┃ ┣ 📜SavingDetailResponse.java
 ┃ ┃ ┃ ┃ ┃ ┗ 📜SavingHistoryResponse.java
 ┃ ┃ ┃ ┗ 📂user
 ┃ ┃ ┃ ┃ ┣ 📂request
 ┃ ┃ ┃ ┃ ┃ ┣ 📜ConnectRequest.java
 ┃ ┃ ┃ ┃ ┃ ┣ 📜JoinRequest.java
 ┃ ┃ ┃ ┃ ┃ ┣ 📜LoginRequest.java
 ┃ ┃ ┃ ┃ ┃ ┗ 📜TutorialRequest.java
 ┃ ┃ ┃ ┃ ┗ 📂response
 ┃ ┃ ┃ ┃ ┃ ┣ 📜ChildResponse.java
 ┃ ┃ ┃ ┃ ┃ ┣ 📜LoginResponse.java
 ┃ ┃ ┃ ┃ ┃ ┣ 📜ParentResponse.java
 ┃ ┃ ┃ ┃ ┃ ┗ 📜TutorialResponse.java
 ┃ ┃ ┗ 📂entity
 ┃ ┃ ┃ ┣ 📂account
 ┃ ┃ ┃ ┃ ┣ 📜AccountHistory.java
 ┃ ┃ ┃ ┃ ┣ 📜AccountHistoryCategory.java
 ┃ ┃ ┃ ┃ ┗ 📜AccountHistoryType.java
 ┃ ┃ ┃ ┣ 📂economy
 ┃ ┃ ┃ ┃ ┣ 📜EconomyPost.java
 ┃ ┃ ┃ ┃ ┣ 📜EconomyTopic.java
 ┃ ┃ ┃ ┃ ┣ 📜Quiz.java
 ┃ ┃ ┃ ┃ ┣ 📜QuizHistory.java
 ┃ ┃ ┃ ┃ ┗ 📜QuizType.java
 ┃ ┃ ┃ ┣ 📂invest
 ┃ ┃ ┃ ┃ ┣ 📜Investment.java
 ┃ ┃ ┃ ┃ ┣ 📜InvestPreset.java
 ┃ ┃ ┃ ┃ ┣ 📜InvestStatus.java
 ┃ ┃ ┃ ┃ ┣ 📜News.java
 ┃ ┃ ┃ ┃ ┗ 📜SharePrice.java
 ┃ ┃ ┃ ┣ 📂job
 ┃ ┃ ┃ ┃ ┣ 📜Job.java
 ┃ ┃ ┃ ┃ ┣ 📜JobHistory.java
 ┃ ┃ ┃ ┃ ┣ 📜JobImage.java
 ┃ ┃ ┃ ┃ ┣ 📜PayTerm.java
 ┃ ┃ ┃ ┃ ┣ 📜ToDo.java
 ┃ ┃ ┃ ┃ ┗ 📜ToDoCheck.java
 ┃ ┃ ┃ ┣ 📂product
 ┃ ┃ ┃ ┃ ┣ 📜Product.java
 ┃ ┃ ┃ ┃ ┗ 📜ProductType.java
 ┃ ┃ ┃ ┣ 📂request
 ┃ ┃ ┃ ┃ ┣ 📜RequestHistory.java
 ┃ ┃ ┃ ┃ ┣ 📜RequestHistoryStatus.java
 ┃ ┃ ┃ ┃ ┗ 📜RequestHistoryType.java
 ┃ ┃ ┃ ┣ 📂saving
 ┃ ┃ ┃ ┃ ┣ 📜Saving.java
 ┃ ┃ ┃ ┃ ┗ 📜SavingHistory.java
 ┃ ┃ ┃ ┗ 📂user
 ┃ ┃ ┃ ┃ ┣ 📜Child.java
 ┃ ┃ ┃ ┃ ┗ 📜Parent.java
 ┃ ┣ 📂repository
 ┃ ┃ ┣ 📂account
 ┃ ┃ ┃ ┗ 📜AccountRepository.java
 ┃ ┃ ┣ 📂economy
 ┃ ┃ ┃ ┣ 📜EconomyPostRepository.java
 ┃ ┃ ┃ ┣ 📜EconomyTopicRepository.java
 ┃ ┃ ┃ ┣ 📜QuizHistoryRepository.java
 ┃ ┃ ┃ ┗ 📜QuizRepository.java
 ┃ ┃ ┣ 📂invest
 ┃ ┃ ┃ ┣ 📜InvestPresetRepository.java
 ┃ ┃ ┃ ┣ 📜InvestRepository.java
 ┃ ┃ ┃ ┣ 📜InvestStatusRepository.java
 ┃ ┃ ┃ ┣ 📜NewsRepository.java
 ┃ ┃ ┃ ┗ 📜SharePriceRepository.java
 ┃ ┃ ┣ 📂job
 ┃ ┃ ┃ ┣ 📜JobHistoryRepository.java
 ┃ ┃ ┃ ┣ 📜JobImageRepository.java
 ┃ ┃ ┃ ┣ 📜JobRepository.java
 ┃ ┃ ┃ ┣ 📜ToDoCheckRepository.java
 ┃ ┃ ┃ ┗ 📜ToDoRepository.java
 ┃ ┃ ┣ 📂request
 ┃ ┃ ┃ ┗ 📜RequestHistoryRepository.java
 ┃ ┃ ┣ 📂saving
 ┃ ┃ ┃ ┣ 📜SavingHistoryRepository.java
 ┃ ┃ ┃ ┗ 📜SavingRepository.java
 ┃ ┃ ┗ 📂user
 ┃ ┃ ┃ ┣ 📜ChildRepository.java
 ┃ ┃ ┃ ┗ 📜ParentRepository.java
 ┃ ┗ 📂service
 ┃ ┃ ┣ 📂account
 ┃ ┃ ┃ ┗ 📜AccountService.java
 ┃ ┃ ┣ 📂common
 ┃ ┃ ┃ ┗ 📜ImageService.java
 ┃ ┃ ┣ 📂economy
 ┃ ┃ ┃ ┗ 📜EconomyService.java
 ┃ ┃ ┣ 📂invest
 ┃ ┃ ┃ ┣ 📜InvestService.java
 ┃ ┃ ┃ ┣ 📜InvestStatusService.java
 ┃ ┃ ┃ ┣ 📜NewsService.java
 ┃ ┃ ┃ ┗ 📜SharePriceService.java
 ┃ ┃ ┣ 📂job
 ┃ ┃ ┃ ┣ 📜JobService.java
 ┃ ┃ ┃ ┣ 📜ToDoCheckService.java
 ┃ ┃ ┃ ┗ 📜ToDoService.java
 ┃ ┃ ┣ 📂request
 ┃ ┃ ┃ ┗ 📜RequestService.java
 ┃ ┃ ┣ 📂saving
 ┃ ┃ ┃ ┗ 📜SavingService.java
 ┃ ┃ ┗ 📂user
 ┃ ┃ ┃ ┣ 📜ChildService.java
 ┃ ┃ ┃ ┣ 📜CustomuserDetailService.java
 ┃ ┃ ┃ ┣ 📜ParentService.java
 ┃ ┃ ┃ ┗ 📜TutorialService.java
 ┣ 📂exception
 ┃ ┣ 📜BalanceOverException.java
 ┃ ┣ 📜ExistInvestException.java
 ┃ ┗ 📜NullJobException.java
 ┗ 📜ButtonUpApplication.java
```

</div>
</details>

<br>
<br>

## 첫단추 Wiki 바로가기

### [🌝첫 단추 HOME](https://lab.ssafy.com/s06-webmobile2-sub2/S06P12B205/-/wikis/home)

---

##### 기획

[🤝첫 단추의 철학](https://lab.ssafy.com/s06-webmobile2-sub2/S06P12B205/-/wikis/첫단추의-철학)  
[📜기능 명세서](https://docs.google.com/spreadsheets/d/1hQY69DIqmML3cubXh1oSkBYgT4yhRZiXsK6mI_f-EeI/edit#gid=0)  
[🖼와이어 프레임](https://www.figma.com/file/WZHm2zGmlgqLCwbs7ftYLR/%EC%B2%AB%EB%8B%A8%EC%B6%94?node-id=585%3A3019)  
[🎾API 설계서](https://docs.google.com/spreadsheets/d/1hQY69DIqmML3cubXh1oSkBYgT4yhRZiXsK6mI_f-EeI/edit#gid=1081310975)

---

[🤝Convention](https://lab.ssafy.com/s06-webmobile2-sub2/S06P12B205/-/wikis/%F0%9F%A4%9DConvention)

---

###### [🚨Issues](https://lab.ssafy.com/s06-webmobile2-sub2/S06P12B205/-/wikis/%F0%9F%9A%A8Issues)

- [🐽적금 통장 컬럼 - 잔액](https://lab.ssafy.com/s06-webmobile2-sub2/S06P12B205/-/wikis/적금-통장-컬럼---잔액)

---

##### [🎫Meeting Log](https://lab.ssafy.com/s06-webmobile2-sub2/S06P12B205/-/wikis/%F0%9F%8E%ABMeeting-Log)

😚 1주차 : 2022.01.08-2022.01.14

> 아이디어 회의 진행

###### 😊 2주차 : 2022.01.15-2022.01.21

[1월 17일 회의록](https://lab.ssafy.com/s06-webmobile2-sub2/S06P12B205/-/wikis/1월-17일-회의)  
[1월 18일 회의록](https://lab.ssafy.com/s06-webmobile2-sub2/S06P12B205/-/wikis/1월-18일-회의)  
[1월 19일 회의록](https://lab.ssafy.com/s06-webmobile2-sub2/S06P12B205/-/wikis/1월-19일-회의)  
[1월 21일 회의록](https://lab.ssafy.com/s06-webmobile2-sub2/S06P12B205/-/wikis/1월-21일-회의)

###### 🤔 3주차 : 2022.01.22-2022.01.28

[1월 24일 회의록](https://lab.ssafy.com/s06-webmobile2-sub2/S06P12B205/-/wikis/1월-24일-회의)  
[1월 25일 회의록](https://lab.ssafy.com/s06-webmobile2-sub2/S06P12B205/-/wikis/1월-25일-회의)  
[1월 26일 회의록](https://lab.ssafy.com/s06-webmobile2-sub2/S06P12B205/-/wikis/1월-26일-회의)

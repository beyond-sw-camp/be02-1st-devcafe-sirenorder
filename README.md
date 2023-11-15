<h1 align="center">DevCafe ☕️</h1>

<div align="center"> 
 <img src="https://postfiles.pstatic.net/MjAyMzExMTVfMTMg/MDAxNzAwMDE5NDQwOTQx.2SDpLn3Kkxsx04ZWQ62gtltmMI3DaJUE-O9b4akkaoIg.ZCuuumag_P1kfPigvHcZ5i58CNF1tjkJpE8GVCzMMrEg.PNG.kimjieun121314/%EC%A0%9C%EB%AA%A9%EC%9D%84-%EC%9E%85%EB%A0%A5%ED%95%B4%EC%A3%BC%EC%84%B8%EC%9A%94_-001.png?type=w773"/>
</div>


> [플레이 데이터] 한화시스템 BEYOND SW캠프 / DEVCafe


🎬[Demo 시연영상]().   
📃[프로젝트 회고록](블로그주소) 

<br>

## ✨ 프로젝트 소개

```sh
기존 카페 온라인 주문 시스템은 일상생활에 녹아들어 일상의 편리함을 주고 있지만
주문시 매장의 혼잡도를 알 수 없는 점이 불편함을 초래한다.
따라서 더 효율적이며 간편하고 현대적인 온라인 주문 시스템을 제공하기 위해
프로젝트를 진행하게 되었다.
```

## 📌 프로젝트 목표

```sh
시간대 별 혼잡도를 나타내주는 아이콘을 추가하여
주문 시 취소가 어려운 사이렌 오더의 단점을 최소화 하고
재주문을 편리하게 할 수 있는 페이지를 만들어 기존의 사이렌 오더와 차별화를 시도하였다.
```
## 📃 프로젝트 시나리오
```sh
1. 사용자 요구사항:
- 주문 기능:사용자는 메뉴에서 음료 및 음식을 선택하고 주문할 수 있어야 합니다.
- 주문 시 옵션(온도, 당도, 크기 등)을 선택할 수 있어야 합니다.
- 계정 관리:사용자는 회원가입 및 로그인을 통해 개인 계정을 관리할 수 있어야 합니다.
- 로그인한 사용자에게는 주문 이력과 적립된 혜택을 확인할 수 있는 기능이 있어야 합니다.

2. 카페 운영자 요구사항:
- 주문 관리:카페 운영자는 주문 목록을 확인하고 주문 상태를 업데이트할 수 있어야 합니다.
- 주문이 준비되면 알림을 전송하고, 완료된 주문에 대한 통계를 확인할 수 있어야 합니다.
- 매장 및 메뉴 관리:카페 운영자는 메뉴 항목을 추가, 수정, 삭제할 수 있어야 합니다.
- 각 매장에 대한 정보(위치, 운영 시간 등)를 관리할 수 있어야 합니다.
- 이벤트 및 할인 설정:카페 운영자는 이벤트 및 할인을 설정하고 이를 사용자에게 알릴 수 있어야 합니다.

3. 시스템 요구사항:
- 알림 서비스:주문 상태 변경 및 이벤트 정보와 같은 알림을 사용자에게 전송할 수 있는 서비스가 필요합니다.
- 결제 시스템:안전하고 신뢰성 있는 결제 시스템을 도입하여 사용자의 결제를 처리해야 합니다.
```

## 🔍 Overview

### 1. 사용자 회원 가입 및 로그인 기능(토큰 인증 방식)

<center>
    <img src="./img/pic2.png" />
</center>
JWT를 이용한 토큰 인증 방식

<br>

### 2. 게시판 기능

<center>
    <img src="./img/pic1.png" />
</center>
어떤 어떤 어떤 걸 작성하는 게시판 기능

<br>


## System Architecture

<center>
    <img src="./img/pic2.png" />
</center>
대용량 트래픽을 고려한 서버 이중화

<br>



## 🤼‍♂️팀원

팀장 : 김도현  
팀원 : 김지은, 김주연, 김준엽

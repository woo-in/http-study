# Week 1 — 질문 / 모범답안 (진승환)

## 1.1. 

**Q.** 

<details><summary></summary>

...

</details>

## 1.2. 

**Q.** 브라우저 말고 HTTP 클라이언트의 예시는?

<details><summary> </summary>

POSTMAN, curl 등

</details>

## 1.3. 

**Q.** 웹서버도 웹서버의 리소스가 될 수 있는가?

<details><summary>  </summary>

YES. 게이트웨이(애플레케이션과 연결된 특별한 웹서버)도 웹서버의 리소스다.

</details>

## 1.4. 

**Q.** PUT과 PATCH의 차이는?

<details><summary></summary>

PUT과 PATCH는 둘다 수정 메서드이지만, PUT은 모든 컬럼을 수정하고, PATCH는 수정할 컬럼만 요청으로 보내면 된다.

</details>

## 1.5.

**Q.** BODY는 Response에만 있다. [ O / X ]

<details><summary></summary>

O

</details>

## 1.6. 

**Q.** 한 서버(IP) 내에서 다양한 프로세스를 구분하기 위해 사용하는 번호는?

<details><summary></summary>

포트 번호

</details>

## 1.8. 

**Q.** Forwarding Proxy와 Reverse Proxy 중 웹 생태계에서 더 많이 쓰이는 것은?

<details><summary></summary>

Reverse Proxy는 클라이언트 입장에서 서버가 어떻게 구성되었는지 알 수 없게 하여 보안적인 측면을 챙기고, 로드밸런싱 기능도 수행한다.
Forwarding Proxy는 서버가 어떤 클라이언트가 요청을 보냈는지 가려준다. 기업 사내망 등에 사용되지만 흔한 웹 서비스 운영자 측면에서 효용이 많지 않다.

</details>

## 2.1.

**Q.** 메일 전송을 위해 사용하는 URL의 scheme은?

<details><summary></summary>

malito

</details>

## 2.6.

**Q.** URL의 한계와 그 URL의 한계를 해결하고자 탄생한 개념은?

<details><summary></summary>

URL은 서버 주소만 저장하고 그 서버의 리소스가 다른 곳으로 옮겨지면 더이상 URL은 의미가 없다는 한계점이 있었다.
그 한계를 보완하기 위해 URN이 등장했다. 
객체의 위치를 저장하는 URL과 달리 객체 name 자체를 저장하고 이름-위치 매핑 시스템은 따로 두어 리소스의 위치에 상관없이
이름만으로 항상 그 객체로 이동시킨다. 
하지만 실질적으로 URL -> URN 패러다임 교체 비용 대비 이미 URL이 표준화되었기 때문에 URN은 도입되고 있지 않다.

</details>
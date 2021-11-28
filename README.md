# Travel Helper
![1](https://user-images.githubusercontent.com/83301981/143764468-9d4fd683-b2dd-4331-b3fc-805649c98a80.PNG)

## A Brief Overview

With-Corona 국면에 접어들면서 국내 또는 해외 여행을 계획하는 사람들이 늘고 있습니다.

하지만 여행 계획을 짤 때에 To-do, 장소, 환율 계산까지 해야할 것이 너무나 많아 어려움을 겪곤 합니다.

따라서 이 모든것을 한 페이지에 할 수 있는 Web Site를 개발하게 되었습니다.

## How to use 

**Plan**

	- 각 날짜마다 그 날의 Title을 입력할 수 있다.
	- 여행 날짜 별로 To-do List처럼 계획을 세우고 수정할 수 있다.
**Budget**

	- 각 날짜마다 그날의 예산을 설정할 수 있다.
	- 각 날짜마다 그날의 지출 내역을 등록할 수 있다.
	- 모든 예산과 지출 내역은 여행 Title 아래에 표시된다.
**Map**

	- 지도에서 장소를 검색하여 줌인/ 줌아웃/ 둘러보기가 가능하다.
	- 여행지 근처의 유명 명소를 확인할 수 있다.

## Web Scenario

1. 여행의 전체 Title과 날짜, 동반자를 입력한다.

![2](https://user-images.githubusercontent.com/83301981/143764502-0ab450ed-1ec9-4006-8a9e-71f4cfabd2ac.PNG)

2. 입력된 날짜에 따라 계획을 입력할 수 있는 칸이 자동으로 생성된다.

![3](https://user-images.githubusercontent.com/83301981/143764503-f05df132-48ae-4b4d-b57e-ade71efe0ff9.PNG)

3. 여행하려는 나라의 화폐를 선택한다.

![4](https://user-images.githubusercontent.com/83301981/143764504-0ec30e0f-3ecd-4b84-82b0-5fe5afb5ed7e.png)

4. PLAN 칸에는 여행 계획을 적고, BUDGET 칸에는 소비 계획을 적는다.

![5](https://user-images.githubusercontent.com/83301981/143764505-436d02a3-043b-4305-8009-9ee69a61a4c2.PNG)

5. 날짜 별로 예산을 각자 세울 수 있다.

![6](https://user-images.githubusercontent.com/83301981/143764506-21fa9319-7b66-486b-bae5-7d0ea84139c1.PNG)

6. 각 날짜의 총 지출과 예산은 합계되어 이쪽에 나타난다.

![7](https://user-images.githubusercontent.com/83301981/143764507-473ea3c9-19f7-41bc-8f1c-43317449fb57.PNG)

7. 지도로 가고싶은 곳을 검색하여 살펴볼 수도 있다.

![8](https://user-images.githubusercontent.com/83301981/143764508-baacf246-084a-4092-9938-8c86b8a16850.png)

## Demo
- [GitHub Page](https://ez615.github.io/OSS_Final_Project/)
<iframe width="900" height="506" src="https://www.youtube.com/embed/Udvk4iuH3Oc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Used api

1. Google map api 사용
	- google map
	- google map 검색창
	https://developers.google.com/maps/documentation/javascript/examples/places-searchbox#maps_places_searchbox-javascript
2. Exchange api
	- Exchange api 
	https://fixer.io/

## Work

1. 우다연
	- 환율 api 사용 및 환전 프로그램 구현
	- 상단의 Total, Budget 박스 및 Budget plan list 박스 구현
	- save, load 기능 일부 적용
2. 이지현
	- html으로 전체적인 레이아웃 구현
	- 날짜 Setting에 맞춰 Container Clone 구현
	- PLAN Container 안의 모든 eventListener와 function 구현

3. 곽상천
	- google map api 사용

## Bug Report

1. API 관련
	- 환율 관련 API XMLHttp Request 오류
	- Google Map clone시 eventListener가 함께 clone되지 않는 오류

2. Save & Load 

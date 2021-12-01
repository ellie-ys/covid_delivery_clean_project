# (클린한끼)
- 코로나로 인한 배달량 증가, 그리고 음식점 위생상태 불만을 해결하기 위한 지역별 위생 가게 리스트 제공 웹 서비스
- [클린한끼 사이트 바로가기](https://kdt-vm-0202011.koreacentral.cloudapp.azure.com/)

## 프로젝트 아키텍처 

![image](https://user-images.githubusercontent.com/76929823/137636476-de8b0ccd-67cb-4ada-abf0-91760cdf315e.png)

🗓 **프로젝트 일정**

- 프로젝트 기간 : 2021.9.27(월) ~ 2021.10.15(금)

![image](https://user-images.githubusercontent.com/76929823/137832730-7af13496-6cf9-49e8-8df4-887bf73d74b1.png)


## 1. 프로젝트 소개

**어떠한 데이터셋와 도구 및 기술을 사용했는지에 대한 설명과 엔드유저에게 보이는 웹서비스에 대한 소개**
- 사용하려는 데이터(제안된 데이터 중 하나 또는 선택한 다른 데이터 세트)를 명시, 이에 대한 설명
  - [전국 인허가 데이터 행정안전부_일반음식점(수시)20210731](https://www.data.go.kr/data/15045016/fileData.do)
  - [행정안전부휴게음식점(수시)_20210731](https://www.localdata.go.kr/data/dataView.do)
  - [식품안전나라 '식품접객업소 위생등급 지정현황' 식품의약품안전처](https://www.foodsafetykorea.go.kr/apiMain.do)
  - [통계청 온라인 쇼핑 거래액 ( 음식 서비스)](http://kostat.go.kr/understand/info/info_lge/1/detail_lang.action?bmode=detail_lang&cd=SL4420)

- 기술 스택 (python, flask, javascript, react, MySQL 등)
- 사용된 라이브러리 (pandas, numpy, matplotlib, wordcloud, chart.js 등)
- 웹서비스에 대한 자세한 개요 (코로나로 인한 배달서비스 급증에 따른 소비자 민원 조사 및 위생상태 불량 적발 건수 데이터 분석과 이러한 사용자들의 불만해결을 위한 지역별 위생 가게 정보 제공)

## 2. 프로젝트 목표

- 데이터 분석 결과 코로나로 인해 비대면 음식 배달이 급증했고, 위생 상태에 대한 불만이 많다는 것을 확인 
- 소비자의 불만을 해결하기 위해 식품의약품안전처에서 인증한 음식점 리스트를 제공하는 등 '클린한끼' 서비스를 개발함


## 3. 프로젝트 기능 설명


  - 주요 기능 (주된 활용성) 및 서브 기능
    - 정보검색 기능
      - 배달 관련 데이터 정보 제공
      - 전국 위생가게 현황 및 등급 시각화
      - 식약처 위생인증 정보 확인
      - 메뉴 추천 추천 게임 ( 음식 마방진, 음식16강)
  
  - 프로젝트만의 차별점, 기대 효과
    * 통계적 기법(정규화)을 이용한 데이터 전처리를 바탕으로 정확한 정보 제공

## 4. 프로젝트 구성도 및 기능 설명
  - [클린한끼v0](https://whimsical.com/v0-V6s8jUiU2bUc7ERLEvcdpa) pw 0000
  - [클린한끼v1](https://whimsical.com/v1-8FPbR2gzgs6eX7WZWtMATJ) pw 1111
  - [클린한끼v2](https://whimsical.com/v2-4X7cqe4585aYoLqXcsM8mW) pw 2222
  - [클린한끼v3](https://whimsical.com/v3-DNqfPKfKN4vVWu96VZwBMa) pw 3333
  - [클린한끼v4-최종](https://whimsical.com/v4-BcsvgFdYjY7voFqVkr1k5C) pw 1234
  
### Implementation List

* [x] 지역별 위생등급별 가게수 확인 기능
* [x] 위생가게 수에 따른 지도 색표시 기능
* [x] 위생가게 수치를 절대값, 상대값 전환 기능
* [x] 프로젝트 소개 페이지 그래프 시각화기능
* [x] 위생가게 정보 검색 기능
* [x] 먹고 싶은 메뉴 고르기 게임 기능


## 5. 팀원 역할 분담
| 이름 | 담당 업무 |
| ------ | ------ |
| 강경모 | 팀장/프론트엔드 개발 |
| 고예림 | 프론트엔드 개발 |
| 김기원 | 기획/데이터분석/백엔드 개발|
| 민경준 | 프론트엔드 개발/백엔드 개발/데이터분석 |
| 최윤성| 기획/데이터분석/백엔드 개발 |

## 6. 버전
  - 프로젝트의 버전 기입
    - V1 - 대시보드형태의 데이터 시각화 정보제공
    - V2 - 스토리텔링 형태의 데이터 시각화 정보제공
    - V3 - 스토리텔링 형태의 데이터 시각화 정보 및 거리기반 위생 가게 정보 제공 및 사용자에게 재미 요소인 메뉴 고르기 게임 

## 7. 배운점

  - 백엔드
      - flask서버와 restful Api에 대해 알게되었고 api설계
      - 서버와 클라이언트간 http 통신이 가능하도록 axios를 사용
      - WAS(web application server)와 Web server에 대해서도 공부
      - azure VM에 접속해 web server인 nginx를 이용한 배포경험
  - 기획
      - 애자일 방법론을 이용해 3주동안 매일 오전 10시 스크럼과 저녁 회고
      - 서비스의 완성도를 높히기 위해 wire frame을 만들어 다각도로 고민함
  - 데이터 분석
      - jupyter notebook을 사용한 분석
      - 코로나 이후로 위생에 대한 인식이 높아졌지만 위생에 관련된 민원은 늘어나는 등의 근거관점 데이터를 수집 및 시각화
      - 식약청 위생인증을 받은 가게리스트를 제공하고, 유저가 검색하기 편리하도록 필요한 데이터 가공
      - 위생인증을 받은 가게 리스트는 프랜차이즈, 카페 비율이 높았기에 구분해 보여줄 필요성이 있어,  프랜차이즈에 대한 기준을 정해 분류
      - 데이터의 정규화를 위해, 전국 식품접객업소에 관한 데이터 (87만개)를 사용하는 등 다각도의 인사이트 제공
        
  - 그 외
      - 커뮤니케이션과 팀웍에 대한 중요성을 느낌
      - 최종발표 땐 '주제가 적절했다', '팀웍이 대단했고, 스타트업와 같은 열정을 느꼈다.' 는 담당 코치님의 피드백을 듣고 뿌듯

  - 팀원으로서 기여한 점
  (애자일 방식으로 와이어 프레임이 4번 바뀌었기 때문에 최종 프로젝트 기준)
    - 식약처 데이터 OPEN API등 데이터를 가지고 분석 및 가공 - jupyter notebook사용
    - backend server api 설계에 참여
    - 데이터베이스 설계 및 테이블 컬럼 추가에 따른 models.py 보완
    - 데이터베이스 생성 및 schema.sql 작성해 데이터 입력
    - server flask Blueprint에 url_prefix를 추가해 nginx에 proxy_pass를 적용할 수 있게 함
    - front, react issue page 작성 및 modal 사용해 그래프 시각화

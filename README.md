# 착한가격 업소 지도

공공데이터포털의 착한가격 업소 데이터를 카카오맵 위에 지역별, 업종별로 보여 주는 정적 웹 서비스입니다. 2022년 4인 팀 프로젝트(팀 STILL)로 진행했으며, 웹 페이지와 함께 모바일 앱과 카카오 챗봇 데모를 만들었습니다.

![착한가격 업소 지도 데이터 흐름](docs/assets/good-price-flow.svg)

## 내가 맡은 일

- 공공데이터 CSV를 JSON으로 바꾸고 조건으로 거르는 변환, 검색 모듈 작성 (`module/search.js`)
- 지역별 데이터셋의 필드명을 하나로 통일하고 서울, 전남 데이터의 출력 오류 수정 (`contentsJSON/`)
- 지역 데이터 표시와 품목 검색 기능 구현 (`app.js`)

## 결과물

- [웹 서비스](https://sebellko.github.io/-Still/)
- [카카오 챗봇 데모](https://pf.kakao.com/_xkxdxmxgb)
- [모바일 앱 (Flutter)](https://github.com/claris0/NearGoodPrice)
- [모바일 페이지 데모](https://github.com/claris0/good-price-jeju)

## 기술 스택

| 영역 | 기술 |
| --- | --- |
| 웹 | JavaScript, HTML, CSS, 카카오맵 API |
| 데이터 | 공공데이터포털 착한가격 업소, Google Places API, Node.js |
| 모바일과 챗봇 | Flutter, 카카오 i 오픈빌더, Python |

## 팀

[고세종](https://github.com/SebellKo), [김유석](https://github.com/NAMUORI00), [이홍규](https://github.com/jymh22), [선종호](https://github.com/claris0)

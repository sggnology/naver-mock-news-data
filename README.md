# naver-mock-news-data
Flutter code in songdo 2022 활동을 위한 테스트 데이터입니다.   
naver 검색 api 를 사용하여 데이터를 추출하였습니다.   

# Mock Data Explanation
- 검색어 `손흥민`에 대한 데이터를 추출
- 총 가짓수는 15개

# 사용방법
## 1. 전체 데이터 호출
> https://my-json-server.typicode.com/sggnology/naver-mock-news-data/items

## 2. 페이징된 데이터 호출
> https://my-json-server.typicode.com/sggnology/naver-mock-news-data/items?_page={}&_limit={}
- _page, _limit 을 통해 페이징 데이터를 호출할 수 있다.

### 파라미터
- _page : 페이지 넘버
- _limit : 데이터 갯수

# 특이사항

## 왜 데이터의 갯수가 15개 인가?
1. open source 로 my-json-server 를 사용할 경우 최대 `10kb`에 해당하는 크기의 응답만 가능하다.(현재 9.63 KB)

## total, display 등을 비롯한 다른 `field` 는 왜 노출하지 않는가?
1. my-json-server 는 beta 로 제공되고 있다. 따라서 특정 데이터의 구조는 지원하지 않는듯 하다.(문서에 설명 없음)   
2. 1번문제를 해결하고자 depth 를 증가시키면, 특정 데이터(여기서는 items)만을 확인하지 못한다.

# 출처
[My JSON Server](https://my-json-server.typicode.com)

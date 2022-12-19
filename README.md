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


# 출처
[My JSON Server](https://my-json-server.typicode.com)

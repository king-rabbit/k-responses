# k-responses
한국 관련 해외 반응을 다룬 유튜브 비디오 데이터 분석.    
- 데이터카우 답변(https://soprize.so/answer/487) 으로 작성된 리포지토리입니다. 
- 답변 내용 중 그래프에 잘못된 내용이 있어 아래 추가했으니 참고해주세요!     
      

   
## 데이터
- data/videos_re.csv : 2020년 7월 ~ 2021년 6월까지 주 단위로 수집한 한국 관련 리액션 유튜브 영상 및 영상 통계치
- data/countries_gni.xlsx : 2019년 국가별 GNI (출처: kosis.kr > 국제통계)
- data/comments.csv : 수집한 영상의 댓글 데이터

## 주피터 노트북
- data_collect.ipynb : 유튜브 api로 데이터 수집
- analysis.ipynb : 데이터 분석 및 시각화

## 그래프
- img/ : 국가별 리액션 영상 개수 / 평균 조회수, 좋아요, 싫어요, 댓글 수 그래프 및 국가별 댓글 워드클라우드


## 그래프 수정 및 추가
- 데이터카우 답변의 그래프에서 핀란드 데이터가 잘못돼 아래로 갈음합니다. (원래 답변보다 핀란드 리액션 영상의 조회수 / 좋아요 / 댓글 수 등이 더 높은 값을 갖고 있습니다.)   

<img src="./img/국가별 1인당 국민소득과 리액션 영상 조회수.png"></img><br/>
<img src="./img/국가별 1인당 국민소득과 리액션 영상 평균 좋아요 수.png"></img><br/>
<img src="./img/국가별 1인당 국민소득과 리액션 영상 평균 싫어요 수.png"></img><br/>
<img src="./img/국가별 1인당 국민소득과 리액션 영상 평균 댓글 개수.png"></img><br/>   
* * *
- 국가별 1인당 국민소득 및 영상 평균 조회수 데이터를 로그변환한 그래프입니다.   
<img src="./img/국가별 1인당 국민소득과 리액션 영상 조회수(로그변환).png"></img><br/>

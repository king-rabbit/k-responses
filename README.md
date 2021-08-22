# k-responses
한국 관련 해외 반응을 다룬 유튜브 비디오 데이터 분석.  
   
## 데이터
- data/videos_re.csv : 2020년 7월 ~ 2021년 6월까지 주 단위로 수집한 한국 관련 리액션 유튜브 영상 및 영상 통계치
- data/countries_gni.xlsx : 2019년 국가별 GNI (출처: kosis.kr > 국제통계)
- data/comments.csv : 수집한 영상의 댓글 데이터

## 주피터 노트북
- data_collect.ipynb : 유튜브 api로 데이터 수집
- analysis.ipynb : 데이터 분석 및 시각화

## 그래프
- img/ : 국가별 리액션 영상 개수 / 평균 조회수, 좋아요, 싫어요, 댓글 수 그래프 및 국가별 댓글 워드클라우드

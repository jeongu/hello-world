# Music Recommendation Based on My Playlist
'Bigdata Analysis' Term Project

> 데이터

데이터는 저작권 문제가 있어 커밋하지 않았습니다.

* 음악 재생 리스트(Ginie) : 음악 정보 + 재생 횟수 정보
* 최신 음악 리스트(Melon) : 음악 정보(2010 ~ 2017)

추천의 대상이 되는 음악 정보는 Ginie의 Web에서 접근이 제한됐기 때문에 Melon을 사용했습니다.
</br>


> 코드

(코드 정리 작업 중입니다.)
* music_recommender : data preprocessing + 추천 리스트 생성 코드 합치는 중

preprocessing : 변수 전처리, 가사를 텍스트 전처리 후 Word2vec으로 vector화하여 유사도 계산<br/>
modeling      : 혼합형 변수들의 gower 유사도, 가사 유사도, 재생 횟수를 활용한 추천 리스트 생성
</br>


> 프로젝트의 의미와 한계
* 일상에서 제공받는 추천 서비스에 만족하지 못해 내 데이터로 나만의 추천 시스템을 구축하는 과정이 재밌었습니다. 추천 결과 또한 기대 이상이었습니다.
* 다른 사용자들의 데이터를 수집할 수 없었습니다. 따라서 일반적인 추천 알고리즘을 활용할 수 없었기 때문에 독자적인 추천 방법을 고민해야 했습니다.
* 추천의 문제는 unsupervised learning이기 때문에 객관적인 성능 측정이 불가능했습니다.

## 1. 자연어처리(NLP)
1. 텍스트 처리
2. 영어 처리
    - 대소문자 통합
    - 정규화(Normalization)
    - 정규표현식(match, compile, search, split, sub, findall, finditer)
3. 토큰화(Tokenization)
   - 단어 토큰화
   - 문장 토큰화
   - 정규 표현식을 이용한 토큰화
   - 케라스를 이용한 토큰화
   - TextBlob을 이용한 토큰화
   - 기타 토크나이저
3. n-gram 추출
4. Pos(Parts of Speech) 태깅
5. 불용어 제거
6. 철자 교정
7. 언어의 단수화와 복수화
8. 어간(Stemming) 추출
9. 표제어(Lemmatization) 추출
10. 개체명 인식(Named Entity Recognition)
11. 단어 중의성(Lexical Ambiguity)
12. 한국어 처리
    - 정규 표현식(match, search, sub)
    - 토큰화(Tokenization) - 한국어 자연어 처리 konlpy와 형태소 분석기 Mecab설치,단어 토큰화,문장 토큰화, 정규 표현식을 이용한 토큰화, 케라스를 이용한 토큰화, TextBlob을 이용한 토큰화
    - Bag of Words(Bow)
    - 문서 단어 행렬(DTM)
    - 어휘 빈도- 문서 역빈도(TF-IDF)분석
## 2. 키워드 분석(Keyword Analysis)
1. 한글 폰트 설정
2. 한국어 자연어 처리 konlpy와 형태소 분석기 설치
3. 네이버 영화 리뷰 데이터
4. 형태소 분석을 이용한 명사 추출
    - 불용어(Stopwords)사전 만들기
    - 불용어를 제외하여 형태소 분석 수행
5. 단어 빈도수 측정
6. 단어 빈도 시각화
7. 워드클라우드(WordCloud)
8. squarify 트리맵 시각화
## 3. 군집 분석(Cluster Analysis)
1. Word2Vec 생성
2. Scikit-learn, Scipy를 이용한 계층적 군집화
   - Scikit-learn
     - ward
     - average
     - complete
   - Scipy
3. Scikit-learn을 이용한 비계층적 군집화
   - 클러스터 개수 3
   - 클러스터 개수 6
## 4. 문서 분류(Document Classification)
1. Scikit-learn을 이용한 문서 분류
   - Logistic Regression
   - Support Vector Machine
   - Naive Bayes
     - DTM을 이용한 Naive Bayes
     - tf-idf를 이용한 정확도 향상
   - Decision Tree
   - XGBoost
2. 교차 검증
3. 정밀도와 재현률
4. 그리드 검색을 이용한 파라미터 최적화
## 5. 의미 연결망 분석(Semantic Network Analysis)
1. n-gram
2. 어휘 동시 출현 빈도의 계수화
3. 중심성(Centrality)지수
   - 연결 중심성(Degree Centrality)
   - 위세 중심성(Eigenvector Centrality)
   - 근접 중심성(Closeness Centrality)
   - 매개 중심성(Betweeness Centrality)
   - 페이지랭크(PageRank)
## 6. 토픽 모델링(Topic Modeling)
1. 잠재 의미 분석(Latent Semantic Analysis)
2. 잠재 디리클레 할당(Latent Dirichlet Allocation)
3. Gensim을 이용한 토픽 모델링
   - 잠재 의미 분석을 위한 LsiModel
   - 잠재 디리클레 할당을 위한 LdaModel
4. 토픽 모델링 시각화
## 7. 감정 분석(Sentiment Analysis)
1. 감정 어휘 사전을 이용한 감정 상태 분류
   - 감정 사전 준비
   - 데이터 준비
   - 감정 상태 분류 및 시각화
2. 기계학습을 이용한 감정 분석
   - 한국어 자연어 처리 konlpy와 형태소 분석기 Mecab
3. 네이버 영화 리뷰 데이터 활용
   - 데이터로드
   - 중복 및 결측치 처리
   - 데이터 정제
   - 토큰화 및 불용어 제거
   - 빈도 수가 낮은 단어 제거
   - 패딩
   - 모델 구축 및 학습
   - 시각화
   - 감정 예측측

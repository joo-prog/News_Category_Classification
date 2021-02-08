# News_Category_Classification
## 뉴스 카테고리 분류


### 2/7
1.body clearing

2.category 개수 파악 후 적은 개수의 category는 제외

3.body의 문장 수를 세서 각각 몇개의 문장으로 이루어져 있는지 파악(sentence_cnt)

4.sentence_cnt를 보고 적절한 문장 개수 선정(5개 이상 28개 이하)

***

### 2/8
1. 토큰화

2. 정수 인코딩

3. 패딩

> **생각할 것**

* body clearing이 제대로 안된거 같다.. 정수 인코딩한거 봤더니 영어, 중국어 등 발견함

* 정수 인코딩한거 보고 stopwords 수정

* 패딩이 꼭 필요한가..

# KyungJinWoo의 포트폴리오 👋

안녕하세요! 저는 Kyung Jin Woo입니다. 다양한 프로젝트를 통해 **프로그래밍**과 **소프트웨어 개발**에 대한 경험을 쌓아왔습니다. 이 포트폴리오는 제가 참여한 프로젝트와 공부한 기술들을 정리한 것입니다.

## 📌 기술 스택

- **Languages**: SQL, R, Python
- **Database**: OracleSQL, DBever, MySQL, MongoDB



## 🌱 최근 공부한 기술

- [**SQL, SQL 튜닝**](https://www.notion.so/SQL-14b89c8bb0e380a69115d96a64e21fe2)
- [**R**](https://www.notion.so/R-139b151ddc8c49eba54c74ff4ad71947)
- [**파이썬**](https://www.notion.so/a0d42fcee4dc4e5392dd9a7f71cc4782)
- [**리눅스와 하둡**](https://www.notion.so/513334f539d24577ad4f453af7ebfaf6)
- [**딥러닝**](https://www.notion.so/11189c8bb0e380cdaca7cfe8ff044daf)
- [**Tableau**](https://github.com/KyungJinWoo/Tableau)



## 📝 프로젝트
( 이미지 클릭시 발표 자료를 열람할 수 있는 노션으로 이동합니다. )

### 1. [세종시 빅데이터 공모전]
<a href="https://www.notion.so/16089c8bb0e38143829df0b80c7f5720">
  <img src="https://github.com/KyungJinWoo/KyungJinWoo/blob/main/%EA%B9%83%ED%97%88%EB%B8%8C%20%EC%8D%B8%EB%84%A4%EC%9D%BC(%ED%87%B4%EC%82%AC%20%EC%97%90%EC%B8%A1).png" width="300"/>
</a>

<details>
  <summary>세종시의 폭염 저감을 위한 쿨페이브먼트 최적입지 선정 프로젝트</summary>  
  
  **활용 데이터**  
  
  **<세종시 출퇴근 인구>**
  - 동별 종사자수 데이터  
  - 동별 상업지역 위치  

  **<세종시 정류장 일일 평균 이용객수 데이터>**
  - 버스 정류장별 이용자수 데이터(24.03~24.08)  
  - 버스 정류장 위치  

  **<세종시 통학 인구>**
  - [초등학교, 중학교, 고등학교, 특수학교, 대학교] 위치, 학생수 데이터  

  **사용 기술**: Python, TensorFlow, Numpy, Shap  

</details>


### 2. [퇴사자 예측 신경망 모델]
<a href="https://www.notion.so/16089c8bb0e38143829df0b80c7f5720">
  <img src="https://github.com/KyungJinWoo/KyungJinWoo/blob/main/%EA%B9%83%ED%97%88%EB%B8%8C%20%EC%8D%B8%EB%84%A4%EC%9D%BC(%ED%87%B4%EC%82%AC%20%EC%97%90%EC%B8%A1).png" width="300"/>
</a>

<details>
  <summary>퇴사자 예측 신경망 모델 제작 프로젝트</summary>  
  
  **활용 데이터**  
  - Kaggle의 IBM데이터  

  **사용 기술**: Python, TensorFlow, Numpy, Shap  

  **모델 성능**  
  훈련 정확도 : 99.49 %  
  AUC-ROC : 0.9961  
  훈련 Loss : 0.1374  
  테스트 정확도 : 98.64 %  
  F1-Score : 0.9864  
  테스트 Loss : 0.1727  
  
</details>


### 3. [헬스 자세 보조 딥러닝 모델]
<a href="https://www.notion.so/16089c8bb0e38143829df0b80c7f5720">
  <img src="https://github.com/KyungJinWoo/KyungJinWoo/blob/main/%EA%B9%83%ED%97%88%EB%B8%8C%20%EC%8D%B8%EB%84%A4%EC%9D%BC(%ED%87%B4%EC%82%AC%20%EC%97%90%EC%B8%A1).png" width="300"/>
</a>

<details>
  <summary>헬스 초보를 위한 자세 보조 딥러닝 모델 제작 프로젝트</summary>  
  
  **활용 데이터**  
  - 피트니스 자세 이미지 데이터  
  - 비만율, 헬스 이용객 통계 자료  
  - 네이버 블로그 홈트 크롤링 데이터  

  **사용 기술**: TSM(Temporal, Shift Module), Bi-LSTM, Mediapipe, Flask  
  
</details>

### 4. [마케팅 프로젝트]
<a href="https://www.notion.so/16089c8bb0e38143829df0b80c7f5720">
  <img src="https://github.com/KyungJinWoo/KyungJinWoo/blob/main/%EA%B9%83%ED%97%88%EB%B8%8C%20%EC%8D%B8%EB%84%A4%EC%9D%BC(%ED%87%B4%EC%82%AC%20%EC%97%90%EC%B8%A1).png" width="300"/>
</a>

<details>
  <summary>이커머스 고객 세분화 분석 프로젝트</summary>  
  
  **활용 데이터**  
  **<데이터셋>**  
  - CUSTOMER_INFO : 고객 정보  
  - ONLINESALES_INFO : 온라인 거래 정보  
  - DISCOUNT_INFO : 할인 쿠폰 정보  
  - MARKETING_INFO : 마케팅 비용 정보  
  - TAX_INFO : 세금 정보  
  데이콘 이커머스 고객 세분화 데이터  

  **사용 기술**: ScikitLearn, matplotlib, Numpy, seaborn, K-Means, Birch, K-medoids, PCA  

  **최종 마케팅 전략**  
  **Cluster0~3**  
  <Cluster0>  
  - 품목 고급화 유도, 추가 구매 유도, 대량 구매시 할인
    
  <Cluster1>  
  - 구매가 몰려있는 Apparel, Nest-USA, Office 위주로 소액 쿠폰 제공  
  - 쿠폰 제공 시에는 동일 카테고리 내 중가 이상의 가격대 상품 추천  
  - 번들 세일  
  
  <Cluster2>  
  - 구매가 많은 금, 토, 일요일에 타임 세일,  
  - 평균단가보다 높은 금액대 제품 한정 고할인율 쿠폰을 제공해 평균 단가를 높이는 전략  
    
  <Cluster3>  
  - 고가 상품 수요에 부응하는 프리미엄관 운영  

  
</details>

### 5. [데이콘 대회](링크)
<a href="https://www.notion.so/16089c8bb0e38143829df0b80c7f5720">
  <img src="https://github.com/KyungJinWoo/KyungJinWoo/blob/main/%EA%B9%83%ED%97%88%EB%B8%8C%20%EC%8D%B8%EB%84%A4%EC%9D%BC(%ED%87%B4%EC%82%AC%20%EC%97%90%EC%B8%A1).png" width="300"/>
</a>

**설명**: Kaggle의 IBM 데이터를 활용해 퇴사자 예측 신경망 모델을 만든 프로젝트입니다.

**사용한 기술**: Python, TensorFlow, Numpy, Shap

## 👯 함께 작업하고 싶은 분야

- 웹 개발 (React, Node.js)
- 머신러닝 및 인공지능
- 클라우드 및 DevOps

## 📫 연락 방법

- 이메일: k_jinoo98@naver.com
- 전화번호 : 010-8223-6746


이 포트폴리오는 제가 만든 **프로젝트**와 **기술 스택**을 바탕으로 작성되었습니다. 언제든지 제게 연락주세요!


# 경진우의 포트폴리오 👋

안녕하세요! 데이터 분석가를 꿈꾸는 경진우입니다. 다양한 프로젝트를 통해 **데이터 분석**에 대한 경험을 쌓아왔습니다. 이 포트폴리오는 제가 참여한 프로젝트와 공부한 기술들을 정리한 것입니다.

## 📌 기술 스택

- **Tool**: SQL, R, Python, Tableau
- **Database**: OracleSQL, DBever, MySQL, MongoDB



## 🌱 최근 공부한 기술

- [**SQL, SQL 튜닝**](https://www.notion.so/SQL-14b89c8bb0e380a69115d96a64e21fe2)
- [**R**](https://www.notion.so/R-139b151ddc8c49eba54c74ff4ad71947)
- [**파이썬**](https://www.notion.so/a0d42fcee4dc4e5392dd9a7f71cc4782)
- [**리눅스와 하둡**](https://www.notion.so/513334f539d24577ad4f453af7ebfaf6)
- [**딥러닝**](https://www.notion.so/11189c8bb0e380cdaca7cfe8ff044daf)
- [**Tableau**](https://github.com/KyungJinWoo/Tableau)



## 📝 프로젝트
( 이미지 클릭시 발표 자료를 열람할 수 있습니다. )

### 1. [세종시 빅데이터 공모전]
<a href="https://github.com/KyungJinWoo/KyungJinWoo/blob/main/%EC%84%B8%EC%A2%85%EC%8B%9C%20%EA%B3%B5%EB%AA%A8%EC%A0%84%20%EC%B5%9C%EC%A2%85.pdf">
  <img src="https://github.com/KyungJinWoo/KyungJinWoo/blob/main/%EC%84%B8%EC%A2%85%EC%8B%9C%20%EA%B3%B5%EB%AA%A8%EC%A0%84%20%EC%8D%B8%EB%84%A4%EC%9D%BC.png" width="300"/>
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

  **성과 및 역할**  
  - 학교, 상업지역, 정류장 밀도를 종합한 가중치 기반 입지 우선순위 설정  
  - SHAP 기반 중요변수 분석 및 시각화 수행  
  
</details>


### 2. [퇴사자 예측 신경망 모델]
<a href="https://github.com/KyungJinWoo/KyungJinWoo/blob/main/%ED%94%BC%EB%93%9C%EB%B0%B1%20%ED%9B%84%20%EC%B5%9C%EC%A2%85_%ED%87%B4%EC%82%AC%EC%9E%90%EC%98%88%EC%B8%A1.pdf">
  <img src="https://github.com/KyungJinWoo/KyungJinWoo/blob/main/%EA%B9%83%ED%97%88%EB%B8%8C%20%EC%8D%B8%EB%84%A4%EC%9D%BC(%ED%87%B4%EC%82%AC%20%EC%97%90%EC%B8%A1).png" width="300"/>
</a>

<details>
  <summary>퇴사자 예측 신경망 모델 제작 프로젝트</summary>  

  **분석 목적**  
  기업의 인재 유지 전략 수립을 위한 퇴사 예측 모델 제작  

  **활용 데이터**  
  - Kaggle IBM HR Analytics 데이터  

  **사용 기술**: Python, TensorFlow, SHAP, 딥러닝 신경망 모델  
  
  **모델 성능**  
  훈련 정확도 : 99.49 %  
  AUC-ROC : 0.9961  
  훈련 Loss : 0.1374  
  테스트 정확도 : 98.64 %  
  F1-Score : 0.9864  
  테스트 Loss : 0.1727  

  **성과 및 역할**  
  - 중요변수 시각화를 통한 퇴사 영향 요인 분석
  - SHAP을 활용한 인사이트 도출
  
</details>


### 3. [헬스 자세 보조 딥러닝 모델]
<a href="https://github.com/KyungJinWoo/KyungJinWoo/blob/main/%ED%8C%8C%EC%9D%B4%EB%84%90%20%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8_%EC%B5%9C%EC%A2%85.pdf">
  <img src="https://github.com/KyungJinWoo/KyungJinWoo/blob/main/%ED%99%88%ED%8A%B8%EB%A0%88%EC%9D%B4%EB%8B%9D%20%EC%9E%90%EC%84%B8%20%ED%8F%89%EA%B0%80%20%EB%AA%A8%EB%8D%B8.png" width="300"/>
</a>

<details>
  <summary>헬스 초보를 위한 자세 보조 딥러닝 모델 제작 프로젝트</summary>  

  **목적**  
  실시간 자세 피드백 제공으로 운동 효과 및 정확성 향상  
   
  **활용 데이터**  
  - 피트니스 자세 이미지 데이터  
  - 비만율, 헬스 이용객 통계 자료  
  - 네이버 블로그 홈트 크롤링 데이터  

  **사용 기술**: TSM(Temporal, Shift Module), Bi-LSTM, Mediapipe, Flask  

  **성과 및 역할**  
  - 포즈 추정 기반 자세 분류 및 피드백 시스템 구현  
  - TSM, Bi-LSTM 모델 비교 실험 및 평가 수행  
  
</details>

### 4. [마케팅 프로젝트]
<a href="https://github.com/KyungJinWoo/KyungJinWoo/blob/main/%EC%B5%9C%EC%A2%85_%EB%A7%88%EC%BC%80%ED%8C%85.pdf">
  <img src="https://github.com/KyungJinWoo/KyungJinWoo/blob/main/%EB%A7%88%EC%BC%80%ED%8C%85%20%EC%8D%B8%EB%84%A4%EC%9D%BC.png" width="300"/>
</a>

<details>
  <summary>이커머스 고객 세분화 분석 프로젝트</summary>  
  
  **활용 데이터**  
  **데이터셋**  
  - **CUSTOMER_INFO** : 고객 정보  
  - **ONLINESALES_INFO** : 온라인 거래 정보  
  - **DISCOUNT_INFO** : 할인 쿠폰 정보  
  - **MARKETING_INFO** : 마케팅 비용 정보  
  - **TAX_INFO** : 세금 정보  
  데이콘 이커머스 고객 세분화 데이터 활용

  **사용 기술**: ScikitLearn, matplotlib, Numpy, seaborn, K-Means, Birch, K-medoids, PCA  

  ### 🛒 최종 마케팅 전략  
  **Cluster 0~3**  

  - **Cluster 0 : 저가 + 대량 구매형 고객**  
    - 품목 고급화 유도, 추가 구매 유도, 대량 구매 시 할인  

  - **Cluster 1 : 저가 + 쿠폰 민감형 고객**  
    - 구매가 몰려있는 Apparel, Nest-USA, Office 위주로 소액 쿠폰 제공  
    - 쿠폰 제공 시, 동일 카테고리 내 중가 이상의 가격대 상품 추천  
    - 번들 세일 적용  

  - **Cluster 2 : 중저가 + 할인율 민감형 고객**  
    - 구매가 많은 금, 토, 일요일에 타임 세일 적용  
    - 평균 단가보다 높은 금액대 제품 한정 고할인율 쿠폰 제공  
    - 평균 단가 상승을 유도하는 전략  

  - **Cluster 3 : 고가 + 쿠폰 둔감형 고객**  
    - 고가 상품 수요에 부응하는 프리미엄관 운영  


  **RFMV 세부 마케팅 전략**  

  - **UUUU : 모든 수치에서 높은 등급에 해당되는 고객군**  
    - 거래 횟수가 많은 수, 금요일에 일정 수요가 있으면서, 평균 단가가 비싼 카테고리인 (Nest-USA, Nest, Bags)에 해당하는 쿠폰을 제공  

  - **UDDD : 재참여 초기 단계의 고객군**  
    - 마지막 구매일로부터 22일이 넘어가는 시점에 리마인드 메세지 혹은 앱푸쉬 알림 (과도한 마케팅 압박을 줄이기 위해 3사분위수인 22일을 이용)  

  - **DUUU : 마지막 구매 이후 시간이 오래 지난 고객군**  
    - 구매가 많았던 Apparel, Nest-USA, Office, Drinkware, Lifestyle 카테고리 위주로 웰컴백 쿠폰 제공, 개인화된 메시지 발송  

  - **UUUD : 구매 카테고리가 한정적인 고객군**  
    - 인기 카테고리인 Nest-USA와 함께 자주 구매된 카테고리 상품(Apparel, Office, Drinkware, Lifestyle)을 추천
   
  - **DDDD : 이탈 고객군**  
    - 거래가 많았던 상품(Apparel, Nest-USA, Office)을 알고리즘에 노출 혹은 추천 메세지 발송
   
  **성과 및 역할**  
  - RFMD 기반 세분화 및 마케팅 전략 수립  
  - 고가/저가, 쿠폰 민감도 기반 고객별 세일 및 추천 전략 도출  
  - 실제 구매 유형과의 비교를 통한 타당성 검증  
</details>


### 5. [데이콘 대회]
<a href="https://github.com/KyungJinWoo/KyungJinWoo/blob/main/%EC%82%B0%ED%83%80_%EA%B2%BD%EB%A1%9C_%EC%B5%9C%EC%A0%81%ED%99%94PDF.pdf">
  <img src="https://github.com/KyungJinWoo/KyungJinWoo/blob/main/%EA%B2%BD%EB%A1%9C%20%EC%B5%9C%EC%A0%81%ED%99%94%20%EC%8D%B8%EB%84%A4%EC%9D%BC.png" width="300"/>
</a>

<details>
  <summary>선물 배송 경로 최적화 경진대회</summary>  
  
  **활용 데이터**  
  - 주어진 거리 행렬 및 TOWN별 수요량(대회처 제시 데이터)   

  **사용 기술**: LKH-3, 4-OPT  

  **성과 및 역할**  

  - 알고리즘 구현, 초기 경로 기반 4-OPT 알고리즘 최적화  
  - 최종 거리: 2173.58914  
  - 전체 241팀 중 7위  

  
</details>


## 📫 연락 방법

- 이메일: k_jinoo98@naver.com
- 전화번호 : 010-8223-6746



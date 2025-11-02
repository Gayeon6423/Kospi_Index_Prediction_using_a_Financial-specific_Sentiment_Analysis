## 금융 특화 감정분석 모델과 딥러닝 시계열 예측 모델을 활용한 코스피 지수 예측
### Kospi Index Prediction using a Financial-specific Sentiment Analysis and Deep Learning-based Time Series Prediction Model

---

## 1. 프로젝트 개요

---

**[기간]**

2023.09~2024.03

**[목표]**

뉴스·보고서의 감성 점수와 시장 시계열 데이터를 융합하여 단기 지수 예측 정확도 향상

**[역할]**

뉴스 데이터 크롤링, LSTM 시계열 모델 설계, KoFinBERT모델 감정 분류 모델로 Fine-Tuning, 뉴스 감정 지수 도출 

**[성과]**

한국산업공학회 논문 게재 (2025.08.15)

**[설명]**

- 뉴스 데이터 기반의 감성 분석 모델과 딥러닝 기반의 시계열 예측 모델을 이용해 코스피 지수를 예측
- 코스피 지수의 종가를 종속변수로, 거시경제 지표와 감성지수와 같은 시장 심리 지표를 독립변수로 사용 / 코스피 관련 뉴스 데이터를 수집해 전처리한 후 제목 또는 요약 기사를 활용해 감성지수 산출에 활용
- KLUE-BERT 모델 기반의 날짜 별 감성지수와 KoFinBERT 모델 기반의 날짜 별 감성지수를 추출
- 시계열 예측 모델로는 LSTM, GRU, CNN-LSTM, CNN-GRU를 사용
- 변수와 모델을 조합하여 실험을 진행한 결과, 요약 기사에 KLUE-BERT를 적용하고 CNN-GRU 모델을 사용했을 때 가장 좋은 성능을 보임

- keyword : Deep Learning, BERT, Sentiment Analysis, LSTM, Kospi Index Prediction

## 2. 논문 투고 관련 정보

---

- Published : Journal of the Korean Institute of Industrial Engineers - Vol.50, No.4, pp.240-250(11 pages)
- ISSN: 1225-0988 (Print) 2234-6457 (Online)
- Print publication date 15 Aug 2024
- Received 12 Jan 2024 Accepted 05 Feb 2024


## 3. 모델 구조

---

![KOSPI](https://github.com/user-attachments/assets/a226200f-0ce4-486a-ab3f-5cf87b2ad574)


## 4. 증빙 자료

---

- KCI 우수등재
    - https://www.kci.go.kr/kciportal/ci/sereArticleSearch/ciSereArtiView.kci?sereArticleSearchBean.artiId=ART003107079
- JKIIE 학회지 게재
    - https://jkiie.org/_PR/view/?aidx=41593&bidx=3767#!po=5.55556

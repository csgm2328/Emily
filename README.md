나만의 로보어드바이저 - 에밀리
=============

💬 LSTM 모델을 이용해 투자 자산의 가격을 예측하고 원하는 매매주기에 따라 최적의 매매 타이밍을 제공합니다.

## 시나리오
<img src="https://user-images.githubusercontent.com/39210160/95105457-28605480-0772-11eb-8811-99ee19aea7d2.png">
<img src="https://user-images.githubusercontent.com/39210160/95105657-6eb5b380-0772-11eb-8dca-fae1dc6b0295.png">
<img src="https://user-images.githubusercontent.com/39210160/95105692-7d03cf80-0772-11eb-8b0c-a28b9579cbb4.png">
<img src="https://user-images.githubusercontent.com/39210160/95105510-38783400-0772-11eb-95ce-44ecebc7c5ee.png">


## 수행내용
- Hyper Parameter Optimization
- (train_set, test_set) 뒤집어 학습: 최근데이터 학습을 위해서
- 학습된 모델들에서 Accuracy, MCC, MAPE 평가해서 우수 모델 추출
- 알고리즘을 통해 최적 매매타이밍을 포착
- 선정기준에 맞도록 지속적인 우수모델 갱신

## 개발환경
- Google Colab (Tesla T4 or Tesla K80)
- Linux (Titan XP)

## 진행문서
[에밀리 진행 Docs](https://docs.google.com/document/d/1TKvwtL3RQNJwFevq9epFiTZhDykAKoCLrA_NXdWJlmg/edit?usp=sharing)
## 정보
- 개발자: 추승지
- 문의사항: csgm2328@jbnu.ac.kr

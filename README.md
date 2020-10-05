나만의 로보어드바이저 - 에밀리
=============

💬 LSTM 모델을 이용해 Stock, BTC 가격 예측하고 최적의 매매 타이밍을 제공

## 시나리오
<img src="https://user-images.githubusercontent.com/39210160/95105457-28605480-0772-11eb-8811-99ee19aea7d2.png">
<img src="https://user-images.githubusercontent.com/39210160/95105657-6eb5b380-0772-11eb-8dca-fae1dc6b0295.png">
<img src="https://user-images.githubusercontent.com/39210160/95105692-7d03cf80-0772-11eb-8b0c-a28b9579cbb4.png">
<img src="https://user-images.githubusercontent.com/39210160/95105510-38783400-0772-11eb-95ce-44ecebc7c5ee.png">


## 설명
- (train_set, test_set) 뒤집어 학습: 최근데이터 학습을 위해서
- 학습된 모델에서 acc, mcc 평가해서 우수 모델 추출
- 위의 평가지표를 최종 예측의 신뢰도로 제공
- 최적 매매타이밍 포착

## 개발환경
- Google Colab
- Linux (Titan XP)

## 정보
- 개발자: 추승지
- 문의사항: csgm2328@jbnu.ac.kr

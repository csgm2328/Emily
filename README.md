나만의 로보어드바이저 - 에밀리
=============
https://user-images.githubusercontent.com/39210160/98380721-43cdc080-208c-11eb-866e-1d9fbd563627.png
💬 LSTM 모델을 이용해 투자 자산의 가격을 예측하고 원하는 매매주기에 따라 최적의 매매 타이밍을 제공합니다.

## 시나리오
https://user-images.githubusercontent.com/39210160/98381577-69a79500-208d-11eb-90dc-39d4f664d832.png

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

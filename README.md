### test.ipynb
스타벅스 지도에서 위/경도 좌표 및 주소를 csv로 저장해주는 소스 <br>
chromeDriver 다운로드 필요
https://m.blog.naver.com/tnsqo1126/222570075666

### 프로젝트#3 캐글 코리아와 함께하는 2nd ML 대회 - House Price Prediction<br>

#### 앙상블(Ensemble) <br>
  ** 여러 개의 학습 알고리즘을 사용 **<br>
  ** 그 예측을 결합 **<br>
  ** 정확한 최종 예측을 도출하는 기법 ** <br>

  ** 이미지, 영상, 음성 등의 비정형 데이터의 분류 ==> 딥러닝 ** <br>
  ** 대부분의 정형 데이터 분류 ==> 앙상블 **<br>

  **앙상블 학습 유형**<br>
  Voting/Averaging : Voting(분류:categorical), Averaging(회귀:numerical) <br>
  Bagging(Bootstrap Aggregating), <br>
  Boosting, <br>
  Stacking 등 다양한 앙상블 학습의 유형<br>



Going Deeper<br>
5. CAM을 만들고 평가해보자<br>
   - RESNET50 + GAP + DENSELAYER와 결합된 CAM모델의 학습<br>
   - CAM방식과 GRAD-CAM방식의 CLASS ACTIVATION MAP 생성, 시각화<br>
   - CAM과 GRAD-CAM각각의 원본이미지 합성, 바운딩박스, IoU계산과정을 통해 CAM과 Grad-CAM의 object localization성능비교/ <br>
<br>
6. 직접 만들어보는 OCR
   - Text recognition을 위해 특화된 데이터셋 구성이 체계적으로 진행되었다.
    .텍스트 이미지 리사이징, ctc loss 측정을 위한 라벨 인코딩, 배치처리 등이 적절히 수행되었다.
   - CRNN 기반의 recognition 모델의 학습이 정상적으로 진행되었다.
    . 학습결과 loss가 안정적으로 감소하고 대부분의 문자인식 추론 결과가 정확하다.
   - keras-ocr detector와 CRNN recognizer를 엮어 원본 이미지 입력으로부터 text가 출력되는 OCR이 End-to-End로 구성되었다.
    . 샘플 이미지를 원본으로 받아 OCR 수행 결과를 리턴하는 1개의 함수가 만들어졌다.
    

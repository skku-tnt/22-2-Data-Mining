# 📚TASK1

### 🍷와인 품질 분류 알고리즘🍇

- [5497, 14]로 구성된 정형 데이터입니다.
- dataset.csv를 이용해서 지금까지 배웠던 내용을 바탕으로 분석을 진행하시면 됩니다. 정답은 없으니 자유롭게 진행해주세요!
    
    예시 순서입니다)
    
    - EDA ( ex) .info(), .head(), .describe() 등)
    - 데이터 전처리 ( ex) object → numeric, 결측치 제거, train_test_split() 등)
    - 훈련
    - 평가 ( ex) accuracy, F1 score,  ROC curve 등)
    - (선택) test.csv를 통한 새로운 데이터에 대한 label값 예측
- 위 링크에서의 EDA코드와 model 생성 코드를 참고하셔도 좋습니다!

<주의사항>

** feature값들 중 ‘quality’를 label로 두고 진행해주세요.

** test.csv 파일에는 label값이 없어 예측값에 대한 평가를 진행할 수 없습니다. dataset.csv 파일의 데이터를 바탕으로 train_test_split()을 진행하신 후 여기서 split된 test set을 바탕으로 정답 label과의 비교를 통해 평가를 진행해주세요.

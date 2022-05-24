# DACON_News_Topic
![20220524_130410](https://user-images.githubusercontent.com/84311270/169953346-fde2ab12-403c-4fb5-b3da-0bef811dda9e.png)
한국어 뉴스 헤드라인을 이용하여, 뉴스의 주제를 분류하는 알고리즘 개발

## Dataset
train_data.csv  
index : 헤드라인 인덱스  
title : 뉴스 헤드라인  
topic_idx : 뉴스 주제 인덱스 값(label)  

test_data.csv  
index : test 헤드라인 인덱스  
title : test 뉴스 헤드라인  

sample_submission.csv  
index : test 헤드라인 인덱스  
topic_idx : 예측해야 하는 뉴스 토픽 인덱스 값  

topic_dict.csv  
topic : 실제 뉴스 토픽  
topic_idx : 뉴스 토픽 인덱스 값  

## Model
형태소 분석기 Mecab과 Kobert 모델을 사용하여 학습을 진행.

## Results
Public Score : 0.8598, Private Score : 0.82873으로 최종 32등으로 마무리.
![20220524_130459](https://user-images.githubusercontent.com/84311270/169975742-5acd1fc3-9597-4736-9903-16916e2282ae.png)


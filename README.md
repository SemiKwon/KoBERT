# *Cognitive Pragmatic Inference in Irony : Utilizing KoBERT-Based AI Model*
AI 한국어 언어 모델을 통해 아이러니 처리에 대비 효과를 적용하는 방법 탐색

1) KoBERT가 한국어 데이터의 화용적 의미인 **문자, 반어, 곡해, 과장**을 구분할 경우의 인지 처리 분석
2) KoBERT를 통한 코사인 유사도 계산 수행

## 📌 KoBERT를 사용하기 위한 패키지 설치 버전
* mxnet
* gluonnlp==0.8.0
* tqdm, pandas, sentencepiece
* transformers
* torch

## 📌 KoBERT(Demo) 모델 확인을 위한 감성 데이터셋 
* 감정 분류를 위한 대화 음성 데이터셋 - 5차년도(2차) **19,374**
- https://aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&dataSetSn=263

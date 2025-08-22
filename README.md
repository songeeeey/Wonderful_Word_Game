# Wonderful_Word_Game
단어 간의 유사도를 이용해서 정답을 유추하는 게임 

### 1. 사용한 데이터 셋

제가 사용한 데이터 셋은 한국어 웹에서 수집된 텍스트로 구성된 대규모 말뭉치 데이터입니다.

|항목|설명|
|---|---|
|출처|[huggingface](https://huggingface.co/datasets/HAERAE-HUB/KOREAN-WEBTEXT)|
|크기|4.47GB|
|행의 수|1,284,879개|
|토큰 수|약 22억개|
|언어|한국어|
|주요 컬럼|text, source, token_count|


```python
# 다음의 코드를 사용하여 데이터 셋 로드
import datasets

dataset = datasets.load_dataset('HAERAE-HUB/KOREAN-WEBTEXT-1B')
```


전체 데이터 셋의 크기가 너무 커서 모델 학습 과정에선 행의 수를 1만개로 자른 샘플 데이터를 사용하였습니다. 



### 2. 대응 기준



### 3. 실행 결과

<img src="./img/img_1.png" />

<img src="./img/img_2.png" />






# NLP 경진대회
## Team

| ![박패캠](https://avatars.githubusercontent.com/u/156163982?v=4) | ![이패캠](https://avatars.githubusercontent.com/u/156163982?v=4) | ![최패캠](https://avatars.githubusercontent.com/u/156163982?v=4) | ![김패캠](https://avatars.githubusercontent.com/u/156163982?v=4) | ![오패캠](https://avatars.githubusercontent.com/u/156163982?v=4) |
| :--------------------------------------------------------------: | :--------------------------------------------------------------: | :--------------------------------------------------------------: | :--------------------------------------------------------------: | :--------------------------------------------------------------: |
|            [박준수](https://github.com/UpstageAILab)             |            [손은혜](https://github.com/UpstageAILab)             |            [임환석](https://github.com/UpstageAILab)             |            [황은혜](https://github.com/UpstageAILab)             |            [윤소영](https://github.com/UpstageAILab)             |
|                            팀장                             |                            팀원                             |                            팀원                             |                            팀원                             |                            팀원                             |

## 0. Overview
### Environment
Jupyter Notebook

Upstage GPU


### Requirements
* GPU
* Python 3.11

#### Hugging Face Transformer 관련

* transformers>=4.41.0

* accelerate>=0.21.0

## 1. Competiton Info

### Overview

Dialogue Summarization | 일상 대화 요약

학교 생활, 직장, 치료, 쇼핑, 여가, 여행 등 광범위한 일상 생활 하는 대화들에 대해 요약합니다.

### Timeline

2025.11.27 ~ 2025.12.10

## 2. Components

### Directory

- _Insert your directory structure_

e.g.
```
├── code
│   ├── jupyter_notebooks
│   │   └── model_train.ipynb
│   └── train.py
├── docs
│   ├── pdf
│   │   └── (Template) [패스트캠퍼스] Upstage AI Lab 1기_그룹 스터디 .pptx
│   └── paper
└── input
    └── data
        ├── eval
        └── train
```

## 3. Data descrption

### Dataset overview

##### train.csv sample                                               
<img width="400" height="300" alt="image" src="https://github.com/user-attachments/assets/29e93a77-99f3-4186-95d7-e71295bd513d" />      



### EDA

화자 역할 교체 -> #perseon1# #person2# 위치 변경 -> 데이터 수 2배로 늘림

원본(encoder), 요약문(decoder)의 토큰 길이 파악 -> 토큰의 길이에 맞게 하이퍼파라미터 값 조정 

<img width="600" height="500" alt="image" src="https://github.com/user-attachments/assets/a4685d9b-ede0-439a-9f5a-577bfb7de287" />

<img width="600" height="451" alt="image" src="https://github.com/user-attachments/assets/aec85e9e-c70f-45ed-a7b7-ad2077c5d79d" />


### Data Processing

##### 특수문자 및 html 태그 제거
1. 노이즈를 제거하여 모델의 불필요한 과정 생략
2. 의미 없는 기호가 차지하던 자리를 실질적인 단어로 채움
3. 요약문의 정보 밀도 상승
<img width="200" height="600" alt="image" src="https://github.com/user-attachments/assets/ecc2f472-867b-40c8-90e2-411aacc25b60" />


## 4. Modeling

### Model descrition

- _Write model information and why your select this model_

### Modeling Process

- _Write model train and test process with capture_

## 5. Result

### Leader Board

- _Insert Leader Board Capture_
- _Write rank and score_

### Presentation

- _Insert your presentaion file(pdf) link_

## etc

### Meeting Log

- _Insert your meeting log link like Notion or Google Docs_

### Reference

- _Insert related reference_

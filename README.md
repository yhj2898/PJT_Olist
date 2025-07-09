# E‑Commerce Data Analysis

> 본 프로젝트는 Olist가 제공하는 E‑Commerce Public Dataset을 활용하여
이커머스 시장의 다양한 데이터 분석을 수행한 결과물입니다.
> 

---

## [1] 분석 개요

- **분석 질문**: 이 프로젝트를 통해 답을 찾고자 하는 핵심 질문들을 간략히 나열합니다.
    - 어떤 카테고리의 상품이 가장 많이 판매되는가?
    - 주요 고객층은 어느 지역에 분포하고 있는가?
    - 결제 수단과 배송 만족도 사이의 관계는 어떠한가?
- **기대 효과**: 분석을 통해 얻을 수 있는 가치나 활용 방안을 설명합니다.

---

## [2] 주요 분석 결과

분석을 통해 도출한 핵심적인 인사이트와 시각화 자료를 요약하여 보여줍니다.

- **인사이트 1**: 신용카드가 전체 거래의 75%를 차지하며, 할부 개월 수가 높을수록 평균 거래액(transaction value)이 증가하는 경향을 보입니다.
- **인사이트 2**: ...

*<핵심적인 그래프나 차트 이미지를 여기에 삽입하세요>*

![](https://images.unsplash.com/photo-1504868584819-f8e8b4b6d7e3?ixlib=rb-4.1.0&q=85&fm=jpg&crop=entropy&cs=srgb)

<필요시 해당 파일로 넘어가는 링크 걸기>

> 사용 기술
> 

```
- Language: Python 3.11
- Libraries: Pandas, Matplotlib, Seaborn 등
- Environment: Jupyter Notebook
```

## [3] 프로젝트 구조

```
ecommerce-analysis/
├── README.md
├── .gitignore
├── img/
│   ├── insight1.jpg
├── requirements.txt (어려우면 빼기)
├── notebooks/
│   ├── data_merge.ipynb
│   ├── analysis.ipynb
│   └── preprocessing.ipynb
├── src/ # 소스코드, 모듈 -> 안 되면 빼기
│   ├── preprocessing.py
│   └── visualization.py
└── data/   (※ 실제 저장소에는 포함하지 않으며, .gitignore로 관리)
```

- `notebooks/` : 데이터 분석 및 시각화용 Jupyter 노트북
- `src/` : 데이터 전처리, 함수, 시각화 등 파이썬 코드
- `requirements.txt` : 분석에 필요한 Python 패키지 목록

## [4] 데이터셋 안내

이 프로젝트는 데이터 파일을 직접 저장소에 포함하지 않습니다.
데이터셋은 아래 링크를 통해 다운로드하신 후, 로컬 환경의 `data/` 폴더에 직접 저장해 주시기 바랍니다.

- **Dataset:** E‑Commerce Public Dataset by Olist
- **Provider:** Olist (via Kaggle)
- **Original Link:** [Kaggle URL](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
- **License:** [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)

**※ 다운로드 방법**

1. 위의 Kaggle 링크에서 데이터셋을 다운로드합니다.
2. 본인의 로컬 저장소 내에 `data/` 폴더를 생성하고, 압축을 해제한 csv 파일을 해당 폴더에 저장합니다.

---

## [5] 데이터셋 라이선스 및 사용 조건

`CC BY-NC-SA 4.0` 라이선스를 따르므로, 데이터 사용 시 해당 라이선스 규정을 준수해야 합니다. 데이터의 상업적 이용 및 원본 라이선스와 다른 조건의 2차 배포는 금지됩니다.
자세한 사항은 [CC BY-NC-SA 4.0 라이선스 안내](https://creativecommons.org/licenses/by-nc-sa/4.0/)를 참고하시기 바랍니다.

<aside>
🚫

**주의사항**

데이터 파일의 직접적인 배포 및 저장소 내 포함은 금지되어 있습니다. 협업 또는 공유 시 `.gitignore` 파일 내 `data/` 폴더와 데이터 파일 형식이 포함되어 있는지 반드시 확인해 주시기 바랍니다.

</aside>
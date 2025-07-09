# E‑Commerce Data Analysis

> 본 프로젝트는 Olist가 제공하는 E‑Commerce Public Dataset을 활용하여
이커머스 시장의 다양한 데이터 분석을 수행한 결과물입니다.
> 

---

## [1] 분석 개요

- **전제** : 최종 소비자 만족도 하락으로 Olist의 매출이 하락했다.

- **분석 목표**: 물류팀의 입장에서, Olist 매출 하락의 원인을 분석하고 해결방안을 제시한다. 

- **분석 질문**  
    - 배송 지연은 최종 소비자 만족도 하락과 어떤 관계가 있는가?
    - 배송 지연은 어떤 상황에서 발생하는가?
    - 구조적 문제인가? 일시적 이벤트인가?
    - 구조적 문제라면 어디에 중점을 두어 해결방안을 제시할 것인가?
  
- **기대 효과**: Olist 매출 하락을 해결할 구체적인 실행방안을 제시한다. 

---

## [2] 분석 방법

- **우선순위 지역 선정** : 개선이 시급한 지역 2개를 우선적으로 선정
  - 배송 지연율이 10% 이상인 지역 중 최종 소비자 수와 매출액을 각각 50% 가중평균하여 선정
    - 최종 소비자 수 : 장기적 관점에서 시장 크기를 가늠할 수 있는 지표로 선정
    - 매출액 : 현재 시점에서 시장 크기를 가늠할 수 있는 지표로 선정
  
## [3] 주요 분석 결과

- **인사이트 1**: 두 지역 모두 특정 시기에 배송 지연율이 높아지며, 반복되는 원인이 있음
- **인사이트 2**: 두 지역 모두 물류사→최종 소비자 단계에서 병목현상 발생
- **인사이트 3** : 일회성 이벤트가 아닌 구조적 문제로, 운송 방식과 물류 단계에서 시스템적 개선 필요

*<핵심적인 그래프나 차트 이미지를 여기에 삽입하세요>*

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
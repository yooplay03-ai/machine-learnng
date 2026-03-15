
# 📊 Data Visualization & PySpark 학습 포트폴리오

Python 기반 데이터 시각화(Matplotlib, Seaborn, Plotly)와 Apache Spark(PySpark) 분산 처리를 단계적으로 학습한 실습 노트북 모음입니다.

---

## 🗂️ 목차

- [학습 목표](#-학습-목표)
- [기술 스택](#-기술-스택)
- [커리큘럼 구조](#-커리큘럼-구조)
- [노트북 목록](#-노트북-목록)
- [실행 방법](#-실행-방법)

---

## 🎯 학습 목표

- Pandas를 활용한 데이터 로딩, 탐색, 통계 분석 익히기
- Matplotlib / Seaborn / Plotly로 다양한 시각화 기법 구현하기
- 실습 데이터(주식, 붓꽃, 타이타닉, NYC 기온 등)를 통해 EDA 역량 강화
- PySpark를 활용한 대용량 데이터 처리 및 SQL 쿼리 분석 익히기
- 중간/기말 시험 문제를 통한 실전 응용 능력 점검

---

## 🛠️ 기술 스택

| 분류 | 라이브러리 / 도구 |
|------|-----------------|
| 언어 | Python 3.11 |
| 데이터 처리 | Pandas, NumPy |
| 시각화 | Matplotlib, Seaborn, Plotly |
| 분산 처리 | PySpark (Apache Spark) |
| 실행 환경 | Jupyter Notebook / JupyterLab |

---

## 📚 커리큘럼 구조

```
📦 root
 ├── 📂 시각화 실습 (01 ~ 13)
 │    ├── Part 1. Pandas + Matplotlib 기초 (01 ~ 07)
 │    ├── Part 2. 시계열 & Seaborn 심화 (08 ~ 12)
 │    └── Part 3. Plotly 인터랙티브 시각화 (13)
 ├── 📂 PySpark 실습 (Spark_01 ~ 05)
 │    ├── 세션 설정 & 데이터 로드
 │    ├── 필터링 / SQL 쿼리
 │    ├── 문자열 & 타입 전처리
 │    └── 집계 분석 (groupBy / agg / pivot)
 └── 📂 시험 문제 풀이
      ├── Exam_Mid  : 보스턴 집값 통계 시각화
      └── Exam_Final: 타이타닉 종합 전처리 및 분석
```

---

## 📒 노트북 목록

### Part 1 · Pandas & Matplotlib 기초

| # | 파일명 | 주요 내용 |
|---|--------|----------|
| 01 | `01_Pandas_기초_및_주식데이터_시각화` | Pandas DataFrame 기초, 주식 데이터 시각화 |
| 02 | `02_붓꽃데이터_통계_및_박스플롯_분석` | 기술 통계, 박스플롯 기초 |
| 03 | `03_Iris_데이터_추출_및_파이차트_실습` | 조건 필터링, 파이차트 |
| 04 | `04_Matplotlib_함수그래프_시각화_기초` | 수학 함수 그래프, 기본 플롯 설정 |
| 05 | `05_고급_박스플롯_및_라벨링_커스터마이징` | 박스플롯 심화, 라벨·색상 커스터마이징 |
| 06 | `06_다중_그래프_레이아웃_및_피규어_설정` | subplot 레이아웃, figure 설정 |
| 07 | `07_Polar_Plot_및_랜덤데이터_시각화` | 극좌표계 플롯, 난수 데이터 시각화 |

### Part 2 · 시계열 & Seaborn 심화

| # | 파일명 | 주요 내용 |
|---|--------|----------|
| 08 | `08_NYC_기온데이터_시계열_분석_기초` | 시계열 플롯, NYC 실제 기온 데이터 |
| 09 | `09_Seaborn_Relplot_관계형_시각화` | relplot, scatterplot, lineplot |
| 10 | `10_Seaborn_Catplot_범주형_데이터분석` | catplot, barplot, violinplot |
| 11 | `11_Titanic_생존율_분석_및_막대그래프` | 타이타닉 EDA, 생존율 분석 |
| 12 | `12_Jointplot_결합_및_Hex_밀도분석` | jointplot, hexbin 밀도 시각화 |

### Part 3 · Plotly 인터랙티브

| # | 파일명 | 주요 내용 |
|---|--------|----------|
| 13 | `13_Plotly_인터랙티브_동적_시각화` | Plotly Express, 인터랙티브 차트 |

### PySpark 실습

| # | 파일명 | 주요 내용 |
|---|--------|----------|
| S01 | `Spark_01_세션설정_및_데이터_로드` | SparkSession 생성, CSV/JSON 읽기, Schema 지정 |
| S02 | `Spark_02_FIFA_데이터_필터링_및_조회` | select, orderBy, where, isin |
| S03 | `Spark_03_FIFA_데이터_SQL_쿼리분석` | createOrReplaceTempView, Spark SQL |
| S04 | `Spark_04_YouTube_문자열_및_타입전처리` | 문자열 함수, timestamp 변환, 열 추가 |
| S05 | `Spark_05_에어비앤비_데이터_집계분석` | groupBy, agg, pivot |

### 시험 풀이

| 파일명 | 내용 |
|--------|------|
| `Exam_Mid_보스턴집값_통계시각화_솔루션` | 중간고사 - 보스턴 집값 데이터 통계 및 시각화 |
| `Exam_Final_타이타닉_종합전처리_및_분석` | 기말고사 - 타이타닉 데이터 전처리 + 종합 분석 |

---

## ▶️ 실행 방법

### 1. 환경 준비

```bash
# 저장소 클론
git clone https://github.com/your-username/your-repo.git
cd your-repo

# 가상환경 생성 (선택)
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# 필수 라이브러리 설치
pip install pandas numpy matplotlib seaborn plotly jupyter
```

### 2. PySpark 추가 설치 (Spark 실습용)

```bash
pip install pyspark

# 환경변수 설정 (로컬 실행 시 필요)
# Windows
set SPARK_LOCAL_IP=localhost

# Mac / Linux
export SPARK_LOCAL_IP=localhost
```

> ⚠️ PySpark는 Java 8 이상이 필요합니다. [Java 설치 링크](https://adoptium.net/)

### 3. Jupyter 실행

```bash
jupyter notebook
# 또는
jupyter lab
```

---

## 📝 사용 데이터셋

| 데이터 | 출처 / 설명 |
|--------|------------|
| 주식 데이터 | 직접 생성 / Yahoo Finance |
| Iris (붓꽃) | scikit-learn 내장 데이터셋 |
| Titanic | Seaborn 내장 / Kaggle |
| NYC 기온 | 공개 기상 데이터 |
| FIFA 선수 | Kaggle FIFA Dataset |
| YouTube | Kaggle YouTube Trending |
| Airbnb | Inside Airbnb |
| Boston 집값 | scikit-learn 내장 데이터셋 |

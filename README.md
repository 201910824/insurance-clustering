# 보험사 고객 군집화 프로젝트

## 📌 프로젝트 목적
보험사 고객 데이터를 분석하여 유사한 고객 군집을 도출하고, 각 군집에 맞는 마케팅 전략을 수립하는 것이 목표입니다.

## 📊 데이터 전처리
- 교육수준, 고용상태, 등록자 유형 등 범주형 변수 인코딩
- 숫자형 변수 스케일링
- 이상치 및 결측치 처리

## 🤖 클러스터링
- 알고리즘: KMeans
- 최적 k값 도출: 엘보우 기법 사용
- inertia 기반 분석

## 📈 분석 결과
- 7개의 군집 도출
- 각 군집별 고객 특성 분석 (예: 고용 안정적, 고소득, 도시근교 거주 등)
- 마케팅 전략 수립 (예: 설계사 중심 접근, 고급 상품 추천, 갱신 인센티브 제공 등)

## 🛠 사용 기술
- Python
- pandas, numpy, matplotlib, seaborn
- sklearn (KMeans, StandardScaler)

## 📂 프로젝트 구조
insurance-clustering/
├── data/                         
│   └── customers_seg.csv                
│   └── data_sc.csv   
│   └── result.csv              
│
├── notebook/                      
│   └── 1. 데이터분석.ipynb  
│   └── 2. 데이터 전처리.ipynb 
│   └── 3. 군집 분석.ipynb 
│
├── requirement.txt/                       
│
├── README.md 
│
├── presentation/
│   └── insurance_clustering_summary.pptx                      



## 🔍 주요 결과 요약

- 7개의 군집으로 분류
- 각 군집의 구매력, 교육 수준, 지역, 선호 상품 등 특성 분석 완료
- 클러스터별 맞춤 마케팅 전략 제시

## 📈 마케팅 전략 예시

> 예: "고소득 석·박사 그룹은 온라인 채널 기반 고급 보장형 상품 마케팅"

## 📊 발표 자료

👉 [보험사 고객 군집화 프로젝트 발표자료 (PPTX)](./presentation/insurance_clustering_summary.pptx)


## 🙌 작성자

- GitHub: [201910824](https://github.com/201910824)

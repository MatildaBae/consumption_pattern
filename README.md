# Developing CBTI (Consumption Behavior Type Indicator) for Single-Person Households in Their 20s

**Excellence Award (2nd Place), Statistics Korea Utilization Contest, Statistics Korea**  
*August 2023*

## Overview

Welcome to the repository of the project "Developing CBTI (Consumption Behavior Type Indicator) for Single-Person Households in Their 20s". This project, awarded the Excellence Award (2nd Place) in the Statistics Korea Utilization Contest, focuses on analyzing the consumption patterns of youth using advanced clustering techniques.

---

## Features

### 🔍 Clustering Analysis

- **K-means Clustering**: Formed 8 clusters in a 6-dimensional space to segment youth consumption patterns.
- **Hierarchical Clustering**: Constructed dendrograms to understand the relationships between clusters.

### 📉 Dimensionality Reduction

- **t-SNE**: Applied t-SNE for effective dimensionality reduction of non-linear data, making it easier to visualize and interpret the clusters.

### 📊 Detailed Comparisons

- **Demographic Variables**: Conducted detailed comparisons among clusters based on demographic variables, revealing significant factors influencing consumption trends.

---

## Project Structure

### 1. Data Collection and Preparation

- **Data Source**: Household Trend Survey annual data from MDIS for the years 2020 to 2022.
- **Target Group**: Extracted data for single-person households with heads aged between 20 and 30 years.

### 2. Clustering Process

- **K-means Clustering**: Set the number of clusters to 8 and used Python’s sklearn.cluster module.
- **Dimensionality Reduction**: Used t-SNE for reducing the dimensionality of the data to 2D for visualization.

### 3. Analysis and Visualization

- **Dendrograms**: Constructed using hierarchical clustering to show the similarity between clusters.
- **Silhouette Coefficient**: Evaluated the clustering quality with the silhouette coefficient, achieving a value of 0.83 for 8 clusters.

---

## Results and Insights

- **Cluster Characteristics**: Identified unique characteristics and consumption patterns for each cluster.
- **Significant Factors**: Found significant demographic factors that influence youth consumption trends.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- Team members: Juyeon Choi, Jiwon Bae, Sehun Lee
- Statistics Korea for the data and support

---

# 더 나은 20대 1인 가구 소비생활을 위한 CBTI(소비유형지표) 구축하기

**우수상 (2등), 통계청 통계활용대회, 통계청**  
*2023년 8월*

## 개요

20대 소비 패턴 분석 프로젝트 리포지토리에 오신 것을 환영합니다. 이 프로젝트는 통계청 통계활용대회에서 우수상(2등)을 수상하였으며, 첨단 군집화 기법을 사용하여 20대의 소비 패턴을 분석하는 데 중점을 두고 있습니다.

---

## 기능

### 🔍 군집 분석

- **K-means 클러스터링**: 6차원 공간에서 8개의 클러스터를 형성하여 20대 소비 패턴을 세분화하였습니다.
- **계층적 군집 분석**: 덴드로그램을 구성하여 클러스터 간의 관계를 이해하였습니다.

### 📉 차원 축소

- **t-SNE**: 비선형 데이터를 효과적으로 차원 축소하여 클러스터를 시각화하고 해석하기 쉽게 만들었습니다.

### 📊 상세 비교

- **인구 통계 변수**: 인구 통계 변수를 기반으로 클러스터 간 상세 비교를 수행하여 소비 경향에 영향을 미치는 중요한 요인을 밝혀냈습니다.

---

## 프로젝트 구조

### 1. 데이터 수집 및 준비

- **데이터 출처**: MDIS의 가계동향조사 연간 데이터(2020-2022년).
- **대상 그룹**: 가구주 연령이 20세 이상 30세 미만인 1인 가구 데이터를 추출하였습니다.

### 2. 군집화 과정

- **K-means 클러스터링**: 군집 수를 8개로 설정하고 Python의 sklearn.cluster 모듈을 사용하였습니다.
- **차원 축소**: 데이터를 2차원으로 축소하기 위해 t-SNE를 사용하였습니다.

### 3. 분석 및 시각화

- **덴드로그램**: 계층적 군집 분석을 통해 클러스터 간의 유사성을 나타내는 덴드로그램을 구성하였습니다.
- **실루엣 계수**: 클러스터링 품질을 평가하기 위해 실루엣 계수를 사용하여 8개의 클러스터에서 0.83의 값을 달성하였습니다.

---

## 결과 및 인사이트

- **클러스터 특성**: 각 클러스터의 고유한 특성과 소비 패턴을 식별하였습니다.
- **중요 요인**: 20대 소비 경향에 영향을 미치는 중요한 인구 통계 요인을 발견하였습니다.

---

## 라이센스

이 프로젝트는 MIT 라이센스 하에 라이센스됩니다. 자세한 내용은 [LICENSE](LICENSE) 파일을 참조하세요.

---

## 감사 인사

- 팀원: 최주연, 배지원, 이세훈
- 데이터와 지원을 제공해 준 통계청

---


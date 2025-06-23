# Price Trend AI - 부동산 가격 예측 서비스
<br>

## 프로젝트 개요
- **프로젝트명**: Price Trend AI
- **진행 기간**: 2025.06.06 ~ 2025.06.13
- **목표**: 공공 데이터를 크롤링하여 조건에 맞는 부동산 시세를 수집하고, 이를 기반으로 향후 1년간의 가격을 AI로 예측해 그래프로 시각화합니다.
<br>

## 프로젝트 소개
부동산 시장은 정책, 금리, 소비자 심리, 공급량 등 다양한 요인에 따라 복합적으로 변동되기 때문에 완벽한 예측은 어렵습니다.<br>
본 프로젝트는 이러한 한계를 인식하고, 과거 데이터를 기반으로 향후 1년 이내의 시세 흐름을 예측하고 시각화 하는 데 중점을 두었습니다.<br>
예측에는 Meta의 Prophet 기반의 시계열 모델을 활용했습니다. 
<br><br>
사용자는 지역, 면적, 거래유형을 기준으로 부동산 시세 정보를 조회할 수 있으며, 예측 결과는 시계열 그래프 형태로 직관적으로 제공됩니다. 
<br><br>
또한, 네이버 부동산의 공식 API가 제공되지 않기 때문에 웹 크롤링 방식으로 데이터를 수집하였으며,<br>
배포는 구조상 제한이 있어 로컬 환경에서의 시연을 중심으로 구성했습니다. 

<br>

## 주요 기능
### 검색 기능  
<div align="center">
  <img src="https://github.com/user-attachments/assets/da8daade-c7e5-4ff1-8473-904c88c1d0b5" width="900"/>
</div>

### 상세 정보 모달 표시  
<div align="center">
  <img src="https://github.com/user-attachments/assets/09ab843f-010e-434f-a6ce-e96aed5aae37" width="900"/>
</div>

### AI 시세 예측 결과 시각화  
<div align="center">
  <img src="https://github.com/user-attachments/assets/d5d2fc75-7bfe-4275-8c4b-93772f06d193" width="900"/>
</div>

### 검색 기록 확인  
<div align="center">
  <img src="https://github.com/user-attachments/assets/1e69a6d7-33f5-41b5-b423-f649ee7f2d53" width="900"/>
</div>

### 다크모드  
<div align="center">
  <img src="https://github.com/user-attachments/assets/7a5308ef-364d-4230-a71b-d94b6c09ea5c" width="900"/>
</div>
<br>

## 기술 스택

| 구분        | 기술                                                     |
|-------------|----------------------------------------------------------|
| 언어        | TypeScript, Python                                       |
| 프론트엔드  | React, Vite, TailwindCSS, Recharts                      |
| 백엔드      | FastAPI, SQLAlchemy, MySQL, Selenium                     |
| AI/ML       | Prophet (시계열 예측 모델)                               |
<br>

## 팀원

| 이름 | 역할 | 주요 담당 |
|------|------|-----------|
| 양유나 | 프론트엔드 | UI 구현, 상태관리 |
| 이예준 | 백엔드 | API 설계, FastAPI 구성 |
| 어영민 | AI/ML | 예측 모델 설계 및 구현 |

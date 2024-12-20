# 교필코딩 팀 프로젝트

## 변수 설명

### DataFrames
- **df1**: 시군구별, 성별, 연령군별 치매환자 통계 데이터
- **df2**: 경찰청 연도별 실종 및 가출 현황 데이터

### Indexes and Data Subsets
- **age_idx**: 연령군별 인덱스 (10세 단위로 구분하여 99세까지 존재)
- **age_df1**: `df1`에서 나이대별로 분리한 데이터

## 분석 목표 및 주요 지표

1. **연령군별 전체 환자 수** (O)
   - `df1` 데이터를 사용하여 각 연령군별로 전체 치매 환자 수를 계산합니다.

2. **연령군별 입내원 평균 일수** (O)
   - 각 연령군별 입내원 일수를 평균하여 분석합니다.

3. **연령군별 비용 평균**
   - 각 연령군별 치매 환자의 비용 평균을 계산합니다.

4. **시도별 전체 환자 수** (O)
   - `df1` 데이터를 사용하여 시도별로 전체 치매 환자 수를 집계합니다.

5. **시도별 입내원 평균 일수** (O)
   - 시도별 평균 입내원 일수를 계산하여 지역별 치매 환자의 평균 입내원 기간을 분석합니다.

6. **시도별 비용 총액** (O)
   - 시도별 전체 비용을 집계하여 치매 환자 치료에 대한 비용 분포를 파악합니다.

7. **성별 환자 수** (O)
   - 성별로 전체 환자 수를 분리하여 남녀 간 치매 환자 수 차이를 분석합니다.

---

### 추가 참고사항
- `df1`에서 연령대와 시도, 성별, 비용 등의 다양한 지표를 활용하여 심층적인 분석을 수행할 수 있습니다.
- `df2`의 경찰청 실종 및 가출 데이터를 추가 분석에 활용할 수 있으며, 이는 치매 환자의 실종 위험 요소와의 상관관계를 파악하는 데 도움이 될 수 있습니다.

### 파일 설명
- **main.ipynb**: 주요 분석을 진행하는 코드가 포함된 Jupyter Notebook 파일.
- **건강보험심사평가원_시군구별 성별 연령군별 치매진료 통계 2023.csv**: 치매환자 통계 데이터.
- **경찰청_연도별 실종아동등 가출인 접수 및 해제현황_20231231.csv**: 실종 및 가출 현황 데이터.

---







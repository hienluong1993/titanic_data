# 🚢 타이타닉 생존자 데이터 탐색 및 실시간 예측

**Streamlit** 기반의 **타이타닉 데이터 EDA 및 생존 여부 실시간 예측**을 위한 깔끔하고 직관적인 앱입니다.

---

## 📌 주요 기능

✅ **EDA (탐색적 데이터 분석):**
- **성별, 좌석 등급, 나이 범위**에 따른 필터링
- 필터 조건에 따른 **실시간 생존 확률 표시**
- 데이터 테이블, 기술 통계, 시각적 분석 제공

✅ **시각화:**
- Countplot: 성별, 좌석 등급, 출발항 vs 생존 여부
- KDE Plot: 나이, 운임 vs 생존 여부
- 각 차트 하단에 인사이트 텍스트 표시

✅ **실시간 ML 예측:**
- 사용자 입력:
  - 성별
  - 나이
  - 좌석 등급
  - 운임
  - 출발항
- 버튼 클릭 시 **생존/사망 여부 및 생존 확률 예측**
- **Logistic Regression** 모델을 사용하여 훈련 및 예측

✅ **데이터 다운로드:**
- 필터링된 데이터를 **CSV 파일로 다운로드** 가능

---

## 🛠️ 설치 및 환경

- Python 3.8 이상
- 필요 라이브러리:
  - `streamlit`
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`
  - `numpy`

필요 라이브러리 설치:
```bash
pip install streamlit pandas matplotlib seaborn scikit-learn numpy

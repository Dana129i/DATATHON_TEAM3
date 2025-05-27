![프로젝트 배너](https://file.nexon.com/NxFile/download/FileDownloader.aspx?oidFile=5485424096059594172)

## 📌 브랜치명: `Jaehong`

데이터톤 프로젝트를 위한 개인 작업 및 팀 협업 산출물이 포함된 브랜치입니다.  

---

## 📁 브랜치 주요 구성 요소 설명

#### `streamlit/`
- 딥러닝 기반 추천 모델의 출력 파일 및 유저 전투력 데이터 파일들을 저장합니다.
  - 예: `best_model.pt`, 유저 벡터 `.npy`, 프로파일 `.pkl` 등
- Streamlit 앱의 시뮬레이션 탭에서 **추천 시스템 출력**으로 활용됩니다.
- 또한 장비 추천 탭에서 **유저 전투력 데이터**로 활용됩니다.

---

## 📘 주요 노트북 파일 설명

#### 📄 `DataThon_JSON.ipynb`
- Open API를 활용한 **데이터 수집 및 병합 자동화** 코드입니다.
- JSON 응답 파싱, 데이터 단순화, CSV 병합 등 작업이 포함됩니다.

#### 📄 `DataThon_EDA1,2.ipynb`
- 수집된 데이터를 기반으로 한 **EDA 및 추론 통계 분석 노트북**입니다.
- 개인 가설 설정 → 통계 분석 검정 수행

#### 📄 `DataThon_ML1,2.ipynb`
- 결측치 처리, 파생변수 생성 등 **데이터 전처리**
- Kmeans, DBSCAN 등 머신러닝 모델 학습 및 성능 비교

#### 📄 `app.ipynb`
- Streamlit을 구현하기 위한 통합코드입니다.
- 캐릭터 정보, 장비 추천, 시뮬레이션 탭으로 구성

#### 📄 `requirements.txt`
- Streamlit을 구동하기 위한 모듈 버전

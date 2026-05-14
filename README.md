작업 환경
```
DataMining-Project/
├── data/                  # [공통] 데이터 보관
│   ├── raw/               # 원본 데이터 (수정 금지)
│   └── processed/         # 전처리가 완료된 공통 데이터
├── notebooks/             # [분리] 각자 작업하는 공간
│   ├── bcy/               # 백찬열 (예: Random Forest 실험)
│   ├── lgh/               # 이기현 (예: XGBoost 실험)
│   └── lsj/               # 이성진 (예: Deep Learning 실험)
├── models/                # [공통/분리] 학습된 모델 저장
│   ├── bcy_A_rf.pkl
│   ├── lgh_B_xgb.pkl
│   └── lsj_C_dl.h5
├── src/                   # [선택] 공통으로 사용하는 함수 (데이터 로드 등)
│   └── utils.py
├── reports/               # [공통] 최종 비교 결과 및 그래프
├── README.md              # 프로젝트 설명 및 역할 분담
└── requirements.txt       # 공통 라이브러리 목록
```
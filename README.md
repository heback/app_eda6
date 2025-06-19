# app_eda6

Streamlit 기반의 웹 애플리케이션으로 Firebase 인증을 통해 로그인과 회원가입을 제공하며,
Bike Sharing Demand 데이터를 탐색하는 EDA 기능을 포함합니다.

## 주요 기능
- 이메일 기반 로그인/회원가입 및 비밀번호 재설정
- 사용자 프로필 수정 및 이미지 업로드
- `train.csv` 파일 업로드 후 데이터 구조 확인
- 시각화, 상관관계 분석, 이상치 제거, 로그 변환 등 기본 EDA 워크플로우 제공

## 실행 방법
```bash
pip install -r requirements.txt
streamlit run app_eda.py
```


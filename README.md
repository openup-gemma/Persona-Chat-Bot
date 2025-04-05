Persona-Chat-Bot

프로젝트 개요

Persona-Chat-Bot은 다양한 페르소나(성격, 역할, 배경 등)를 지닌 AI 챗봇을 개발하는 프로젝트입니다.
사용자가 직접 설정할 수 있는 AI 캐릭터를 제공하며, 다양한 분야(예: 운동 트레이너, 재무 상담사, 셰익스피어 스타일 AI)에서 활용될 수 있습니다.

주요 기능

페르소나 프로파일링: 다양한 인물 및 가상 캐릭터의 성격, 대화 스타일을 반영

대화 데이터 수집 및 전처리: 각 페르소나에 맞는 대화 데이터를 수집하고 Fine-Tuning 적용

Gemma 모델 활용: 페르소나 기반 AI 캐릭터의 대화 생성 최적화

감정 및 상황 인식: AI가 맥락을 이해하고 감정을 반영한 대화 제공

멀티모달 인터페이스: 텍스트뿐만 아니라 애니메이션, 아바타, 음성 지원

프로젝트 구조

Persona-Chat-Bot/
│── Financial Advisor Jay.ipynb  # 재무 상담 AI 챗봇
│── Health_Trainer_Jay.ipynb  # 건강 트레이너 AI 챗봇
│── Health_Trainer_Jay_2.ipynb  # 추가 건강 트레이너 챗봇
│── test_gemma_2B.ipynb  # Gemma 모델 테스트
│── temp.ipynb  # 임시 테스트 파일
│── 윌리엄_셰익스피어_Persona20240516.ipynb  # 셰익스피어 스타일 챗봇
│── README.md  # 프로젝트 설명 파일

설치 및 실행 방법

필수 라이브러리 설치

pip install -r requirements.txt

Jupyter Notebook 실행

jupyter notebook

원하는 페르소나 노트북 실행

Financial Advisor Jay.ipynb

Health_Trainer_Jay.ipynb

윌리엄_셰익스피어_Persona20240516.ipynb

API 사용 방법 (추가 예정)

현재 Jupyter Notebook 기반 프로젝트로, 추후 API 연동 기능이 추가될 예정입니다.

필요 라이브러리

pandas

transformers

torch

jupyter

matplotlib

기여 방법

본 레포지토리를 포크합니다.

새로운 브랜치를 생성합니다.

변경 사항을 커밋하고 푸시합니다.

Pull Request를 생성하여 기여합니다.

라이선스

이 프로젝트는 MIT 라이선스를 따릅니다.


# 영상 인식을 활용한 실시간 꿀벌 보호 시스템 🐝

**프로젝트 개요**  
이 프로젝트는 딥러닝을 활용한 말벌 탐지 시스템을 개발하여 말벌 침입으로 인한 위험을 예방하는 것을 목표로 합니다. 
말벌을 실시간으로 모니터링하고 알림 시스템을 통해 사용자에게 경고 메시지를 전달하는 기능을 포함합니다.

---

## 📌 주요 기능
- **실시간 말벌 감지**: 딥러닝 모델(CNN)을 사용해 카메라에서 수집된 영상을 분석하여 말벌을 실시간으로 탐지합니다.
- **알림 전송**: 말벌이 감지되면 사용자에게 즉시 경고 알림을 전송합니다.
- **데이터 저장**: 탐지된 말벌의 데이터를 기록하여 모델 정확도를 향상 시킵니다.

---

## 📂 프로젝트 구조
```bash
project-root/
│
├── src/                   # 소스 코드 저장 폴더
│   └── main.py            # 메인 프로그램 파일
│
├── doc/                   # 문서 저장 폴더
│   └── proposal.pdf       # 프로젝트 제안서 파일
│
└── README.md              # 프로젝트 설명 파일
```

---

## 🚀 설치 및 사용 방법
1. 저장소 클론
```
[git clone https://github.com/username/wasp-monitoring.git
cd wasp-monitoring](https://github.com/hyeonwooCH/OpenSource.git)
```

2. 필요한 패키지 설치
```
pip install opencv-python
```

3. 모델 학습
```
python src/train.py --data ./data/dataset.csv
```

4. 실시간 모니터링 실행
```
python src/monitor.py --camera 0
```

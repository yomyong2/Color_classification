# 🎨 색맹을 위한 인공지능 색상 분류기

> 이 프로젝트는 색맹을 가진 사람들을 위해 개발된 **모바일 전용 인공지능 색상 인식 웹앱**입니다.  
> 사용자의 스마트폰 카메라로 실시간으로 촬영된 이미지를 기반으로 주요 색상을 분류하고 시각적으로 표현합니다.

---

## 🧠 주요 기능

- 📷 **실시간 색상 인식** (TensorFlow.js + Teachable Machine)
- 🎨 빨강, 주황, 노랑, 초록, 파랑, 보라, 핑크, 갈색 총 8가지 색상 지원
- 📊 각 색상별 확률 막대로 시각화
- 🏷 가장 높은 확률의 색상을 상단에 텍스트로 표시
- 📱 **모바일 전용 웹앱** (PC 접속 시 리디렉션됨)

---

## 🌐 사용 방법

1. 이 저장소를 클론하거나 다운로드합니다.
2. `index.html` 파일을 모바일 브라우저로 엽니다.
3. 카메라 접근 권한을 허용합니다.
4. 실시간으로 인식된 색상과 확률이 표시됩니다.

> 📌 이 웹페이지는 **모바일 환경에서만 작동**합니다. 데스크탑 환경에선 접속 시 리디렉션됩니다.

---

## 🧾 폴더 구조

```
Color_classification/
│
├── index.html            # 메인 웹 페이지
├── my_model/             # Teachable Machine에서 내보낸 모델 폴더
│   ├── model.json
│   ├── metadata.json
│   └── ...
└── README.md             # 프로젝트 설명 파일
```

---

## 🛠 기술 스택

- HTML5, CSS3, JavaScript (Vanilla)
- [TensorFlow.js](https://www.tensorflow.org/js)
- [Teachable Machine](https://teachablemachine.withgoogle.com/) 이미지 모델
- 모바일 웹 브라우저 (Chrome, Safari 등)

---

## 📦 배포 방법

GitHub Pages 또는 Netlify 등 정적 웹 호스팅 서비스를 통해 배포할 수 있습니다.

### GitHub Pages 예시:

```bash
git clone https://github.com/your-username/color-ai.git
cd color-ai
# index.html과 my_model 폴더 포함
# GitHub에서 Pages 기능 활성화 (main 브랜치 / root 경로)
```

---

## 📌 참고

- 모델은 `my_model/` 폴더에 위치해야 하며, `model.json`과 `metadata.json`이 포함되어야 합니다.
- Teachable Machine에서 이미지 모델을 내보내면 해당 폴더 구조가 자동으로 생성됩니다.


---

## 📄 라이선스

이 프로젝트는 MIT 라이선스를 따릅니다. 자유롭게 사용 및 수정 가능합니다.

# 🌱 PlantParent - Indoor Plant Care Dashboard

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)](https://tailwindcss.com)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Gemini](https://img.shields.io/badge/Gemini_API-8E75C2?style=flat-square&logo=googlegemini&logoColor=white)](https://ai.google.dev/)

> **"Nurtured Growth" (식물의 성장과 마음의 치유를 위한 동반자)**
> 
> **PlantParent**는 현대 도시 생활 속에서 반려식물을 가꾸는 사람들을 위한 감성적이고 직관적인 실내 식물 관리 대시보드 웹 서비스입니다. 
> 복잡하고 딱딱한 디지털 인터페이스에서 벗어나 자연과 교감하는 평온한 감성을 전달하며, 체계적인 관리 도구와 AI 전문가 비서를 통해 반려식물이 건강하게 자랄 수 있도록 돕습니다.

<br>

---

## 📸 주요 화면 (Screenshots)

GitHub 리포지토리에서 바로 확인하실 수 있는 주요 대시보드 화면입니다.

<table width="100%">
  <tr>
    <td width="50%" align="center">
      <b>🌿 메인 대시보드 개요 (Overview)</b>
      <br/>
      <img src="plant_care_dashboard_overview/screen.png" alt="Overview" width="100%" style="border-radius: 12px; margin-top: 8px;"/>
    </td>
    <td width="50%" align="center">
      <b>💧 물주기 일정 관리 (Watering Schedule)</b>
      <br/>
      <img src="watering_schedule/screen.png" alt="Watering Schedule" width="100%" style="border-radius: 12px; margin-top: 8px;"/>
    </td>
  </tr>
  <tr>
    <td width="50%" align="center">
      <b>☀️ 일조량 가이드 (Sunlight Tracker)</b>
      <br/>
      <img src="sunlight_tracker_guide/screen.png" alt="Sunlight Tracker" width="100%" style="border-radius: 12px; margin-top: 8px;"/>
    </td>
    <td width="50%" align="center">
      <b>🧪 비료 주기 알림 (Fertilization Reminders)</b>
      <br/>
      <img src="fertilization_reminders/screen.png" alt="Fertilization Reminders" width="100%" style="border-radius: 12px; margin-top: 8px;"/>
    </td>
  </tr>
</table>

<br>

---

## ✨ 핵심 기능 (Key Features)

### 1. **My Collection (Overview)**
- **Nurture Today**: 오늘 당장 관리가 필요한 식물(물주기, 거름주기 등)을 모아보고 완료 여부를 체크할 수 있습니다.
- **My Collection Bento Grid**: Snake Plant, Peace Lily, Bird of Paradise 등 키우고 있는 다양한 식물의 수분율과 조도 상태를 비주얼 카드 형태로 한눈에 보여줍니다.
- **PlantParent AI 비서**: 대시보드 우측 하단의 플로팅 아이콘을 통해 식물 의사 AI 비서와 실시간 대화를 나눌 수 있습니다. 질문에 답변하기 위해 **Gemini API**를 활용하며, 사용자의 브라우저 로컬 스토리지에 API Key를 안전하게 보관하여 유연하게 동작합니다.

### 2. **Watering Schedule**
- 식물들의 수분 관리 주기를 캘린더 및 타임라인 뷰로 체계적으로 관리합니다.
- 토양 수분 센서 데이터(가상)와 연동하여 물을 줄 시기를 놓치지 않도록 직관적인 UI 피드백을 제공합니다.

### 3. **Sunlight Tracker**
- 실내 채광 수준(Bright Direct, Indirect, Low Light 등)에 따라 적합한 식물 배치 공간을 안내합니다.
- 식물들의 빛 요구량과 일조 시간 통계를 추적하여 최적의 생육 환경을 가이드합니다.

### 4. **Fertilization Reminders**
- 계절과 생장 주기에 맞춘 영양제 및 비료 시비 일정을 기록하고 알림을 설정합니다.

<br>

---

## 🎨 디자인 철학 & 시스템 (Design Identity)

본 프로젝트는 **Contemporary Organic Minimalism (현대적 유기적 미니멀리즘)** 스타일을 표방합니다. 자세한 설계 가이드는 [`botanical_essence/DESIGN.md`](./botanical_essence/DESIGN.md)에서 확인하실 수 있습니다.

* **Color Palette (자연에서 영감을 얻은 색감)**:
  * <img src="https://via.placeholder.com/15/163826/000000?text=+" alt="Primary Color"/> **Forest Green (`#163826`)**: 자연의 안정감을 선사하는 메인 브랜드 컬러.
  * <img src="https://via.placeholder.com/15/964824/000000?text=+" alt="Secondary Color"/> **Terracotta Orange (`#964824`)**: 토분의 따뜻함을 품은 포인트 컬러.
  * <img src="https://via.placeholder.com/15/F9F7F2/000000?text=+" alt="Background Color"/> **Neutral Cream (`#F9F7F2`)**: 종이 질감의 편안한 바탕을 제공하여 눈의 피로를 감소.
* **Typography**:
  * **Noto Serif**: 식물 이름 및 주요 헤드라인에 편집숍 매거진 같은 클래식하고 고급스러운 권위를 부여.
  * **Be Vietnam Pro**: 데이터와 라벨, 본문 텍스트에 친근하고 현대적인 가독성을 보장.
* **UI Elements**:
  * 날카로운 모서리 대신 식물의 부드러운 잎사귀를 닮은 둥근 모서리(`rounded-xl`) 및 스크롤 시 뒤쪽 식물 이미지가 은은하게 투영되는 유리모프(Glassmorphism) 네비게이션 바 적용.

<br>

---

## 📁 프로젝트 구조 (Project Structure)

```bash
stitch_indoor_plant_care_dashboard/
├── index.html                           # 진입 페이지 (Overview로 자동 리다이렉트)
├── plant_care_dashboard_overview/       # 메인 대시보드 개요 모듈
│   ├── code.html                        # 대시보드 화면 및 AI 챗봇 탑재
│   └── screen.png                       # 스크린샷 이미지
├── watering_schedule/                   # 물주기 스케줄 모듈
│   ├── code.html
│   └── screen.png
├── sunlight_tracker_guide/              # 일조량 가이드 모듈
│   ├── code.html
│   └── screen.png
├── fertilization_reminders/             # 비료 알림 모듈
│   ├── code.html
│   └── screen.png
├── plantparent_care_dashboard/          # 추가 케어 대시보드
│   └── code.html
└── botanical_essence/                   # 디자인 시스템 정의 디렉토리
    └── DESIGN.md                        # 디자인 상세 명세서
```

<br>

---

## ⚙️ 시작하기 및 사용 방법 (How to Start)

1. 이 리포지토리를 로컬 환경에 클론합니다.
   ```bash
   git clone https://github.com/parkwonminn/Vibecoading1234.git
   ```
2. 루트 디렉토리의 `index.html`을 브라우저에서 실행하거나, 개발 서버(Live Server 등)를 통해 열어줍니다.
3. **AI 비서 활용법**:
   * 대시보드 화면 우측 하단의 로봇 아이콘을 클릭합니다.
   * 우측 상단의 **열쇠(key) 아이콘**을 클릭하여 본인의 **Gemini API Key**를 입력 후 저장합니다.
   * 이후에는 로컬에 저장된 키를 기반으로 식물 관리에 대해 AI 비서와 자유롭게 묻고 답할 수 있습니다.

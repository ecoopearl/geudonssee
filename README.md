# 🚗 그돈씨? (Geudonssee)
> **AI 기반 자동차 트림·옵션 가성비 판독 및 소득 대비 유지비 검증 서비스**

## 📌 프로젝트 소개
현대/기아 및 독일 3사(BMW, Benz, Audi)의 전 차종을 대상으로, 불필요한 고가 옵션(옵션질)을 필터링하고 연소득 대비 유지비 적합성을 판정해 주는 웹 애플리케이션입니다.

## ✨ 주요 기능
- **차급 역전 경고**: 하위 차급 풀옵션 가격이 상위 차급 기본 가격과 겹칠 때 "그돈씨!" 경고 발동
- **옵션 가성비 판정**: 중고차 감가 방어율 및 실용성에 기반한 '적합!' / '그돈씨?' 뱃지 부여
- **정밀 유지비 계산**: 취등록세(7%), 자동차세, 유류비, 보험료 및 할부금을 소득과 대조해 안전/주의/위험 신호등 표시
- **Gemini AI 연동**: Google AI Studio API를 활용한 실시간 맞춤 구매 총평 제공

## 🛠 사용 기술
- **Frontend**: HTML5, CSS3, JavaScript (Vanilla JS)
- **AI Engine**: Google Gemini Flash via Google AI Studio API
- **Data**: JSON 기반 제조사별 트림/옵션 카탈로그
- **Deployment**: GitHub Pages

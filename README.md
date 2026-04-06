# 📈 AI Quant Desk - Portfolio Manager & Advisor

단일 HTML 파일로 동작하는 초경량 주식 포트폴리오 관리 도구이자 Google Gemini 기반 AI 투자 상담사 애플리케이션입니다.

## ✨ 주요 기능
- **포트폴리오 대시보드:** 보유 주식의 매수 단가, 수량, 현재가를 기반으로 한 실시간 손익 및 수익률 자동 계산
- **AI 맞춤 상담 (Gemini 2.0 Flash):** 사용자의 포트폴리오 데이터를 시스템 프롬프트에 자동으로 주입하여, 맥락을 파악하고 개인화된 대답을 제공하는 AI 채팅
- **서버리스 & 영속성:** `localStorage`를 활용하여 백엔드/DB 없이 브라우저 내에서만 프라이빗하게 데이터 영구 보관 보장
- **100% Client-Side:** 복잡한 Node.js 빌드 과정 없이 `stock-portfolio.html` 단일 파일만으로 언제 어디서든 작동

## 🚀 실행 방법
1. 저장소의 `stock-portfolio.html` 파일을 다운로드하거나 브라우저(Chrome, Edge, Safari 등)로 그대로 엽니다.
2. 우측 상단의 **[설정]** 버튼을 클릭합니다.
3. [Google AI Studio](https://aistudio.google.com/)에서 발급받은 Gemini API Key를 입력하고 저장합니다.
4. 나만의 주식 매수 내역을 추가하고, 우측 AI 로봇에게 투자 전략이나 시장 동향 등을 질문하세요!

## 🛠 기술 스택
- HTML5 / CSS3 (CSS Variables, Grid & Flexbox)
- Vanilla JavaScript (ES2022+ / Async API)
- Google Gen AI REST API (Gemini-2.0-flash-preview)

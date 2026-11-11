# TiroTalk Live (티로톡 라이브)
> **내 Tiro 회의록을 바탕으로 Gemini Live 스타일의 실시간 음성 비즈니스 영어 회의를 시뮬레이션하는 전용 앱**

## 🌟 주요 특징
1. **Tiro 회의록 원클릭 주입**:
   - 티로(Tiro)에서 복사한 회의 요약본/스크립트(한국어/영어 무관)를 넣으면 AI가 핵심 안건과 쟁점을 자동 파악합니다.
   - 3가지 실무 프리셋(기능 릴리즈 연기 협의, 글로벌 파트너십 API 제휴, Q3 실적 & AI 도입) 내장.
2. **Gemini Live 스타일 실시간 음성 롤플레잉**:
   - Canvas 기반 인터랙티브 오디오 오브(Orb) 파형 시각화.
   - Web Speech STT/TTS를 통한 음성 양방향 대화 및 턴테이킹(Barge-in 말 끊기 지원).
   - 상대방 AI 페르소나 선택 가능 (미국 본사 VP Alex, 글로벌 PM Sarah, 해외 바이어 David).
   - "💡 긴급 추천 표현(Cheat Sheet)" 버튼: 말문이 막혔을 때 즉각 쓸 수 있는 비즈니스 문장 제시.
3. **무료 체험 모드 & 실제 Gemini API 연동**:
   - **무료 체험 모드**: API 키 없이도 브라우저 음성 인식과 내장 스마트 엔진으로 즉시 테스트 가능.
   - **Gemini API 연동 모드**: Google AI Studio 무료 API Key를 입력하여 최신 Gemini 2.0 Flash 모델과 실시간 대화.
4. **회의 종료 후 맞춤형 코칭 리포트**:
   - 유창성, 비즈니스 어조, 실무 어휘 활용도 스코어카드.
   - **Better Phrasing (교정 카드)**: 내가 한 말 vs 원어민 비즈니스 표현 비교 및 해설.
   - 핵심 비즈니스 숙어 플래시카드 & Follow-up 영문 이메일 초안 자동 생성 (원클릭 복사).

## 🚀 로컬 실행 방법
```bash
python3 -m http.server 3000 --directory /home/antigravity/tiro-english-live
```
브라우저에서 `http://localhost:3000` 접속 후 마이크 권한을 허용하면 바로 사용할 수 있습니다.

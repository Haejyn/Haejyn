### 안녕하세요, 이해준입니다 👋

AI 에이전트와 도구를 **직접 만들어 쓰게 하고, 숫자로 믿을 수 있게 다듬는** 일을 합니다.
서울시립대 전자전기컴퓨터공학부 · 에이전트 도구 · 비전 AI · 신뢰성 검증

---

### 🤖 에이전트 · AI 도구

**[🐻‍❄️ isnew-crew](https://github.com/Haejyn/isnew-crew)** — 사내 AI 크루: 팀 채팅에서 `@crew` 로 일을 맡기면 계획 → 실행 → 검증 → 자기 수정 → 사람 승인 → 반영
- 계획 에이전트(LLM)가 요청을 분류·계획하고, 코딩 에이전트 여러 개(Claude Code · Codex)가 격리된 git 워크트리에서 동시에 작업
- 테스트가 판정하고, 실패하면 실패 로그를 돌려줘 스스로 고치고, 담당자가 승인해야 반영
- 팀 · 업무 템플릿 · 에이전트별 사용 지표(자동 해결률 · 승인율 · 비용 · 절약 시간 추정 · 예산) → "어떤 일을 AI 에 맡길까"를 데이터로
- TypeScript · Hono · React · SSE · vitest

<a href="https://github.com/Haejyn/isnew-crew"><img src="https://github.com/Haejyn/isnew-crew/raw/main/docs/media/crew.gif" width="720" alt="isnew-crew"></a>

**[🔬 wafer-defect-agent](https://github.com/Haejyn/wafer-defect-agent)** — 웨이퍼 불량 판독 에이전트: 로컬 LLM이 판독 카드를 쓰고, 코드가 검사하고, 틀리면 다시 묻는다
- 판독 카드 첫 답 검사 통과 8 % → 94 % (프롬프트·검사기 개선을 측정하며 반복)
- 처음 보는 패턴 경고 AUROC 0.919 · Grad-CAM 위치 · 유사 사례 검색 · 81만 장 실제 팹 데이터

<a href="https://github.com/Haejyn/wafer-defect-agent"><img src="https://github.com/Haejyn/wafer-defect-agent/raw/main/docs/media/agent.gif" width="720" alt="wafer agent"></a>

**[🚗 biw-weld-twin](https://github.com/Haejyn/biw-weld-twin)** — 차체 용접 디지털 트윈 + AI 제조성 판정을 브라우저 도구로 제품화
- 전체 시뮬레이션 약 3분 → AI 0.05 초 · 처음 보는 설계 재현율 99.9 % · 정밀도 100 %
- 탐색 결과를 시뮬레이터로 재검증하다 AI 특징 버그를 찾아 고친 과정까지 기록

---

### 🛰️ 신뢰성 · 시스템

- **[ccsds-downlink-reliability](https://github.com/Haejyn/ccsds-downlink-reliability)** — 실제 위성 신호(Astrocast · EIRSAT-1) 복호 수신 처리기 · C#/.NET · 뮤테이션 테스트 94.7 %
- **[orbit-pass-sim](https://github.com/Haejyn/orbit-pass-sim)** — 위성 궤도 전파 · 지상국 패스 예측 · Java↔C# 차분 520건 일치 · PIT 95 %

---

### 🏆 수상 · 논문

- 한국수자원공사 사장 상장 — 드론 다중분광 녹조 세그멘테이션 (2026.09)
- 서울시립대학교 총장 최우수상 — 공공기관 AI 프로젝트 챌린지 (2026.09)
- 전국학생설계경진대회 동상 — AI 생명체 감지 해양 쓰레기 수거기, 약 1,000팀 중 (2025.10)
- 대한기계학회 국문논문집 C 게재 — 같은 프로젝트, SW·AI 담당 (2026.09)

### 🧰 쓰는 것

`Python` `TypeScript` `C#` `Java` · `PyTorch` `LightGBM` `YOLO` `U-Net` · `Claude Code` `Codex` `Ollama` · `React` `Hono` `three.js`

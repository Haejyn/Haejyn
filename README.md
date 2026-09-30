## 이해준

서울시립대 전자전기컴퓨터공학부. 에이전트 도구 · 비전 AI · 신뢰성 검증.

---

### 에이전트 · AI 도구

**[isnew-crew](https://github.com/Haejyn/isnew-crew)** 사내 AI 크루
- 채팅 `@crew` 요청, 계획, 병렬 실행, 검증, 자기 수정, 사람 승인, 반영
- Claude Code · Codex 를 격리 git 워크트리에서 병렬 실행
- 팀 · 템플릿 · 에이전트별 지표: 자동 해결률, 승인율, 비용, 절약 시간(추정)
- TypeScript · Hono · React · SSE · vitest

<a href="https://github.com/Haejyn/isnew-crew"><img src="https://github.com/Haejyn/isnew-crew/raw/main/docs/media/crew.gif" width="720" alt="isnew-crew"></a>

**[wafer-defect-agent](https://github.com/Haejyn/wafer-defect-agent)** 웨이퍼 불량 판독 에이전트
- 로컬 LLM 판독 카드, 코드 검사, 실패 시 재질문
- 첫 답 검사 통과 8 % → 94 %
- 미학습 패턴 경고 AUROC 0.919 · Grad-CAM · 유사 사례 검색 · 실제 팹 데이터 81만 장

<a href="https://github.com/Haejyn/wafer-defect-agent"><img src="https://github.com/Haejyn/wafer-defect-agent/raw/main/docs/media/agent.gif" width="720" alt="wafer agent"></a>

**[biw-weld-twin](https://github.com/Haejyn/biw-weld-twin)** 차체 용접 디지털 트윈 + AI 제조성 판정
- 전체 시뮬레이션 약 3분 → AI 0.05 초
- 처음 보는 설계 재현율 99.9 % · 정밀도 100 %
- 재검증으로 AI 특징 버그 발견 · 수정

---

### 신뢰성 · 시스템

- **[ccsds-downlink-reliability](https://github.com/Haejyn/ccsds-downlink-reliability)** 실제 위성 신호 복호 수신 · C#/.NET · 뮤테이션 테스트 94.7 %
- **[orbit-pass-sim](https://github.com/Haejyn/orbit-pass-sim)** 궤도 전파 · 패스 예측 · Java↔C# 차분 520건 일치 · PIT 95 %

---

### 수상 · 논문

- 한국수자원공사 사장 상장, 드론 다중분광 녹조 세그멘테이션 (2026.09)
- 서울시립대학교 총장 최우수상, 공공기관 AI 프로젝트 챌린지 (2026.09)
- 전국학생설계경진대회 동상, 약 1,000팀 중 (2025.10)
- 대한기계학회 국문논문집 C 게재, SW·AI 담당 (2026.09)

### 스택

`Python` `TypeScript` `C#` `Java` · `PyTorch` `LightGBM` `YOLO` `U-Net` · `Claude Code` `Codex` `Ollama` · `React` `Hono` `three.js`

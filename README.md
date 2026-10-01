### 안녕하세요, 이해준입니다 👋

AI 가 낸 답을 **코드로 검사하고, 숫자로 증명하는** 걸 좋아합니다.
서울시립대 전자전기컴퓨터공학부 · 에이전트 도구 · 비전 AI · 소프트웨어 신뢰성

[포트폴리오](https://haejyn.github.io) · [willnew](https://github.com/Haejyn/willnew) · [wafer-defect-agent](https://github.com/Haejyn/wafer-defect-agent) · [biw-weld-twin](https://github.com/Haejyn/biw-weld-twin)

<br>

## 🤖 [willnew](https://github.com/Haejyn/willnew) — 팀 AI 에이전트 플랫폼

채팅에서 `@willnew` 로 부탁하면 계획 → Claude Code · Codex 병렬 실행 → 테스트 검증 → 자기 수정 → 사람 승인 → 병합.
에이전트마다 격리된 git 워크트리에서 돌고, 팀 · 템플릿 · 에이전트별 해결률 · 승인율 · 비용을 지표로 남깁니다.

<a href="https://github.com/Haejyn/willnew"><img src="https://raw.githubusercontent.com/Haejyn/willnew/main/docs/media/demo.gif" width="720" alt="willnew 데모"></a>

<sub>TypeScript · Hono · React · SSE · vitest</sub>

## 🔬 [wafer-defect-agent](https://github.com/Haejyn/wafer-defect-agent) — 웨이퍼 불량 판독 에이전트

실제 팹 웨이퍼 맵 81만 장으로 아는 패턴은 분류하고, 처음 보는 패턴은 경고하고, 로컬 LLM 이 쓴 판독 카드는 코드가 검사합니다.

| 판독 카드 첫 답 통과 | 처음 보는 패턴 경고 | 유사 사례 검색 |
|:---:|:---:|:---:|
| **8 % → 94 %** | **AUROC 0.943** | **정밀도@5 0.856** |

<a href="https://github.com/Haejyn/wafer-defect-agent"><img src="https://raw.githubusercontent.com/Haejyn/wafer-defect-agent/main/docs/media/agent.gif" width="720" alt="wafer-defect-agent 판독 흐름"></a>

<sub>PyTorch · Grad-CAM · Ollama</sub>

## 🚗 [biw-weld-twin](https://github.com/Haejyn/biw-weld-twin) — 차체 용접 디지털 트윈 + AI 제조성 판정

KUKA KR210 실제 기구학으로 용접 로봇 배치 · 경로 · 간섭을 시뮬레이션하고, AI 대리 모델로 새 설계를 즉시 판정합니다.
AI 첫 판의 특징 버그를 재검증으로 잡아 정밀도 93.4 → 100 % 로 고친 기록까지 남겼습니다.

| 판정 시간 | 처음 보는 설계 재현율 | 정밀도 |
|:---:|:---:|:---:|
| **약 3분 → 0.05 초** | **99.9 %** | **100 %** |

<a href="https://github.com/Haejyn/biw-weld-twin"><img src="https://raw.githubusercontent.com/Haejyn/biw-weld-twin/main/docs/media/demo_weld.gif" width="720" alt="biw-weld-twin 용접 시퀀스"></a>

<sub>Python · LightGBM · SHAP · OR-Tools · three.js · STEP</sub>

## 🛰️ 신뢰성 · 시스템

| 프로젝트 | 내용 | 검증 |
|---|---|---|
| [ccsds-downlink-reliability](https://github.com/Haejyn/ccsds-downlink-reliability) | 실제 위성 신호 복호 · CCSDS TM 수신 처리기 (C#/.NET) | 뮤테이션 테스트 95 % |
| [orbit-pass-sim](https://github.com/Haejyn/orbit-pass-sim) | 궤도 전파 · 지상국 패스 예측 (Java · C# 이식) | Java↔C# 차분 520건 일치 · PIT 95 % |

## 🏆 수상 · 논문

- **2026.09** 한국수자원공사 사장상 — 드론 다중분광 녹조 세그멘테이션
- **2026.09** 서울시립대학교 총장 최우수상 — 공공기관 AI 프로젝트 챌린지
- **2026.09** 대한기계학회 국문논문집 C 게재 — SW · AI 담당
- **2025.10** 전국학생설계경진대회 동상 — 약 1,000팀 중

## 🧰 스택

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?logo=dotnet&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-2563EB)
![YOLO](https://img.shields.io/badge/YOLO-111111)
![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)
![Hono](https://img.shields.io/badge/Hono-E36002?logo=hono&logoColor=white)
![three.js](https://img.shields.io/badge/three.js-000000?logo=threedotjs&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude%20Code-D97757?logo=anthropic&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-111111?logo=ollama&logoColor=white)

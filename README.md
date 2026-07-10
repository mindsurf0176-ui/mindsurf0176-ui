# 이민서 (Minseo Lee)

### AI Automation Engineer · Technical Art & Tooling

반복적인 제작 작업을 Python·Godot·LLM 도구로 자동화하고, 결과물을 실제 런타임에서 검증 가능한 파이프라인으로 만듭니다. 1인으로 앱과 게임을 설계·개발·출시하며, AI가 만든 결과보다 **생성 규칙·결정적 조립·실행 검증**을 직접 소유하는 방식으로 일합니다.

## Selected work

| Project | What I built | Evidence |
|---|---|---|
| [Vesper / Game Asset Pipeline](https://github.com/mindsurf0176-ui/vesper) | 상태 기반 스프라이트 생성 → 공통박스·발 정렬 → Godot 상태기계·캡처 QA | 6 states · 33 frames · 16 Python tools |
| [Fissh](https://github.com/mindsurf0176-ui/fissh) | 폰에서 Mac의 Claude Code를 제어하는 WebSocket 브리지와 QR 페어링 | Node.js · Capacitor · Swift · Tailscale |
| [Callog](https://github.com/mindsurf0176-ui/callog) | 사진 기반 칼로리 추정을 측정 가능한 5단계 보정 파이프라인으로 구현 | pass rate 70→88% · MAPE 31→19% |
| [Oracle Tarot](https://github.com/mindsurf0176-ui/oracle-tarot) | 결정론 엔진·3-provider 폴백·결제 백필을 결합한 유료 LLM 서비스 | 40 serverless endpoints · failure-safe result |
| [Haebari](https://github.com/mindsurf0176-ui/haebari) | 4단계 캐시와 in-flight dedupe를 적용한 멀티채널 운세 앱 인프라 | 토스 출시 · App Store 심사 중 |
| [Kotoba](https://github.com/mindsurf0176-ui/kotoba) | 4개 ONNX 모델을 Swift로 이식한 완전 오프라인 일본어 학습앱 | 9,734 cards · runtime network 0 |

## How I work

```text
Problem → measurable baseline → deterministic pipeline → runtime QA → production feedback
```

- **Technical art:** Godot, Python, Pillow/NumPy, sprite assembly, runtime capture QA
- **AI systems:** OpenAI·Anthropic·Gemini orchestration, structured output, fallback and cost control
- **Product engineering:** TypeScript/React, Vercel serverless, Postgres/Redis, Swift/SwiftUI
- **On-device ML:** ONNX Runtime, mobile inference, caching and concurrency control

## Contact

- Email: [mindsurf0176@gmail.com](mailto:mindsurf0176@gmail.com)
- GitHub: [@mindsurf0176-ui](https://github.com/mindsurf0176-ui)

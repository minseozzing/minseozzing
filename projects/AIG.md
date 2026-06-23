# 🌐 AIG (AIGround)

> AI 에이전트와의 상호작용을 추적·분석해 학습자의 문제 해결 과정을 투명하게 기록하고 피드백을 제공하는 AI 학습 플랫폼

`2026.04 ~ 2026.05` · `팀 6인 (FE 2 · BE 3 · AI 1)` · **Frontend 담당**

<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white"/> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/> <img src="https://img.shields.io/badge/Zustand-eab23f?style=flat-square&logo=Zustand&logoColor=white"/> <img src="https://img.shields.io/badge/TanStack_Query-FF4154?style=flat-square&logo=react&logoColor=white"/> <img src="https://img.shields.io/badge/Monaco_Editor-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white"/> <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white"/>

## 주요 작업

- Lighthouse 진단으로 미사용 한글 폰트 로딩 버그를 찾아 LCP 2.8s → 1.2s(**-57%**), Performance 74 → 97 개선
- `useEffect` ↔ `useLayoutEffect` 실행 시점 차이를 파고들어 Monaco Editor TextModel dispose race condition 해결
- 외부 라이브러리 없이 SVG 직접 구현으로 인터랙티브 튜토리얼 투어, 5축 레이더 차트 제작 (번들 증가 0KB)

🔗 [Live Demo](https://aig.pyan.kr/) · [GitHub](https://github.com/SSAFY14-D103/AIG)

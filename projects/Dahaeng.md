# ✈️ 다행 (Dahaeng)

> YouTube 시청 이력과 여행 성향을 분석해 161개 도시 중 나에게 맞는 여행지를 AI가 추천하는 여행 플랫폼

`2026.02 ~ 2026.04` · `팀 6인 (FE 2 · BE 4)` · **Frontend 담당**

<img src="https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black"/> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/> <img src="https://img.shields.io/badge/TanStack_Router/Query-FF4154?style=flat-square&logo=react&logoColor=white"/> <img src="https://img.shields.io/badge/Zustand-eab23f?style=flat-square&logo=Zustand&logoColor=white"/> <img src="https://img.shields.io/badge/Zod-3E67B1?style=flat-square&logo=zod&logoColor=white"/> <img src="https://img.shields.io/badge/react--globe.gl-000000?style=flat-square&logo=three.js&logoColor=white"/>

## 주요 작업

- 서버 상태(TanStack Query)와 UI 상태(Zustand)의 책임을 분리해 불필요한 리렌더링과 API 중복 호출 제거
- 다중 401 응답 시 발생하는 토큰 재발급 경쟁 조건(Thundering Herd)을 `isRefreshing` 플래그 + 대기열 패턴으로 해결
- `react-globe.gl` 기반 인터랙티브 지구 시각화에 161개 도시 추천 점수를 마커 크기·색상으로 실시간 표시, hover 시 상세 데이터 prefetch

🔗 [Live Demo](https://youtube-data-based-travel-recommendation.pages.dev/) · [GitHub](https://github.com/minseozzing/YouTube-Data-based-Travel-Recommendation)

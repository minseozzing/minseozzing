# 🔨 뮤즈옥션 (Muse Auction)

> Firebase RTDB와 MySQL을 이중화해 실시간성과 정합성을 동시에 보장하는 Android 실시간 경매 앱

`2025.11 ~ 2025.12` · `팀 2인` · **Android (Mobile Frontend) 담당**

<img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white"/> <img src="https://img.shields.io/badge/MVVM-7F52FF?style=flat-square"/> <img src="https://img.shields.io/badge/Firebase_RTDB-FFCA28?style=flat-square&logo=firebase&logoColor=black"/> <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/> <img src="https://img.shields.io/badge/BLE_Beacon-0082FC?style=flat-square&logo=bluetooth&logoColor=white"/> <img src="https://img.shields.io/badge/Gemma_3n_On--Device_AI-8E75B2?style=flat-square&logo=googlegemini&logoColor=white"/>

## 주요 작업

- 입찰가는 RTDB(실시간), 낙찰 확정은 MySQL(영구)에 나눠 저장하는 구조에서 "RTDB 삭제 → MySQL 갱신 → FCM 발송" 순서를 트랜잭션처럼 보장하고, 실패 시 자동 재경매 롤백 로직 구현
- BLE Beacon으로 오프라인 매장 내 상품 위치를 인식하고, On-Device AI(Gemma-3n)로 네트워크 없이 상품 설명을 생성

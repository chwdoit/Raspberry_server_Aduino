# ﻿Raspberry pi를 이용한 TCP server Arduino 제어 시스템 구현
## 👨‍🏫 프로젝트 소개
﻿소매점의 재고 관리와 판매를 효율적으로 처리할 수 있는 프로그램입니다. 
 
 주요 기능으로는 재고 추가 및 제거, 제품 검색, 유통기한 확인, 로그인 기능, 제품 판매 및 환불 기능을 포함하고 있습니다.



## ⏲️ 개발 기간
2024.07.09(화) ~ 2023.07.11(목)

## 🚀 Skills
<img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" /> <img src="https://img.shields.io/badge/Eclipse-2C2255?style=for-the-badge&logo=eclipse&logoColor=white" /> <img src = "https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white"/> <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white"/>  <img src ="https://img.shields.io/badge/Arduino_IDE-00979D?style=for-the-badge&logo=arduino&logoColor=white"/> <img src="https://img.shields.io/badge/Raspberry%20Pi-A22846?style=for-the-badge&logo=Raspberry%20Pi&logoColor=white"/> <img src="https://img.shields.io/badge/IntelliJ_IDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white"/>
             


## 📌 주요 기능
﻿1. 주요 기능
- 온도 및 습도 센서 데이터 수집 및 실시간 표시
- 사용자 입력에 따라 LED, RGB의 상태 변경 (켜기/끄기)
- TCP/IP 프로토콜을 사용한 클라이언트-서버 통신 구현
2. 기술적 구현
- 서버 구현: Raspberry Pi에서 동작하는 C++ 기반 TCP 서버 구현
- Raspberry Pi와 연결된 Arduino를 통해 데이터 수집 및 제어 명령 수신
- C++ 소켓 프로그래밍을 사용하여 클라이언트 요청 처리
- 클라이언트 구현: JavaFX를 사용하여 GUI 구현
- Java의 Socket클래스를 이용한 서버와의 TCP 연결
- 멀티스레드를 활용하여 서버로부터 실시간 데이터 수신 및 GUI 업데이트 처리
- 실시간 데이터 업데이트: 온도 및 습도 센서에서 받아온 데이터를 프로그래스 바와 레이블을 통해 실시간으로 표시
- LED,RGB 제어: 사용자가 GUI 버튼을 클릭하여 LED와 RGB의 상태를 제어할 수 있음.
- Arduino의 디지털 핀을 제어하여 LED,RGB를 켜고 끔


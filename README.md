# 이정우 | Backend Developer

Java와 Spring Boot를 중심으로 백엔드 시스템을 개발하고 있습니다.

비동기 작업 처리, 데이터 정합성, 성능 최적화에 관심이 있습니다. 기능 구현에 그치지 않고 로그와 측정 지표로 문제를 분석하고, 개선 결과를 검증하는 개발을 지향합니다.

## 기술 스택

**Backend**

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Data JPA](https://img.shields.io/badge/Spring%20Data%20JPA-6DB33F?style=flat-square&logo=spring&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

**Database & Messaging**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-CC0200?style=flat-square&logo=flyway&logoColor=white)

**DevOps & Infrastructure**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![AWS EC2](https://img.shields.io/badge/AWS%20EC2-FF9900?style=flat-square&logo=amazonec2&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**AI & Real-time**

`RAG` · `FAISS` · `LangChain` · `WebSocket` · `WebRTC`

## 주요 프로젝트

### [AutoQuant](https://github.com/NPrawn/AutoQuant) — 암호화폐 투자전략 백테스트·모의투자 플랫폼

사용자가 설계한 투자 전략을 과거 시세로 검증하고, 시장 데이터를 활용해 모의투자할 수 있는 플랫폼입니다.

- **담당:** 팀장, 백엔드, 백테스트·모의투자 실행 엔진 및 운영
- **주요 구현:** RabbitMQ 기반 비동기 Worker, Transactional Outbox, PostgreSQL 무결성 제약, JDBC Batch 저장
- **성과:** 24건 동시 백테스트 전체 처리 시간 66.526초 → 36.645초(약 44.9% 감소)
  - 초기 1회와 개선 후 6회 중앙값 비교이며, 여러 개선 사항의 복합 효과입니다.
- **기술:** Java, Spring Boot, PostgreSQL, RabbitMQ, Kafka, Docker, Jenkins

### [PinGo](https://github.com/NPrawn/PinGo) — 지하철 실내 길찾기·실시간 영상 상담

외국인 관광객이 지하철역 내부에서 길을 찾고, 필요한 경우 상담자의 도움을 받을 수 있는 서비스입니다.

- **담당:** 백엔드, 실시간 통신, CI/CD
- **주요 구현:** WebSocket Signaling 인증 및 상담방 상태 관리, STUN/TURN 연동, HLoc/COLMAP 기반 위치 인식 서버 연동
- **운영:** Jenkins, Docker, Nginx, EC2 기반 배포 환경 구성
- **성과:** SSAFY 공통 프로젝트 우수상
- **기술:** Java, Spring Boot, MySQL, WebSocket, WebRTC, Jenkins

### [KnungAI](https://github.com/NPrawn/KnungAI) — LLM RAG 기반 학교 특화 챗봇

학교 공지와 학사 정보를 검색해 사용자 질문에 답변하는 RAG 기반 챗봇입니다.

- **담당:** 팀장, 백엔드, RAG 시스템 개발
- **주요 구현:** FastAPI 기반 API, FAISS 문서 검색, LLM 응답 생성, Arize Phoenix 기반 품질 평가
- **성과:** 한국디지털콘텐츠학회 대학생 논문경진대회 동상
- **기술:** Python, FastAPI, FAISS, RAG, LLM

### [Algorithm](https://github.com/NPrawn/Algorithm) — 알고리즘 문제 풀이

Python과 Java로 자료구조·알고리즘 문제를 해결하고 풀이를 기록하고 있습니다.

- 알고리즘 문제 풀이 및 구현 연습
- 삼성 SW 역량테스트 B형 취득

## 수상 경력

| 시기 | 수상 |
| --- | --- |
| 2026.10 | FLY ASIA 해양 × AI 아이디어 해커톤 우수상 (2등) |
| 2026.08 | SSAFY 공통 프로젝트 우수상 |
| 2026.06 | SSAFY 프로젝트 경진대회 최우수상 |
| 2026.06 | SSAFY SW·AI 교육 성적우수상 |
| 2025.11 | SW 알고리즘 경진대회 우수상 |
| 2025.07 | 한국디지털콘텐츠학회 대학생 논문경진대회 동상 |

## 자격 및 역량

정보처리기사 · 삼성 SW 역량테스트 B형 · TOEIC Speaking IM2

## 연락처

[![Email](https://img.shields.io/badge/Email-ljwljw522%40gmail.com-444444?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ljwljw522@gmail.com)

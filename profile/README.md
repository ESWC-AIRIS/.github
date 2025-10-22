# GazeHome - AIRIS

> **시선으로 제어하는 스마트홈**

## 📌 프로젝트 소개

GazeHome은 시선 추적 기술을 활용하여 거동이 불편한 사용자들이 
시선만으로 스마트홈 기기를 제어할 수 있도록 돕는 AI 기반 시스템입니다.

### 🎯 주요 기능
- 👁️ 실시간 시선 추적 및 깜빡임 인식
- 🤖 AI 기반 사용자 의도 파악
- 🏡 스마트홈 기기 자동 제어
- 📊 개인 맞춤형 사용 패턴 학습

## 시스템 구조
Edge Device (시선 추적)
->
Communication Gateway (통신 관리)
->
AI Services (의도 분석)
->
IoT 기기 제어

<img width="6290" height="9700" alt="image" src="https://github.com/user-attachments/assets/a88eaaaa-0a86-459a-ba55-20f984b4c584" />


## 레포지토리

| 레포                                                     | 설명                          | 담당        |
| -------------------------------------------------------- | ----------------------------- | ----------- |
| [ai-services](https://github.com/ESWC-AIRIS/ai-services) | AI 백엔드 (LangGraph, Gemini) | AI 팀       |
| [comm-gateway](https://github.com/ESWC-AIRIS/comm-gateway)         | 통신 게이트웨이 & 인프라      | 클라우드 팀 |
| [edge-module](https://github.com/ESWC-AIRIS/edge-module) | 시선 추적 하드웨어            | 하드웨어 팀 |

## 🛠️ 기술 스택

**Backend:** FastAPI, LangGraph  
**AI:** Google Gemini, LangChain  
**Hardware:** Raspberry Pi, OpenCV  
**Infrastructure:** Docker, AWS, GitHub Actions  
**Database:** MongoDB, ChromaDB

## 👥 Team AIRIS

**Artificial Intelligence + Irise**

제23회 임베디드SW경진대회 스마트 가전 부문

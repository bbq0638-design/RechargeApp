# RechargeApp

본 Repository는 **휴먼교육센터 Java·Spring 기반 풀스택 개발자 과정**의  
**3차 팀 프로젝트 결과물**로,  
전기차 충전 중 사용자의 휴식 시간을 고려한  
**미디어 추천 중심 라이프스타일 모바일 앱**입니다.

웹 서비스로 시작한 프로젝트를 **모바일 앱(React Native)** 환경으로 확장하며,  
외부 API 연동, AI 추천, 사용자 개인화 기능 구현에 중점을 두었습니다.

---

##  프로젝트 개요

- **프로젝트명** : RechargeApp  
- **플랫폼** : Mobile App (Android)  
- **설명** :  
  전기차 충전소 위치/정보 제공과 함께  
  충전 대기 시간 동안 영화·음악 추천, 운세, 커뮤니티 기능을 제공하는  
  라이프스타일 플랫폼 앱

---

## 담당 구현 기능

- 모바일 앱 환경에 맞춘 **영화/음악 추천 UI 재설계 및 구현**
- 외부 API 기반 **영화·음악 추천 도메인 전반 설계**
- Python FastAPI를 활용한 **AI 추천 기능 구현 및 Spring Boot 연동**
- 마이페이지, 즐겨찾기 등 **사용자 개인화 기능 구현**

---

## 기술 스택

- **Frontend** : React Native  
- **Backend** : Spring Boot (Java 17), MyBatis  
- **AI Service** : Python FastAPI  
- **Communication** : Axios  
- **External API** :  
  TMDB, Apple Music RSS, iTunes Search API, OpenAI API  

---

##  프로젝트를 통해 배운 점 (요약)

- 외부 API 호출 로직이 여러 Service 계층에 분산될 경우  
  유지보수성과 확장성이 저하됨을 경험함
- 외부 API 연동 로직을 **공통 Client 계층으로 분리해야 할 필요성 인식**
- Spotify API 도입 검토 과정에서  
  **인증 구조와 운영 복잡도가 구현 난이도에 직접적인 영향을 미침을 체감**
- 기술적 이상보다 **프로젝트 일정·팀 역량을 고려한 기능 범위 조정의 중요성 학습**
- 향후 **API 연동 구조 사전 검증과 단계적 확장이 가능한 설계**의 필요성을 인식

---

##  시연 영상

https://drive.google.com/drive/folders/1_0sNIPvVOM1LtBVjzIurqiAFDY60wm4v?hl=ko

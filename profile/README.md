<p align="center">
  <img width="200" alt="Synthor Logo" src="https://github.com/user-attachments/assets/2564b321-0bf8-44a8-b53e-d3e599c64497" />
</p>



# TOPGEON - Synthor

---

## 1. 프로젝트 개요
**Synthor**는 개발자를 위한 **AI 기반 더미 데이터 생성 플랫폼**입니다.  
복잡한 조건이나 다양한 데이터 타입을 손쉽게 생성하고, 원하는 포맷(JSON, CSV, SQL 등)으로 변환해  
테스트 및 개발 효율성을 극대화합니다.  

본 프로젝트는 **2025 오픈소스 공모전 출품작**으로,  
Frontend · Backend · AI 모듈이 유기적으로 협력하는 통합 시스템입니다.

---

## 2. 프로젝트 소개
- **프로젝트 명**: Synthor  
- **출품 분야**: 2025 오픈소스 공모전  
- **구성**: Frontend · Backend · AI 모듈 통합  
- **슬로건**: *“테스트 데이터를 가장 스마트하게 생성하는 방법”*  

📸 주요 화면
- 데이터 타입 선택 모달 (51종 데이터 타입 지원)  
<img width="3404" height="1968" alt="image" src="https://github.com/user-attachments/assets/ed48a2fa-1c3d-48fa-8c19-0bdb07cb2256" />


- 데이터 타입 옵션 설정 (예: 비밀번호 조건)  
<img width="3404" height="1968" alt="image" src="https://github.com/user-attachments/assets/dd2a603d-14f4-47b7-9be9-d15465731c11" />

---

## 3. 프로젝트 목표
- **자연어 기반 데이터 생성** → “비밀번호는 최소 10자 이상” 같은 문장으로 조건 인식  
- **다국어 지원** → 한국어 + 영어 모두 사용 가능  
- **테스트 효율성 극대화** → JSON, CSV, SQL 등 6가지 포맷으로 바로 다운로드  
- **누구나 쉽게 활용 가능한 오픈소스 플랫폼 제공**  

---

## 4. 주요 기능
- **데이터 타입 다양성**  
  9개 카테고리, 총 **51종 데이터 타입 지원**  
- **AI 조건 생성**  
  자연어 프롬프트로 조건 기반 데이터 생성 (*예: 김씨 성만, 네이버 메일만*)  
- **포맷 변환 (6종)**  
  JSON · CSV · SQL · HTML · XML · LDIF  
- **웹 UI 제공**  
  React 기반 직관적 인터페이스  
- **REST API 제공**  
  Swagger 기반 문서화 & 외부 연동  

🎥 주요 기능 
- **데이터 필드별 프롬프트로 조건 설정** (이메일, 비밀번호 등 각 필드별 조건 지정)  
<img width="1702" height="984" alt="image" src="https://github.com/user-attachments/assets/e6e0ad9c-e4a3-4f11-9e39-1e6699ff5715" />
![개별 데이터 프롬프트](https://github.com/user-attachments/assets/ef7d3be0-2f7b-493c-b2f9-95a3599098f4)


- **전체 프롬프트 시연** (한 번의 입력으로 전체 데이터 조건 반영)
<img width="1702" height="984" alt="image" src="https://github.com/user-attachments/assets/8037e043-093c-479b-a9ff-fd3162bfa972" />
![전체 프](https://github.com/user-attachments/assets/b310379c-e117-4ff9-be89-f3b0c1887bb8)


- **실제 데이터 다운로드 확인** (CSV, SQL 등으로 변환 후 저장)  
![데이터 다운로드 ](https://github.com/user-attachments/assets/0519bb35-a42c-414c-a245-35cfe1dd5a70)


---

## 5. 팀원 소개
- **Frontend** → [Synthor-front](../Synthor-front)  
- **Backend** → [Synthor-back](../Synthor-back)  
- **AI** → [Synthor-AI](../Synthor-AI)  

---

## 6. 기술 스택
- **Frontend**: React, Vite, TailwindCSS  
- **Backend**: Spring Boot, Swagger, MySQL  
- **AI**: Python (FastAPI, Pydantic, Langdetect)  
- **Infra**: Docker, Render, GitHub Actions, Cloudflare Pages  



📸 시스템 아키텍처  
<img width="596" height="631" alt="image" src="https://github.com/user-attachments/assets/091aed34-093f-4e5b-9041-a7d86e66177a" />

 
---

## 7. 문서 자료
- API 문서 (Swagger)
<img width="1702" height="984" alt="스크린샷 2025-08-18 오후 3 18 16" src="https://github.com/user-attachments/assets/2e818110-de07-42fe-97d8-8a06ec31f914" />
<img width="1702" height="984" alt="스크린샷 2025-08-18 오후 3 18 30" src="https://github.com/user-attachments/assets/8d903f79-5453-4622-9329-9239b3659666" />

- 기능 시연 영상



---

## 📜 라이선스
본 프로젝트는 [MIT License](../LICENSE) 하에 공개됩니다.

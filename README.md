<div align="center">
<img src="https://cdn.discordapp.com/attachments/1347419441855467584/1382918307140862093/IMG_3913.png?ex=687eff89&is=687dae09&hm=6b9ab85159a42e938596b52f5aece13268ddd15617d60fbe8ea636c434168c82" width="300" />

### 가톨릭대 택시 동승 서비스 *CATXI*
서비스 바로가기(링크 예정)
</div>

## 🚕 소개

캣시(Catxi)는 가톨릭대학교 캠퍼스 근처에서 학생들이 안전하고 저렴하게 택시를 함께 이용할 수 있도록 돕는 실시간 택시 합승 플랫폼입니다.

출발지, 시간, 인원을 설정해 택시를 함께 탈 사람을 모집하고, 실시간 채팅을 통해 커뮤니케이션하며 빠르고 간편하게 합승을 매칭할 수 있습니다.

채팅방에서 준비완료된 인원들은 서로의 위치를 지도를 통해 실시간으로 공유하여 신뢰성을 더합니다.

## 🖥 서비스 화면 (사진 업데이트 예정)

<img src="https://cdn.discordapp.com/attachments/1347419441855467584/1384583858615357490/image.png?ex=687f1ff4&is=687dce74&hm=c3b9e41b6f449296df96277b5ffe35f1ce86b4e92f6a0a9545860d1e7fe2f4dd&" />
<img src ="https://cdn.discordapp.com/attachments/1347419441855467584/1384583869906288811/image.png?ex=687f1ff6&is=687dce76&hm=f76927315ed01ff39a8fb264c0a902a7368e414144cce6269c4ddd53ebc8a019&" />


## 🛠 Tech Stacks

### 🎨 Frontend Tech Stack

- **pnpm / Vite**: 빠르고 효율적인 패키지 설치 및 프론트엔드 빌드 환경
- **Tailwind CSS**: 유틸리티 기반 CSS 프레임워크
- **@tailwindcss/vite**: Vite에서 Tailwind CSS를 쉽게 사용할 수 있도록 지원하는 플러그인

- **React**: 컴포넌트 기반 UI 개발을 위한 JavaScript 라이브러리
- **react-router-dom**: SPA 라우팅 처리 라이브러리

- **Axios**: REST API와 통신하기 위한 HTTP 클라이언트

- **react-hook-form**: 선언적이고 간결한 폼 상태 관리 라이브러리
- **@hookform/resolvers / Zod**: react-hook-form과 함께 사용하는 유효성 검사 및 스키마 검증 도구

- **@tanstack/react-query**: 서버 상태(fetching, caching 등)를 효율적으로 관리하는 라이브러리
- **@tanstack/react-query-devtools**: React Query 상태를 시각적으로 디버깅할 수 있는 개발 도구

- **react-intersection-observer**: 뷰포트 진입 여부를 감지하는 Intersection Observer 구현 라이브러리

- **clsx**: 조건부 className 조합을 간편하게 할 수 있는 유틸 함수

- **vite-plugin-svgr**: SVG 파일을 React 컴포넌트로 변환해 사용할 수 있도록 하는 Vite 플러그인

- **vite-plugin-pwa**: PWA(Progressive Web App) 지원을 위한 Vite 플러그인

- **sockjs-client / webstomp-client**: STOMP 프로토콜 기반의 실시간 WebSocket 통신을 위한 클라이언트

- **react-mobile-picker-scroll**: 모바일 환경에서 사용할 수 있는 스크롤형 선택 피커 UI


---

### ⚙️ Backend

- **Spring Boot**: Java 기반 웹 애플리케이션 프레임워크
- **Java 17**: 최신 LTS 버전의 Java
- **Spring Security + JWT**: 인증 및 권한 처리
- **Redis Pub/Sub**: 실시간 채팅 메시지 전파
- **MySQL**: 관계형 데이터베이스
- **JPA (Hibernate)**: ORM 프레임워크
- **WebSocket (STOMP)**: 실시간 채팅 기능 구현

---

### ☁️ Infrastructure (아키텍처 사진))

- **AWS EC2**: 애플리케이션 서버 호스팅
- **AWS RDS (MySQL)**: 관리형 데이터베이스
- **AWS S3**: 이미지 및 파일 업로드 스토리지
- **Nginx**: 리버스 프록시 및 SSL 인증 처리
- **Docker**: 컨테이너 기반 환경 구성

---

### 🔁 CI/CD & DevOps (CICD 사진))

- **Jenkins**: CI/CD 파이프라인 구축 및 자동 배포
- **GitHub Actions**: 테스트 및 코드 품질 검사 자동화
- **Shell Script**: SSH를 이용한 서버 배포 자동화
- **Discord Webhook**: 배포 및 장애 알림 전송

---

### 💬 Communication & Collaboration

- **GitHub Projects / Issues**: 이슈 및 프로젝트 관리
- **Notion**: 문서 협업 및 일정 관리
- **Figma**: UI/UX 디자인 협업
- **Discord**: 팀 커뮤니케이션



## 👥 Members

| PM / Backend | Backend | Backend | Backend | Frontend | Frontend | Designer |
|:------------:|:-------:|:-------:|:-------:|:--------:|:--------:|:--------:|
| ![](https://avatars.githubusercontent.com/u/164463609?v=4&s=120)<br> [이동준](https://github.com/dongjune8931) | ![](https://avatars.githubusercontent.com/u/155940734?v=4&s=120) <br> [이가영](https://github.com/LGY010011) | ![](https://avatars.githubusercontent.com/u/162654709?v=4&s=120) <br> [최민수](https://github.com/CMIN-SU) | ![](https://avatars.githubusercontent.com/u/150355097?v=4&s=120) <br> [박규민](https://github.com/FrontHeadlock) | ![](https://avatars.githubusercontent.com/u/97932282?v=4&s=120) <br> [고민균](https://github.com/miinnne) | ![](https://avatars.githubusercontent.com/u/96588957?v=4&s=120) <br> [채연](https://github.com/lwittyl) | ![]() <br> 이서연 |



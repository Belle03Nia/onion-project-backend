# 🧅 onion-project-backed

> 자취생을 위한 공동구매 플랫폼 `onion`의 백엔드 프로젝트입니다.  
> NestJS를 기반으로 RESTful API 서버를 구축하였습니다.

---

## 🛠️ Tech Stack

- **Framework**: [NestJS](https://nestjs.com/)
- **Language**: TypeScript
- **Database**: MySQL
- **ORM**: TypeORM
- **Authentication**: JWT
- **API Docs**: Swagger (OpenAPI)
- **환경 분리**: `dev`, `prod`, `test` 환경 구성

---

## 📁 프로젝트 구조

```bash
src/
├── auth/              # 로그인, 회원가입, JWT 인증
├── user/              # 사용자 관리
├── address/           # 주소 (시/도 ~ 읍/면/동)
├── category/          # 카테고리 (야채, 과일 등)
├── item/              # 항목 (양파, 당근 등)
├── post/              # 공동 구매 글
├── participation/     # 참여자 정보
├── common/            # 공통 인터셉터, 유틸 등
├── config/            # 환경 변수 설정
└── main.ts            # 앱 진입점
```

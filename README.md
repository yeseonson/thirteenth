# 13월의 가계부

> 연중에 미리 보는 연말정산

## 구성

| 영역   | 구성                                         | 폴더                 |
| ------ | -------------------------------------------- | -------------------- |
| BE     | NestJS + TypeORM (Docker → EC2)              | [server/](server/)   |
| FE     | Next.js 정적 빌드 + PWA (Cloudflare Pages)   | [web/](web/)         |
| DB     | Supabase (Postgres + Auth)                   | -                    |
| Deploy | GitHub Actions (테스트 → 빌드 → 배포)        | [.github/workflows/](.github/workflows/) |
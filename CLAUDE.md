# KWS 업무 포털 — 프로젝트 전용 규칙

> 문서 저장·GitHub 연동 등 공통 규칙은 전역 CLAUDE.md 적용

## 프로젝트 정보

- **서비스**: KWS 업무 포털 (대한사회복지회 사내 링크 포털)
- **포털 주소**: https://kwsdeveloper.github.io/kws-project
- **GitHub 저장소**: https://github.com/kwsDeveloper/kws-project
- **로컬 경로 (PC 1)**: C:\ClaudeProjects\kws-portal\
- **주요 파일**: index.html (단일 HTML SPA)

## 기술 구성

- **호스팅**: GitHub Pages (master 브랜치 자동 배포)
- **데이터 저장**: Supabase PostgreSQL
- **API**: Supabase Edge Function (portal-api)
- **Supabase 프로젝트 Ref**: czrdvknzbkmryvnjyiki

## 코드 수정 규칙

- index.html 수정 후 반드시 `git push`까지 완료
- Supabase Service Role 키는 절대 index.html에 포함하지 않음
- 민감 정보(비밀번호, API 키)는 답변에 재출력하지 않음

# python-fastapi-study

백엔드(Java/Kotlin + Spring) 개발자의 Python · FastAPI 학습 기록.
6주 동안 직접 코드를 치면서 배우고, 마지막에는 LLM 기능이 붙은 API 서버를 만들어 배포한다.

## 로드맵

| 주 | 주제 | 만드는 것 | 폴더 (예정) |
|---|---|---|---|
| 1 | 파이썬 핵심 (Java/Kotlin과 비교) | 외부 API를 부르는 CLI 도구 + 테스트 | `week1-cli` |
| 2 | FastAPI 기초 | 메모리 저장 CRUD API + Swagger 문서 | `week2-fastapi` |
| 3 | FastAPI + DB · 인증 | 로그인 + CRUD API (PostgreSQL) | `week3-db-auth` |
| 4–6 | 최종 프로젝트 | LLM 기능 붙은 API 서버: 기획 → 구현 → 배포 | 별도 저장소 |
| 7–8 | (선택) Django | API 일부를 Django로 다시 만들기 | `week7-django` |

## 기술 스택

Python · uv · Ruff · pytest · httpx · FastAPI · Pydantic · SQLAlchemy · Alembic · PostgreSQL · Docker · Claude API (Anthropic SDK) · Django

## 개발 환경

- Python: `.python-version`
- 패키지 · 가상환경 관리: uv

## 규칙

- 모든 실습 코드는 직접 친다. 복붙하지 않는다.
- 수업이 끝날 때마다 커밋한다.

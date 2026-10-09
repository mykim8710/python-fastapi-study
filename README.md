# python-fastapi-study

백엔드(Java/Kotlin + Spring) 개발자의 Python · FastAPI · Django 학습 기록.
8주 동안 직접 코드를 치면서 배운다. 같은 API 명세를 FastAPI로 먼저 만들고, 다음 주에 Django로 다시 만들어 두 프레임워크를 비교한다.
마지막에는 Django와 FastAPI 두 서비스를 연동한 LLM 서비스 백엔드를 만들어 배포한다.

## 로드맵

| 주 | 주제 | 만드는 것 | 폴더 (예정) |
|---|---|---|---|
| 1 | 파이썬 핵심 (Java/Kotlin과 비교) | 외부 API를 부르는 CLI 도구 + 테스트 | `week1-cli` |
| 2 | FastAPI 기초 | 메모리 저장 CRUD API + Swagger 문서 | `week2-fastapi` |
| 3 | Django 기초 (DRF) | 2주차와 같은 CRUD API (SQLite) + 관리자 페이지 | `week3-django` |
| 4 | FastAPI + DB · 인증 | 로그인 + CRUD API (SQLAlchemy · Alembic · PostgreSQL) | `week4-fastapi-db` |
| 5 | Django + DB · 인증 | 4주차와 같은 명세 (Django ORM · 마이그레이션 · auth) | `week5-django-db` |
| 6–8 | 최종 프로젝트 | Django(회원 · 관리자 · 대화 기록) + FastAPI(LLM 스트리밍 · RAG) 두 서비스: 기획 → 구현 → 배포 | 별도 저장소 |

## 기술 스택

- 공통: Python · uv · Ruff · pytest · httpx · PostgreSQL · Docker · Claude API (Anthropic SDK)
- FastAPI: FastAPI · Pydantic · SQLAlchemy · Alembic
- Django: Django · Django REST Framework

## 개발 환경

- Python: `.python-version`
- 패키지 · 가상환경 관리: uv

## 규칙

- 모든 실습 코드는 직접 친다. 복붙하지 않는다.
- 수업이 끝날 때마다 커밋한다.

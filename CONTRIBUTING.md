# Contributing to CultureMate

## 저장소 역할

- 화면과 사용자 경험 변경은 `CultureMate-frontend`에서 작업합니다.
- API와 데이터 변경은 `CultureMate-backend`에서 작업합니다.
- 통합 실행, 아키텍처와 공통 문서는 이 저장소에서 작업합니다.

## 작업 흐름

1. `develop`에서 기능 브랜치를 만듭니다.
2. 변경 범위에 맞는 테스트를 추가하거나 실행합니다.
3. Pull Request에 변경 이유와 확인 방법을 작성합니다.
4. 리뷰와 필수 테스트가 끝난 뒤 병합합니다.
5. 통합 저장소의 submodule 포인터가 필요하면 검증된 커밋으로 갱신합니다.

## 브랜치 이름

```text
feature/<issue>-short-description
fix/<issue>-short-description
docs/<issue>-short-description
```

실제 API 키, 비밀번호와 개인용 `.env` 파일은 커밋하지 않습니다.

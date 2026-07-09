# music-prompt-guides

Claude 아티팩트로 만든 음악 프롬프트 가이드 HTML 백업 저장소.
저장소가 원본(source of truth)이고, 아티팩트는 배포본이다.

## HTML 수정 의뢰 워크플로

수정 의뢰가 오면 아래 3단계를 한 번에 수행한다:

1. 저장소의 HTML 파일 수정
2. git 커밋 (push는 사용자 승인 후)
3. **같은 아티팩트 URL에 재배포** — Artifact 도구에 아래 매핑 표의 URL을 `url` 파라미터로 전달해 기존 링크를 유지한 채 내용만 갱신한다. 새 URL을 만들지 말 것.

## 파일 ↔ 아티팩트 URL 매핑

| 파일 | 아티팩트 URL |
|------|--------------|
| `2026-ai-composition-prompt-guidebook.html` | https://claude.ai/public/artifacts/30dec025-f08d-4a39-8552-3d3811cf0e30 |
| `music-prompt-guide.html` | https://claude.ai/public/artifacts/eda6f4ce-1d20-409b-b83f-fb00670dd981 |

## 전제조건

- 모든 콘텐츠는 반드시 한국어·일본어 2개 언어를 함께 대응한다.
- HTML은 외부 의존성 없는 단일 파일로 유지한다 (오프라인 동작 보장).

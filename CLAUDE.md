# music-prompt-guides

음악 프롬프트 가이드 HTML 저장소. GitHub Pages로 공개 배포한다.
저장소가 원본(source of truth)이고, Pages 링크가 공식 공유 링크다.

## HTML 수정 의뢰 워크플로

수정 의뢰가 오면 아래를 한 번에 수행한다:

1. 저장소의 HTML 파일 수정 — 표지 `cover-date`도 수정일로 갱신
   (한국어판·일본어판 각각 있음. 예: `최종 수정 2026.07.09` / `最終更新 2026.07.09`)
2. git 커밋 + **push** — push까지 해야 Pages에 반영된다.
   이 저장소의 유지보수 push는 사용자가 사전 승인함 (2026-07-09).
3. push 후 1~2분 내 Pages 자동 배포. 필요 시 공유 링크를 열어 반영 확인.

## 공유 링크 (GitHub Pages)

| 파일 | 공유 링크 |
|------|-----------|
| `2026-ai-composition-prompt-guidebook.html` | https://solnime.github.io/music-prompt-guides/2026-ai-composition-prompt-guidebook.html |
| `music-prompt-guide.html` | https://solnime.github.io/music-prompt-guides/music-prompt-guide.html |

## 전제조건

- 모든 콘텐츠는 반드시 한국어·일본어 2개 언어를 함께 대응한다.
- HTML은 외부 의존성 없는 단일 파일로 유지한다 (오프라인 동작 보장).
- 저장소는 public이다 — 민감 정보(키·토큰·개인정보)를 절대 커밋하지 말 것.

## 이력

- 2026-07-09: claude.ai 아티팩트 링크 → GitHub Pages로 이관.
  구 claude.ai 공개 아티팩트 링크와 Claude Code 아티팩트 링크는 폐기 대상
  (Claude Code 아티팩트는 Max 플랜에서 공유 불가로 확인됨).
  문제가 생기면 claude.ai 아티팩트 방식으로 복귀 가능성 있음.

# music-prompt-guides

Claude 아티팩트로 만든 음악 프롬프트 가이드 HTML 백업 저장소.
저장소가 원본(source of truth)이고, 아티팩트는 배포본이다.

## HTML 수정 의뢰 워크플로

수정 의뢰가 오면 아래 단계를 한 번에 수행한다:

1. 저장소의 HTML 파일 수정 (표지 `cover-date`도 수정일로 갱신)
2. git 커밋 (push는 사용자 승인 후)
3. 배포용 사본 생성 — Artifact 도구는 DOCTYPE/head/body 골격을 자동으로 씌우므로,
   저장소 HTML에서 `<!DOCTYPE>`·`<html>`·`<head>`·`<body>` 태그를 제거하고
   `<title>`·`<style>`·본문만 남긴 사본을 스크래치패드에 만든다
4. **같은 아티팩트 URL에 재배포** — Artifact 도구에 아래 매핑 표의 URL을 `url` 파라미터로
   전달해 기존 링크를 유지한 채 내용만 갱신한다. 새 URL을 만들지 말 것.
   favicon도 표의 값으로 고정 유지.

## 파일 ↔ 아티팩트 URL 매핑

| 파일 | 아티팩트 URL | favicon |
|------|--------------|---------|
| `2026-ai-composition-prompt-guidebook.html` | https://claude.ai/code/artifact/ff08b662-e949-428f-8119-bd381699f50d | 🎵 |
| `music-prompt-guide.html` | https://claude.ai/code/artifact/53cdacca-87c7-4ece-be31-e479c722c518 | 🎼 |

> 구 claude.ai 대화 아티팩트 링크(claude.ai/public/artifacts/...)는 Claude Code에서
> 갱신 불가하여 2026-07-09에 위 링크로 이관. 구 링크는 사용자가 claude.ai에서 직접 삭제.

## 전제조건

- 모든 콘텐츠는 반드시 한국어·일본어 2개 언어를 함께 대응한다.
- HTML은 외부 의존성 없는 단일 파일로 유지한다 (오프라인 동작 보장).
- HTML 수정 시 표지의 `cover-date`를 수정한 날짜로 갱신한다. 한국어판·일본어판 각각 있음
  (예: `최종 수정 2026.07.09` / `最終更新 2026.07.09`).

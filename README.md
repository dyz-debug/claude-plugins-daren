# claude-plugins-daren

Daren이 만든 Claude Code 플러그인 모음.

## 포함된 플러그인

### `/lite` — 가벼운 모드 전환

Claude Code를 자료조사·일반 질의·짧은 답변용 모드로 전환하는 슬래시 커맨드.

- 짧고 직접적인 답변 (헤더·표·구조화 자제)
- 도구 호출 최소화 (`WebFetch`/`WebSearch`/`Read`만)
- 프로젝트 맥락(CLAUDE.md의 BEFORE/WHEN 트리거) 의도적 무시
- 추측은 명확히 표시

본인 프로젝트 작업 요청 또는 "lite 해제"/"풀모드" 키워드가 나오면 자동으로 평소 모드로 복귀.

## 설치

```
/plugin marketplace add dyz-debug/claude-plugins-daren
/plugin install lite@daren-plugins
```

설치 후 Claude Code 세션에서 `/lite` 입력 → 가벼운 모드 진입.

## 라이선스

MIT

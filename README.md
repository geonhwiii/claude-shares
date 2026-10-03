# claude-shares

Claude Code 플러그인과 스킬을 모아 두는 저장소입니다.

## 설치

Claude Code에서 마켓플레이스를 한 번 추가한 뒤 원하는 플러그인을 설치합니다.

```
/plugin marketplace add geonhwiii/claude-shares
/plugin install <plugin>@claude-shares
```

## 플러그인

| 이름 | 설명 |
| --- | --- |
| [turn-progress](plugins/turn-progress) | 프롬프트 위에 턴 진행 상태(요청 → 생각 → 작업 → 답변)를 바 한 줄로 보여줍니다. |

## 구조

```
.claude-plugin/marketplace.json   마켓플레이스 목록
plugins/<name>/                   플러그인마다 폴더 하나
```

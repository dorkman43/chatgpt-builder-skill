# ChatGPT 만들기 지침 (chatgpt-builder)

비개발자가 ChatGPT(무료 포함)와 MCP 도구로 업무 도구·설문·웹 화면을 만들 때, **AI가 지킬 지침**이에요. 쉬운 대화, 쓰기 전 확인, 개인정보 보호, 공개 설문, 화면 문구·디자인, 무료 사용량 절약을 다뤄요.

<img src="qr.png" alt="이 저장소 주소 QR 코드" width="160">

## 들어 있는 것
| 파일 | 내용 |
|---|---|
| `custom-instructions.txt` | 핵심 16줄(짧은 판). ChatGPT 맞춤 설정에 그대로 붙여 넣어요 |
| `SKILL.md` | 짧은 판 + 주제별 상세(대화 방식, 만드는 순서, 안전, 개인정보, 공개 설문, 화면 문구, 검사 실패, 배포, 사용량, 하지 않는 것, 대화 예시) |
| `LICENSE` | Apache-2.0 |

## 쓰는 법
### ChatGPT (무료 포함)
1. `custom-instructions.txt`를 열어 전체를 복사해요.
2. ChatGPT **설정 → 맞춤 설정**의 "ChatGPT가 어떻게 응답하기를 원하시나요?" 칸에 붙여 넣고 저장해요.
3. 새 대화를 열면 적용돼요. 메뉴 이름과 위치는 ChatGPT 화면이 바뀌면 달라질 수 있어요.

### Claude Code · Codex 같은 코딩 에이전트
`SKILL.md`가 들어 있는 이 폴더를 에이전트의 스킬 폴더에 넣어요. 예: 저장소의 `.agents/skills/chatgpt-builder/` 또는 `.claude/skills/chatgpt-builder/`.

## 참고
- 도구 이름(`start`, `add_tool` 등)은 이 지침을 만든 MCP 기준의 예시예요. 다른 MCP에서는 그 도구 이름으로 바꿔 읽으면 돼요.
- 의견과 고칠 점은 이슈로 남겨 주세요.

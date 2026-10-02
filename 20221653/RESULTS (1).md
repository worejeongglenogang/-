# 5주차 4교시 — Slack API 메시지 전송

## 한 일
- [x] Create New App → Blank app
- [x] Bot Token Scopes 에 `chat:write` 추가
- [x] Install → Bot User OAuth Token(xoxb-) 발급 → `.env` 저장
- [ ] `/invite @앱이름` 으로 #수업-출력물 채널에 봇 초대
- [ ] `send_slack_message.py` 실행 → 메시지 도착 확인
- [ ] `chain_to_slack.py` 실행 → 체인 결과가 슬랙에 도착

## 만난 에러와 해결 과정

| 에러 코드 | 원인 | 해결 |
|-----------|------|------|
| (예) not_in_channel | 봇이 채널에 없음 | 채널에서 `/invite @앱이름` |

## 확인 사항
- 메시지 도착 화면 캡처 (토큰 노출 없이)
- `git status` 에 `.env` 가 나타나지 않는지 확인

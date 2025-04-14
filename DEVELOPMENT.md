1. https://github.com/sonnylazuardi/cursor-talk-to-figma-mcp 접속하여 프로젝트 다운로드
2. 커서AI 툴 설치하여 1번에서 다운로드 받은 프로젝트 열기
3. 커서AI 상단 툴바에서 Terminal > New Terminal 선택
4. bun 설치 : curl -fsSL https://bun.sh/install | bash
5. bun 설치 확인 : bun --version
6. bun 설정 실행 : bun setup
7. bun 웹소켓 서버 시작 : bun socket
8. 새터미널 커서AI 상단 툴바에서 Terminal > New Terminal 선택하여 열기
9. MCP 서버 실행 : bunx cursor-talk-to-figma-mcp
10. 피그마 툴 설치하여 빈 디자인파일 생성
11. 피그마 툴 상단 Plugins > Development > Import Plugin from manifest 선택
12. 1번에서 받은 프로젝트 경로에 src > cursor_mcp_plugin > manifest.json 열기
13. 피그마에서 플러그인 팝업이 나오면 Cursor MCP Plugin 실행 -> 서버 연결 확인가능
14. 피그마 플러그인에서 채널명 확인 후 커서AI 툴 chat을 이용하여 채널 연걸 하기 : Join channel 채널명
15. chat 결과로 run tool 나올시 실행 -> 실패해도 커서AI가 수정해줌
16. 커서AI chat을 이용해서 디자인 연동 확인
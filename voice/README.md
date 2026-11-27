# voice/
이 폴더의 mp3를 홈페이지가 먼저 재생합니다 (아이폰 무음 모드에서도 재생됨).
파일이 없으면 브라우저 음성 읽기로 대신합니다.
만들 파일 목록과 문장: ../voice_lines.json
생성 예: edge-tts --voice ko-KR-InJoonNeural --rate=+5% --text "문장" --write-media voice/greet.mp3

수달·족제비 AI 분류 사이트

실행 방법
1. 이 ZIP 파일을 압축 해제합니다.
2. 폴더 안의 index.html을 로컬 웹 서버로 실행합니다. (model.json, weights.bin, metadata.json이 같은 폴더에 있어야 합니다.)
3. 간단한 방법: VS Code에서 폴더를 열고 Live Server 확장으로 index.html을 실행합니다.
   또는 Python이 설치되어 있다면 폴더에서 `python -m http.server 8000` 실행 후 http://localhost:8000 접속합니다.
4. 인터넷 연결이 필요합니다. TensorFlow.js와 Teachable Machine 라이브러리를 CDN에서 불러옵니다.

참고
- 업로드한 Teachable Machine 모델(model.json, weights.bin, metadata.json)을 그대로 사용합니다.
- 분류 클래스: 족제비, 수달
- 사진은 브라우저에서 모델로 분석하며 서버로 업로드하지 않습니다.

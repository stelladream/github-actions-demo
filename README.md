# github-actions-demo

이 GitHub Actions 워크플로우는 push 이벤트가 발생하면 자동으로 실행됩니다. 
Explore-GitHub-Actions 작업은 ubuntu-latest 환경에서 실행되며, 현재 이벤트, 서버 운영체제, 브랜치 이름 및 저장소 정보를 출력합니다. 
actions/checkout을 사용하여 저장소 코드를 체크아웃하고, 파일 목록을 표시해 코드를 테스트할 준비가 되었음을 확인합니다. 
마지막으로 작업의 상태를 출력하여 성공 여부를 알립니다. 
Fork한후, 소스 코드를 커밋/푸시하면 workflow가 자동 실행됩니다.

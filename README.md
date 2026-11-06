# SOFTM 앱 다운로드

다운로드 사이트: https://softm.github.io/apks/

- 이 저장소는 앱 다운로드 페이지와 releases.json을 관리합니다.
- APK 원본은 이 저장소의 GitHub Releases에 버전별로 보관합니다. Git에는 바이너리를 커밋하지 않습니다.
- 릴리스 태그는 앱 식별자-versionCode, 파일명은 앱-versionCode-release.apk입니다.
- 새 버전은 실제 서명된 Release APK를 설치 검증한 뒤 게시합니다. 패키지·버전·서명·SHA-256을 확인합니다.
- releases.json의 앱별 releases는 최신 버전부터 정렬하고 file에는 Release asset의 절대 URL을 기록합니다.
- 이전 APK를 덮어쓰지 않으며, 비밀번호·키스토어·개인 키를 저장하지 않습니다.
- APK 업로드와 페이지 게시 후 다운로드 파일의 SHA-256을 대조합니다.
- 2026-11-07 softm/softm.github.io의 apks 폴더에서 이관했습니다.

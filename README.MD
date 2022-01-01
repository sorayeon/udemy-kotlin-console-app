# Kotlin 실습

### Kotlin 콘솔앱 프로젝트 생성

- 프로젝트 생성
  - IntelliJ IDEA 실행
  - New Project
  - Kotlin 프로젝트
    - Name : udemy-kotlin-console-app
    - Project Template : Console Application 
    - Build System : Gradle Groovy
    - Project JDK : 11
    - JVM Version : 11
    - Finish
- 프로젝트 구성완료
  - MainKt 실행
  - build -> Hello World! 출력
  - build 폴더 생성
  
### IntelliJ 와 GitHub 연동

- Git 설치확인
  - Preferences | Version Control
  - Git : Path -> detected 확인
- GitHub 계정 연동
  - Add (+) 
  - Log in via GitHub..
  - 브라우저 창에서 Authorize in GitHub 버튼 클릭
  - intelliJ 와 연결 허용
  
### GitHub Repository 연동

- GitHub Repository 생성
  - github.com 로그인
  - (+) New repository 클릭
  - Repository name : udemy-kotlin-console-app
  - Public 저장
  - Create Repository 버튼 클릭
- Git 으로 버전관리 설정
  - intelliJ 
  - VCS -> Enable Version Control Integration 메뉴 선택
  - Git 으로 설정
  - 완료되면 버전이 관리되지 않은 파일의 색상이 변경
- GitHub Repository 등록 (intelliJ 연동)
  - Git -> Manage Remotes 메뉴 선택
  - Add (+) 
  - URL : https://github.com/sorayeon/udemy-kotlin-console-app.git
- gitignore 추가
  - https://www.toptal.com/developers/gitignore
  - 운영체제, 빌드도구, 개발환경, IDE 등 추가\
    - (macOS, Gradle, Kotlin, Intellij+all)
- 첫번째 Commit 하기
  - 프로젝트 생성
  - master -> main branch 로 변경
- Commit Push 하기
  - Git -> Push
  - github.com 에서 확인하기
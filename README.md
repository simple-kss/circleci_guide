# circleci_guide

CircleCI -> Go to Application -> Project -> Repo name 에 현재 프로젝트 등록

### 기본 용어
- version : CircleCI의 언어 버전
- jobs: 작업 목록
- build: 작업의 이름. build가 아니어도 됨
- docker: <executor>를 docker로 쓰겠다는 의미
  - image: 사용할 커스텀 도커이미지 이름

- run: 모든 프로그램 명령어를 실행시키기 위해 사용됨
  - command: 쉘을 통해 실행할 명령어들 (필수로 작성)
  - working_directory: 이 스텝을 실행하기 위한 디렉토리 위치 (작업의 working_directory로 생각해도 됨) (default는 .임) (필수로 작성 X)
  - environment: 맵임, 환경변수와 값들을 위한. (필수로 작성 X)





### 출처
아래의 정보를 내가 요약해서 정리함.




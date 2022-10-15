## Git 이란?

- 형상관리도구 중 하나로, 버전 관리 시스템이라고도 한다
- Git은 프로젝트 소스코드를 효과적으로 관리할 수 있는 시스템

<img src="https://velog.velcdn.com/images/im_sulhwa/post/8528f0d0-236f-4c35-9d21-b75afd3cfa6f/image.png"></img>

## Git 초기화

- 명령어 : git init
- 초기화 할 대상 폴더에서 명령어 (git init) 입력
- Git 초기화 시 폴더 안에 숨김 폴더로 .git 폴더 생성 (Local Config 등으로 구성)

> 초기화는 폴더 안에 들어가는 모든 파일(문서, 소스코드 ..)을 깃으로 관리한다고 선언한다는 뜻!
> → Local repository를 만든다고도 한다.

## Git commit

- 명령어 : git commit
- 로컬 저장소(local repository)에 코드 변경 이력을 남기기 위해서 사용
- Staging Area에 등록된 파일을 Local Storage로 등록 (add한 파일을 stagingArea에서 Local Repository로)

> git commit으로 코드 변경 이력을 남기더라도 원격 저장소에서는 알 수 없어서 반드시 git push를 날려 그 동안 로컬 저장소에서 남긴 코드 변경 이력들이 원격 저장소로 전송해야한다 !

## Git push

- 명령어 : git push
- Local Storage에서 변경된 파일들을 Remote Repository(원격저장소)로 등록

> git commit 이후 git push를 하면 로컬 저장소에 있는 변경 이력이 원격 저장소에도 반영된다 !

## Git branch

- 명령어 : git checkout < branch >
- 체크아웃(checkout)이란, 내가 사용할 브랜치를 지정하는 것을 의미
  <br>
- 명령어 : git checkout -b
- 새로운 브랜치 생성

> 명령어가 실행되면 현재 작업 중인 브랜치에서 새 브랜치가 생성, 새 브랜치의 커밋 히스토리는 작업하고 있던 브랜치의 마지막 커밋에서 시작된다!

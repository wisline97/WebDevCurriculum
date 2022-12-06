# Quest 00. 형상관리 시스템

## Introduction
* git은 2021년 현재 개발 생태계에서 가장 각광받고 있는 버전 관리 시스템입니다. 이번 퀘스트를 통해 git의 기초적인 사용법을 알아볼 예정입니다.

## Topics
* git
  * `git clone`, `git add`, `git commit`, `git push`, `git pull`, `git branch`, `git stash` 명령
  * `.git` 폴더
* GitHub

## Resources
* [Resources to learn Git](https://try.github.io)
* [Learn Git Branching](https://learngitbranching.js.org/?locale=ko)
* [Inside Git: .Git directory](https://githowto.com/git_internals_git_directory)

## Checklist
* 형상관리 시스템은 왜 나오게 되었을까요?
  > 형상관리 시스템은 변화를 체계적으로 준비하고 또 관리하기 위해서 나오게 되었다.
* git은 어떤 형상관리 시스템이고 어떤 특징을 가지고 있을까요? 분산형 형상관리 시스템이란 무엇일까요?
  > git은 2005-07-11에 리누스 토르발스에 의해 개발된 분산형 버전관리 시스템(DVCS)이다. 무료 공개 소프트웨어이다. Git이란 이름은 사실 아무 의미도 없다 해석하기 나름. 랜덤한 알파벳을 발음이 가능하도록 조합한 것일 뿐이다.
  > 분산 모델(DVCS)은 프로젝트에 참여하는 모든 개발자가 전체 저장소에 대한 복사본 갖고 작업하는 형태이다. 각자가 온전한 전체 저장소의 사본을 본인의 컴퓨터에 가지는 형태이다.
  * git은 어떻게 개발되게 되었을까요? git이 분산형 시스템을 채택한 이유는 무엇일까요?
    > git은 리눅스의 창시자 리누스 토르발스에 의해 개발되었다.
    > 리눅스는 불편하고 비효율적인 작업환경 속에서 약 26년 동안 1만 명이 넘는 소프트웨어 엔지니어들이 함께 개발했는데 이런 환경을 개선하기 위해 리누스 토르발스가 세상에 “지옥에서 온 관리자” Git을 소개하게 되었다. 
* git과 GitHub은 어떻게 다를까요?
  > git은 소스 코드 수정에 따른 버전을 관리해주는 시스템 그 자체이고, github는 이 시스템을 지원하는 웹 호스팅 시스템이다. github가 존재하지 않았을 때는 CD, 이메일, USB를 사용했다.
* git의 clone/add/commit/push/pull/branch/stash 명령은 무엇이며 어떨 때 이용하나요? 그리고 어떻게 사용하나요?
  > git clone 사용법
  > 1. command line을 통해 해당 깃을 가져오고자 하는 폴더로 이동한다.(윈도우의 경우 cd Desktop 명령어를 쳐서 이동)
  > 2. git clone 명령어를 사용하여 복사하고자 하는 url을 입력해준다 git clone https://github.com/wisline97/WebDevCurriculum.git
  > 3. 그럼 클론 성공!
* git의 Object, Commit, Head, Branch, Tag는 어떤 개념일까요? git 시스템은 프로젝트의 히스토리를 어떻게 저장할까요?
* 리모트 git 저장소에 원하지 않는 파일이 올라갔을 때 이를 되돌리려면 어떻게 해야 할까요?

## Quest
* GitHub에 가입한 뒤, [이 커리큘럼의 GitHub 저장소](https://github.com/KnowRe-Dev/WebDevCurriculum)의 우상단의 Fork 버튼을 눌러 자신의 저장소에 복사해 둡니다.
* Windows의 경우 같이 설치된 git shell을, MacOSX의 경우 터미널을 실행시켜 커맨드라인에 들어간 뒤, 명령어를 이용하여 복사한 저장소를 clone합니다.
  * 앞으로의 git 작업은 되도록 커맨드라인을 통해 하는 것을 권장합니다.
* 이 문서가 있는 폴더 바로 밑에 있는 sandbox 폴더에 파일을 추가한 후 커밋해 보기도 하고, 파일을 삭제해 보기도 하고, 수정해 보기도 하면서 각각의 단계에서 커밋했을 때 어떤 것들이 저장되는지를 확인합니다.
* `clone`/`add`/`commit`/`push`/`pull`/`branch`/`stash` 명령을 충분히 익혔다고 생각되면, 자신의 저장소에 이력을 push합니다.

## Advanced
* Mercurial은 어떤 형상관리 시스템일까요? 어떤 장점이 있을까요?
* 실리콘밸리의 테크 대기업들은 어떤 형상관리 시스템을 쓰고 있을까요?


# github 01
## GIT
- version control system
(버전관리체계)
## hub 등재 과정
1. 작업한다. (workstaion)
2. 세운다. (stage)
3. 등재한다. (commit)
## 이용절차
```sh
$ git init # 현 directory에 .git 생성 (master)
$ git config --global user.name "name" # 사용자 이름 지정
$ git config --global user.email "id@email.com" # 사용자 이메일 지정
$ git add (filename) # 해당 파일을 stage에 마운트
$ git commit -m # 현재 directory에 stage된 파일을 commit
$ git push <nickname> <branch> # commit된 파일을 github에 업로드
```
## 그 외
```sh
$ git status # 파일 stage여부 확인
$ git log # 내역 확인
$ cat ~/.gitconfig # 서명이 정상적으로 등록되어 있는지 확인
$ git remote add <nickname> <URL> # github에 있는 remote연결
$ git pull <nickname> <branch> # remote파일 불러오기
$ git clone <url> # remote 복제
$ git remote -v # 등록된 저장소 확인
```

## Worning
1. 현재위치 확인
2. home 디렉토리 또는 repo.하위 디렉토리에 `git init` 금지
3. branch숙달 전 github에 파일 편집 직접 금지

## 프로젝트 작업 절차
|When|Command|
|-|-|
|프로젝트 시작|`$ mkdir project`|
|해당폴더 이동|`$ cd project`|
|repo. 초기화|`$ git init`|
|README, gitignore 생성|`$ touch README.md .gitignore`|
|파일 스테이징|`$ git add .`|
|commit|`$ git commit -m '짧고 간결한 메세지'`|
|원격저장소 생성|github 사이트에서 진행|
|원격저장소 등록|`$ git remote add origin <URL>`|
|원격저장소 업로드|`$ git push origin master`|
|다른 컴퓨터에서 원격저장소 복제|`$ git clone <URL>`|
|작업|`$ git add`, `$ git commit`|
|귀가 직전|`$ git push origin master`|
|집 도착 이후|`$ git pull origin master`|
|작업|`$ git add`, `$ git commit`|
|작업 종료|`$ git push origin master`|
|다른 컴퓨터에서 반복|`$ git pull origin master`|
# git 1일차
## GIT
- version control system
(버전관리체계)
## hub 등재 과정
1. 작업한다. (workstaion)
2. 세운다. (stage)
3. 등재한다. (commit)
## 이용절차
```
$ git init # 현 directory에 .git 생성 (master)
$ git add (filename) # 해당 파일을 stage에 마운트
$ git commit -m (현재 directory에 stage된 파일을 github에 등재)
```
## 그 외
```
$ git status # 파일 stage여부 확인
$ git log 내역 확인
$ git config --global user.name "name" 사용자 이름 지정
$ git config --global user.email "id@email.com" 사용자 이메일 지정
```
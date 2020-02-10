# Hello Git World

## 1. local에 폴더 생성하기
## 2. 해당 폴더 위치에서 git 선언하기 (git 설치 안되어 있으면 설치하기)
```
git init
```
## 3. github에 repository 생성하기
## 4. 로컬에 있는 폴더에 github로 올릴  파일 두기
## 5. local 폴더 위치에서 add 하기
```
git add *
```
## 6. add 한 내용들 commit 하기
(
	-m, --message <message>
	-a, --all             commit all changed files
)
```
git commit -am "커밋 내용"
```
## 7. 최초 커밋시 연결하기 
```
git remote add origin http://github.com/@@@/###
```
## 8. push 하여 레파지토리에 commit 반영하기
```
git push origin master
```
## 9. 다음 반영시 add / commit / push 반복.

# ** 유효한 명령어 ** 
## git status : 현재 상태(add/commit) 보기
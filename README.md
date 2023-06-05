# Git 명령어

## Git 로컬 컴퓨터에서 사용자 등록하기

- git config --global user.name "rkawkclsrn"
- git config --global user.email "rkawkclsrn@naver.com"

## Git 시작하기

- git init
- git add .
- git commit -m "최초 커밋"

## Github 업로드하기

- git remote add origin 주소
- git push origin master

## 다시 업로드 법

- 소스코드 변경
- git add .
- git commit -m "변경내용적고"
- git push origin master

## 잘안될때 해결법

- git remote -v
- git remote rm origin
- git remote add origin https://github.com/rkawkclsrn/HelloWorld.git
- git remote -m "변경내용 적고"

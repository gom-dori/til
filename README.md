# TIL(Today I Learned)

## 2017-07-24

### FastC CS 01

- git

  아주 기본적인 명령어

  ```shell
  git status
  git config --global user.name "username"
  git.config --global user.email "github email"
  git config --list
  ```

  git의 구조는 workspace > index > local repo > remote repo로 되어있다

  origin을 등록한 후 add init > add > commit > push 순으로 업데이트

  ```shell
  git init
  git add <file name>
  git commit -m "commit에 대한 코멘트"
  ```

  깃허브에 repo를 만든 후에 

  ```shell
  git remote add origin <url address>
  git push origin master
  ```

- math

  반지름 r을 10으로 선언하고 지름, 둘레, 넓이, 구의 부피 구하기
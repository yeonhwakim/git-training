# git-training

### 저장소 생성

1. git clone 원격저장소

2. 
  $ echo "# test" >> README.md

  $ git init

  $ git add README.md

  $ git commit -m "first commit"

  $ git branch -M main

  $ git remote add origin 원격 저장소 주소

  $ git push -u origin main

  $ git remote add origin 원격 저장소 주소

  $ git branch -M main

  $ git push -u origin main


### 기본 명령어
  ```
  $ git add .
  ```

  ```
  $ git commit -m 커밋명 => 안티패턴

  $ git commit => 타이틀 / 한 줄 띄고 / 내용

  * 커밋 vscode 에디터에서 수정
  $ git config --global core.editor "code --wait"
  ```

  [좋은 git 커밋 메시지를 작성하기 위한 8가지 약속](https://djkeh.github.io/articles/How-to-write-a-git-commit-message-kor/)

  [git 커밋 가이드](https://commit.style/)

  ```
  $ git push origin main
  ```

  #### 기본 명령어 실습
  기본 명령어 작성후 바로 실습.

  #### 좋은 git 커밋 메시지 작성 실습
  
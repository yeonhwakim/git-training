# git-training

### 저장소 생성

1. git clone 원격저장소

2. 
  ```
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
  ```

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

  ```
  $ git pull origin main
  ```

  #### 기본 명령어 실습
  기본 명령어 작성후 바로 실습.

  #### 좋은 git 커밋 메시지 작성 실습
![커밋연습](https://user-images.githubusercontent.com/47783128/148632676-1b48e8f0-aebf-462f-9227-b6cb97325f75.PNG)

### 브랜치
  - 커밋 사이를 가볍게 이동할 수 있는 어떤 포인터 같은 것이다.
  - 독립적인 작업공간.

  브랜치 생성

  ```
    $ git branch 브랜치명
  ```

  브랜치 확인

  ```
    로컬 - $ git branch

    원격 - $ git branch -r

    로컬, 원격 - $ git branch -a

    커밋정보 - $ git branch -v
  ```

  원격 브랜치 가져오기

  ```
    $ git branch -t 브랜치명
  ```

  브랜치 전환

  ```
    $ git checkout 브랜치명

    $ git switch 브랜치명
  ```

  브랜치 생성 & 전환

  ```
    $ git checkout -b 브랜치명
  
    $ git switch -c 브랜치명

  ```

  * checkout 과 switch

  ```
    - checkout: Switch branches or restore working tree files (switch + restore)

    - switch: Switch branches

    - restore: Restore working tree files
  ```

  로컬 브랜치 삭제

  ```
    $ git branch -d 브랜치명 - 안전 (병합되지 않은 변경사항이 있는경우 삭제방지)

    $ git branch -D 브랜치명 - 강제 삭제
  ```

  원격 브랜치 삭제

  ```
    $ git push origin --delete 브랜치명

    $ git push origin :브랜치명
  ```

  브랜치명 수정

  ```
    main 브랜치에서
    $ git branch -m old_브랜치명 new_브랜치명

    해당 브랜치에서
    $ git branch -m new_브랜치명
  ```

  브랜치 병합

  ```
    $ git merge 브랜치명

      - fast forward

      - merge commit
  ```
   #### 브랜치 명령어 실습
   ##### 브랜치 생성 확인
   
![브랜치 생성 확인](https://user-images.githubusercontent.com/47783128/148634911-cdf9a999-0e0b-476e-ac09-84d5e01e7642.PNG)

   ##### 로컬 브랜치 원격 저장소에 추가
   
![원격저장소에 브랜치 추가](https://user-images.githubusercontent.com/47783128/148634963-5498680f-eedd-4f21-9a1d-2dcd97f9e4a4.PNG)
![원격 저장소 리스트](https://user-images.githubusercontent.com/47783128/148634994-671e19fa-1487-4e1e-a1ca-5d80c2be660c.PNG)

   ##### 원격 브랜치 로컬에 추가
   
![원격 저장소 추가 리스트](https://user-images.githubusercontent.com/47783128/148634982-ac68101e-a7a5-47ba-b788-26d3a5f2541b.PNG)
![원격저장소 브랜치 로컬저장소에 추가](https://user-images.githubusercontent.com/47783128/148635001-90eb594a-9898-4c0d-81d7-6f563a94b61e.PNG)

   ##### 브랜치 삭제
   
![브랜치 삭제](https://user-images.githubusercontent.com/47783128/148635010-406a8ad7-bf32-4aa2-99b7-f8ba9eda95c2.PNG)
![로컬에서 원격 브랜치 삭제](https://user-images.githubusercontent.com/47783128/148635018-2f1a46ba-72d5-4f7a-9766-89e42e6fed36.PNG)

   #### 브랜치 병합 실습
   * [merge 기초](https://git-scm.com/book/ko/v2/Git-%EB%B8%8C%EB%9E%9C%EC%B9%98-%EB%B8%8C%EB%9E%9C%EC%B9%98%EC%99%80-Merge-%EC%9D%98-%EA%B8%B0%EC%B4%88)

   ##### fast forword 
  main 브랜치 기반으로 새로운 커밋 생성 없이 커밋 이동
  
  [fast forword 실습](branch-fast-forword.md)

   ##### merge commit (Merge made by the 'recursive' strategy.) 
  공통의 부모를 찾아 양쪽을 반영한 새로운 커밋 생성

  [merge commit 실습](branch-merge-commit.md)

   ##### auto merging
  main branch 기반으로 같은 파일을 수정한 경우

  [auto merging 실습](branch-auto-merging.md)

   ##### confilcts 
  같은 부분을 수정한 경우

  [confilcts 실습](branch-confilcts.md)

   ##### 복습  
  [복습](review-merge.md)

### commit 조작
  #### 로컬에서 최근 커밋 수정 (커밋 덮어쓰기)

  ```bash
  $ git commit --amend

  $ git commit --amend --no-edit => 편집기 실행 안됨
  ```
  
  - 커밋 메세지 수정
  - 나중에 수정한 파일 마지막 commit 안에 밀어넣기
  - 커밋을 고치는 내용이 오타를 살짝 고치거나 실수로 빠뜨린 것을 넣는 등 아주 사소하거나 이미 커밋 메시지가 충분히 이를 반영하고 있을 수 있다. 이런 경우 다음과 같이 --no-edit 옵션을 사용하면 커밋 메시지를 수정하도록 편집기가 실행되지는 않는다.

  #### [git commit --amend 복습
  [git commit --amend 복습](commit-amend.md)

  #### 커밋을 버리고 특정 버전으로 다시 되돌아가기, 이전 커밋으로 돌아가기 (커밋 취소)

  ```bash
  $ git reset --soft 돌아가고 싶은 커밋

  $ git reset --mixed 돌아가고 싶은 커밋

  $ git reset --hard 돌아가고 싶은 커밋

  $ git reset --hard ORIG_HEAD 

  $ git reset file path
  ```

  #####  reset 단계
  
  __1 단계: HEAD 이동 (--soft)__

  `$ git reset --soft`

  HEAD는 계속 현재 브랜치를 가리키고 있고, 현재 브랜치가 가리키는 커밋을 바꾼다. => 커밋을 취소 한다.

  * HEAD => 취소한 커밋

  여기서 다시 commit 하면 새로운 커밋생성 (git commit --amend 랑 동일)

  ```bash
  $ git status
  `Changes to be committed''
  ```

  __2 단계: Index 업데이트 (--mixed)__

  `$ git reset --mixed`

  HEAD는 계속 현재 브랜치를 가리키고 있고, 현재 브랜치가 가리키는 커밋을 바꾼다. => 커밋을 취소 한다.

  Index를 현재 HEAD가 가리키는 스냅샷으로 업데이트 => git add 취소

  * HEAD => 취소한 커밋
  * Index => git add 하기전

  ```bash
  $ git status
  `Changes not staged for commit,`
  ```

  __3 단계: 워킹 디렉토리 업데이트 (--hard)__

  `$ git reset --hard`

  HEAD는 계속 현재 브랜치를 가리키고 있고, 현재 브랜치가 가리키는 커밋을 바꾼다. => 커밋을 취소 한다.

  Index를 현재 HEAD가 가리키는 스냅샷으로 업데이트 => git add 취소

  워킹 디렉토리의 내용까지도 되돌린다. => 마지막 커밋을 되돌린다.

  * HEAD => 취소한 커밋
  * Index => git add 하기전
  * Working Directory => 내용까지 되돌림

  ```bash
  $ git status
  `nothing to commit, working tree clean`
  ```

  [Reset 명확히 알고 가기](https://git-scm.com/book/ko/v2/Git-%EB%8F%84%EA%B5%AC-Reset-%EB%AA%85%ED%99%95%ED%9E%88-%EC%95%8C%EA%B3%A0-%EA%B0%80%EA%B8%B0)

  [git reset HEAD^ 실습](reset-head-1.md)

  [git reset HEAD~ 실습](reset-head-2.md)

  [git reset 커밋 실습](reset-commit.md)
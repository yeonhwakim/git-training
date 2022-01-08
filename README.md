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
   ##### fast forword
   ##### auto commit (Merge made by the 'recursive' strategy.)
   ##### auto merging
   ##### confilcts 실습
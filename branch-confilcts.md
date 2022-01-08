### 브랜치 병합 - confilcts 충돌

1. main 브랜치 수정이 있다.
2. 1.을 commit 한다.
3. 새로운 or 기존의 다른 브랜치에서 main 브랜치돠 동일한 부분을 수정한다.
4. 3.번을 commit 한다. 
5. main 브랜치에서 4.를 병합한다.
6. 충돌이 난다.
7. 충돌난 부분 
  <<<< HEAD ... ======== ... >>>> 
  에서 필요한 부분 남기고 저장한다.
8. 새로 commit 한다.

![충돌](https://user-images.githubusercontent.com/47783128/148645119-7a8c2b50-2282-4941-8ded-1bfe257deb33.PNG)

![충돌 재현](https://user-images.githubusercontent.com/47783128/148645110-3a5a3275-dae8-4c57-88f5-d26a173f6a2e.PNG)

![충돌 해결후 커밋](https://user-images.githubusercontent.com/47783128/148645103-713f1d1f-df2c-4bec-a531-18074a917c6a.PNG)

![충돌로그](https://user-images.githubusercontent.com/47783128/148645097-37cd7502-b6c6-41ea-8e41-528d25d9a035.PNG)

### 브랜치 병합 - fast forward

1. main 브랜치는 수정이 없다.
2. 새로운 or 기존의 다른 브랜치에 수정이 있다.
3. 2.번을 commit 한다.
4. main 브랜치에서 2.브랜치를 병합한다.
5. main 브랜치가 3.번 커밋을 바라본다. 

=> 기준 브랜치에서 작업 브랜치의 새로운 커밋이 단순히 최신 커밋으로 더해지고, 기준 브랜치가 바라보는 최신 커밋만 변경된다.

![branch-fast-forward에서 main switch](https://user-images.githubusercontent.com/47783128/148645410-abb82072-7bd0-4d06-b621-582b69b1ea2e.PNG)

![fast forward 결과](https://user-images.githubusercontent.com/47783128/148645384-9a677f75-f93c-43ec-a1d4-d52dd8aef4dd.PNG)

![main 에서 branch-fast-forward merge](https://user-images.githubusercontent.com/47783128/148645390-5f714769-4753-426e-9843-71565d385125.PNG)

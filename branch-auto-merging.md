### 브랜치 병합 - auto merging

1. main 브랜치 수정이 있다.
2. 1.을 commit 한다.
3. 같은 파일을 새로운 or 기존의 다른 브랜치에서 수정이 있다.
4. 3.번을 commit 한다.
4. main 브랜치에서 3.브랜치를 병합한다.
5. 양쪽에서 변경내용이 하나로 합쳐진다. 

=> 같은 파일을 수정 할 경우 양쪽에서 변경된 내용이 하나로 합쳐지면서 새로운 커밋이 생기고, 기준 브랜치가 그 커밋을 바라본다.

![main 브런치 수정](https://user-images.githubusercontent.com/47783128/148645284-1a4f77f5-f520-4bc9-8a41-59c06190cc81.PNG)

![같은 파일을 auto merging 브랜치에서 수정](https://user-images.githubusercontent.com/47783128/148645224-42a8cb62-7110-4874-a07d-6ae24a15d745.PNG)

![auto merging](https://user-images.githubusercontent.com/47783128/148645202-adfecfd9-b60d-4e0b-9508-7bfa8f446bfb.PNG)

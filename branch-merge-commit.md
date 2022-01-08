### 브랜치 병합 - merge commit

1. 새로운 or 기존의 다른 브랜치에서 수정이 있다.
2. 1.을 commit 한다.
3. main 브랜치 수정이 있다.
4. 3.번을 commit 한다.
5. 2.를 수정하고 또 commit 한다.
6. main 브랜치에서 5.를 병합한다.
7. 공통의 부모를 찾고 새로운 commit을 만든다.. 

=> 공통의 부모를 찾고 양쪽에서 변경된 내용이 하나로 합쳐지면서 새로운 커밋이 생기고, 기준 브랜치가 그 커밋을 바라본다.

![merge commit](https://user-images.githubusercontent.com/47783128/148645329-dddab57b-72a9-4c09-87ae-bff785df3965.PNG)

![merge commit 결과](https://user-images.githubusercontent.com/47783128/148645298-7adc7c5a-027c-4e5f-b844-2dcaf01421fa.PNG)

![merge commit log](https://user-images.githubusercontent.com/47783128/148645312-f6c4c3f2-f08a-477b-96b2-fb811dc043e8.PNG)

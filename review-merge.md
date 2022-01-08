1. main branch에서 review-branch-fast-forward 브랜치 생성
2. review-merge.md 파일 수정
3. review-merge 브랜치 커밋 
5. main 브랜치에서 review-branch-fast-forward 병합

![1  main 브랜치 로그](https://user-images.githubusercontent.com/47783128/148662737-7832b152-fb2d-4e3b-9a71-553dce62bea2.PNG)

![2  fast forward 브랜치 로그](https://user-images.githubusercontent.com/47783128/148662740-044d2156-2db6-4e70-af93-9244d9b15117.PNG)

![3  병합](https://user-images.githubusercontent.com/47783128/148662746-f40cdb8e-171e-4bcc-96d4-b039af6a7236.PNG)

![4  병합 후 로그](https://user-images.githubusercontent.com/47783128/148662788-9bbcf867-8215-422f-afc6-de51d3fc5a8b.PNG)

=> 기준 브랜치가 바라보는 최신 커밋만 변경된거 확인

---> fast forward review

6. main branch에서 review-branch-merge-commit 브랜치 생성
* 다시 확인을 위해 main과 review-branch-merge-commit 싱크 맞춤
7. review-branch-merge-commit 브랜치 에서 review-merge.md 파일 수정 
8. review-branch-merge-commit 브랜치 커밋
9. 다시 main 브랜치에서
10. review-merge.md 파일 수정
11. main 브랜치 커밋 
12. main 브랜치에서 review-branch-merge-commit 병합

![5  main 브랜치](https://user-images.githubusercontent.com/47783128/148662795-b7363a99-dfbc-49b6-b4b1-e01040ecd0f8.PNG)

![6  merge commit 수저후 브랜치 로그](https://user-images.githubusercontent.com/47783128/148662798-4ece2094-de1f-45be-b453-134b24182dd8.PNG)

![7  main 브랜치 수정후 로그](https://user-images.githubusercontent.com/47783128/148662802-8ab96dd3-b103-4f2e-87e4-3a0acd6e755e.PNG)

![8  병합](https://user-images.githubusercontent.com/47783128/148662806-ebe5c037-f5cf-4a93-afe6-abf314ba5836.PNG)

![9  병합후 로그](https://user-images.githubusercontent.com/47783128/148662810-7942d756-245a-4093-b25d-b822220be093.PNG)

=> 공통부모를 찾고 새로운 커밋을 바라보는거 확인

---> merge commit 

13. main branch에서 review-branch-merge-conflicts 브랜치 생성
14. review-merge.md 파일 수정
15. review-branch-conflicts 브랜치 커밋
16. main 브랜치에서 같은 부분 수정
17. main 브랜치 커밋
18. main 브랜치에서 review-branch-conflicts 병합
19. 충돌
20. 충돌 부분 수정후 커밋

![7  충돌 브랜치 로그](https://user-images.githubusercontent.com/47783128/148662266-fc8718f4-5918-49fb-90f0-6f38dc486f00.PNG)

![8  main 브랜치 에서 같은 곳 수정](https://user-images.githubusercontent.com/47783128/148662267-260bfbac-c49f-4b75-b9a4-10d1c5136bf9.PNG)

![9  충돌](https://user-images.githubusercontent.com/47783128/148662268-d7c61c5d-5bd5-45e7-83cf-d6c76e02e966.PNG)

![10 충돌](https://user-images.githubusercontent.com/47783128/148662274-6bc95f09-f800-4a44-9dfb-7b1b02a35b8d.PNG)

![11 충돌 부분 수정](https://user-images.githubusercontent.com/47783128/148662275-bdfd7c31-119e-40f7-8999-dca98062d74f.PNG)

![12 충돌 수정 커밋](https://user-images.githubusercontent.com/47783128/148662279-0e70cccc-dca5-433f-a813-0713c4e31f1e.PNG)

---> merge conflicts 

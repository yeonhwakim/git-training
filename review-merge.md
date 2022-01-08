1. main branch에서 review-branch-fast-forward 브랜치 생성
2. review-merge.md 파일 수정
3. review-merge 브랜치 커밋 
5. main 브랜치에서 review-branch-fast-forward 병합

---> fast forward review

6. main branch에서 review-branch-merge-commit 브랜치 생성
7. review-merge.md 파일 수정 
8. review-branch-merge-commit 브랜치 커밋
9. 다시 main 브랜치에서
10. review-merge.md 파일 수정
11. main 브랜치 커밋 
12. main 브랜치에서 review-branch-merge-commit 병합

![4  mc 커밋 로그](https://user-images.githubusercontent.com/47783128/148662245-ee1ca0a5-9276-4ef1-ac12-e457aa028399.PNG)

![5  main도 수정](https://user-images.githubusercontent.com/47783128/148662248-b793ed6b-0ec7-448d-9575-f65bdf53e8d7.PNG)

![6  merge 후](https://user-images.githubusercontent.com/47783128/148662252-3b5268de-3998-4d83-b299-629c2e76cd0c.PNG)


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

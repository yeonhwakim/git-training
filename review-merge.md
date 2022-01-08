1. main branch에서 review-merge 브랜치 생성
2. review-merge.md 파일 생성
3. review-merge 브랜치 커밋
4. 로그를 비교해보고 싶어서 다시 main branch에서 review-branch-merge 브랜치생성
5. main 브랜치에서 review-branch-merge 병합
---> fast forward
5. main branch에서 review-branch-merge-commit 브랜치 생성
6. review-merge.md 파일 수정 
7. review-branch-merge-commit 브랜치 커밋
7. 다시 main 브랜치에서
8. review-merge.md 파일 수정
9. main 브랜치 커밋 
5. main 브랜치에서 review-branch-merge-commit 병합
---> merge commit 
10. main branch에서 review-branch-merge-conflicts 브랜치 생성
11. review-merge.md 파일 수정
12. review-branch-conflicts 브랜치 커밋
13. main 브랜치에서 같은 부분 수정
14. main 브랜치 커밋
15. main 브랜치에서 review-branch-conflicts 병합
16. 충돌
16. 충돌 부분 수정후 커밋
---> merge conflicts 
1. 라벨 생성 (논의)

2. 칸반보드 생성

3. 이슈 템플릿 정하기

4. 이슈발행
  - Assignees : 해당 작업의 담당자
  - Labels: 해당 작업의 성격

5. 이슈 기반 브랜치 생성
  - 기능명칭-이슈번호

6. Pull Request
  - Reviewer: 리뷰어 지정
  - Assignees : 해당 작업의 담당자
  - Labels: 해당 작업의 성격

7. PR 제목 [#이슈번호] 내용 수정

8. 코드리뷰
  - Comment: 승인과 무관하게 일반적인 커멘트
  - Approve: 리뷰어가 승인을 하는 것으로, 머지해도 무관
  - Request changes: 변경을 요청하는 것으로, 승인 거부 

9. 모든 준비가 끝나고 리뷰하기 전에 PR 코멘트 창에 resolved #이슈번호 내용 추가

10. merge [branch]
  - closed [branch]
  - closed [#이슈번호]
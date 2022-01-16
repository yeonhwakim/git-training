__git reset HEAD~2 --soft__

HEAD => 최근 커밋 바로 이전 커밋 (v4)

Index => 최근 수정 (v6)

Working Directory => 최근 수정 (v6)

__git reset HEAD~2 --mixed__

HEAD => 최근 커밋 바로 이전 커밋 (v2)

Index => 최근 수정 git add 하기전 (v2)

Working Directory => 최근 수정 (v6) 2를 기준으로 3,4,5,6 commit 내용이 추가 되어있는상태 (중간에 commit 안하고 계속 진행)

__git reset HEAD~2 --hard__

HEAD => 최근 커밋 바로 이전 커밋 ()

Index => 최근 수정 git add 하기전 ()

Working Directory => 내용도 되돌림 ()
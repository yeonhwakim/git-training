__git reset 579ff41e9bd42248e2d2d53ab333c11a7b84c1b5 --soft__

579ff41e9bd42248e2d2d53ab333c11a7b84c1b5 (Add fourth commit)

HEAD => 최근 커밋 바로 이전 커밋 (579ff41e9bd42248e2d2d53ab333c11a7b84c1b5)

Index => 최근 수정 (마지막 커밋)

Working Directory => 최근 수정 (마지막 커밋)

__git commit 하면 git commit --amend랑 동일하게 가기__

__git reset 27e9ebebce6298ad5c0382e86f6181fc2df2a548 --mixed__

27e9ebebce6298ad5c0382e86f6181fc2df2a548 (Add third commit)

HEAD => 최근 커밋 바로 이전 커밋 (27e9ebebce6298ad5c0382e86f6181fc2df2a548)

Index => 최근 수정 git add 하기전 (27e9ebebce6298ad5c0382e86f6181fc2df2a548)

Working Directory => 최근 수정 (마지막 커밋) 2를 기준으로 4,5,6 commit이 추가 되어있는상태 (중간에 commit 안하고 계속 진행)

__git reset 14090c77d45c635ed53032a0f708358e25ee5c57 --hard__

14090c77d45c635ed53032a0f708358e25ee5c57 (Add first commit)

HEAD => 최근 커밋 바로 이전 커밋 (14090c77d45c635ed53032a0f708358e25ee5c57)

Index => 최근 수정 git add 하기전 (14090c77d45c635ed53032a0f708358e25ee5c57)

Working Directory => 내용도 되돌림 (14090c77d45c635ed53032a0f708358e25ee5c57)

__git reset --hard ORIG_HEAD__

reset 실행 전으로 돌아감

계속 올라가는게 아니고

다시 하면 reset 했던 head로 다시 돌아감
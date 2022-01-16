### 시작

![0_셋팅](https://user-images.githubusercontent.com/47783128/149649366-24242e9a-4807-4dfe-be96-02149af6a452.PNG)

![0_1_셋팅](https://user-images.githubusercontent.com/47783128/149649370-7dbe4d12-557a-415f-9d4c-597209a1a818.PNG)


### git reset 579ff41e9bd42248e2d2d53ab333c11a7b84c1b5 --soft

579ff41e9bd42248e2d2d53ab333c11a7b84c1b5 (Add fourth commit)

HEAD => 최근 커밋 바로 이전 커밋 (579ff41e9bd42248e2d2d53ab333c11a7b84c1b5)

Index => 최근 수정 (마지막 커밋)

Working Directory => 최근 수정 (마지막 커밋)

![1_soft_log](https://user-images.githubusercontent.com/47783128/149649373-ada21bf8-706f-4bba-bb46-7a8fd2af8303.PNG)

![1_1_soft_modified](https://user-images.githubusercontent.com/47783128/149649375-eb1207d6-1e89-4441-8589-f6183f9f06bf.PNG)

![1_2_soft_status](https://user-images.githubusercontent.com/47783128/149649380-a34ee8c3-1b33-4047-8f68-0501e9b74dad.PNG)


### git commit 하면 git commit --amend랑 동일하게 가기

![2_amend](https://user-images.githubusercontent.com/47783128/149649397-213daa25-a3f2-4156-94ba-11d2f449934c.PNG)


### git reset 27e9ebebce6298ad5c0382e86f6181fc2df2a548 --mixed

27e9ebebce6298ad5c0382e86f6181fc2df2a548 (Add third commit)

HEAD => 최근 커밋 바로 이전 커밋 (27e9ebebce6298ad5c0382e86f6181fc2df2a548)

Index => 최근 수정 git add 하기전 (27e9ebebce6298ad5c0382e86f6181fc2df2a548)

Working Directory => 최근 수정 (마지막 커밋) 2를 기준으로 4,5,6 commit이 추가 되어있는상태 (중간에 commit 안하고 계속 진행)

![3_mixed_log](https://user-images.githubusercontent.com/47783128/149649401-4b3cf278-b2a1-4ad3-8509-6e7459543ffc.PNG)

![3_1_mixed_modified](https://user-images.githubusercontent.com/47783128/149649405-4f441f6d-a59c-49e5-84ac-d519c0a96a89.PNG)

![3_2_mixed_status](https://user-images.githubusercontent.com/47783128/149649407-2af0db75-c71a-4f5a-8309-46e04d1c2112.PNG)


### git reset 14090c77d45c635ed53032a0f708358e25ee5c57 --hard

14090c77d45c635ed53032a0f708358e25ee5c57 (Add first commit)

HEAD => 최근 커밋 바로 이전 커밋 (14090c77d45c635ed53032a0f708358e25ee5c57)

Index => 최근 수정 git add 하기전 (14090c77d45c635ed53032a0f708358e25ee5c57)

Working Directory => 내용도 되돌림 (14090c77d45c635ed53032a0f708358e25ee5c57)

![4_hard_log](https://user-images.githubusercontent.com/47783128/149649409-bb7d1868-a9b6-4614-b609-2b258922ec71.PNG)

![4_1_hard_modified](https://user-images.githubusercontent.com/47783128/149649412-a85b05b4-24cc-47ef-a86c-a6904ef75545.PNG)

![3_2_hard_status](https://user-images.githubusercontent.com/47783128/149649415-e5d54847-d956-4c55-80ed-714fd7a948e8.PNG)

### git reset --hard ORIG_HEAD

reset 실행 전으로 돌아감

HEAD => 최근 커밋 바로 이전 커밋 (27e9ebebce6298ad5c0382e86f6181fc2df2a548)

Index => 최근 수정 git add 하기전 (27e9ebebce6298ad5c0382e86f6181fc2df2a548)

Working Directory => 내용도 되돌림 (27e9ebebce6298ad5c0382e86f6181fc2df2a548)

계속 올라가는게 아니고

다시 하면 reset 했던 head로 다시 돌아감

HEAD => 최근 커밋 바로 이전 커밋 (14090c77d45c635ed53032a0f708358e25ee5c57)

Index => 최근 수정 git add 하기전 (14090c77d45c635ed53032a0f708358e25ee5c57)

Working Directory => 내용도 되돌림 (14090c77d45c635ed53032a0f708358e25ee5c57)

![5_reset_되돌리기](https://user-images.githubusercontent.com/47783128/149649417-b1fbf5cc-25ea-49bd-9c3e-23c50024441a.PNG)

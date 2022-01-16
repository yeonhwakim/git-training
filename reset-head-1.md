### 시작

![0_셋팅](https://user-images.githubusercontent.com/47783128/149649217-38959516-674a-4b2d-bf41-69deaeff1444.PNG)

![0_1_셋팅](https://user-images.githubusercontent.com/47783128/149649219-afa28c92-b0f5-406e-8a3b-cedfbf143be4.PNG)


### git reset HEAD^ --soft

HEAD => 최근 커밋 바로 이전 커밋 (v3)

Index => 최근 수정 (v4)

Working Directory => 최근 수정 (v4)

![1_soft_log](https://user-images.githubusercontent.com/47783128/149649221-d09e93f7-2b52-45fb-81b6-11d704ffae5c.PNG)

![1_1_soft_modified](https://user-images.githubusercontent.com/47783128/149649226-c7b05e62-04ef-41ed-a9db-bb46df7570b9.PNG)

![1_2_soft_status](https://user-images.githubusercontent.com/47783128/149649229-99b7aa4f-33da-4f2d-bfaf-44572b7f4092.PNG)


### git reset HEAD^ --mixed

HEAD => 최근 커밋 바로 이전 커밋 (v2)

Index => 최근 수정 git add 하기전 (v2)

Working Directory => 최근 수정 (v4) 2를 기준으로 3,4 commit이 추가 되어있는상태 (중간에 commit 안하고 계속 진행)

![2_mixed_log](https://user-images.githubusercontent.com/47783128/149649234-39f306e6-c0ff-475b-9eb0-2f7f1a87daf6.PNG)

![2_1_mixed_modified](https://user-images.githubusercontent.com/47783128/149649240-cdc5ef78-d17a-4ffd-a532-5efc35751105.PNG)

![2_2_mixed_status](https://user-images.githubusercontent.com/47783128/149649244-c41f51c6-3640-4406-a927-6f9dd1ee9148.PNG)


### git reset HEAD^ --hard

HEAD => 최근 커밋 바로 이전 커밋 (v1)

Index => 최근 수정 git add 하기전 (v1)

Working Directory => 내용도 되돌림 (v1)

![3_hard_log](https://user-images.githubusercontent.com/47783128/149649253-00e65cb7-2721-4909-9a0c-15a0f28c9129.PNG)

![3_1_hard_modified](https://user-images.githubusercontent.com/47783128/149649258-1a18f632-6ee4-4ebe-adfe-37a8c02d1bcc.PNG)

![3_2_hard_status](https://user-images.githubusercontent.com/47783128/149649264-5ecd140f-f79c-42df-901d-d0cbc2d29bed.PNG)


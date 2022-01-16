### 시작

![0_셋팅](https://user-images.githubusercontent.com/47783128/149649315-92d3e3b9-b68e-4b4f-a90e-11d906bc587f.PNG)

![0_1_셋팅](https://user-images.githubusercontent.com/47783128/149649317-032357ef-cce8-4fb3-aa69-1135cd7d1357.PNG)


### git reset HEAD~2 --soft

HEAD => 최근 커밋 바로 이전 커밋 (v4)

Index => 최근 수정 (v6)

Working Directory => 최근 수정 (v6)

![1_soft_log](https://user-images.githubusercontent.com/47783128/149649320-0a13b16a-e37c-486d-830b-7bb19f2668ce.PNG)

![1_1_soft_modified](https://user-images.githubusercontent.com/47783128/149649325-e5b699a2-30ef-4330-b3df-a79eec6fd852.PNG)

![1_2_soft_status](https://user-images.githubusercontent.com/47783128/149649326-2637334c-24f8-46ff-817f-1a2d530fe4a8.PNG)



### git reset HEAD~2 --mixed

HEAD => 최근 커밋 바로 이전 커밋 (v2)

Index => 최근 수정 git add 하기전 (v2)

Working Directory => 최근 수정 (v6) 2를 기준으로 3,4,5,6 commit 내용이 추가 되어있는상태 (중간에 commit 안하고 계속 진행)

![2_mixed_log](https://user-images.githubusercontent.com/47783128/149649328-5ca1fc6a-08a8-48e3-b461-6f6ab948527f.PNG)

![2_1_mixed_modified](https://user-images.githubusercontent.com/47783128/149649331-6c310bb1-4233-4b2f-a545-0170e9f8ec0a.PNG)

![2_2_mixed_status](https://user-images.githubusercontent.com/47783128/149649333-99ebfcf5-7d58-435b-bf7c-66f032fb1cab.PNG)


### git reset HEAD~2 --hard

HEAD => 최근 커밋 바로 이전 커밋 ()

Index => 최근 수정 git add 하기전 ()

Working Directory => 내용도 되돌림 ()

![3_hard_log](https://user-images.githubusercontent.com/47783128/149649342-14c8b02d-df25-41b3-a64f-c8489b7c3c47.PNG)

![3_1_hard_modified](https://user-images.githubusercontent.com/47783128/149649343-fbdd523a-771b-404b-b8e2-c12c6f3af2d1.PNG)

![3_2_hard_status](https://user-images.githubusercontent.com/47783128/149649347-c25d454e-d8f7-40ea-82dc-c134b1b6e332.PNG)

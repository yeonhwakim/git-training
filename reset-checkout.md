__commit__

$ git reset [commit] => 해당 커밋으로 덮어써버림

![7_reset hard_commit_status_덮어씀](https://user-images.githubusercontent.com/47783128/149711174-7603a5aa-6a0b-44f2-94fb-58d22e289e47.PNG)

$ git checkout [commit] => 저장하지 않은 것이 있는지 확인해서 날려버리지 않는다는 것을 보장 / head가 분리됨

![7_checkout_commit_status_head가 분리됨](https://user-images.githubusercontent.com/47783128/149711150-9085eb20-1349-4189-bbde-8e8ea526d1ae.PNG)

__file path__

$ git reset [file path] => Unstage 상태로 되돌림

![333333333333](https://user-images.githubusercontent.com/47783128/149711770-f15a467c-afe6-4ea8-b9df-8388a84496db.PNG)

![44444444](https://user-images.githubusercontent.com/47783128/149711776-8316bf52-4b00-4b0e-abc2-7e6b9d3fb824.PNG)


$ git checkout [file path] => Unstage 상태에서 Unmodified 상태로 되돌림

![1111111111111](https://user-images.githubusercontent.com/47783128/149711752-df28efa2-722b-486c-ac85-105aef4491e3.PNG)

![2222222222](https://user-images.githubusercontent.com/47783128/149711760-1b5a223d-1b3a-4f45-bf90-24bbf1afe448.PNG)


__branch__

$ git reset [branch] => head가 가리키는 branch가 바라보는 커밋을 변경 

![9_checkout_branch_log](https://user-images.githubusercontent.com/47783128/149711112-6bc28519-1892-40f1-b0c5-4228f34cdef4.PNG)

$ git checkout [branch] => head의 branch를 변경

![9_reset_branch_log](https://user-images.githubusercontent.com/47783128/149711108-7672b5d6-8de7-4ae6-88e1-dceb91525153.PNG)

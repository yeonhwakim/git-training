__commit__

$ git reset [commit] => 해당 커밋으로 덮어써버림

$ git checkout [commit] => 저장하지 않은 것이 있는지 확인해서 날려버리지 않는다는 것을 보장

__file path__

$ git reset [file path] => Unstage 상태로 되돌림

$ git checkout [file path] => Unstage 상태에서 Unmodified 상태로 되돌림

__branch__

$ git reset [branch] => head가 가리키는 branch가 바라보는 커밋을 변경 

$ git checkout [branch] => head의 branch를 변경

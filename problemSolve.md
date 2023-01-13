git oct개발자의 수정 파일을 git cat에서 내려 받아서 수정한 후​
feature와 tshirt-list 파일을 추가해서 올리려고 시도했다.​
교재의 내용대로 했으나 문제가 됨​
사용자가 달라서 충돌이 일어난 것인지, 사용자가 바뀔 때마다 branch name 이 생성되어야 하는지도 모르겠다.
​

CLI에서 브랜치를 추가하고, checkout <branchname> 으로 변경하였다. Head가 head-><branchname> 으로 변경되었다.​
이후 업로드가 자연스럽게 잘 되었다. 사용자가 1인에서 2인으로 변하면서 충돌이 일어난 것 같다.​

master는 아직 변경되지 않았다.
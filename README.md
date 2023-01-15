# git-test
git 처음사용해서 연습용

기본적인 함수

git init

git branch //현재 브랜치 상황을 파악하거나 브랜치를 형성 (-d) 대상 브랜치를 제거

git log (--oneline, --branches , --graph)

git status

git add "대상 파일"

git commit (-a,-m) "massage"

git repair

git checkout //브랜치간의 이동, (-- 대상파일) // 수정사항을 저장소 최신으로 되돌림

git reset // 스테이지를 취소함 또는 특정 커밋으로 이동함

git merge (대상 branch) //병합을 시키는 역할

git stash // 잠시 수정된 파일들이 저장되지 않도록 만듦

git stash pop // 보관되있던 파일을 다시 복원시킴

git remote add origin (깃허브 주소)

git push -u origin master

git pull origin master

# pragmatic
django


# 23.03.30
## GIT 원격저장소 내용으로 업데이트 하기
1. 원격 저장소 확인하기
git remote -v

2.fetch
git fetch origin
fatch를 통해 origin의 내용을 받아온다. 하지만 아직 로컬에도 적용되지 않은 상태 

3.merge
git merge origin/main
받아온 origin의 main branch 내용들을 내 로컬에 merge한다.
로컬에서 확인해보면 이제 내용이 업데이트 된 내용으로 바뀐 것을 볼 수 있다.
origin에서 업데이트 된 내용이 내 repository의 내용과 confilct가 날 경우에는 해당 파일을 수정하거나 제거한 뒤 merge를 수행해야 한다.

4.push
git push
바뀐 내용들을 올려서 적용한다.

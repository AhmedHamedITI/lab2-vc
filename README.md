How to remove the branches locally and remotely ???
locally :
git branch -d branch_name
git branch -d dev
git branch -d test
remotely:
git push origin --delete dev
git push origin --delete test

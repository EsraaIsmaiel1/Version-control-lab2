![Sky](https://picsum.photos/seed/picsum/200/300)
git branch -d test
git branch -d dev
git push origin --delete test
git push origin --delete dev
git stash
git checkout test
git tag
git tag -d v1.7
git push --delete origin v1.7

### git test ###
1. git 合并远程多个commit
```
git rebase -i 3a4226     填的是第N个commit的版本号，即合并这个commit之后的所有commit (不包括这个)
将要删除的commit设置为f 或者都改为 s 或 squash
如果为s会在弹出一个框，可以进行编辑，删除不必要的注释
git push -f 强制push
注意其他人的提交
```
2. 正在编辑，拉去远程代码
```
git stash save "test-stash"
git pull --rebase
git stash pop
```
3. git revert
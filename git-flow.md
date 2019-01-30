1. 创建feature分支 git flow feature start 1.0
2. 完成feature分支 git flow feature finish 1.0（默认该分支会删除，并合并代码到develop分支上）
3. 创建release分支 git flow release start 1.0
4. 创建release分支 git flow release finish 1.0（默认从develop分支拉去代码，提交后该分支会删除，并合并代码到master和develop分支上，打上标签（此时代码并未提交，需要手动push））
1. 创建hotfix分支 git flow hotfix start test
2. 完成hotfix分支 git flow hotfix finish test（默认从master分支拉去代码，提交后该分支会删除，并合并代码到master和develop分支上，打上标签（此时代码并未提交，需要手动push））
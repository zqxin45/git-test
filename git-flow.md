1. 创建feature分支 git flow feature start 1.0
2. 完成feature分支 git flow feature finish 1.0（默认该分支会删除，并合并代码到develop分支上）
3. 创建release分支 git flow release start 1.0
4. 创建release分支 git flow release finish 1.0（默认从develop分支拉去代码，提交后该分支会删除，并合并代码到develop分支上）
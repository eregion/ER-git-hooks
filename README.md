ER-git-hooks
============

Git hooks being used in our project

* post-merge

Main goal of this hook - autoincrement project version.
Hook runs after merge only if current branch is master.
It increments version in specified file and rewrite last commit.
Note: increments only last part of version (xx.xx.xx.XX)

TODO: 

* adding tag after incrementing version
* merge hook does not work on commit after merge conflict

ER-git-hooks
============

Git hooks being used in our project

* post-merge
Main goal of this hook - autoincrement project version.
Hook runs after merge only if current branch is master.
It increments version in specified file and rewrite last commit.

TODO: adding tag after incrementing version
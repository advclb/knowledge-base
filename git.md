# Git

## Branching model and workflow

### NoFlow

You don't branch. Everything is directly committed to master branch. It is only used when you are the only developer in the project and here isn't code reviews by others. **Don't use it in teams of any sizes**.

### OneFlow

[OneFlow](https://www.endoflineblog.com/oneflow-a-git-branching-model-and-workflow) is a simple yet useful Git branching model and workflow. You only maintain one branch: master. Each feature branch was forked from master and will then be merged back to master. It fits GitHub/GitLab/BitBucket perfectly. If the project is deployed automatically from master branch, the master + develop variant model is safer. **Recommended for most projects**.

### GitFlow

[GitFlow](https://nvie.com/posts/a-successful-git-branching-model/) is for libraries and SasS applications where you need to maintain different release branches at the same time. It is rarely used in today's industry. But it shows you some good things of Git. **Don't use it**.

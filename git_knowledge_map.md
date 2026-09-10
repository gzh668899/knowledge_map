# Git 知识地图

## 00. Git 前置基础

- 版本控制
- 源代码管理
- Repository
- Local Repository
- Remote Repository
- Working Directory
- File
- Commit
- Branch
- Tag

## 01. Git 基本概念

- Git
- Repository
- Working Tree
- Staging Area
- Commit
- HEAD
- Branch
- Remote
- Remote Branch
- Tracking Branch
- Tag

## 02. Git 基本工作流

- Working Directory
- git status
- git add
- Staging Area
- git commit
- Commit History
- git log
- git diff
- Working Tree → Stage → Commit

## 03. Git 文件状态

- Untracked
- Unmodified
- Modified
- Staged
- Deleted
- Renamed
- Copied
- 状态转换

## 04. Git 配置

- git config
- System Config
- Global Config
- Local Config
- user.name
- user.email
- core.editor
- core.autocrlf
- alias
- Configuration Priority

## 05. Commit

- Commit
- Commit Message
- Parent Commit
- Commit ID
- SHA
- Commit History
- HEAD
- HEAD~
- HEAD^
- Multiple Parents
- Commit Graph

## 06. 查看历史

- git log
- git log --oneline
- git log --graph
- git log --stat
- git show
- git diff
- git diff HEAD
- git diff --cached
- git blame
- git reflog
- History Traversal

## 07. Branch

- Branch
- Branch Pointer
- HEAD
- Current Branch
- git branch
- git switch
- git checkout
- Create Branch
- Delete Branch
- Rename Branch
- List Branch
- Branch Tracking

## 08. Branch 原理

- Branch 是什么
- Branch Pointer
- HEAD Pointer
- Commit DAG
- Fast-forward
- Diverged Branch
- Common Ancestor
- Branch Creation

## 09. Merge

- git merge
- Fast-forward Merge
- Three-way Merge
- Merge Commit
- Common Ancestor
- Automatic Merge
- Merge Conflict
- Conflict Marker
- Resolve Conflict
- git add
- git merge --continue
- git merge --abort

## 10. Rebase

- git rebase
- Rebase 原理
- Commit Replay
- Rebase Onto
- Interactive Rebase
- Squash
- Fixup
- Reword
- Edit
- Drop
- Rebase Conflict
- git rebase --continue
- git rebase --skip
- git rebase --abort

## 11. Merge vs Rebase

- Merge History
- Rebase History
- Linear History
- Merge Commit
- Commit Hash Change
- Public Branch
- Private Branch
- 使用场景

## 12. Remote

- Remote Repository
- origin
- Remote URL
- Remote Branch
- Remote-tracking Branch
- git remote
- git remote -v
- git remote add
- git remote remove
- git remote rename

## 13. Push

- git push
- Push Branch
- Push Commit
- Upstream Branch
- -u
- Force Push
- --force
- --force-with-lease
- Push Rejection

## 14. Fetch

- git fetch
- Fetch Remote Objects
- Remote-tracking Branch
- origin/main
- Fetch vs Pull
- Fetch 后本地状态

## 15. Pull

- git pull
- Pull = Fetch + Merge
- Pull = Fetch + Rebase
- --rebase
- Pull Conflict
- Pull Strategy

## 16. GitHub / GitLab 协作

- Repository
- Fork
- Clone
- Pull Request
- Merge Request
- Code Review
- Reviewer
- Approval
- CI
- CD
- Protected Branch
- Branch Policy

## 17. Clone

- git clone
- Clone Repository
- Clone Branch
- Clone Depth
- Shallow Clone
- Clone URL
- HTTPS
- SSH

## 18. SSH

- SSH
- Public Key
- Private Key
- ssh-keygen
- ~/.ssh
- authorized_keys
- known_hosts
- SSH Agent
- Git SSH Authentication

## 19. Git Ignore

- .gitignore
- Pattern
- Wildcard
- Directory Pattern
- Negation
- Global gitignore
- Tracked File vs Ignored File
- git check-ignore

## 20. 文件操作

- git mv
- git rm
- git rm --cached
- Rename Detection
- Delete File
- Restore File
- Unstage File

## 21. Undo / 撤销

- 修改但未 Stage
- 已 Stage
- 已 Commit
- git restore
- git restore --staged
- git reset
- git reset --soft
- git reset --mixed
- git reset --hard
- git revert
- reset vs revert
- reflog 恢复

## 22. Reset

- HEAD 移动
- --soft
- --mixed
- --hard
- HEAD
- Index
- Working Tree
- Reset 三层模型

## 23. Revert

- git revert
- Revert Commit
- 新 Commit
- Public History
- Merge Commit Revert
- Reset vs Revert

## 24. Stash

- git stash
- Working Tree Stash
- Staged Stash
- git stash push
- git stash list
- git stash show
- git stash pop
- git stash apply
- git stash drop
- Stash Conflict

## 25. Tag

- Tag
- Lightweight Tag
- Annotated Tag
- git tag
- Create Tag
- Delete Tag
- Push Tag
- Version Tag
- Release

## 26. Cherry-pick

- git cherry-pick
- Pick Commit
- Commit Replay
- Cherry-pick Conflict
- --continue
- --abort
- Cherry-pick vs Merge

## 27. Bisect

- git bisect
- Good Commit
- Bad Commit
- Binary Search
- Automated Bisect
- Bug Localization

## 28. Advanced Branch Operations

- git branch -d
- git branch -D
- Branch Rename
- Branch Tracking
- Upstream
- Detached HEAD
- Detached HEAD Recovery
- Orphan Branch

## 29. Git Object Model

- Git Object
- Blob
- Tree
- Commit Object
- Tag Object
- Object ID
- SHA-1
- SHA-256
- Object Database

## 30. Git 三层模型

- Working Tree
- Index
- HEAD
- Working Tree → Index
- Index → HEAD
- HEAD → Working Tree
- git add
- git commit
- git restore
- git reset

## 31. Git 内部存储

- .git
- objects
- refs
- HEAD
- config
- index
- logs
- hooks
- refs/heads
- refs/remotes
- refs/tags

## 32. Git Object 深入

- Blob
- Tree
- Commit
- Parent
- Tree Pointer
- Blob Pointer
- Object Hash
- Object Graph

## 33. Git DAG

- Directed Acyclic Graph
- Commit Graph
- Parent
- Ancestor
- Descendant
- Common Ancestor
- Reachability
- Graph Traversal

## 34. Reference

- Reference
- Branch Reference
- Tag Reference
- HEAD
- Symbolic Reference
- refs/heads
- refs/remotes
- refs/tags
- Packed References

## 35. Reflog

- Reflog
- HEAD Reflog
- Branch Reflog
- Lost Commit
- Recovery
- Reset Recovery
- Rebase Recovery

## 36. Git Packfile

- Loose Object
- Packfile
- .pack
- .idx
- Delta Compression
- Object Compression
- git gc
- git repack
- Garbage Collection

## 37. Git 网络协议

- Local Repository
- Remote Repository
- Git Transport
- HTTP
- HTTPS
- SSH
- Git Protocol
- Packfile Transfer
- Negotiation
- Object Transfer

## 38. Git 大型仓库

- Large Repository
- Shallow Clone
- Partial Clone
- Sparse Checkout
- Sparse Index
- Git LFS
- Submodule
- Subtree
- Monorepo

## 39. Submodule

- Submodule
- Parent Repository
- Child Repository
- Gitlink
- .gitmodules
- Clone Submodule
- Update Submodule
- Init Submodule
- Submodule Commit

## 40. Git LFS

- Large File
- Pointer File
- LFS Server
- Track
- Push
- Pull
- LFS vs Git

## 41. Git Hooks

- Hook
- Client-side Hook
- Server-side Hook
- pre-commit
- commit-msg
- pre-push
- post-merge
- Automation

## 42. Git 高级协作

- Feature Branch
- Git Flow
- Trunk-based Development
- Release Branch
- Hotfix Branch
- Development Branch
- Main Branch
- Code Review
- PR
- CI/CD

## 43. Commit 规范

- Commit Message
- Atomic Commit
- Commit Granularity
- Conventional Commits
- feat
- fix
- refactor
- docs
- test
- chore
- Breaking Change

## 44. Git 冲突排查

- Merge Conflict
- Rebase Conflict
- Cherry-pick Conflict
- Conflict Marker
- Conflict Resolution
- ours
- theirs
- git diff
- git status
- Conflict Recovery

## 45. Git 安全

- SSH Key
- Access Token
- Credential
- Secret
- Secret Leak
- .gitignore
- Credential Helper
- Force Push Risk
- History Rewrite

## 46. Git 性能

- Repository Size
- Object Count
- Packfile
- Delta Compression
- git gc
- Commit Graph
- Multi-pack Index
- Sparse Checkout
- Partial Clone
- FSMonitor

## 47. Git 工程实践

- 日常开发工作流
- Feature 开发
- Bug 修复
- Code Review
- Release
- Hotfix
- 回退版本
- 恢复误删 Commit
- 处理冲突
- 清理 Commit
- 整理 Branch
- 同步上游
- 跨 Branch 移植 Commit
- 查找 Bug 引入 Commit
- 大型项目 Git 工作流

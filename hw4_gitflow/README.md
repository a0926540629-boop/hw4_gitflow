# HW4 git flow / github flow 實作說明
本次實作項目：
1. 建立分支（branch）
2. 分支合併（merge）
3. Fork 專案
4. Pull Request（PR）

## 使用流程：GitHub Flow（簡單線性流程）
GitHub Flow 適合持續部署，規則：
- main 分支永遠是可上線、穩定版本
- 要改功能就從 main 開新分支
- 改完推上 GitHub，發 Pull Request
- 討論、檢查完，合併回 main
- 合併後刪掉功能分支

### 1. 建立分支 branch
指令：
```bash
git branch feature-demo
git checkout feature-demo

git switch -c feature-demo

本次實作：在 feature-demo 分支修改 test.txt，做修改紀錄，之後合併回 main


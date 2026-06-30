# My First Repo

你好，我正在从 0 开始学习 GitHub。

```text
GitHub 网页 = 云端仓库
GitHub Desktop = 管理本地仓库和云端仓库的工具
你电脑里的文件夹 = 本地仓库
```

## 今天学到的内容

- GitHub Desktop 可以帮我管理项目
- Repository 是仓库
- README.md 是项目说明文件
- Commit 是一次保存记录

## 我的目标

学会用 GitHub 管理自己的学习笔记和项目。

## 附件

- Name：仓库名字
- Description：仓库简介
- Local path：保存在电脑哪里
- README：项目说明文件，建议勾选
- Git ignore：忽略不上传的文件，新手先 None
- License：开源协议，新手先 None

- Keep this code private 不勾选 = 公开
- Keep this code private 勾选 = 私有


## Day 2 总结

- Commit = 保存一次修改记录
- History = 查看修改历史
- Fetch = 检查云端更新
- Pull = 下载云端更新
- Push = 上传本地更新
- Changes = 当前还没提交的修改


## Day 3 总结

今天我学习了 Branch 分支。

main 是正式版本，branch 是临时修改版本。
我可以先在分支上修改内容，确认没问题后再合并回 main。

- 流程:创建分支 -> 修改文件 -> commit -> publish branch -> pull request -> merge -> main 更新
- Publish branch 意思是：把你电脑里的这个新分支上传到 GitHub 云端。
- Create Pull Request 意思是：我想把 add-day-3-notes 的修改合并到 main，请检查一下
- Merge pull request 意思是：确认把 add-day-3-notes 的修改放进 main

合并时一定要看清楚两个东西：
``` text
base branch = 要合并到哪里
compare branch = 从哪里拿修改

base: main
compare: add-day-3-notes

把 add-day-3-notes 合并到 main
```

## Day 4 总结

- Star = 收藏项目
- Fork = 复制项目到自己账号
- Watch = 订阅项目动态
- README.md = 项目说明书，最先看
- Code = 项目文件和代码
- Issues = 问题、需求、讨论
- Pull requests = 别人提交的修改
- Commits = 修改历史
- Releases = 发布版本


## Day 5 总结

今天我学习了 Issue 的完整流程。

- Issue 用来记录任务、问题、建议或讨论。
- 完成任务时，可以创建分支进行修改，再通过 Pull Request 合并到 main。
```text
Issue = 记录任务
Branch = 单独完成任务
Commit = 保存修改
Publish = 上传分支
Pull Request = 请求合并
Closes #编号 = 合并后关闭 Issue
Merge = 合并到 main
Delete branch = 删除完成的临时分支
Pull = 同步最新 main 到本地

Close issue = 关闭任务
#1 = Issue 编号
Closes #1 = 合并后自动关闭 Issue
PR = 提交修改来完成 Issue
```




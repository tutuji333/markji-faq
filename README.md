# 墨墨记忆卡常见问答

这是墨墨记忆卡常见问答与故障排查站点的公开仓库。

- FAQ 站点：`https://tutuji333.github.io/markji-faq/`
- 使用手册：`https://tutuji333.github.io/markji-manual/`
- 仓库地址：`https://github.com/tutuji333/markji-faq`
- 论坛入口：`https://markji.discourse.group/`
- 反馈邮箱：`tutuji333@proton.me`

## 这个仓库是做什么的

- 给终端用户提供 FAQ、求助入口和故障排查
- 负责高频短问题、异常定位、恢复动作和反馈前准备信息
- 与使用手册仓库分工协作，但不再承载完整教学正文
- 给维护者提供一套稳定的文档协作和发布流程

## 当前内容结构

- `docs/index.md`：FAQ 首页
- `docs/changelog.md`：更新日志，记录站点内容与结构变化
- `docs/getting-help.md`：求助分流页
- `docs/troubleshooting.md`：故障排查总入口
- `docs/study-cards.md` 等专题页：只做问题索引，不在这里堆长答案
- `docs/content-creation.md`：制卡与创作入口，专门收内容制作相关高频问题
- `docs/questions/`：具体问题单页，后续新增 FAQ 默认优先加在这里
- `docs/questions/sign-in/` 和 `docs/questions/decks/`：除了软件使用，也会承接签到规则、分享规则、共享牌组边界这类高频短问答

## 如果你只是想查问题

直接访问对应站点即可：

- 常见问答：`https://tutuji333.github.io/markji-faq/`
- 使用手册：`https://tutuji333.github.io/markji-manual/`

## 如果你想反馈问题

- 文档错误、过时内容、不清楚的说明：提 [Issue](https://github.com/tutuji333/markji-faq/issues/new/choose)
- 直接修改文档：提 [PR](https://github.com/tutuji333/markji-faq/compare)
- 不方便使用 GitHub：发邮件到 `tutuji333@proton.me`
- 想讨论、提愿望、分享案例：去 [论坛](https://markji.discourse.group/)

## 如果你想参与协作

1. 先阅读 `CONTRIBUTING.md`
2. 先判断内容是否属于“FAQ / 故障排查 / 求助入口”
3. 优先判断是补一个具体问题页，还是只需要在专题索引页补链接
4. 提交 Issue 或直接发起 PR
5. 合并到 `main` 后自动发布到 GitHub Pages

## 本地预览

```powershell
python -m pip install -r requirements-docs.txt
python -m mkdocs serve -f mkdocs.yml
```

## 发布流程

1. 修改或新增文档
2. 提交 PR
3. 审核通过后合并到 `main`
4. GitHub Actions 自动构建
5. GitHub Pages 自动发布

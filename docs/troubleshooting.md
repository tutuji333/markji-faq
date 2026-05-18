# 出现问题时先做什么？

如果你遇到的是失败、报错、闪退、同步不一致、导入异常或明显不符合预期的行为，先按这个顺序处理。

## 1. 先确认是不是版本问题

- 先看你当前的 App、网页端或系统版本
- 如果论坛里明确提到某个修复版本，先升级到那个版本再试
- 不要一边用旧版本，一边拿新口径判断行为是否正常

## 2. 先缩小问题范围

提交前最好先弄清楚：

- 只有一台设备出问题，还是所有设备都出问题
- 只有某个牌组 / 某个文件出问题，还是所有内容都出问题
- 是稳定复现，还是偶发
- 具体是在哪一步开始异常

## 3. 再决定走哪个处理入口

- `功能异常 / bug / 签到失败 / 网页行为异常`：优先走 `异常反馈`
- `跨设备同步失败`：先走 `异常反馈`，再视情况补邮件
- `登录时提示学习数据解压密码错误` 或其他需要账号人工排查的问题：发邮件 `support@markji.com`
- `导入 .apkg` 失败 / `Anki` 导入乱码：保留原文件，并通过 `异常反馈` 或邮件把文件一并交给官方
- `只是想看看别人怎么理解这个功能`：先看对应 FAQ，再去论坛

## 4. 提交前准备这些信息

- 平台、系统版本、App 版本
- 复现路径
- 截图或录屏
- 如果和导入有关，直接附上原文件
- 如果和账号有关，准备好注册账号

## 这两类问题别混在一起

- `找不到补签按钮 / 想知道提前签到有什么用`：先看规则说明，不要先按 bug 处理
- `已经满足条件但还是失败`：再按异常处理

## 常见异常入口

- [导入 `.apkg` 提示文件解析失败](questions/troubleshooting/apkg-parse-failed.md)
- [Anki 导入失败或乱码](questions/troubleshooting/anki-import-garbled.md)
- [“新学受复习上限影响”表现不对](questions/troubleshooting/review-limit-bug.md)
- [登录时提示学习数据解压密码错误](questions/troubleshooting/login-data-error.md)
- [跨设备同步失败](questions/troubleshooting/sync-failed.md)
- [签到失败或按钮异常](questions/troubleshooting/sign-in-failed.md)
- [网页功能或导出异常](questions/troubleshooting/web-export-bug.md)

## 参考帖子

- [入站必看：墨墨记忆卡用户服务指南](https://markji.discourse.group/t/topic/500)
- [异常反馈：跨设备同步失败](https://markji.discourse.group/t/topic/69)
- [无法正常登录：提示学习数据解压密码错误](https://markji.discourse.group/t/topic/604)
- [异常反馈：签到失败](https://markji.discourse.group/t/topic/607)
- [请求互助：导入 apkg 显示“文件解析失败，请更换其他文件”](https://markji.discourse.group/t/topic/249)

--8<-- "_partials/feedback-actions.md"

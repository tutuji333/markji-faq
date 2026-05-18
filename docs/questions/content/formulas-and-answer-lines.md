# 理工科公式、答案线和特殊格式怎么处理？

## 简答

论坛里目前最稳的做法，是把这类问题拆成两层：

- `公式 / 特殊符号 / 排版`：优先走网页端 + KaTeX + 语法文档
- `答案线 / 挖空 / 显示异常`：优先看具体语法和常见坑

也就是说，墨记当前更接近“有一套可用语法和若干成熟技巧”，而不是一套完整的 Markdown 编辑器。

## 公式怎么做

[topic 319](https://markji.discourse.group/t/topic/319) 里的官方邮件明确提到：

- 当前支持 `KaTeX` 语法
- 更建议在电脑网页端操作
- 可以先让 AI 生成公式，再批量导入

帖子里给出的官方示例写法是：

- `[E##公式内容]`

论坛互助里还补充了一些理工科常用场景：

- 化学式上下标
- 反应箭头
- 条件标注

但社区也提到，并不是所有 KaTeX / LaTeX 符号都完全可用，所以别把“高度兼容”理解成“毫无差异”。

## 一个公式想放成一整块怎么办

论坛互助里更常见的建议，是把整段公式一起包进同一组公式语法里，见 [topic 463](https://markji.discourse.group/t/topic/463)。

如果你遇到的是“第二行为什么跑开了”，先不要急着一行一行拆，优先检查是不是整块公式被拆成了多段。

## 公式里想挖空怎么办

[topic 470](https://markji.discourse.group/t/topic/470) 里给出的常见做法是：

- 把想挖空的地方直接写成 `???`
- 再单独配置答案

这更像论坛里成熟的社区技巧，不是完整的官方语法白皮书，但已经足够解决很多公式填空卡问题。

## 为什么答案线有时候不起效

[topic 633](https://markji.discourse.group/t/topic/633) 里一个很高频的坑是：

- 答案线语法后面残留了空格

论坛里更一致的建议是：

- 答案线结束后立刻换行
- 不要在行尾留下肉眼不容易发现的空格

## 方括号、加粗、颜色为什么会冲突

这是另一类高频问题。

- [topic 53](https://markji.discourse.group/t/topic/53) 的社区常用解法，是把正文里的半角 `[]` 改成全角 `［］`
- [topic 91](https://markji.discourse.group/t/topic/91) 则更建议复杂组合格式优先在网页端可视化编辑里处理

如果你是为了 AI 制卡或查细节语法，最好再回到 [topic 407](https://markji.discourse.group/t/topic/407) 指向的语法文档入口。

## 一个很现实的建议

如果你的目标是“尽快做出一套能学的卡片”，而不是把每一张都排成展示级效果，那么论坛里也反复出现一个朴素建议：

- 复杂到很花时间的排版，必要时可以直接截图处理

它不一定最美，但常常最省时间。

## 参考帖子

- [使用指南：卡片编辑理工科相关公式技巧](https://markji.discourse.group/t/topic/319)
- [请求互助：大佬们，怎么把第二行的公式放在第一行呀，为什么一个公式只能在一行？](https://markji.discourse.group/t/topic/463)
- [请求互助：大佬们怎么把公式里面的一部分“挖空”](https://markji.discourse.group/t/topic/470)
- [请求互助：为什么我的大部分卡片答案线不起效](https://markji.discourse.group/t/topic/633)
- [编辑语法：卡片内容中出现方括号，同时又需要加粗或颜色怎么办](https://markji.discourse.group/t/topic/53)
- [制卡语法：能否同时对文字加粗、背景、变换颜色吗？](https://markji.discourse.group/t/topic/91)
- [请求互助：请问有没有制卡语法的官方文档？](https://markji.discourse.group/t/topic/407)

--8<-- "../../_partials/feedback-actions.md"

# 如何更高效地批量生成语音？

## 简答

按目前论坛里能确认的口径，`高效生成语音` 和 `批量生成语音` 是两回事：

- `高效生成`：现在已经有更快的单条操作办法
- `批量生成`：论坛里还没有看到稳定公开的“一键批量生成语音”入口

如果你现在要处理的是几百张、上千张卡片，更现实的结论仍然是：`先把文本做好，再分批补语音`。

## 少量内容时，先把快捷生成用熟

论坛里已经比较稳定的操作经验是：

- 移动端：选中文本后走 `发音 -> 合成语音`
- 网页端：选中文本后，用快捷键  
  `Windows: Ctrl + 5`  
  `macOS: Cmd + 5`

[topic 313](https://markji.discourse.group/t/topic/313) 里还提到一个实用细节：

- 网页端快捷键会复用你上一次手动选择过的语音模型

所以如果你发现网页端声音不对，先手动生成一次，并确认当前模型，再继续走快捷键。

## 为什么“批量语音”比想象中更难

论坛互助里对这个问题有一套很清楚的拆解，见 [topic 591](https://markji.discourse.group/t/topic/591)：

1. 先做文字转语音
2. 再把音频文件上传
3. 最后把文件 ID 写回卡片内容

也就是说，哪怕未来有更强的批量编辑，`语音批量化` 也不完全等于“把文本一口气改掉”。

## 论坛当前更接近的结论

- [topic 591](https://markji.discourse.group/t/topic/591) 里，社区更一致的判断是：短期仍然不够省事
- [topic 709](https://markji.discourse.group/t/topic/709) 里，也有人直接把问题回指到同一条讨论，说明这仍是高频痛点
- [topic 546](https://markji.discourse.group/t/topic/546) 的官方创作公告又把 `开放 API` 放进了路线图，所以更合理的预期是：后面会变好，但不要把它当成已经成熟开放的现成功能

## 如果你现在就得做很多语音

论坛里更现实的建议通常有 3 种：

- 先把文本卡片批量做好，再分批补语音
- 只给最关键、最依赖发音的卡片补语音
- 如果是团队或协作场景，让协作者帮忙分工处理

## Pro 能解决什么，不能解决什么

[topic 666](https://markji.discourse.group/t/topic/666) 的官方邮件只明确了一点：

- 升级 Pro 之后，每日语音生成次数会更多

但这不等于：

- 已经有了“批量生成语音”按钮
- 也不等于可以直接自动处理整套大牌组

## 相关问题

- [如何快速生成语音？](../web/quick-speech.md)
- [专业版生成语音次数有什么变化？](../pro/pro-tts-quota.md)

## 参考帖子

- [请求互助：关于如何快速生成语音？](https://markji.discourse.group/t/topic/313)
- [请求互助：如何语音大量生成](https://markji.discourse.group/t/topic/591)
- [请求互助：如何批量生成语音](https://markji.discourse.group/t/topic/709)
- [使用答疑：关于专业版生成语音次数说明](https://markji.discourse.group/t/topic/666)
- [创作公告：关于创作福利发放及精选牌组制卡指南](https://markji.discourse.group/t/topic/546)

--8<-- "../../_partials/feedback-actions.md"

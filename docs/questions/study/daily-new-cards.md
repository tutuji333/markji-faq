# 如何尽量保证每天都有固定新学？

## 简答

论坛里关于这个问题，其实存在两个阶段的答案：

- `5.0` 之前：官方邮件说过，当时**还不支持单独设置每日固定新学量**，更接近的做法是手动添加新卡
- `5.0` 之后：官方预告和后续回复明确说，学习设置改成了按牌组分别设置 `每日新学上限` 和 `每日复习上限`

所以如果你现在看的是新版本，优先去牌组里的 `学习设置`，不要直接把旧帖里的“手动补新卡”当成唯一答案。

## 论坛目前能确认的当前用法

- `5.0` 起，学习量设置改成按牌组独立管理
- 旧的全局学习量入口和 `一键选卡` 入口因此被隐藏
- 关闭 `新学受复习上限影响` 后，新学和复习会变成两个独立任务池
- 开启该按钮时，如果当天待复习量超过复习上限，系统可能不会再安排新学

## 你可以怎么做

1. 进入目标牌组右侧 `⋮`
2. 打开 `学习设置`
3. 分别设置 `每日新学上限` 和 `每日复习上限`
4. 如果你希望复习再多也尽量每天安排新学，优先检查 `新学受复习上限影响` 是否关闭
5. 如果这个开关的表现和描述不一致，先升级到 `5.1.0` 或更高版本

## 为什么论坛里会看到两种答案

- [主题 `205`](https://markji.discourse.group/t/topic/205) 对应的是 `5.0` 之前的旧口径
- [主题 `486`](https://markji.discourse.group/t/topic/486)、[`617`](https://markji.discourse.group/t/topic/617)、[`658`](https://markji.discourse.group/t/topic/658) 对应的是 `5.0` 之后的新设置逻辑

## 相关问题

- [“新学受复习上限影响”是什么意思？](review-limit-toggle.md)
- [为什么一键选卡不见了？](one-tap-selection-missing.md)
- [“新学受复习上限影响”表现不对怎么办？](../troubleshooting/review-limit-bug.md)

## 参考帖子

- [使用指南：如何保证每日固定的新学量（旧口径）](https://markji.discourse.group/t/topic/205)
- [更新预告：关于 5.0 版本“每日学习量”设置更新的预告](https://markji.discourse.group/t/topic/486)
- [请求互助：关于区分新学复习如何使用](https://markji.discourse.group/t/topic/617)
- [异常反馈：“新学受复习上限影响”效果疑似不符合描述（已修复）](https://markji.discourse.group/t/topic/658)
- [请求互助：一键选卡功能缺失](https://markji.discourse.group/t/topic/675)

--8<-- "../../_partials/feedback-actions.md"

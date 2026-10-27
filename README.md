# WEEK 01 · 从单神经元到卷积

交通预测方向的周度进度汇报。2026-10-28。

线上：https://week.taffyshine.asia

## 页面

| 文件 | 内容 |
|---|---|
| `index.html` | 汇报主页，六节：研究背景、数据来源、模型递进、误差机制、卷积验证、下阶段计划 |
| `study_notes.html` | 学习笔记：文献原文截图、五页电子笔记、两页纸质笔记 |
| `hidden_layer.html` | 隐藏层解剖：单个样本的 16 个神经元权重、z 和 h |
| `cnn_conv.html` | 卷积核可视化：滑窗、逐项相乘、两层卷积对比 |

## 本地打开

双击 `index.html`。纯静态，无依赖，不需要服务器。

四个页面之间可以互相跳转，子页面左上角有返回链接。

## 数据说明

实验用 CityFlow 的 `INT_001` 路口，2040 个小时点，合成数据。
所有结果仅用于验证流程和代码正确性，不作为研究结论。

## 目录

```
.
├─ index.html
├─ study_notes.html
├─ hidden_layer.html
├─ cnn_conv.html
├─ assets/          文献截图、实验图表、CityFlow 检查图
├─ note_assets/     电子笔记五页
└─ cnn_assets/      卷积演示的三张特征图
```

# Gemini 4 测试案例 · 公开展示

公开预览地址：**https://cwybruce.github.io/gemini4-showcase/**

首页是案例集锦入口（`index.html`），每个案例独立目录。

## 已有案例

| 编号 | 标题 | 来源 | 目录 |
|------|------|------|------|
| Case 01 | 自媒体从 0 到 100 万粉完整打法 · 交互式 2D 动画图解 | Gemini 生成 | `case-01/` |
| Case 02 | 自媒体 90% 慢知识生产流程与议程设置 · 交互式 2D 动画全案 | Gemini 生成 | `case-02/` |
| Case 03 | 鹈鹕单车沿海奇遇记 · SVG 2D 动画 | Gemini 生成 | `case-03/` |

注：Case 03 引用了 Tailwind CDN 与 Google Fonts，需联网加载。

## 模型能力横向测试（bench/，筹备中）

用同一套网页任务（信息图解 / 数据仪表盘 / 小游戏），在 Gemini / Claude / GPT
等主流模型上各跑一遍，输出全部入库、每个案例附完整提示词。

目录规范：`bench/<任务>-<模型>/index.html` + `prompt.md`，
首页集锦页会自动收录（手动在 `index.html` 的 grid 里加一张卡片）。

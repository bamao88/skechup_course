# SketchUp + AI 入门课

给大一新生的一节 SketchUp 入门课（约 60 分钟）：基本设置 → 基本功能 → 搭小木屋 → 自学，之后是 AI 部分（待细化）。

## 目录

| 路径 | 内容 |
| --- | --- |
| `lecture/` | 课堂讲稿：左图右文，一行一个知识点，含模型文件规划。打开 `lecture/index.html` 即可浏览 |
| `lecture/data/script.json` | 讲稿的全部文字（讲稿 / 操作 / 模型标注），改文字直接改这个文件 |
| `lecture/img/` | 讲稿配图：官方帮助中心截图、官方小木屋教案截图、官方速查表裁图、占位示意图 |
| `resources/pack/` | 课程资源包：按课程顺序整理的官方资源与图示 |
| `resources/pdf/` | 官方简体中文速查表（Mac / Windows）。小木屋教案原件见 https://docs.google.com/document/d/1J4TVe1BYtEShqdCh7fZFvXTLYe5KcmcIZeSCN6fpUKI/edit |

## 在线版本（claude.ai）

- 课堂讲稿（可在线编辑、自动保存）：https://claude.ai/artifact/B36CM2axtTcDEkDhoWzeRj
- 课程资源包：https://claude.ai/artifact/44VBaMdxju1tZZKFMyNtBk
- 备课方案：https://claude.ai/code/artifact/5b1781d9-3202-4a1f-b4cd-e75b6f6bd829
- 课堂演示手册：https://claude.ai/code/artifact/db0bf77e-c985-4f34-96a8-f69ad41abdc4

## 说明

- 本地直接打开 `lecture/index.html` 时，页面使用内嵌的文字数据，修改不会保存；需要改文字请编辑 `lecture/data/script.json`（然后运行一个本地服务器预览，例如 `python3 -m http.server`）。
- 图片来源均已在讲稿中逐张标注：SketchUp 官方帮助中心、SketchUp for Schools「Design Your Own Cabin」教案、官方 Quick Reference Card、B 站视频页面。
- 模型文件（`SketchUp课堂演示.skp`）目前只有文字规划，见讲稿顶部「模型规划」。

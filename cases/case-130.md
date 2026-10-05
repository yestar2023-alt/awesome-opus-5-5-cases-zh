# Clawd 水彩卡通与代码配乐

把原作者分镜做成十五秒水彩卡通；画面、配乐和渲染分别由代码执行，文档公开了完整制作链。

作者：az9713 · 状态：已核验

## 对象归属

作者明确使用 Opus 5.5 编程，另有 Fable 5.1 顾问建议。

## 输入

公开程度：完整公开

仓库有完整输入与分镜。输入框架参考 Code Bear，但此作品的故事和代码独立；不因复用输入模板合并不同作品。

[公开输入位置（未必在本库全文转载）](https://github.com/az9713/opus-5.5-musical-cartoon)

## 已知流程

1. p5.js 与 p5.brush 预绘水彩资产，Canvas 按帧时间绘制场景。
2. 共享 cues.json 对齐画面和声音；Node 合成 WAV。
3. Puppeteer 截帧、FFmpeg 编码，检查样帧后修改；有第二模型建议。

## 结果

归属：作者自述。文档报告输出 15 秒、1920×1080、24 fps 的 MP4；未独立运行渲染或听完配乐。


## 尝试与复现

检查程度：有复现文档

1. 取得源码进入 clawd-prose；准备 Node、Chrome 和 FFmpeg。
2. render.mjs 的 CHROME 与 BIN 默认是 Windows 路径，按本机修改，并确认端口 8765 可用。
3. 按文档运行 npm install、node score.mjs、node render.mjs，核对输出和样帧。

## 局限

- 文档说明没有人工听音验收，不能以波形检查替代听感判断。
- 不同系统字体和图形后端可能改变渲染；本轮只读文档，没有独立复现。

## 来源

- [clawd-cartoon-repo](https://github.com/az9713/opus-5.5-musical-cartoon) · 已读正文 · 2026-09-30：已读作者项目说明、输入位置和制作过程；长分镜只链接。
- [clawd-cartoon-guide](https://github.com/az9713/opus-5.5-musical-cartoon/blob/main/clawd-prose/README.md) · 已读正文 · 2026-09-30：已读复现文档：Node、Chrome、FFmpeg，源码路径和命令；默认可执行文件路径针对 Windows，换系统需修改。

## 可迁移实践

- [time-based-rendering](../PRACTICES.md#time-based-rendering)
- [sample-review-loop](../PRACTICES.md#sample-review-loop)

[返回首页](../README.md)

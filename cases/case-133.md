# Papermorph：将 PDF 转成动画互动网页书

通过章节规划、分镜、旁白和交互练习生成静态网页书，仓库包含可本地浏览的示例。

作者：DozenTwelve · 状态：已核验

## 对象归属

作者 README 明确当前使用 Opus 5.5，并提供 Claude Code 调用方法。

## 输入

公开程度：部分公开或未确认完整性

README 公开带文件路径和目标读者占位符的调用模板；不等于各示例的完整制作对话。

[公开输入位置（未必在本库全文转载）](https://github.com/DozenTwelve/Papermorph/blob/main/README.md)

## 已知流程

1. 先从 PDF 提取章节，再确认读者、章节计划和视觉约定。
2. 制作首章供人审核，再逐章编写 SVG 动画、旁白节拍与测验。
3. 旁白通过 Edge TTS 合成，静态站点与原始 PDF、提取文本分开存放。

## 结果

归属：作者自述。仓库提供在线书架、预览媒体和 site 示例目录；已读工作流，尚未逐章检查教学内容或播放旁白。


## 尝试与复现

检查程度：有复现文档

1. 取得仓库并检查 site 目录。
2. 运行 python3 -m http.server 8765 -d site，打开 http://localhost:8765/ 浏览已有示例。
3. 重新生成章节需另行配置 Claude Code、Opus 5.5 和作者文档列出的 PDF、TTS 与预览工具。

## 局限

- README 的“Opus 5.5 only”不代表所有媒体都由模型原生输出；实际工作流使用外部 Edge TTS。
- 首章及章节规划需要人工审核，不描述为整本书一次输入完成。
- 本轮未安装该 Skill、执行生成或核验各章知识与测验答案。
- 作者当前版本没有图像模型、配乐或完整多语言支持。

## 来源

- [papermorph-readme](https://github.com/DozenTwelve/Papermorph/blob/main/README.md) · 已读正文 · 2026-10-05：已读取原始正文，未运行项目或完整观看媒体。 文件 SHA f2e2b44e586d6f47db79dd554304e75781efae2f
- [papermorph-skill](https://github.com/DozenTwelve/Papermorph/blob/main/.claude/skills/papermorph/SKILL.md) · 已读正文 · 2026-10-05：已读取原始正文，未运行项目或完整观看媒体。 文件 SHA 2e4f1637e1fa1fdf526218212f7546e3510618ab

[返回首页](../README.md)

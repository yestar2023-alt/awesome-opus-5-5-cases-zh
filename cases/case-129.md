# QQ 飞车风格竞速与漂移

以 QQ 飞车键位和漂移玩法为目标，制作网页赛车与多条赛道。

作者：riba2534 · 状态：已核验

## 对象归属

作者仓库明确说明这三个项目由 Opus 5.5 在 Claude Code 中制作。

## 输入

公开程度：完整公开

作者 README 的对应游戏段落提供完整短输入；本库只给位置，不全文转载。

[公开输入位置（未必在本库全文转载）](https://github.com/riba2534/claude-opus-5-5-demo)

## 已知流程

1. 作者提出短任务，在 Claude Code 中完成；后续自测和修复按作者记录。
2. 已读取此目录的依赖及 esbuild 脚本，打包为单个 HTML。

## 结果

归属：作者自述。以 QQ 飞车键位和漂移玩法为目标，制作网页赛车与多条赛道。


## 尝试与复现

检查程度：有复现文档

1. 取得作者仓库，进入 qq-speed 目录。
2. 按文档运行 npm install，再运行 node build.mjs。
3. 打开 dist/index.html，检查所述控制、场景和错误；本轮未执行构建。

## 局限

- 一次输入不表示内部只执行一步；生成、测试和修复发生在代理会话中。
- 仅核对文档、依赖与构建脚本，没有独立游玩或完成本地构建。

## 来源

- [riba-repo](https://github.com/riba2534/claude-opus-5-5-demo) · 已读正文 · 2026-09-30：已读作者 README；一次输入、测试及部署过程均按作者记录。
- [riba-qq-speed-package-json](https://github.com/riba2534/claude-opus-5-5-demo/blob/main/qq-speed/package.json) · 已读正文 · 2026-09-30：GitHub 文件接口逐一读到：独立工程依赖清单。
- [riba-qq-speed-build-mjs](https://github.com/riba2534/claude-opus-5-5-demo/blob/main/qq-speed/build.mjs) · 已读正文 · 2026-09-30：GitHub 文件接口逐一读到：esbuild 从本目录入口构建并内联输出 dist/index.html。

[返回首页](../README.md)

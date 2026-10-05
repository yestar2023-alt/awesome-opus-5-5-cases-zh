# 夜之学校：固定镜头生存恐怖游戏

在深夜日本学校探索怪谈的网页恐怖游戏，采用固定镜头、复古画面与故事章节；与作者此前的卡牌游戏是独立项目。

作者：AiSongMan / KantLex · 状态：已核验

## 对象归属

已核对原作者帖正文，明确使用 Claude Opus 5.5，并指向这个独立源码仓库。

## 输入

公开程度：未公开或未核对原文

原帖只摘要制作方向：Alone in the Dark 风格与日本学校恐怖主题，没有完整输入。

## 已知流程

1. 作者称用 Opus 5.5 在数小时内制作游戏；不把个人时间描述当成普遍基准。
2. 源码以 Three.js 渲染，浏览器 WebAudio 合成音乐和环境声，女主角语音来自 ElevenLabs。
3. 构建脚本将 src 中的 HTML 和 JavaScript 拼成 index.html，仓库提供本地启动说明。

## 结果

归属：作者自述。仓库说明包含房间探索、怪谈敌人、章节与多语言；已读到独立构建脚本和渲染入口，但没有实际通关或检查全部功能。


## 尝试与复现

检查程度：有复现文档

1. 取得作者仓库，先阅读 README 和源码；本轮没有执行作者脚本。
2. 按作者说明运行 ./build.sh 生成 index.html，再以 python3 -m http.server 8000 启动本地服务。
3. 浏览器打开本地地址；需能访问 Three.js CDN 与字体资源，分别检查操作、保存和语言。

## 局限

- 女主角语音由 ElevenLabs 生成，不属于代码合成音效，也不随源码 MIT 许可一并授权。
- 本轮只读原帖、文档、构建脚本与部分入口源码，未运行、通关或独立复现。
- 学校、人物和怪谈是作者的虚构设定，不用于说明真实事件。

## 来源

- [x-2105174453818654723](https://x.com/aisongman/status/2105174453818654723) · 已读正文 · 2026-09-30：Chrome 按目标帖自己的时间永久链接读取，核对作者、版本和项目地址；未看完预告片。
- [yoru-readme](https://github.com/KantLex/yoru-no-gakko/blob/main/README.md) · 已读正文 · 2026-09-30：已读项目说明和运行文档，确认独立恐怖游戏、外部 CDN 与 ElevenLabs 配音；blob SHA 1cd7bd8362bb92b0212de872633137c7a9757bd0。
- [yoru-build](https://github.com/KantLex/yoru-no-gakko/blob/main/build.sh) · 已读正文 · 2026-09-30：已读构建脚本，拼接 src 文件生成 index.html；未执行。blob SHA 223a09cb2ec615b4d68e88e26752fbbf9a98b3ef。
- [yoru-core](https://github.com/KantLex/yoru-no-gakko/blob/main/src/01-core.js) · 已读正文 · 2026-09-30：已读前 45 行，确认 Three.js CDN 导入及低分辨率渲染设置；未读取全部游戏逻辑。blob SHA 9e6f4cf8ffccc25fead2f553232084d556527eba。

[返回首页](../README.md)

# cardiHero 像素卡牌对战

AiSongMan 用 Opus 5.5 制作炉石风格像素 1v1 卡牌游戏，并在同一线程公开 Claude 作品和 GitHub 源码。

作者：aisongman · 状态：已核验

## 对象归属

目标帖正文明确提到 Opus 5.5；不以二手索引作为版本证据。

## 输入

公开程度：完整公开

原作者 README 公开完整短输入，以下只引用这段简短原文。

[公开输入位置（未必在本库全文转载）](https://github.com/KantLex/cardiHero/blob/main/README.md)

[查看公开输入或标记的重构输入](../prompts/case-119.md)

## 已知流程

1. 作者提交像素风卡牌游戏短输入。
2. 作者仓库说明使用 Canvas、原生 JavaScript 和程序化图像/声音，提供规则引擎与 AI 模块。
3. 发布作品与独立源码，并公开完整输入和运行说明。

## 结果

归属：作者自述。AiSongMan 用 Opus 5.5 制作炉石风格像素 1v1 卡牌游戏，并在同一线程公开 Claude 作品和 GitHub 源码。


## 尝试与复现

检查程度：有复现文档

1. 取得 cardiHero 仓库，打开 index.html，或按作者说明用 python3 -m http.server 提供本地服务。
2. 作者另有 node tests/sim.js 200 的无头 AI 对局检查；本轮未执行。
3. 先核对出牌、攻击和回合结束，再判断规则；文档的功能清单不是本轮实测结论。

## 局限

- 未测试完整对局、AI、平衡和规则不变量；作者的功能清单仍按自述。
- 模型生成次数按原作者说明，未取得生成会话日志。

## 来源

- [x-2103763192971461057](https://x.com/aisongman/status/2103763192971461057) · 已读正文 · 2026-09-30：直接定位原帖自己的时间链接并读取正文；未播放完整媒体或独立运行代码。
- [reference-index](https://github.com/yihui-dev/awesome-opus5-5-videos) · 已读正文 · 2026-09-29：候选发现索引；本地读取 389 条记录，原帖 URL 均不同。其提示词字段未逐条与原作者核对。
- [cardihero-demo-reply](https://x.com/aisongman/status/2103763194896593067) · 已读正文 · 2026-09-30：作者回复给出 Claude artifact 链接；未实际试玩。
- [cardihero-code-reply](https://x.com/aisongman/status/2103763196553408631) · 已读正文 · 2026-09-30：作者回复给出 KantLex/cardiHero 源码链接。
- [cardihero-code](https://github.com/KantLex/cardiHero) · 已读正文 · 2026-09-30：已读 GitHub 仓库页面和文件入口，未运行游戏。
- [cardihero-readme](https://github.com/KantLex/cardiHero/blob/main/README.md) · 已读正文 · 2026-09-30：已通过 GitHub 文件接口读取 README，包含 Opus 5.5 归属、完整短输入、本地打开方法和测试说明；未执行测试。blob SHA 59655064f70dab3ca8bbbad46665938a28184874。

## 更正与补充记录

- 2026-09-30：由待审转为正式案例；题名从“像素风一对一卡牌游戏”改为“cardiHero 像素卡牌对战”；未测试完整对局、规则平衡或 AI，对外部仓库只检查可访问性与文件入口。；[x-2103763192971461057](https://x.com/aisongman/status/2103763192971461057)
- 2026-09-30：补读 README，确认完整短输入与本地运行文档；文档检查不等于实际运行。；[cardihero-readme](https://github.com/KantLex/cardiHero/blob/main/README.md)

[返回首页](../README.md)

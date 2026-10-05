# 实践与适用边界

证据类型区分官方建议、跨案例观察、单案例经验和待验证假设；合集不能证明某做法普遍最优。

<a id="time-based-rendering"></a>
## 以时间函数控制逐帧渲染

证据类型：cross_case_pattern

做法：画面根据给定时间或帧号计算，截图工具逐帧取样，编码工具合成；需要音画同步时共享节拍或事件时间。

适用条件：需要可重复截图、离线输出和准确镜头时序的代码动画。

验收方法：重复渲染同一帧并比较；检查首尾、关键事件、帧数和音画时序。以上为编辑建议，未在所有案例上独立执行。

失效边界：这些作者采用相近结构，不证明其必然提高质量；随机种子、视频解码和平台字体仍可能破坏确定性。

案例：[case-063](cases/case-063.md)、[case-078](cases/case-078.md)、[case-080](cases/case-080.md)、[case-130](cases/case-130.md)

来源：[x-2103206747846701462](https://x.com/ParkerRex/status/2103206747846701462)、[x-2103485566570369333](https://x.com/__morse/status/2103485566570369333)、[x-2102554209166000267](https://x.com/twoclipping/status/2102554209166000267)、[clawd-cartoon-guide](https://github.com/az9713/opus-5.5-musical-cartoon/blob/main/clawd-prose/README.md)

<a id="explicit-human-inputs"></a>
## 把人工输入和后续修改记录为制作过程

证据类型：cross_case_pattern

做法：在生成前明确设计文件、图纸、需求或原型，在更新中记录用户修改的用途、样式和控制方式。

适用条件：案例依赖已有设计或产品上下文，需要读者判断可复用条件。

验收方法：读者能识别哪些来自输入、模型实现或人工修订；对依赖原型的结果不写成从零完成。

失效边界：这是证据记录方法，不证明任何一种输入方式普遍更有效；私有上下文缺失时仍不能完整复现。

案例：[case-083](cases/case-083.md)、[case-090](cases/case-090.md)、[case-102](cases/case-102.md)、[case-116](cases/case-116.md)

来源：[x-2103739079745827092](https://x.com/BThreeAgency/status/2103739079745827092)、[x-2104181266459644283](https://x.com/aayush4soni/status/2104181266459644283)、[x-2103789415323562325](https://x.com/froessell/status/2103789415323562325)、[x-2104070894251282849](https://x.com/izmaelmag/status/2104070894251282849)

<a id="sample-review-loop"></a>
## 将渲染检查与修复纳入代理制作流程

证据类型：cross_case_pattern

做法：先检查样帧、交互和运行问题，再按问题修改、保留版本并重新检查；把这些内部步骤与用户输入次数分开统计。

适用条件：长时间创作、三维程序或需要多轮质量修订的动画。

验收方法：保留问题清单、修改依据和检查结果；有能力时复查同一条件下的问题是否消失。

失效边界：各案例的审查次数和效果主要由作者报告；不能据此称多代理或多轮自测已被证明优于单代理。

案例：[case-067](cases/case-067.md)、[case-068](cases/case-068.md)、[case-127](cases/case-127.md)、[case-130](cases/case-130.md)

来源：[x-2103881538592981110](https://x.com/NathanWilbanks_/status/2103881538592981110)、[x-2103117246860345550](https://x.com/Voxyz_ai/status/2103117246860345550)、[riba-repo](https://github.com/riba2534/claude-opus-5-5-demo)、[clawd-cartoon-repo](https://github.com/az9713/opus-5.5-musical-cartoon)

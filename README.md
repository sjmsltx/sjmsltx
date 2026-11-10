# 李滨宇 · libinyu

地理信息科学在读，西南大学。平时写点自己想做的东西——大多是先被一个问题卡住，然后把它拆开做完。

我更在意**过程能不能被验证**，而不是结论看起来对不对。所以做的东西都尽量留下数据、跑法和踩过的坑。

---

## 在做的事

**桌面 AI 桌宠** — [deepseek-desktop-pet](https://github.com/sjmsltx/deepseek-desktop-pet)

Python + PySide6 + DeepSeek。双角色、长期记忆、工具调用，从 2.x 迭代到 3.x。

最近大半时间在啃它的一块硬骨头：**长期记忆该不该说出口**。让程序记住一个人不难，难的是每次开口前判断「这句话现在该不该讲」——判错就是「你正问代码报错，它突然提你爱吃桃片」。

调了几个月阈值之后发现方向错了：候选里本来就有答案，缺的不是「找得到」，是「挑得对」。

---

## 其他东西

| 项目 | 说明 |
|---|---|
| [satellite-orbit-sim](https://github.com/sjmsltx/satellite-orbit-sim) | 卫星轨道模拟器：GEO/SSO 可视化 + 真实 TLE(SGP4) + 星座分组 |
| [ai-knowledge-base-indexer](https://github.com/sjmsltx/ai-knowledge-base-indexer) | 通用知识库索引器，给本地文档建可检索的目录 |
| [agent-governance-template](https://github.com/sjmsltx/agent-governance-template) | 跨 harness 的 Agent 自治管理模板（规/序/物 + 检索） |
| [autoclaw-mgmt-template](https://github.com/sjmsltx/autoclaw-mgmt-template) | 个人管理系统模板 |

---

## 常用的

Python / PySide6 · GIS（ArcGIS Pro、QGIS、GDAL）· 一点前端

**最近在折腾**：向量检索、记忆压缩、评测方法

---

## 写的东西

技术记录写在博客里，大多是实验失败的过程，不是成功经验：

- RRF 名次融合为什么救不了「该不该说」
- 三种标定方法，全都失败了
- 一个从没生效过的功能（生产环境的兜底代码如何掩盖故障）

> 结论的对错你可能没法验证，但过程可以。

<!-- 博客地址待部署后补 -->

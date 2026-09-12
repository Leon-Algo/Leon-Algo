# 李健 · Leon

### AI 算法工程师 · 大模型后训练与企业 Agent

我在深圳做 AI 算法与工程，主导过 **9 个 AI 项目从 0 到 1**。工作从业务问题出发，覆盖模型训练、效果评估和系统交付。

[技术博客](https://www.cnblogs.com/Leon-Algo) · [公开代码](https://github.com/Leon-Algo?tab=repositories)

<sub>AI engineer in Shenzhen, working on LLM post-training, reinforcement learning and enterprise agents.</sub>

---

## 最近的工作

**让小模型可靠地完成企业查询任务**

企业里的 AI 需要查对数据，也需要满足私有化部署与稳定性要求。在电能质量台账查询 Agent 项目中，我主导数据构建、监督微调、强化学习、奖励设计和评估，把一次查询中的工具调用与最终答案一起纳入检查。

在同口径的台账工具任务模型裁判（Judge）评估中，**2B 专训模型正确率为 86%，外部 35B 模型为 63%**。这里比较的是特定业务任务的表现；训练框架和问题诊断方法也已迁移到后续 Agent 项目。

**把设计院的手工绘图变成可交付的自动化系统**

我主导 CADDrawer 智能绘图引擎，打通结构化数据、规则校验、空间布局到 DWG 图纸输出，并通过钉钉工作台交付设计院使用。原先小时级的手工绘图缩短到分钟级，**人力节省 80%+**。

<sub>以上为企业项目经历，指标来自项目内评估与交付记录；业务代码与数据不在本主页公开。</sub>

## 可以直接看的作品

下面是公开代码与个人工程实践，与上面的企业项目分开列出。

| 项目 | 看什么 |
| --- | --- |
| [DesktopPets](https://github.com/Leon-Algo/mac-desktop-pets) | 桌面宠物应用：同一 Swift 核心连接 macOS 与 Windows，包含交互实现、测试和发布记录。 |
| [MIBSA 算法示例](https://github.com/Leon-Algo/MIBSAdemo_code) | 路径规划方向的算法实验与可视化代码。 |

## 技术背景

- **训练与评估**：PyTorch、SFT、GRPO/PPO、奖励设计、模型蒸馏、LLM-as-Judge。
- **工程实现**：Python、FastAPI、MongoDB、vLLM；从训练数据生产到服务部署。
- **教育与研究**：华中农业大学应用统计学硕士；以第一作者在 *Optical Fiber Technology* 发表光纤网络规划算法论文（2024）。
- **团队实践**：2026 年 AttraX AI 黑客松，所在团队获赛道一等奖，我承担后端与算法开发。

## 继续了解

我把技术实践整理在 [博客](https://www.cnblogs.com/Leon-Algo)，也在公众号 **拾光学迹** 分享。

如果你正在做企业 Agent、模型后训练或 AI 产品落地，欢迎交流具体问题、技术方案与合作机会。

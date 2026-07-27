# Johnny Watters / 0AI / CyberViser

<p align="center">
  <a href="https://cyberviserai.com/">
    <img src="https://raw.githubusercontent.com/0ai-Cyberviser/0ai/main/assets/0ai-social-card.png" alt="CyberViser AI / 0AI portfolio hub" width="100%">
  </a>
</p>

<p align="center">
  <strong><a href="https://cyberviserai.com/">cyberviserai.com</a></strong>
  · <a href="https://0ai-cyberviser.github.io/0ai/">0AI Pages</a>
  · <a href="https://cyberviser.github.io/Hancock/">Hancock Pages</a>
  · <a href="https://github.com/0ai-Cyberviser">GitHub</a>
</p>

`0ai-Cyberviser` 是 Johnny Watters 的主要 GitHub 个人资料，也是 CyberViser / 0AI 的公开工程身份。

其使命是围绕 AI 智能体、模糊测试（fuzzing）、数据集生成、漏洞情报、SOC/IR 工作流以及 GitHub 维护自动化，构建一个互联、伦理且开源的网络安全自动化生态系统。

## 核心技术栈

| 项目 | 角色 | 链接 |
|---|---|---|
| CyberViser AI | 将生态系统整合在一起的公共枢纽 | https://cyberviserai.com/ |
| Hancock | 用于渗透测试、SOC、Sigma、YARA、IOC、OSINT、代码、CISO 和模糊测试工作流的 AI 网络安全智能体 | https://github.com/0ai-Cyberviser/Hancock |
| PeachFuzz | 用于 harness、崩溃最小化、复现器和解析器语料库的模糊测试引擎 | https://github.com/0ai-Cyberviser/peachfuzz |
| PeachTree | 用于构建安全、可追溯 JSONL 数据集的递归学习树数据集引擎 | https://github.com/0ai-Cyberviser/PeachTree |
| MrClean | 策略优先的 GitHub PR/仓库维护智能体 | https://github.com/0ai-Cyberviser/mrclean |
| 0AI | 更广泛的项目协调和作品集展示面 | https://github.com/0ai-Cyberviser/0ai |
| CyberViser-ViserHub | CyberViser AI 公开网站的源代码仓库 | https://github.com/0ai-Cyberviser/CyberViser-ViserHub |

## 免费优先的运行模式

当前的构建路径特意保持低成本：

- 使用 GitHub Pages 托管公开网站
- 在可用情况下使用 GitHub Actions 进行 CI 和部署
- 使用 Pull requests 进行可审查的改进
- 使用 Issues 跟踪路线图
- 在本地机器上运行数据集和模糊测试工作流
- 在仓库/网站完善阶段不依赖付费 GPU

## 项目如何关联

```mermaid
flowchart LR
    Site[cyberviserai.com] --> Hancock[Hancock]
    Site --> PeachFuzz[PeachFuzz]
    Site --> PeachTree[PeachTree]
    Site --> MrClean[MrClean]
    MrClean --> PRs[PR / Repo Maintenance]
    PeachFuzz --> Seeds[Fuzz Seeds + Reproducers]
    PeachTree --> Datasets[JSONL Datasets]
    Datasets --> Hancock
    Seeds --> Hancock
```

## 仓库完善标准

每个核心仓库都应致力于实现：

- 清晰的任务陈述（Mission Statement）
- 徽章（Badges）和状态链接
- 快速入门指南
- 架构或工作流图表
- 安全 / 伦理边界定义
- 相关项目链接
- 路线图
- 回链至 `https://cyberviserai.com/`

## 账户结构

- [0ai-Cyberviser](https://github.com/0ai-Cyberviser): 主要的工程和作品集账户
- [cyberviser](https://github.com/cyberviser): CyberViser 品牌和项目发布账户
- [cyberviser-dotcom](https://github.com/cyberviser-dotcom): 公共分叉（fork）和分发账户

## 所有权与许可政策

- 原始 0AI / CyberViser 项目根据其特定仓库的许可条款和控制通知进行维护。
- 分叉仓库仍受其上游许可的约束。
- 分叉仓库中的所有权主张仅适用于由 Johnny Watters 合法控制的分叉特定修改、品牌、元数据、通知以及新的原创材料。

## 联系方式

- 0ai@cyberviserai.com
- cyberviser@proton.me

<sub>由 Johnny Watters (`0ai-Cyberviser`) 在 CyberViser / 0AI 旗下运营。</sub>

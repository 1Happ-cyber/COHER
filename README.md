# Balancing Tripartite Interests in Cloud Service Composition and Optimal Selection via Curriculum-based Reinforcement Learning

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/release/python-380/)
[![Paper](https://img.shields.io/badge/Paper-Accepted-success.svg)](#) <!-- 在这里替换为你的论文链接 -->

本仓库是论文 **"Balancing Tripartite Interests in Cloud Service Composition and Optimal Selection via Curriculum-based Reinforcement Learning"** 的官方 PyTorch 实现。

我们提出了一种名为 **COHER** 的新型深度强化学习算法，旨在解决智能制造 (IMfg) 场景下云服务组合与优选 (CSCOS) 中的三方利益平衡问题。

---

## 🌟 核心亮点 (Key Features)

- **多维目标优化**：首次在服务优选中综合平衡了消费者、提供商和云平台三方的利益。
- **软后见经验回放 (Soft HER)**：通过提供更细粒度的奖励，有效缓解了多维目标扩展带来的严重“奖励稀疏”问题。
- **课程学习 (Curriculum Learning)**：引入课程学习机制引导智能体进行更有效的学习过程，大幅提升了收敛速度和学习效率。
- **卓越的性能**：在不同规模的任务场景下均表现出极高的求解效率和质量。

---

## 📊 实验结果 (Performance)

我们在四个不同规模的测试场景（200, 300, 400, 500 个任务）下进行了广泛的实验。与当前最先进的基线模型 (SOTA) 相比，**COHER** 展现出了显著的优势：

| **评估指标** | **COHER 表现** | **对比 SOTA 提升/优势** |
| :--- | :--- | :--- |
| **QoS (服务质量)** | 显著提升 | 平均提升 **6.8%** |
| **求解时间** | 极速响应 | 平均耗时仅 **0.69 秒** |
| **收敛稳定性** | 强 | 成功克服多维奖励稀疏陷阱 |

*(注：详细的实验对比图表请参考论文实验部分或 `results/` 文件夹。)*

---

## ⚙️ 环境依赖 (Prerequisites)

请确保你的本地环境满足以下要求：

- OS: Linux (推荐 Ubuntu 20.04) / Windows
- Python >= 3.8
- PyTorch >= 1.10.0

安装所需依赖包：

```bash
git clone https://github.com/YourUsername/Your-Repo-Name.git
cd Your-Repo-Name
pip install -r requirements.txt

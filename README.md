# Balancing Tripartite Interests in Cloud Service Composition and Optimal Selection via Curriculum-based Reinforcement Learning

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/release/python-380/)
[![Paper](https://img.shields.io/badge/Paper-Accepted-success.svg)](#) <!-- 在这里替换为你的论文链接 -->

本仓库是论文 **"Balancing Tripartite Interests in Cloud Service Composition and Optimal Selection via Curriculum-based Reinforcement Learning"** 的官方 PyTorch 实现。

我们提出了一种名为 **COHER** 的新型深度强化学习算法，旨在解决智能制造 (IMfg) 场景下云服务组合与优选 (CSCOS) 中的三方利益平衡问题。

---

## 🌟 Key Features

- **多维目标优化**：首次在服务优选中综合平衡了消费者、提供商和云平台三方的利益。
- **软后见经验回放 (Soft HER)**：通过提供更细粒度的奖励，有效缓解了多维目标扩展带来的严重“奖励稀疏”问题。
- **课程学习 (Curriculum Learning)**：引入课程学习机制引导智能体进行更有效的学习过程，大幅提升了收敛速度和学习效率。
- **卓越的性能**：在不同规模的任务场景下均表现出极高的求解效率和质量。

---
## ⚙️ Framework

<img width="879" height="416" alt="image" src="https://github.com/user-attachments/assets/f547bda8-c126-435d-a2bb-d37952b06edf" />

---
## 📊 Performance

The QoS values of various models across task scales T200, T300, T400, and T500
<img width="813" height="739" alt="image" src="https://github.com/user-attachments/assets/ae08a4cb-5681-4a38-b085-52f20925d393" />

---

## ⚙️ Prerequisites

- OS: Linux (Ubuntu 20.04)
- Python >= 3.8
- PyTorch >= 1.10.0

安装所需依赖包：

```bash
git clone https://github.com/1Happ-cyber/COHER.git
cd COHER
pip install -r requirements.txt

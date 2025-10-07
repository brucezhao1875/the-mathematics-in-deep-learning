# The Mathematics in Deep Learning (深度学习里的数学知识)

## 项目简介 (Project Introduction)

本项目旨在系统地积累和整理深度学习 (Deep Learning)、人工智能 (AI) 和机器学习 (Machine Learning) 领域所需的数学知识与思考。我们将以数学的永恒性和深度为指引，深入探索这些技术背后的数学原理，并记录学习体会。

本项目将参考包括 Springer GTM (Graduate Texts in Mathematics) 系列在内的经典数学教材，但笔记结构将更侧重于知识点的归纳和个人理解，而非严格遵循某一本书的章节。

## 目录结构 (Directory Structure)

```
.
├── README.md                 # 项目介绍、目录、如何使用等
├── .gitignore                # Git忽略文件配置
├── docs/                     # 存放所有数学笔记的根目录
│   ├── Linear_Algebra/       # 线性代数 (如：向量、矩阵、特征值、SVD等)
│   ├── Calculus/             # 微积分 (如：导数、梯度、链式法则、积分等)
│   ├── Probability_Statistics/ # 概率论与数理统计 (如：概率分布、贝叶斯定理、假设检验等)
│   ├── Optimization/         # 优化理论 (如：梯度下降、凸优化、各种优化器等)
│   ├── Information_Theory/   # 信息论 (如：熵、交叉熵、KL散度等)
│   ├── General_Concepts/     # 跨领域或通用数学概念 (如：集合论、群论基础等)
│   └── Daily_Log/            # 每日笔记和随笔，可以先在这里记录，再定期整理到其他分类
└── assets/                   # 存放笔记中使用的图片、图表等资源
```

## 如何使用 (How to Use)

1.  **日常记录**：
    *   当你阅读 GTM 系列书籍或其他资料，产生新的思考或体会时，可以先在 `docs/Daily_Log/` 目录下创建一个新的 Markdown 文件进行记录。建议文件名包含日期，例如 `2025-10-07_GTM_X_阅读体会.md`。
    *   这些笔记可以比较随意，记录你的即时想法、疑问、关键概念等。

2.  **整理与归档**：
    *   当 `Daily_Log/` 中的某个主题笔记积累到一定程度，或者你希望对其进行更系统化的整理时，可以将其内容提炼、完善，并移动到 `docs/` 下对应的数学领域文件夹中（例如 `docs/Linear_Algebra/`）。
    *   在整理后的笔记中，请务必注明参考来源，特别是 GTM 系列书籍的名称和章节，例如：“*本笔记主要参考 GTM 123: Linear Algebra Done Right, 第五章。*”

3.  **添加资源**：
    *   笔记中使用的任何图片、图表或其他辅助文件，请统一存放在 `assets/` 目录下，并在 Markdown 文件中正确引用。

## 贡献与反馈 (Contribution & Feedback)

欢迎对本项目提出建议、纠正错误或分享你的学习心得。你可以通过提交 Issue 或 Pull Request 的方式参与进来。

---

**开始你的数学探索之旅吧！**

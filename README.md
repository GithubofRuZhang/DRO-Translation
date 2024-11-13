# Distributionally Robust Optimization (分布鲁棒优化) 译文

## 项目概述 (Project Overview)
这个项目是对文章《Distributionally Robust Optimization》的中文翻译，原文由 Daniel Kuhn、Soroosh Shafiee 和 Wolfram Wiesemann 撰写，并于2024年11月4日提交至数学领域的优化与控制学科（Mathematics > Optimization and Control）上。本文旨在提供分布鲁棒优化（DRO）领域的综述，解释其核心概念、方法以及在不同领域的应用。

This project is a Chinese translation of the paper "Distributionally Robust Optimization," authored by Daniel Kuhn, Soroosh Shafiee, and Wolfram Wiesemann, and submitted on November 4, 2024, to the Mathematics > Optimization and Control section. The paper aims to provide an overview of the field of Distributionally Robust Optimization (DRO), explaining its key concepts, methods, and applications across various fields.

### 文章概述 (Paper Overview)
分布鲁棒优化（DRO）研究在不确定性下的决策问题，其中不确定问题参数的概率分布本身也存在不确定性。DRO模型的关键组成部分是其模糊集，即一组与可用的结构或统计信息一致的概率分布。DRO旨在寻找在模糊集中的最坏分布下表现最好的决策。该最坏情况准则得到了心理学和神经科学研究的支持，表明许多决策者对分布的模糊性具有较低的容忍度。DRO根植于统计学、运筹学和控制理论，最近的研究揭示了它与机器学习中的正则化技术和对抗训练之间的深刻联系。本文综述以统一且自包含的方式呈现了该领域的主要研究成果。

Distributionally Robust Optimization (DRO) studies decision problems under uncertainty where the probability distribution governing the uncertain problem parameters is itself uncertain. A key component of any DRO model is its ambiguity set, which is a family of probability distributions consistent with any available structural or statistical information. DRO seeks decisions that perform best under the worst distribution in the ambiguity set. This worst-case criterion is supported by findings in psychology and neuroscience, indicating that many decision-makers have a low tolerance for distributional ambiguity. DRO is rooted in statistics, operations research, and control theory, and recent research has uncovered its deep connections to regularization techniques and adversarial training in machine learning. This survey presents the key findings of the field in a unified and self-contained manner.

**文章信息 (Paper Information)**
- 论文标题 (Title): Distributionally Robust Optimization
- 发表日期 (Submission Date): 2024年11月4日
- 作者 (Authors): Daniel Kuhn, Soroosh Shafiee, Wolfram Wiesemann
- 领域 (Subjects): 优化与控制 (math.OC), 机器学习 (cs.LG, stat.ML)
- DOI: [10.48550/arXiv.2411.02549](https://doi.org/10.48550/arXiv.2411.02549)
- 论文链接 (Paper Link): [arXiv:2411.02549](https://arxiv.org/abs/2411.02549)

## 项目目的 (Project Purpose)
该项目的目的是将这篇文章的核心内容翻译成中文，以便中文读者能够更容易理解和应用分布鲁棒优化的相关概念和方法。翻译后的内容将以Markdown格式整理，便于大家阅读、分享和修改。

The purpose of this project is to translate the core content of this paper into Chinese, making it easier for Chinese-speaking readers to understand and apply the concepts and methods related to Distributionally Robust Optimization (DRO). The translated content will be organized in Markdown format, making it easy for readers to read, share, and modify.

## 如何参与 (How to Contribute)
欢迎参与此翻译项目！如果你发现翻译中有任何问题或者有改进建议，欢迎提交Pull Requests。具体参与方法如下：

We welcome contributions to this translation project! If you notice any issues or have suggestions for improvement, feel free to submit Pull Requests. Here’s how to contribute:

1. Fork 本仓库。
2. 在你自己的Fork版本中修改或改进翻译。
3. 提交Pull Request，我们会尽快审查并合并你的修改。

1. Fork this repository.
2. Modify or improve the translation in your own Fork.
3. Submit a Pull Request, and we will review and merge your changes as soon as possible.

## 项目结构 (Project Structure)
- `README.md`：项目概述和参与说明 (Project Overview and Contribution Guidelines)
- `DRO_Translation.md`：翻译的正文内容 (Main Translated Content)
- `figures/`：如有插图或表格，可以存放在此文件夹中 (Folder for Figures or Tables, if applicable)

## 进度 (Progress)
- [ ] 第一部分翻译：进行中 (Second Section Translated: In Progress)
- [ ] 第二部分翻译：待翻译 (Third Section Translated: Pending)
- [ ] 第三部分翻译：待翻译 (Third Section Translated: Pending)

## 版权声明 (Copyright Notice)
此项目基于原文进行翻译，所有权归原作者所有。原文链接：[Distributionally Robust Optimization](https://arxiv.org/abs/2411.02549)。翻译仅用于学术交流，非商业用途。

This project is a translation based on the original work, with all rights reserved by the original authors. Original paper link: [Distributionally Robust Optimization](https://arxiv.org/abs/2411.02549). The translation is for academic exchange only and is not for commercial use.

---

如果你有任何问题或建议，欢迎通过GitHub Issues与我们沟通。

If you have any questions or suggestions, feel free to communicate with us through GitHub Issues.

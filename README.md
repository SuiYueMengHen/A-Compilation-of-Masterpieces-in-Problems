# A Compilation of Masterpieces in Problems | 难题杰作编译

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/your_github_username/your_repository_name/pulls)

> **A curated treasury of profound challenges in Mathematics and Physics.**
> **一份精心整理的数学与物理学深度难题集萃。**

This repository is an open-source collection of what I consider to be "masterpiece" problems—elegant, insightful, and deeply challenging puzzles that reveal the beauty and complexity of mathematical and physical thinking. It is designed for students, educators, and enthusiasts who seek to go beyond routine exercises and engage with truly exceptional problems.

本仓库是一个开源项目，收录了我个人甄选的“杰作”级难题——这些题目优雅、深刻且极具挑战性，旨在揭示数学与物理思维之美与复杂性。本项目面向学生、教育工作者及爱好者，帮助大家超越常规练习，接触真正非凡的难题。

## 📚 Table of Contents | 目录

-   [Overview | 项目概述](#-overview--项目概述)
-   [Content Structure | 内容结构](#-content-structure--内容结构)
-   [How to Use | 使用指南](#-how-to-use--使用指南)
-   [Compiling the TeX File | 编译 TeX 文件](#-compiling-the-tex-file--编译-tex-文件)
-   [Contributing | 贡献指南](#-contributing--贡献指南)
-   [License & Attribution | 许可与版权](#-license--attribution--许可与版权)
-   [Acknowledgments | 致谢](#-acknowledgments--致谢)

## 🎯 Overview | 项目概述

The name "Masterpieces in Problems" reflects the core idea: these problems are not merely difficult; they are works of art. Each one has been selected for its ability to illuminate a fundamental concept, demonstrate a surprising result, or employ a particularly clever method of solution. This living document is compiled in LaTeX and will grow over time with contributions from the community.

“难题杰作编译”这一名称反映了项目的核心思想：这些难题不仅仅是困难，它们更是艺术品。每一道题都因其能阐明一个基本概念、展示一个惊人结果、或运用一个特别巧妙的解决方法而被选中。本文档由 LaTeX 编写，是一个“活”的文档，期待随着社区的贡献而不断丰富。

## 📁 Content Structure | 内容结构

The main source file is `Masterpieces_in_Problems.tex`.

主源代码文件为 `Masterpieces_in_Problems.tex`.

```
.
├── Masterpieces_in_Problems.tex  # Main LaTeX source file | 主LaTeX源文件
├── Masterpieces_in_Problems.pdf  # Compiled output (Generated, not stored in repo) | 编译后的PDF（由脚本生成，不保存在仓库中）
├── assets/                       # Directory for figures and diagrams | 图片与图表目录
│   └── ...                
├── .github/
│   └── workflows/
│       └── build-latex.yml       # GitHub Action for auto-compiling PDF | 自动编译PDF的GitHub Action工作流
├── LICENSE
└── README.md
```

**The problems are tentatively organized into the following sections: | 问题暂定分为以下章节：**

*   **Mathematics | 数学**
    *   *Analysis*: Real, Complex, Functional
    *   *代数*: Abstract Algebra, Linear Algebra
    *   *Geometry & Topology*: Differential Geometry, Algebraic Topology
*   **Physics | 物理**
    *   *Classical Mechanics*: Lagrangian, Hamiltonian, Chaos
    *   *量子力学*: Foundations, Symmetries, Approximation Methods
    *   *Electrodynamics*: Statics, Dynamics, Radiation
    *   *Statistical Mechanics & Thermodynamics*: Ensembles, Phase Transitions
    *   *广义相对论与宇宙学*: Tensor Calculus, Cosmological Models
*   **Interdisciplinary & Puzzles | 交叉学科与趣味谜题**

## 🛠 How to Use | 使用指南

1.  **Read Online | 在线阅读:** The latest version of the PDF is automatically built and can be downloaded from the **Releases** page or the **Actions** tab.
    最新版本的PDF会自动编译生成，可从 **Releases** 页面或 **Actions** 标签页下载。
2.  **Download and Compile | 下载并编译:** Clone the repository to your local machine to get the LaTeX source. You can then compile it yourself to get a PDF (see instructions below).
    克隆本仓库至本地以获取LaTeX源代码，然后您可以自行编译生成PDF（见下文说明）。
3.  **Solve and Ponder | 钻研与思考:** Use this compilation for self-study, as a source for university tutorial sheets, or as a stimulating challenge for reading groups.
    您可将其用于自学、作为大学习题课的素材，或作为学习小组的 stimulating challenge。

## 📄 Compiling the TeX File | 编译 TeX 文件

### Locally | 在本地编译

You need a LaTeX distribution (e.g., TeX Live, MiKTeX, MacTeX).

您需要安装 LaTeX 发行版（如 TeX Live, MiKTeX, MacTeX）。

```bash
# Clone the repository | 克隆仓库
git clone https://github.com/your_github_username/your_repository_name.git
cd your_repository_name

# Compile the document | 编译文档
pdflatex Masterpieces_in_Problems.tex
# Run again to resolve references | 再次运行以处理引用
pdflatex Masterpieces_in_Problems.tex
```
A PDF file `Masterpieces_in_Problems.pdf` will be generated.
这将生成 `Masterpieces_in_Problems.pdf` 文件。

### Automatically via GitHub Actions | 通过 GitHub Actions 自动编译

This repository is configured with a **GitHub Action workflow** (`.github/workflows/build-latex.yml`). Every time you push a change to the `main` branch, the PDF will be automatically compiled and attached to a new "Release." You can download it from there.

本仓库配置了 **GitHub Action 工作流** (`.github/workflows/build-latex.yml`)。每次您向 `main` 分支推送更改时，PDF 将自动编译并附加到一个新的 "Release" 中。您可以从那里下载。

## 🤝 Contributing | 贡献指南

Contributions are the heart of this open-source project! You are warmly welcome to add new masterpieces, improve existing ones, or provide elegant solutions.

贡献是这个开源项目的核心！我们热烈欢迎您添加新的杰作、改进现有内容或提供优雅的解答。

**How to contribute: | 如何贡献：**

1.  **Fork** this repository.
    **Fork** 本仓库。
2.  **Create a feature branch** (`git checkout -b feature/AmazingProblem`)
    创建一个**特性分支** (`git checkout -b feature/AmazingProblem`)
3.  **Edit** the `Masterpieces_in_Problems.tex` file. Please follow the existing LaTeX formatting style. Use the `\problem{}` and `\solution{}` commands.
    **编辑** `Masterpieces_in_Problems.tex` 文件。请遵循现有的 LaTeX 格式风格。使用 `\problem{}` 和 `\solution{}` 命令。
4.  **Commit** your changes (`git commit -m 'Add an amazing problem from Landau'`)
    **提交**您的更改 (`git commit -m 'Add an amazing problem from Landau'`)
5.  **Push** to the branch (`git push origin feature/AmazingProblem`)
    **推送**到分支 (`git push origin feature/AmazingProblem`)
6.  **Open a Pull Request**. Describe the problem and its source.
    **开启一个 Pull Request**。请描述问题及其来源。

Please ensure that the problems you contribute are from sources that permit sharing for educational purposes. Always provide attribution where possible.

请确保您贡献的问题来自允许出于教育目的分享的来源。请尽可能提供 attribution。

## 📜 License & Attribution | 许可与版权

The **LaTeX source code** and **original written content** in this repository are licensed under the [MIT License](LICENSE).

本仓库中的 **LaTeX 源代码**和**原创文本内容**均采用 [MIT 许可证](LICENSE)。

**The problems themselves** are the intellectual property of their original authors (textbooks, academic papers, etc.). This compilation is considered a fair use for educational and non-commercial purposes. Every effort has been made to attribute the original source. If you are an author and believe a problem has been included without proper attribution or against your wishes, please contact me via GitHub Issues, and it will be removed immediately.

**问题本身**的版权归其原始作者（教科书、学术论文等）所有。本汇编被视为出于教育和非商业目的的合理使用。我们已尽力标注原始来源。如果您是原作者并认为某个问题未被正确标注或您不希望它被收录于此，请通过 GitHub Issues 与我联系，我将立即将其删除。

## 🙏 Acknowledgments | 致谢

*   The brilliant minds who authored the original problems and textbooks.
  感谢创作了原始难题和教科书的杰出学者。
*   Contributors and future contributors who help expand this collection.
  感谢帮助扩展本作品集的当前与未来的贡献者们。
*   The communities at [Physics Stack Exchange](https://physics.stackexchange.com/) and [Mathematics Stack Exchange](https://math.stackexchange.com/) for endless inspiration.
  感谢 [Physics Stack Exchange](https://physics.stackexchange.com/) 和 [Mathematics Stack Exchange](https://math.stackexchange.com/) 社区带来的无尽灵感。

---

*Happy Problem-Solving! | 祝您解题愉快！*

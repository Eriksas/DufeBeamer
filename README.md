# DufeBeamer
## 项目介绍
这是一个基于`Beamer`的演示文稿模板，特别适用于东北财经大学的学生和教职工。模板风格简洁优雅，支持中英文混排，具有东财蓝和东财红两种主题色选项。它不仅能为学术报告、课件展示提供帮助，还可以用作学校活动和会议的演示文稿模板。

## 特点
1.**主题色**：支持东财蓝和东财红主题色。
2.**图表展示**：内置图表、公式、代码和表格的展示模板，适合学术研究和报告。
3.**自定义命令与环境**：提供了多种常用命令与环境的支持，包括图表、列表、公式等。
4.**GitHub 项目地址**：/url[https://github.com/Eriksas/DufeBeamer]

## 安装方法
1. **克隆项目或下载 ZIP 文件到本地**：
   ```bash
   git clone https://github.com/Eriksas/DufeBeamer.git
2. **将模板文件复制到你的 LaTeX 项目中**
    在 LaTeX 编辑器中编译使用该模板。推荐使用`XeLaTeX`编译器，以确保中文字符的正确显示。

## 使用说明
**选择主题色**：

默认使用 `东财蓝` 主题色。你可以通过修改 `\usepackage[blue]{DufeBeamer}` 来选择东财蓝主题。
如果需要使用 东财红 主题色，修改为 `\usepackage[red]{DufeBeamer}`。
如果不需要背景样式，可以使用 `\usepackage{DufeBeamer}`。

**编译选项**：

中文支持：请使用 `XeLaTeX` 编译选项。
引用：请使用 BibTeX 来管理参考文献。
模板文件结构：

`DufeBeamer.tex`：主模板文件，包含了基本设置和样式。
参考文献文件（如 `.bib`）。

**常用命令与环境**：

`\cmd{command}`：自定义命令显示。
`\env{environment}`：环境命令展示（如 `itemize`, `enumerate` 等）。

支持多种数学公式、图表和表格的展示。

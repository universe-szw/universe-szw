<div align="center">

# Zhewei Shen · 沈哲炜

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=1000&color=2F81F7&center=true&vCenter=true&width=680&lines=LLM+Safety+%26+Evaluation;Benchmarks+%C2%B7+LLM-as-a-Judge;Reproducible+Experiments+%C2%B7+Open+Research" alt="LLM safety, evaluation, and reproducible experiments" />

**大模型安全与评测研究｜从风险样本构建到自动评分与实验验证**

希望参与 **AI 安全算法 / 大模型评测** 相关研究型实习，对 Agent 安全感兴趣。

[![Paper](https://img.shields.io/badge/Scientometrics-First_Author_2026-16803C?style=flat-square)](https://doi.org/10.1007/s11192-026-05773-0)
[![WSDM 2027](https://img.shields.io/badge/WSDM_2027-Main_Conference_Accepted-006D77?style=flat-square)](#-publications)
[![Benchmark](https://img.shields.io/badge/Benchmark-Code_%26_Data-2F81F7?style=flat-square&logo=github&logoColor=white)](https://github.com/universe-szw/scientometric-llm-ethics-benchmark)

[Featured Work](#-featured-work) · [Publications](#-publications) · [Toolkit](#-toolkit)

</div>

## 🔬 Featured Work

### [Scientometric LLM Ethics Benchmark](https://github.com/universe-szw/scientometric-llm-ethics-benchmark)

**面向科学计量学场景的五维大模型伦理评测。** 围绕引文核验、同行评议、资助评估等任务，检验模型的内容安全、隐私保护、偏见、鲁棒性与价值对齐表现。

项目自启动以来由我负责并维护，覆盖领域样本设计、实验实现、评测分析与论文撰写。

| Benchmark prompts | Ethical dimensions | Model families | Valid responses |
| :---: | :---: | :---: | :---: |
| **1,500** | **5** | **8** | **35,997** |

**Engineering & Validation**

- **实验采集**：覆盖 3 次重复运行，实现请求重试、断点续跑、结构化评分解析。
- **评分验证**：主评审与两种辅助评审对照，结合 **2,000 组人工验证样本—响应对**，分析评审敏感性与结果可靠性。
- **结果聚合**：先对每题重复评分取均值，再按模型与维度汇总，保留缺失值及有效样本数量说明。
- **开源复现**：公开样本、响应、评分和脚本，提供无需 API Key 的 dry-run 示例，以 **pytest + GitHub Actions** 验证解析、续跑和聚合逻辑。

#### Model × Dimension Results

<a href="https://github.com/universe-szw/scientometric-llm-ethics-benchmark#published-evaluation-results">
  <img src="https://raw.githubusercontent.com/universe-szw/scientometric-llm-ethics-benchmark/main/assets/figures/model_dimension_scores.png" alt="Published Figure 1: mean automated scores for eight model families across five ethical evaluation dimensions" width="900" />
</a>

<sub>论文 Figure 1：8 个模型系列在五个维度上的自动评分，汇总三次重复运行；色标为 0–10。结果对应论文报告的模型版本与实验条件，具体解释见论文中的人工验证及局限性分析。</sub>

**Explore** → [Code & Data](https://github.com/universe-szw/scientometric-llm-ethics-benchmark) · [Data Card](https://github.com/universe-szw/scientometric-llm-ethics-benchmark/blob/main/DATA_CARD.md) · [Quick Start](https://github.com/universe-szw/scientometric-llm-ethics-benchmark#quick-start-without-an-api-key) · [Paper](https://doi.org/10.1007/s11192-026-05773-0)

## 📄 Publications

**Finite-Budget Pair-Span Search for Classifier-Based Prompt Screening**<br>
*WSDM 2027* · **Main Conference 已录用** · To appear

研究固定分类器下的有限预算擦除-检查搜索，结合单片段证据、自适应双片段配对与确定性几何覆盖，分析攻击恢复率、查询成本与良性误报之间的权衡。

**Ethical evaluation of large language models for scientometrics: a multidimensional perspective**  
**Zhewei Shen** et al. · 第一作者 · *Scientometrics* **131**, 7001–7024 (2026)<br>
[DOI: 10.1007/s11192-026-05773-0](https://doi.org/10.1007/s11192-026-05773-0) · [Companion Repository](https://github.com/universe-szw/scientometric-llm-ethics-benchmark)

## 🛠 Toolkit

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,pytorch,git,githubactions,linux,latex&perline=6" alt="Python, PyTorch, Git, GitHub Actions, Linux, LaTeX" height="48" />
</p>

| Research & Evaluation | Experiments & Analysis |
| --- | --- |
| LLM-as-a-Judge · Benchmark 设计 · 人工验证 | Python · PyTorch · NumPy · Pandas |
| 安全评测 · 评审敏感性分析 · 结果聚合 | pytest · GitHub Actions · Matplotlib · LaTeX |

## 🐍 Contributions

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/universe-szw/universe-szw/output/github-snake-dark.svg" />
  <img src="https://raw.githubusercontent.com/universe-szw/universe-szw/output/github-snake.svg" alt="GitHub contribution snake, updated daily" width="900" />
</picture>

<div align="center">

欢迎交流大模型安全与评测问题，项目反馈可通过 [GitHub Issues](https://github.com/universe-szw/scientometric-llm-ethics-benchmark/issues) 提交。

</div>

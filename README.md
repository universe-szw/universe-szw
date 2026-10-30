<div align="center">

# Hi, I'm Zhewei Shen 👋

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=1000&color=2F81F7&center=true&vCenter=true&width=680&lines=LLM+Safety+%26+Evaluation;Benchmarks+%C2%B7+LLM-as-a-Judge;Reproducible+Experiments+%C2%B7+Open+Research" alt="LLM safety, evaluation, and reproducible experiments" />

研究大模型安全与评测，负责从领域数据构建、模型响应采集到自动评分与结果验证的实验实现。

[![Research](https://img.shields.io/badge/Research-LLM_Safety-2F81F7)](#-focus)
[![Paper](https://img.shields.io/badge/Paper-Scientometrics_2026-16803C)](https://doi.org/10.1007/s11192-026-05773-0)
[![Code](https://img.shields.io/badge/Code-Python-3776AB?logo=python&logoColor=white)](https://github.com/universe-szw/scientometric-llm-ethics-benchmark)

</div>

## 🔭 Focus

- **安全与伦理评测**：围绕内容安全、隐私保护、偏见、鲁棒性与价值对齐设计领域评测。
- **LLM-as-a-Judge**：实现自动评分，通过辅助评审及人工验证分析评分可靠性。
- **实验工程**：实现请求重试、断点续跑、结构化解析与评分聚合，使用离线测试和持续集成验证流程。

希望参与大模型安全算法与评测相关的研究型实习，对 Agent 安全也有兴趣。

## 🧩 Featured Project

### [Scientometric LLM Ethics Benchmark](https://github.com/universe-szw/scientometric-llm-ethics-benchmark)

面向科学计量学场景的大模型五维伦理评测。项目自启动以来由我负责并维护，公开了评测样本、模型响应、评分结果和实验脚本。

| 评测内容 | 公开材料 |
| --- | --- |
| 数据与覆盖范围 | 1,500 条样本，覆盖五个伦理维度 |
| 模型实验 | 8 个模型系列、3 次重复运行，35,997 条有效响应 |
| 评分验证 | 主评审与两种辅助评审，2,000 组人工验证样本—响应对 |
| 工程实现 | 响应采集、自动评分、断点续跑、按题与维度聚合 |
| 可复现性 | 无 API Key 的 dry-run 示例、数据说明、pytest 与 GitHub Actions |

**我的工作**：领域样本改写与风险标注、实验流程实现、评测分析、论文撰写，以及开源仓库的开发维护。

[代码与数据](https://github.com/universe-szw/scientometric-llm-ethics-benchmark) · [数据说明](https://github.com/universe-szw/scientometric-llm-ethics-benchmark/blob/main/DATA_CARD.md) · [离线运行示例](https://github.com/universe-szw/scientometric-llm-ethics-benchmark#quick-start-without-an-api-key) · [论文](https://doi.org/10.1007/s11192-026-05773-0)

<details>
<summary><b>查看论文中的模型 × 维度评测结果</b></summary>

![Eight model families across five ethical evaluation dimensions](https://raw.githubusercontent.com/universe-szw/scientometric-llm-ethics-benchmark/main/assets/figures/model_dimension_scores.png)

原论文 Figure 1：各模型在五个维度上的自动评分均值，汇总三次重复运行，色标为 0–10。该图对应论文报告的实验条件与模型版本；解释评分时需结合论文中的验证结果与适用范围。

</details>

## 📄 Publication

**Ethical evaluation of large language models for scientometrics: a multidimensional perspective**  
Zhewei Shen et al. · 第一作者 · *Scientometrics* **131**, 7001–7024 (2026)  
[DOI: 10.1007/s11192-026-05773-0](https://doi.org/10.1007/s11192-026-05773-0)

## 🛠 Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,pytorch,git,githubactions,linux,latex&perline=6" alt="Python, PyTorch, Git, GitHub Actions, Linux, LaTeX" />
</p>

**评测与数据**：LLM-as-a-Judge · Benchmark 设计 · NumPy · Pandas · Matplotlib  
**实验与验证**：pytest · 断点续跑 · 评分聚合 · 人工验证 · 评审敏感性分析

## 🐍 Contributions

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/universe-szw/universe-szw/output/github-snake-dark.svg" />
  <img src="https://raw.githubusercontent.com/universe-szw/universe-szw/output/github-snake.svg" alt="GitHub contribution snake" />
</picture>

项目问题或改进建议，欢迎通过 [GitHub Issues](https://github.com/universe-szw/scientometric-llm-ethics-benchmark/issues) 交流。

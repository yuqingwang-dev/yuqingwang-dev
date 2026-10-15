<picture>
  <source media="(max-width: 640px) and (prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/yuqingwang-dev/yuqingwang-dev/main/assets/hero-mobile-dark.svg?v=research-v2">
  <source media="(max-width: 640px)" srcset="https://raw.githubusercontent.com/yuqingwang-dev/yuqingwang-dev/main/assets/hero-mobile.svg?v=research-v2">
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/yuqingwang-dev/yuqingwang-dev/main/assets/hero-dark.svg?v=research-v2">
  <img src="https://raw.githubusercontent.com/yuqingwang-dev/yuqingwang-dev/main/assets/hero.svg?v=research-v2" alt="Sunny — AI Systems &amp; Applied Research. Agents / RAG / Recommendation." width="100%">
</picture>

<p align="center"><b>AI 应用开发 · Agent / RAG / 推荐系统</b></p>
<p align="center"><a href="https://github.com/yuqingwang-dev/GenRecAgent">GenRecAgent</a> · <a href="https://github.com/yuqingwang-dev/Qingtu">Qingtu 晴途</a> · <a href="https://github.com/yuqingwang-dev?tab=repositories">Repositories</a></p>

你好，我是 **Sunny**。我关注大模型应用、推荐系统，以及从模型到产品的完整实现。
我的项目围绕检索、工具调用与系统验证展开，重视实验记录、失败路径和可复现的结果。

<picture>
  <source media="(max-width: 640px) and (prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/yuqingwang-dev/yuqingwang-dev/main/assets/work-mobile-dark.svg?v=research-v2">
  <source media="(max-width: 640px)" srcset="https://raw.githubusercontent.com/yuqingwang-dev/yuqingwang-dev/main/assets/work-mobile.svg?v=research-v2">
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/yuqingwang-dev/yuqingwang-dev/main/assets/work-dark.svg?v=research-v2">
  <img src="https://raw.githubusercontent.com/yuqingwang-dev/yuqingwang-dev/main/assets/work.svg?v=research-v2" alt="01 Selected research &amp; systems — 精选研究与系统项目" width="100%">
</picture>

<a href="https://github.com/yuqingwang-dev/GenRecAgent">
<picture>
  <source media="(max-width: 640px) and (prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/yuqingwang-dev/yuqingwang-dev/main/assets/project-genrec-mobile-dark.svg?v=research-v2">
  <source media="(max-width: 640px)" srcset="https://raw.githubusercontent.com/yuqingwang-dev/yuqingwang-dev/main/assets/project-genrec-mobile.svg?v=research-v2">
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/yuqingwang-dev/yuqingwang-dev/main/assets/project-genrec-dark.svg?v=research-v2">
  <img src="https://raw.githubusercontent.com/yuqingwang-dev/yuqingwang-dev/main/assets/project-genrec.svg?v=research-v2" alt="GenRecAgent — 生成式推荐与可验证工具调用。112,590 件商品，8,151 名测试用户，9 个工具动作。" width="100%">
</picture>
</a>

[项目源码 ↗](https://github.com/yuqingwang-dev/GenRecAgent) · [架构设计](https://github.com/yuqingwang-dev/GenRecAgent/blob/main/docs/architecture.md) · [实验结果与适用范围](https://github.com/yuqingwang-dev/GenRecAgent/blob/main/docs/resume_project_zh.md)

<details>
<summary>项目摘要 / GenRecAgent</summary>

生成式推荐与可验证工具调用 Agent，连接 Semantic ID、生成式召回、工具执行与离线评测。

- 在 **112,590** 件商品、**8,151** 名测试用户上开展离线评测。
- 实现 RQ-VAE、Transformer 与 Dense 召回对照，以及 **9** 个工具动作的执行环境。
- 使用 Qwen + LoRA 进行工具调用实验，保留执行轨迹、约束校验与有界恢复。
- 技术：Python、PyTorch、Semantic ID、Qwen、LoRA。实验结果与限制见项目文档。

</details>

<br>

<a href="https://github.com/yuqingwang-dev/Qingtu">
<picture>
  <source media="(max-width: 640px) and (prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/yuqingwang-dev/yuqingwang-dev/main/assets/project-qingtu-mobile-dark.svg?v=research-v2">
  <source media="(max-width: 640px)" srcset="https://raw.githubusercontent.com/yuqingwang-dev/yuqingwang-dev/main/assets/project-qingtu-mobile.svg?v=research-v2">
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/yuqingwang-dev/yuqingwang-dev/main/assets/project-qingtu-dark.svg?v=research-v2">
  <img src="https://raw.githubusercontent.com/yuqingwang-dev/yuqingwang-dev/main/assets/project-qingtu.svg?v=research-v2" alt="Qingtu 晴途 — 中文 AI 旅行规划助手。真实 POI 与路线、混合检索 RAG、可观察的 Agent 工作流。" width="100%">
</picture>
</a>

[项目源码 ↗](https://github.com/yuqingwang-dev/Qingtu) · [RAG 设计](https://github.com/yuqingwang-dev/Qingtu/blob/main/docs/KNOWLEDGE_RAG.md) · [演示指南](https://github.com/yuqingwang-dev/Qingtu/blob/main/docs/demo_runbook.md) · [开源来源](https://github.com/yuqingwang-dev/Qingtu/blob/main/docs/UPSTREAM.md)

<details>
<summary>项目摘要 / Qingtu 晴途</summary>

基于开源项目二次开发的中文 AI 旅行规划助手，将真实地点、交通路线、攻略检索和 Agent 工作流整合到可交互产品中。

- 真实 POI 搜索与逐日路线规划。
- BM25 + 向量混合检索，回答附带来源。
- 可观察的 Agent 工作流与依赖服务状态页。
- 技术：FastAPI、Next.js、TypeScript、PostgreSQL、pgvector。

</details>

<picture>
  <source media="(max-width: 640px) and (prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/yuqingwang-dev/yuqingwang-dev/main/assets/engineering-mobile-dark.svg?v=research-v2">
  <source media="(max-width: 640px)" srcset="https://raw.githubusercontent.com/yuqingwang-dev/yuqingwang-dev/main/assets/engineering-mobile.svg?v=research-v2">
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/yuqingwang-dev/yuqingwang-dev/main/assets/engineering-dark.svg?v=research-v2">
  <img src="https://raw.githubusercontent.com/yuqingwang-dev/yuqingwang-dev/main/assets/engineering.svg?v=research-v2" alt="02 Research practice — 研究与工程实践" width="100%">
</picture>

| Evidence / 有据可依 | Observability / 过程可见 | Reproducibility / 结果可验 |
| :--- | :--- | :--- |
| 把回答落到检索结果、真实工具返回与可核验来源。 | 记录工具调用、停止条件与失败原因，区分模型输出和规则降级。 | 保留实验配置、测试与运行说明，明确指标适用范围。 |

<picture>
  <source media="(max-width: 640px) and (prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/yuqingwang-dev/yuqingwang-dev/main/assets/toolbox-mobile-dark.svg?v=research-v2">
  <source media="(max-width: 640px)" srcset="https://raw.githubusercontent.com/yuqingwang-dev/yuqingwang-dev/main/assets/toolbox-mobile.svg?v=research-v2">
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/yuqingwang-dev/yuqingwang-dev/main/assets/toolbox-dark.svg?v=research-v2">
  <img src="https://raw.githubusercontent.com/yuqingwang-dev/yuqingwang-dev/main/assets/toolbox.svg?v=research-v2" alt="03 Technical stack — 技术栈" width="100%">
</picture>

**AI & Retrieval**　`Python` `PyTorch` `Transformers` `PEFT / LoRA` `BM25` `pgvector`<br>
**Application**　`FastAPI` `TypeScript` `React` `Next.js` `Tailwind CSS`<br>
**Engineering**　`PostgreSQL` `Redis` `Docker` `Git` `pytest` `GitHub Actions`

<br>
<p align="center"><sub>Evidence. Reproducibility. Useful systems.</sub></p>

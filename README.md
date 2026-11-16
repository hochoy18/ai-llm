# ai-llm

记录 LLM 相关的知识与内容，面向应用开发视角：不追求从头训练大模型，但深入理解底层原理，以便在应用层进行调优和边界把控。

> 本知识库持续更新，以下大纲会根据实际情况扩展。

## 知识大纲

### 1. 大语言模型（LLM）基础底座

#### 1.1 Transformer 架构与注意力机制

- [ ] Encoder-Decoder 与 Decoder-Only 架构的区别
- [ ] 自注意力机制（Self-Attention）原理
- [ ] 多头注意力的演进与对比：MHA → MQA → GQA
- [ ] 位置编码技术：绝对位置编码、RoPE 旋转位置编码、ALiBi

#### 1.2 模型训练与对齐生命周期

- [ ] 预训练（Pre-training）、指令微调（SFT）、人类对齐（RLHF / DPO）的目标与差异
- [ ] 高效微调方案：LoRA、QLoRA
  - [ ] 核心数学原理（低秩分解）
  - [ ] 参数选择依据（rank、alpha、target modules 等）

#### 1.3 生成策略与超参数控制

- [ ] Temperature、Top-P、Top-K 的作用机制
- [ ] 不同业务场景下的参数取舍（确定性任务 vs 创意生成）
- [ ] 解码策略：Greedy Search、Beam Search、核采样（Nucleus Sampling）

---

## 待扩展方向（占位）

- 2. Prompt 工程与上下文管理
- 3. RAG（检索增强生成）
- 4. Agent 与工具调用（Function Calling / MCP）
- 5. 推理与部署优化（量化、KV Cache、vLLM 等）
- 6. 评估与可观测性（Evals、幻觉检测）

> 以上仅为规划占位，具体内容按实际学习与项目需要补充。

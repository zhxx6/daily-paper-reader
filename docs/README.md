<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-09-07
- 运行时间：2026-09-07 23:18:09 UTC
- 运行状态：成功
- 本次总论文数：5
- 精读区：4
- 速读区：1

### 今日简报（AI）
今日精读4篇、速读1篇，聚焦无训练MoE推理加速手段。最值得关注两项9分工作：细粒度MoE激活专家减半，以及免校准的专家跳过方法，均不依赖额外训练。后续可优先复现这类“免费”加速方案，留意其在大模型推理中的精度与吞吐折中。
- 详情：[/202609/07/README](/202609/07/README)

### 精读区论文标签
1. [Training-Free Halving of Activated Experts in Fine-Grained Mixture-of-Experts Models](/202609/07/2609.04575v1-training-free-halving-of-activated-experts-in-fine-grained-mixture-of-experts-models)  
   标签：评分：9.0/10、query:moe-gk-quant
   evidence：仅调节归一化概率质量即可减半激活专家，免训练降低MoE推理计算量
2. [ACE: Adaptive Calibration-Free Expert Skipping for MoE-based LLMs](/202609/07/2609.05228v1-ace-adaptive-calibration-free-expert-skipping-for-moe-based-llms)  
   标签：评分：9.0/10、query:moe-gk-quant
   evidence：无训练无校准的token自适应专家跳过方法可加速MoE大模型推理
3. [When Load-Balancing Goes Too Far: Expert Pruning in Over-Dispersed Mixture-of-Experts Models](/202609/07/2609.04453v1-when-load-balancing-goes-too-far-expert-pruning-in-over-dispersed-mixture-of-experts-models)  
   标签：评分：8.0/10、query:moe-gk-quant
   evidence：面向MoE服务成本降低的专家剪枝分析
4. [FlexPosit: Tunable Fractional Precision for LLM Inference Accelerators](/202609/07/2609.04724v1-flexposit-tunable-fractional-precision-for-llm-inference-accelerators)  
   标签：评分：8.0/10、query:moe-gk-quant
   evidence：面向LLM推理加速器的Posit量化，覆盖组粒度与混合精度，直接服务于大模型量化推理需求

### 速读区论文标签
1. [FlowTT: Exploiting Computation Flow Reuse in Irregular Tensor-Train Embedding](/202609/07/2609.03459v1-flowtt-exploiting-computation-flow-reuse-in-irregular-tensor-train-embedding)  
   标签：评分：6.0/10、query:moe-gk-quant
   evidence：在张量列嵌入中做GPU核融合与前缀索引分组，可迁移至分组专家计算


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>

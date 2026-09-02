<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-09-02
- 运行时间：2026-09-02 21:34:17 UTC
- 运行状态：成功
- 本次总论文数：4
- 精读区：3
- 速读区：1

### 今日简报（AI）
今日精读聚焦两篇9分高价值论文，覆盖大模型量化与MoE动态调度，另速读一篇7分量化优化。最值得关注：REAL-Q用动态梯度下降实现端到端LLM量化，DynaNDE则通过近数据专家调度提升批量MoE推理效率。若想快速进阶，建议优先精读这两篇高分开山之作，并结合OCGQuant的异常值分组思路做横向对比。
- 详情：[/202609/02/README](/202609/02/README)

### 精读区论文标签
1. [REAL-Q: E2E LLM Quantization via Dynamic Gradient Descent](/202609/02/2609.00049v1-real-q-e2e-llm-quantization-via-dynamic-gradient-descent)  
   标签：评分：9.0/10、query:moe-gk-quant
   evidence：直接研究大语言模型后训练权重量化，提出端到端损失对齐的动态梯度下降方法以提升量化部署质量
2. [DynaNDE: Dynamic Near-Data Expert Scheduling for Batched MoE Inference](/202609/02/2609.00407v1-dynande-dynamic-near-data-expert-scheduling-for-batched-moe-inference)  
   标签：评分：9.0/10、query:moe-gk-quant
   evidence：面向批处理MoE推理的动态近数据专家调度框架，直接提升NPU系统推理效率
3. [PCoMoE: Shifting MoE Inference from Monolithic Expert Selection to Fine-Grained Path Composition](/202609/02/2609.01024v1-pcomoe-shifting-moe-inference-from-monolithic-expert-selection-to-fine-grained-path-composition)  
   标签：评分：9.0/10、query:moe-gk-quant
   evidence：直接针对混合专家模型高效推理，提出以细粒度路径组合替代整体专家执行的PCoMoE框架

### 速读区论文标签
1. [OCGQuant: Outlier-Companion Grouping for NVFP4 Quantization](/202609/02/2609.00066v1-ocgquant-outlier-companion-grouping-for-nvfp4-quantization)  
   标签：评分：7.0/10、query:moe-gk-quant
   evidence：面向NVFP4低比特量化提出离群伴随分组，缓解激活离群值导致的量化误差，适用于高效推理


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>

<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-08-28
- 运行时间：2026-08-28 04:09:11 UTC
- 运行状态：成功
- 本次总论文数：6
- 精读区：5
- 速读区：1

### 今日简报（AI）
今日聚焦MoE高效推理，共读6篇，精读5篇，其中两篇高分工作尤为亮眼。  
最值得关注的是NOVA的“近存计算+SSM混合架构”协同设计，以及ExFold的无训练专家折叠加速方案，分别解决内存墙和Prefill-Decode阶段负载不均问题。  
建议普通读者优先吸收ExFold的直觉：通过结构化重组专家权重，在不训练的前提下显著提升吞吐，后续可关注其与NOVA在真实硬件上的联合验证。
- 详情：[/202608/28/README](/202608/28/README)

### 精读区论文标签
1. [NOVA: Technology-Architecture Co-Design of Near-Memory Processing for Attention-SSM-MoE Hybrid LLM Inference](/202608/28/2608.22613v1-nova-technology-architecture-co-design-of-near-memory-processing-for-attention-ssm-moe-hybrid-llm-inference)  
   标签：评分：9.0/10、query:moe-gk-quant
   evidence：面向含MoE层的混合大模型推理，通过近内存处理架构提升推理效率
2. [ExFold: Unified Expert Folding for Training-Free MoE Prefill-Decode Acceleration](/202608/28/2608.24938v1-exfold-unified-expert-folding-for-training-free-moe-prefill-decode-acceleration)  
   标签：评分：9.0/10、query:moe-gk-quant
   evidence：免训练的MoE预填充-解码统一加速
3. [Launch-Bound and Substitutable: Why Three Inference Optimizations Fail to Pay Off in Mixture-of-Experts Models](/202608/28/2608.26612v1-launch-bound-and-substitutable-why-three-inference-optimizations-fail-to-pay-off-in-mixture-of-experts-models)  
   标签：评分：9.0/10、query:moe-gk-quant
   evidence：端到端评估了融合Triton内核与INT4量化在MoE推理中的效果
4. [AirMoE: Realizing Over-the-Air Distributed Mixture-of-Experts Inference at the Wireless Edge](/202608/28/2608.22932v2-airmoe-realizing-over-the-air-distributed-mixture-of-experts-inference-at-the-wireless-edge)  
   标签：评分：8.0/10、query:moe-gk-quant
   evidence：提出AirMoE，通过无线波形叠加实现分布式MoE推理的高效专家输出聚合
5. [Activation Outliers Matter: Robust Recovery for Quantized Multimodal LLMs](/202608/28/2608.26581v1-activation-outliers-matter-robust-recovery-for-quantized-multimodal-llms)  
   标签：评分：8.0/10、query:moe-gk-quant
   evidence：针对大型多模态语言模型的低比特量化系统研究，指出激活离群值是性能损失关键来源

### 速读区论文标签
1. [Meta-Learning Where to Allocate Experts: Task-Conditioned Layer-Wise Compression for MoEs](/202608/28/2608.26650v1-meta-learning-where-to-allocate-experts-task-conditioned-layer-wise-compression-for-moes)  
   标签：评分：7.0/10、query:moe-gk-quant
   evidence：面向MoE高效推理的任务条件分层专家分配


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>

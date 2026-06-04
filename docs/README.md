<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-06-04
- 运行时间：2026-06-04 22:01:49 UTC
- 运行状态：成功
- 本次总论文数：8
- 精读区：3
- 速读区：5

### 今日简报（AI）
今日推荐8篇论文，重点聚焦大模型量化与压缩，精读3篇涉及混合专家模型(MoE)量化及低比特生成质量提升。

最值得关注的方向：混合专家模型的量化（如AlphaQ的无校准位分配）与低比特量化提升生成质量（LFQ的logit感知块量化），速读中ConMoE的MoE压缩也值得一看。

建议优先精读《AlphaQ》和《LFQ》两篇，了解无校准位分配与生成质量增强技巧，可应用于实际模型部署。
- 详情：[/202606/04/README](/202606/04/README)

### 精读区论文标签
1. [AlphaQ: Calibration-Free Bit Allocation for Mixture-of-Experts Quantization](/202606/04/2606.04980v1-alphaq-calibration-free-bit-allocation-for-mixture-of-experts-quantization)  
   标签：评分：9.0/10、query:moe-gk-quant
   evidence：MoE权重量化的无校准位分配
2. [LFQ: Logit-aware Final-block Quantization for Boosting the Generation Quality of Low-Bit Quantized LLMs](/202606/04/2605.29756v1-lfq-logit-aware-final-block-quantization-for-boosting-the-generation-quality-of-low-bit-quantized-llms)  
   标签：评分：8.0/10、query:moe-gk-quant
   evidence：面向大语言模型的低比特权重量化，结合logit感知最终块优化
3. [ViBE: Co-Optimizing Workload Skew and Hardware Variability for MoE Serving](/202606/04/2606.00735v1-vibe-co-optimizing-workload-skew-and-hardware-variability-for-moe-serving)  
   标签：评分：8.0/10、query:moe-gk-quant
   evidence：通过处理负载倾斜和硬件变异性来提升MoE推理效率

### 速读区论文标签
1. [ConMoE: Expert-Pool Consolidation via Prototype Reassignment for MoE Compression](/202606/04/2605.29350v1-conmoe-expert-pool-consolidation-via-prototype-reassignment-for-moe-compression)  
   标签：评分：7.0/10、query:moe-gk-quant
   evidence：通过合并专家池压缩MoE，减少推理内存
2. [LASER: Loss-Aware Singular-value Decomposition and Rank Allocation for Efficient Low-Precision Vision-Language Models](/202606/04/2606.00573v1-laser-loss-aware-singular-value-decomposition-and-rank-allocation-for-efficient-low-precision-vision-language-models)  
   标签：评分：7.0/10、query:moe-gk-quant
   evidence：通过损失感知的SVD和秩分配实现低精度VLM推理
3. [PrunePath: Towards Highly Structured Sparse Language Models](/202606/04/2605.28283v1-prunepath-towards-highly-structured-sparse-language-models)  
   标签：评分：6.0/10、query:moe-gk-quant
   evidence：利用MoEfication和结构化稀疏化实现高效FFN推理
4. [DAG-MoE: From Simple Mixture to Structural Aggregation in Mixture-of-Experts](/202606/04/2606.01062v1-dag-moe-from-simple-mixture-to-structural-aggregation-in-mixture-of-experts)  
   标签：评分：6.0/10、query:moe-gk-quant
   evidence：提出MoE模型的结构化聚合方法，提升推理效率
5. [PRISM: Synergizing Vision Foundation Models via Self-organized Expert Specialization](/202606/04/2606.03444v1-prism-synergizing-vision-foundation-models-via-self-organized-expert-specialization)  
   标签：评分：6.0/10、query:moe-gk-quant
   evidence：通过专家专门化的混合专家推理技术


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>

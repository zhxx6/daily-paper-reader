<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-05-06 ~ 2026-06-04
- 运行时间：2026-06-04 11:21:40 UTC
- 运行状态：成功
- 本次总论文数：16
- 精读区：0
- 速读区：16

### 今日简报（AI）
今日速读16篇MoE相关论文，其中三篇高分论文聚焦自适应路由、分层优化与低秩量化。

重点推荐《Adaptive Inverted-Index Routing》与《TileQ: Efficient Low-Rank Quantization》，分别提出细粒度路由与二维分块量化新方法，均获9.0分。

建议优先精读这三篇高分论文，关注其路由与量化技术，后续可探索MoE的部署效率与稀疏性平衡。
- 详情：[/20260506-20260604/README](/20260506-20260604/README)

### 精读区论文标签
- 本次无精读推荐。

### 速读区论文标签
1. [Adaptive Inverted-Index Routing for Granular Mixtures-of-Experts](/20260506-20260604/2605.04952v1-adaptive-inverted-index-routing-for-granular-mixtures-of-experts)  
   标签：评分：9.0/10、query:moe-gk-quant
   evidence：基于向量量化的路由减少细粒度MoE路由开销
2. [Hierarchical Mixture-of-Experts with Two-Stage Optimization](/20260506-20260604/2605.08292v1-hierarchical-mixture-of-experts-with-two-stage-optimization)  
   标签：评分：9.0/10、query:moe-gk-quant
   evidence：层次化分组MoE，包含组间均衡和组内专化
3. [TileQ: Efficient Low-Rank Quantization of Mixture-of-Experts with 2D Tiling](/20260506-20260604/2605.09281v1-tileq-efficient-low-rank-quantization-of-mixture-of-experts-with-2d-tiling)  
   标签：评分：9.0/10、query:moe-gk-quant
   evidence：基于低秩量化的MoE高效推理与融合计算
4. [BEAM: Binary Expert Activation Masking for Dynamic Routing in MoE](/20260506-20260604/2605.14438v1-beam-binary-expert-activation-masking-for-dynamic-routing-in-moe)  
   标签：评分：9.0/10、query:moe-gk-quant
   evidence：二进制掩码动态路由减少MoE推理计算量
5. [XFP: Quality-Targeted Adaptive Codebook Quantization with Sparse Outlier Separation for LLM Inference](/20260506-20260604/2605.14844v1-xfp-quality-targeted-adaptive-codebook-quantization-with-sparse-outlier-separation-for-llm-inference)  
   标签：评分：9.0/10、query:moe-gk-quant
   evidence：针对LLM和MoE层的权重量化
6. [GEMQ: Global Expert-Level Mixed-Precision Quantization for MoE LLMs](/20260506-20260604/2605.23078v1-gemq-global-expert-level-mixed-precision-quantization-for-moe-llms)  
   标签：评分：9.0/10、query:moe-gk-quant
   evidence：面向MoE大语言模型的全局专家级混合精度量化
7. [How Far Can Disaggregation Go? A Design-Space Exploration of Attention-FFN Disaggregation for Efficient MoE LLM Serving](/20260506-20260604/2605.28302v1-how-far-can-disaggregation-go-a-design-space-exploration-of-attention-ffn-disaggregation-for-efficient-moe-llm-serving)  
   标签：评分：9.0/10、query:moe-gk-quant
   evidence：探索注意力-FFN解聚以优化MoE服务效率
8. [Eigenvectors of Experts are Training-free Non-collapsing Routers](/20260506-20260604/2605.30992v1-eigenvectors-of-experts-are-training-free-non-collapsing-routers)  
   标签：评分：9.0/10、query:moe-gk-quant
   evidence：无训练非坍缩路由器提升MoE推理
9. [Federation of Experts: Communication Efficient Distributed Inference for Large Language Models](/20260506-20260604/2605.06206v1-federation-of-experts-communication-efficient-distributed-inference-for-large-language-models)  
   标签：评分：8.0/10、query:moe-gk-quant
   evidence：专家联邦通过按KV头分组MoE集群消除全对全通信
10. [Uncovering Intra-expert Activation Sparsity for Efficient Mixture-of-Expert Model Execution](/20260506-20260604/2605.08575v1-uncovering-intra-expert-activation-sparsity-for-efficient-mixture-of-expert-model-execution)  
   标签：评分：8.0/10、query:moe-gk-quant
   evidence：利用专家内部激活稀疏性加速MoE推理
11. [DECO: Sparse Mixture-of-Experts with Dense-Comparable Performance on End-Side Devices](/20260506-20260604/2605.10933v1-deco-sparse-mixture-of-experts-with-dense-comparable-performance-on-end-side-devices)  
   标签：评分：8.0/10、query:moe-gk-quant
   evidence：面向终端设备的稀疏MoE架构提升推理效率
12. [DECO: Sparse Mixture-of-Experts with Dense-Comparable Performance on End-Side Devices](/20260506-20260604/2605.10933v2-deco-sparse-mixture-of-experts-with-dense-comparable-performance-on-end-side-devices)  
   标签：评分：8.0/10、query:moe-gk-quant
   evidence：面向端侧的高效MoE推理架构
13. [ADMM-Q: An Improved Hessian-based Weight Quantizer for Post-Training Quantization of Large Language Models](/20260506-20260604/2605.11222v1-admm-q-an-improved-hessian-based-weight-quantizer-for-post-training-quantization-of-large-language-models)  
   标签：评分：8.0/10、query:moe-gk-quant
   evidence：基于ADMM的大语言模型权重量化算法
14. [Fast MoE Inference via Predictive Prefetching and Expert Replication](/20260506-20260604/2605.11537v1-fast-moe-inference-via-predictive-prefetching-and-expert-replication)  
   标签：评分：8.0/10、query:moe-gk-quant
   evidence：通过专家复制加速MoE推理
15. [HodgeCover: Higher-Order Topological Coverage Drives Compression of Sparse Mixture-of-Experts](/20260506-20260604/2605.13997v1-hodgecover-higher-order-topological-coverage-drives-compression-of-sparse-mixture-of-experts)  
   标签：评分：8.0/10、query:moe-gk-quant
   evidence：压缩降低MoE推理成本
16. [Beyond Task-Agnostic: Task-Aware Grouping for Communication-Efficient Multi-Task MoE Inference](/20260506-20260604/2606.01007v1-beyond-task-agnostic-task-aware-grouping-for-communication-efficient-multi-task-moe-inference)  
   标签：评分：8.0/10、query:moe-gk-quant
   evidence：面向通信高效MoE推理的任务感知专家分组


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>

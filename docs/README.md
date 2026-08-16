<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-08-16
- 运行时间：2026-08-16 19:39:01 UTC
- 运行状态：成功
- 本次总论文数：3
- 精读区：1
- 速读区：2

### 今日简报（AI）
今日精读1篇、速读2篇，重点聚焦大模型推理与稀疏专家系统的效率优化。最值得关注的是《SwiftQK》（8.0分），它针对Query-Key归一化提出通信高效张量并行方案，显著降低长序列场景下的并行开销；速读中关于专家路由去耦的思路也值得一瞥。普通读者下一步可优先了解张量并行在长上下文推理中的实际收益，避开Top-k过滤这类偏工程细节的方向。
- 详情：[/202608/16/README](/202608/16/README)

### 精读区论文标签
1. [SwiftQK: Fast and Communication-Efficient Tensor Parallelism for Query-Key Normalization](/202608/16/2608.09160v1-swiftqk-fast-and-communication-efficient-tensor-parallelism-for-query-key-normalization)  
   标签：评分：8.0/10、query:moe-gk-quant
   evidence：面向QK-Norm的多GPU RMSNorm内核优化，降低Transformer推理通信开销

### 速读区论文标签
1. [Beyond Routing: Decoupling Expert Dispatch and Aggregation in Sparse Mixture-of-Experts](/202608/16/2608.08853v1-beyond-routing-decoupling-expert-dispatch-and-aggregation-in-sparse-mixture-of-experts)  
   标签：评分：7.0/10、query:moe-gk-quant
   evidence：在稀疏MoE推理中解耦专家调度与聚合
2. [Prof-K: Probabilistic One-Pass Filtering for Efficient Top-k Selection](/202608/16/2608.12573v1-prof-k-probabilistic-one-pass-filtering-for-efficient-top-k-selection)  
   标签：评分：6.0/10、query:moe-gk-quant
   evidence：为稀疏激活提供高效top-k选择，可加速MoE路由


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>

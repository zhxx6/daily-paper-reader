<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-08-12
- 运行时间：2026-08-12 21:30:12 UTC
- 运行状态：成功
- 本次总论文数：5
- 精读区：1
- 速读区：4

### 今日简报（AI）
今日聚焦混合专家模型（MoE）优化，精读1篇、速读4篇，核心围绕专家压缩与高效路由。最值得关注的是《Shape Mutating Expert Compression》获8.0高分，提出LorExperts与BTExperts两种专家压缩方案；另可留意《Compute-Optimal Is Not Cluster-Optimal》揭示算力最优不等于集群最优的系统级缩放视角。建议普通读者优先精读高分解压方案，并追踪系统感知的MoE扩展思路，后续可深入对比路由剪枝与共享专家框架的适用场景。
- 详情：[/202608/12/README](/202608/12/README)

### 精读区论文标签
1. [Shape Mutating Expert Compression:LorExperts and BTExperts](/202608/12/2608.07814v1-shape-mutating-expert-compressionlorexperts-and-btexperts)  
   标签：评分：8.0/10、query:moe-gk-quant
   evidence：通过低秩增量分解压缩MoE专家以降低部署成本

### 速读区论文标签
1. [Compute-Optimal Is Not Cluster-Optimal: Systems-Aware Scaling for Sparse Mixture-of-Experts](/202608/12/2608.10605v1-compute-optimal-is-not-cluster-optimal-systems-aware-scaling-for-sparse-mixture-of-experts)  
   标签：评分：7.0/10、query:moe-gk-quant
   evidence：面向稀疏MoE的系统感知扩展，建立计算、通信与内存性能模型
2. [Router Sensitivity Under Lightweight Fine-Tuning Identifies Prunable Experts in Mixture-of-Experts Models](/202608/12/2608.07890v1-router-sensitivity-under-lightweight-fine-tuning-identifies-prunable-experts-in-mixture-of-experts-models)  
   标签：评分：6.0/10、query:moe-gk-quant
   evidence：通过路由敏感性剪枝MoE专家，减少存储和推理开销
3. [Share First, Route What Remains: A Unified Framework for Token-Adaptive MoE Computation](/202608/12/2608.10392v1-share-first-route-what-remains-a-unified-framework-for-token-adaptive-moe-computation)  
   标签：评分：6.0/10、query:moe-gk-quant
   evidence：提出统一框架，先提取共享可复用计算再路由剩余部分，降低MoE每token计算量
4. [SQuaT: Self-Supervised Knowledge Distillation via Student-Aware Quantized Teacher Features](/202608/12/2608.10709v1-squat-self-supervised-knowledge-distillation-via-student-aware-quantized-teacher-features)  
   标签：评分：6.0/10、query:moe-gk-quant
   evidence：面向无标签量化感知训练的学生感知量化教师特征方法


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>

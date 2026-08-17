<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-08-17
- 运行时间：2026-08-17 20:48:50 UTC
- 运行状态：成功
- 本次总论文数：5
- 精读区：4
- 速读区：1

### 今日简报（AI）
今日共读5篇论文，精读4篇、速读1篇，聚焦量化训练、MoE负载均衡与KV缓存压缩。  
最值得看的是两篇9.0分工作：QUASAR用损失感知重建降低量化训练损失下限，FreeBalance用残差工作负载预测实现预路由MoE均衡。  
建议优先深入这两篇方法，并留意KV缓存压缩与它们结合优化的潜力。
- 详情：[/202608/17/README](/202608/17/README)

### 精读区论文标签
1. [QUASAR: Lowering the Loss Floor of Quantization-Aware Training with Loss-Aware Reconstruction](/202608/17/2608.13966v1-quasar-lowering-the-loss-floor-of-quantization-aware-training-with-loss-aware-reconstruction)  
   标签：评分：9.0/10、query:moe-gk-quant
   evidence：直接面向大语言模型权重量化，提出损失感知重构的量化感知训练方法
2. [FreeBalance: Pre-Routing Online Moe Load Balancing via Residual Workload Prediction](/202608/17/2608.14205v1-freebalance-pre-routing-online-moe-load-balancing-via-residual-workload-prediction)  
   标签：评分：9.0/10、query:moe-gk-quant
   evidence：直接通过在线负载均衡优化分布式MoE推理延迟
3. [Beyond Capacity: Scalable MoE LLM Inference via High-Bandwidth Flash with Direct GPU and HBM Paths](/202608/17/2608.14333v1-beyond-capacity-scalable-moe-llm-inference-via-high-bandwidth-flash-with-direct-gpu-and-hbm-paths)  
   标签：评分：9.0/10、query:moe-gk-quant
   evidence：针对MoE大模型推理的显存架构优化，提升推理效率
4. [DeaMoE: Efficient MoE Structure for Fast Small-Batch Decoding](/202608/17/2608.14385v1-deamoe-efficient-moe-structure-for-fast-small-batch-decoding)  
   标签：评分：9.0/10、query:moe-gk-quant
   evidence：直接面向MoE小批量解码效率，通过对专家分组解决权重加载瓶颈

### 速读区论文标签
1. [KV Cache Compression Through the Lens of Transform Coding](/202608/17/2608.14191v1-kv-cache-compression-through-the-lens-of-transform-coding)  
   标签：评分：6.0/10、query:moe-gk-quant
   evidence：面向LLM推理的KV缓存量化压缩方法，与权重量化技术紧密相关


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>

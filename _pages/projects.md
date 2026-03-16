# Selected Projects 🏭
*2026* **Large-Scale LLM Pre-Training, Mid-Training, and Multimodal Training with RWKV**
- Served as a core technical leader in the development of next-generation large language model architectures in the RWKV series, including linear-attention models (RWKV-4/5/6/7), hybrid-attention models (RWKV-X), and vision-language models (VisualRWKV).
- Made major contributions across the full training pipeline, including large-scale pre-training, mid-training, and multimodal training, with primary ownership of the multimodal training direction.
- Led or co-led key efforts in scaling models beyond 10B parameters and training on approximately 8T tokens, covering architecture innovation, training methodology, and large-scale system optimization.
- Advanced a novel architecture that unifies Transformer-style parallelizable training with RNN-style efficient inference, making RWKV a strong candidate for future foundation model and AGI-oriented architectures.

*2026* **LLM Post-Training Optimization with PSPO** (Accepted by AAAI-26)
- Led/participated in the design of an efficient reinforcement fine-tuning method for large language models, addressing training instability and poor data utilization in GRPO-based post-training.
- Introduced EMA-based reward smoothing and priority-based prompt sampling, improving the stability of policy updates and increasing the reuse value of high-impact prompts without storing full trajectories.
- Boosted training effectiveness over GRPO baselines with up to 5%+ absolute improvement in some settings, while also improving convergence speed.
- Open-sourced the project and validated it on **Qwen2.5-Math-1.5B/7B** and other model variants across multiple mathematical reasoning benchmarks, including **AIME24, MATH500, AMC23, Minerva Math, and OlympiadBench**.

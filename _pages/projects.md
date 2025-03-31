# Projects 🏭
*2022* E-Commerce Visual Language Pre-training
- Developed a large-scale (100M pairs) e-commerce visual-language pre-training model for enhanced product understanding.
- Proposed **BagFormer**, a dual encoder for cross-modal retrieval using bag-wise interaction and entity-aware text granularity. Achieved top recall with low latency.
- Ranked **1st in MUGE Challenge** with BagFormer.

*2021* WeChat Video Product Identification
- Led design & development of scalable video product ID pipeline: data processing, model training, inference acceleration, and deployment (TensorRT, Kubernetes, Pulsar).
- Led the development of major modules:  multimodal video classification(ResNet-50, BERT, and NextVlad), product detection(YOLO-v5), product retrieval(Siamese Network), and product tagging(ALBEF+XGBoost). 
- Boosted overall GSB by **12.37%**, Top-3 GSB by **26%**, contributing to WeChat Video reaching **500M DAU**.  
- Won 2nd place in the AAAI 2021 Watch and Buy Challenge.

*2020* WeChat Pay Merchant Understanding
- Tagged **7.7M merchants** with **370M high-quality tags** using distant supervision and active learning.
- Modeled merchant-tag relations as a **reading comprehension** task using BERT + fine-grained entity types.
- Achieved **96.6% top-1 accuracy** on head merchants and **89.0%** overall.
- Improved pickup rate by **6.58%** and usage rate by **0.28%** (via A/B testing).

*2019* WeChat Search Query Improvement
- Built relevant query recommendation system to improve search satisfaction.
- Constructed co-click query graphs (Hadoop), filtered with FastText, trained DSSM with hard negatives, and deployed **FAISS PQ Index** for real-time similarity search (latency < 100ms).
- Led to **4.5% daily query view increase**, raising search ad revenue by **3%**.
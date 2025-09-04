# VLM-review

🔥🔥🔥 A paper list for **Advancing Vision-Language Models: Critical Insights from Methodological Innovations and Data Curation**

## Table of Contents

- [Method](#method)
  - [Pre-Training](#pre-training)
    - [Vision Encoder Enhancement](#vision-encoder-enhancement)
    - [End-to-End VLM Pretraining](#end-to-end-vlm-pretraining)
  - [Post-Training](#post-training)
    - [Resolution Adaptation & Visual Instruction Tuning](#resolution-adaptation--visual-instruction-tuning)
    - [Architectural Innovations for Vision-Language Models](#architectural-innovations-for-vision-language-models)
    - [Reinforcement Learning for Multimodal Reasoning](#reinforcement-learning-for-multimodal-reasoning)
  - [Enhancement Strategies for VLMs](#enhancement-strategies-for-vlms)
    - [Chain-of-Thought Reasoning Enhancement](#chain-of-thought-reasoning-enhancement)
    - [Agent-based and Expert Integration](#agent-based-and-expert-integration)
    - [Retrieval-Augmented Generation (RAG) for VLMs](#retrieval-augmented-generation-rag-for-vlms)
- [Data](#data)
  - [Pre-Training Data](#pre-training-data)
  - [Fine-Tuning Data](#fine-tuning-data)
  - [Benchmarks](#benchmarks)

## Method

### Pre-Training

#### Vision Encoder Enhancement

- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2103.000205-red?logo=arxiv" height="14" /> [Learning Transferable Visual Models From Natural Language Supervision](https://arxiv.org/abs/2103.00020). [CLIP]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2303.15343 -red?logo=arxiv" height="14" /> [Sigmoid Loss for Language Image Pre-Training](http://arxiv.org/abs/2303.15343). [SigLip]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2502.14786 -red?logo=arxiv" height="14" /> [SigLIP 2: Multilingual Vision-Language Encoders with Improved Semantic Understanding, Localization, and Dense Features](https://arxiv.org/abs/2502.14786). [SigLip2]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2312.14238 -red?logo=arxiv" height="14" /> [InternVL: Scaling up Vision Foundation Models and Aligning for Generic Visual-Linguistic Tasks](https://arxiv.org/abs/2312.14238). [InternVL]
- <img alt="icml" src="https://img.shields.io/badge/ICML-2024-yellow?logo=icml" height="14" />[Scalable Pre-training of Large Autoregressive Image Models](https://arxiv.org/abs/2401.08541).[AIM]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2411.14402 -red?logo=arxiv" height="14" /> [Multimodal Autoregressive Pre-training of Large Vision Encoders](https://arxiv.org/abs/2411.14402).[AIMv2]
- <img alt="icml" src="https://img.shields.io/badge/ICML-2023-yellow?logo=icml" height="14" /> [Scaling Vision Transformers to 22 Billion Parameters](https://arxiv.org/abs/2302.05442). 
- <img alt="icml" src="https://img.shields.io/badge/ICML-2021-yellow?logo=icml" height="14" />[Scaling Up Visual and Vision-Language Representation Learning With Noisy Text Supervision](https://arxiv.org/abs/2102.05918).[ALIGN]
- <img alt="iclr" src="https://img.shields.io/badge/ICLR-2024-purple?logo=iclr" height="14" />[Vision Transformers Need Registers](https://arxiv.org/abs/2309.16588).
- <img alt="NeurIPS" src="https://img.shields.io/badge/NeurIPS-2023-0596D3?logo=neurips" height="14" />[Patch n' Pack: NaViT, a Vision Transformer for any Aspect Ratio and Resolution](https://openreview.net/forum?id=VpGFHmI7e5).[NaViT]
- <img alt="icml" src="https://img.shields.io/badge/ICML-2023-yellow?logo=icml" height="14" />[Token Merging: Your ViT But Faster](https://arxiv.org/abs/2210.09461).[ToMe]
- <img alt="cvpr" src="https://img.shields.io/badge/CVPR-2023-blue?logo=cvpr" height="14" />[DINOv2: Learning Robust Visual Features without Supervision](https://arxiv.org/abs/2304.07193).[DINOv2]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2303.15389 -red?logo=arxiv" height="14" />[EVA-CLIP: Improved Training Techniques for CLIP at Scale](https://arxiv.org/abs/2303.15389).[EVA-CLIP]
- <img alt="cvpr" src="https://img.shields.io/badge/CVPR-2025-blue?logo=cvpr" height="14" />[TokenFlow: Unified Image Tokenizer for Multimodal Understanding and Generation](https://arxiv.org/abs/2412.03069)[TokenFlow]
- <img alt="NeurIPS" src="https://img.shields.io/badge/NeurIPS-2024-0596D3?logo=neurips" height="14" />[LocCa: Visual Pretraining with Location-aware Captioners](https://arxiv.org/abs/2403.19596)[LocCa]
- <img alt="NeurIPS" src="https://img.shields.io/badge/NeurIPS-2023-0596D3?logo=neurips" height="14" />[Image Captioners Are Scalable Vision Learners Too](https://arxiv.org/abs/2306.07915)

#### End-to-End VLM Pretraining

- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2312.07533 -red?logo=arxiv" height="14" /> [VILA: On Pre-training for Visual Language Models](https://arxiv.org/abs/2312.07533). [VILA]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2309.04669 -red?logo=arxiv" height="14" /> [Unified Language-Vision Pretraining in LLM with Dynamic Discrete Visual Tokenization](https://arxiv.org/abs/2309.04669). [LaVIT]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2410.14332 -red?logo=arxiv" height="14" /> [Croc: Pretraining Large Multimodal Models with Cross-Modal Comprehension](https://arxiv.org/abs/2410.14332). [Croc]
- <img alt="iclr" src="https://img.shields.io/badge/ICLR-2024-purple?logo=iclr" height="14" />[Emu: Generative Pretraining in Multimodality](https://openreview.net/forum?id=mL8Q9OOamV)[Emu]

### Post-Training

#### Resolution Adaptation & Visual Instruction Tuning

- <img alt="NeurIPS" src="https://img.shields.io/badge/NeurIPS-2023-0596D3?logo=neurips" height="14" /> [Visual Instruction Tuning](https://arxiv.org/abs/2304.08485). [LLaVA]
- <img alt="cvpr" src="https://img.shields.io/badge/CVPR-2024-blue?logo=cvpr" height="14" />[Improved Baselines with Visual Instruction Tuning](https://arxiv.org/abs/2310.03744). [LLaVA-1.5, LLaVA-NeXT]
- <img alt="cvpr" src="https://img.shields.io/badge/CVPR-2024-blue?logo=cvpr" height="14" />[Monkey: Image Resolution and Text Label Are Important Things for Large Multi-modal Models](https://openaccess.thecvf.com/content/CVPR2024/papers/Li_Monkey_Image_Resolution_and_Text_Label_Are_Important_Things_for_CVPR_2024_paper.pdf). [Monkey]
- <img alt="iclr" src="https://img.shields.io/badge/ICLR-2025-purple?logo=iclr" height="14" />[Oryx MLLM: On-Demand Spatial-Temporal Understanding at Arbitrary Resolution](https://arxiv.org/abs/2409.12961).[Oryx]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2409.12191 -red?logo=arxiv" height="14" /> [Qwen2-VL: Enhancing Vision-Language Model's Perception of the World at Any Resolution](https://arxiv.org/abs/2409.12191). [Qwen2-VL]
- <img alt="icml" src="https://img.shields.io/badge/ICML-2022-yellow?logo=icml" height="14" />[BLIP: Bootstrapping Language-Image Pre-training for Unified Vision-Language Understanding and Generation](https://arxiv.org/pdf/2201.12086).[BLIP]
- <img alt="icml" src="https://img.shields.io/badge/ICML-2023-yellow?logo=icml" height="14" />[BLIP-2: Bootstrapping Language-Image Pre-training with Frozen Image Encoders and Large Language Models](https://dl.acm.org/doi/10.5555/3618408.3619222).[BLIP-2]
- <img alt="NeurIPS" src="https://img.shields.io/badge/NeurIPS-2023-0596D3?logo=neurips" height="14" />[InstructBLIP: Towards General-purpose Vision-Language Models with Instruction Tuning](https://arxiv.org/pdf/2305.06500).[InstructBLIP]
- <img alt="ecva" src="https://img.shields.io/badge/ECVA-2024-teal?logo=ecva" height="14" /> [SQ‑LLaVA: Self-Questioning for Large Vision-Language Assistant](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/01393.pdf). [SQ-LLaVA]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2307.04087 -red?logo=arxiv" height="14" /> [SVIT: Scaling up Visual Instruction Tuning](https://arxiv.org/abs/2307.04087). [SVIT]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2306.17107 -red?logo=arxiv" height="14" /> [LLaVAR: Enhanced Visual Instruction Tuning for Text-Rich Image Understanding](https://arxiv.org/abs/2306.17107). [LLaVAR]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2410.11665 -red?logo=arxiv" height="14" /> [VisualRWKV-HD and UHD: Advancing High‑Resolution Processing for Visual Language Models ](https://arxiv.org/abs/2410.11665). [VisualRWKV-HD]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2505.06840 -red?logo=arxiv" height="14" /> [Visual Instruction Tuning with Chain of Region-of-Interest ](https://arxiv.org/abs/2505.06840). [CoRoI]
- <img alt="cvpr" src="https://img.shields.io/badge/CVPR-2025-blue?logo=cvpr" height="14" /> [FastVLM: Efficient Vision Encoding for Vision Language Models ](https://openaccess.thecvf.com/content/CVPR2025/papers/Vasu_FastVLM_Efficient_Vision_Encoding_for_Vision_Language_Models_CVPR_2025_paper.pdf). [FastVLM]
- <img alt="iclr" src="https://img.shields.io/badge/ICLR-2025-purple?logo=iclr" height="14" />[Feast Your Eyes: Mixture‑of‑Resolution Adapter for Multimodal Large Language Models](https://arxiv.org/abs/2403.03003).[LLaVA-HR]
- <img alt="ecva" src="https://img.shields.io/badge/ECVA-2024-teal?logo=ecva" height="14" />[LLaVA‑UHD: an LMM Perceiving Any Aspect Ratio and High‑Resolution Images](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/11080.pdf).[LLaVA-UHD]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2403.01487 -red?logo=arxiv" height="14" /> [InfiMM‑HD: A Leap Forward in High‑Resolution Multimodal Understanding ](https://arxiv.org/abs/2403.01487). [InfiMM‑HD]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2505.21375 -red?logo=arxiv" height="14" /> [GeoLLaVA-8K: Scaling Remote-Sensing Multimodal Large Language Models to 8K Resolution](https://arxiv.org/abs/2505.21375). [GeoLLaVA-8K]

#### Architectural Innovations for Vision-Language Models

- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2401.15947 -red?logo=arxiv" height="14" /> [MoE-LLaVA: Mixture of Experts for Large Vision-Language Models](https://arxiv.org/abs/2401.15947). [MoE-LLaVA]

#### Reinforcement Learning for Multimodal Reasoning

- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2503.12937 -red?logo=arxiv" height="14" /> [R1-VL: Learning to Reason with Multimodal Large Language Models via Step-wise Group Relative Policy Optimization](https://arxiv.org/abs/2503.12937). [R1-VL]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2312.00849 -red?logo=arxiv" height="14" /> [RLHF-V: Towards Trustworthy MLLMs via Behavior Alignment from Fine-grained Correctional Human Feedback](https://arxiv.org/abs/2312.00849). [RLHF-V]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2411.17265 -red?logo=arxiv" height="14" /> [A Topic-level Self-Correctional Approach to Mitigate Hallucinations in MLLMs](https://arxiv.org/abs/2411.17265v2).
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2410.15926 -red?logo=arxiv" height="14" /> [Mitigating Object Hallucination via Concentric Causal Attention](https://arxiv.org/abs/2410.15926).
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2504.16656 -red?logo=arxiv" height="14" /> [Skywork R1V2: Multimodal Hybrid Reinforcement Learning for Reasoning](https://arxiv.org/abs/2504.16656). [Skywork R1V2]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2502.19634 -red?logo=arxiv" height="14" /> [MedVLM-R1: Incentivizing Medical Reasoning Capability of Vision-Language Models (VLMs) via Reinforcement Learning](https://arxiv.org/abs/2502.19634). [MedVLM-R1]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2503.01785 -red?logo=arxiv" height="14" /> [Visual-RFT: Visual Reinforcement Fine-Tuning](https://arxiv.org/abs/2503.01785). [Visual-RFT]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2505.04623 -red?logo=arxiv" height="14" /> [EchoInk-R1: Exploring Audio-Visual Reasoning in Multimodal LLMs via Reinforcement Learning](https://arxiv.org/abs/2505.04623). [EchoInk-R1]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2506.01713 -red?logo=arxiv" height="14" /> [SRPO: Enhancing Multimodal LLM Reasoning via Reflection-Aware Reinforcement Learning](https://arxiv.org/abs/2506.01713). [SRPO]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2503.16081 -red?logo=arxiv" height="14" /> [OThink-MR1 Stimulating multimodal generalized reasoning capabilities via dynamic reinforcement](https://arxiv.org/abs/2503.16081). [OThink-MR1]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2503.05379 -red?logo=arxiv" height="14" /> [R1-Omni: Explainable Omni-Multimodal Emotion Recognition with Reinforcement Learning](https://arxiv.org/abs/2503.05379). [R1-Omni]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2507.01006 -red?logo=arxiv" height="14" /> [GLM-4.1V-Thinking: Towards Versatile Multimodal Reasoning with Scalable Reinforcement Learning](https://arxiv.org/abs/2507.01006). [GLM-4.1V-Thinking]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2505.18531 -red?logo=arxiv" height="14" /> [Generative RLHF-V: Learning Principles from Multi-modal Human Preference](https://arxiv.org/abs/2505.18531). [Generative RLHF-V]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2503.17682 -red?logo=arxiv" height="14" /> [Safe RLHF-V: Safe Reinforcement Learning from Multi-modal Human Feedback](https://arxiv.org/abs/2503.17682). [Safe RLHF-V]
- <img alt="acl" src="https://img.shields.io/badge/ACL24--finding-red?logo=acm" height="14" /> [ALIGNING LARGE MULTIMODAL MODELS WITH FACTUALLY AUGMENTED RLHF](https://aclanthology.org/2024.findings-acl.775.pdf). [LLaVA-RLHF]



### Enhancement Strategies for VLMs

#### Chain-of-Thought Reasoning Enhancement

- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2410.16198 -red?logo=arxiv" height="14" />[Improve Vision Language Model Chain-of-thought Reasoning](https://arxiv.org/abs/2410.16198).
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2411.10440 -red?logo=arxiv" height="14" />[LLaVA-CoT: Let Vision Language Models Reason Step-by-Step](https://arxiv.org/abs/2411.10440).[LLaVA-CoT]
- <img alt="NeurIPS" src="https://img.shields.io/badge/NeurIPS-2024-0596D3?logo=neurips" height="14" />[Visual CoT: Advancing Multi-Modal Language Models with a Comprehensive Dataset and Benchmark for Chain-of-Thought Reasoning](https://openreview.net/forum?id=aXeiCbMFFJ#discussion).[VisCoT]
- <img alt="tmlr" src="https://img.shields.io/badge/TMLR-2024-orange?logo=tmlr" height="14" />[Multimodal Chain-of-Thought Reasoning in Language Models](https://arxiv.org/abs/2302.00923).[Multimodal-CoT]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2305.02317 -red?logo=arxiv" height="14" />[VISUAL CHAIN-OF-THOUGHT: BRIDGING LOGICAL GAPS WITH MULTIMODAL INFILLINGS](https://arxiv.org/abs/2305.02317).[VCoT]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2501.07542 -red?logo=arxiv" height="14" />[Imagine while Reasoning in Space: Multimodal Visualization-of-Thought](https://arxiv.org/abs/2501.07542).[MVoT]
- <img alt="iclr" src="https://img.shields.io/badge/ICLR-2024-purple?logo=iclr" height="14" />[Chain-of-Table: Evolving Tables in the Reasoning Chain for Table Understanding](https://openreview.net/forum?id=4L0xnS4GQM).
- <img alt="iclr" src="https://img.shields.io/badge/ICLR-2024-purple?logo=iclr" height="14" />[COT3DREF: CHAIN-OF-THOUGHTS DATA-EFFICIENT 3D VISUAL GROUNDING](https://openreview.net/forum?id=ORUiqcLpV6).[COT3DREF]
- <img alt="acm mm" src="https://img.shields.io/badge/ACM%20MM-2024-blue?logo=acm" height="14" />[A Picture Is Worth a Graph: A Blueprint Debate Paradigm for Multimodal Reasoning](https://arxiv.org/abs/2403.14972).[BDoG]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2301.05226 -red?logo=arxiv" height="14" />[See, Think, Confirm: Interactive Prompting Between Vision and Language Models for Knowledge-based Visual Reasoning](https://arxiv.org/abs/2301.05226).[IPVR]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2311.09241 -red?logo=arxiv" height="14" />[CHAIN OF IMAGES FOR INTUITIVELY REASONING](https://arxiv.org/abs/2311.09241).
- <img alt="cvpr" src="https://img.shields.io/badge/CVPR-2024-blue?logo=cvpr" height="14" />[Compositional Chain-of-Thought Prompting for Large Multimodal Models](https://openaccess.thecvf.com/content/CVPR2024/papers/Mitra_Compositional_Chain-of-Thought_Prompting_for_Large_Multimodal_Models_CVPR_2024_paper.pdf). [CCoT]
- <img alt="acml" src="https://img.shields.io/badge/ACML-2024-green?logo=acm" height="14" />[DCoT: Dual Chain-of-Thought Prompting for Large Multimodal Models](https://openreview.net/pdf?id=0saecDOdh2). [DCoT]
- <img alt="iccv" src="https://img.shields.io/badge/ICCV-2023-orange?logo=cc" height="14" />[CoTDet: Affordance Knowledge Prompting for Task Driven Object Detection](https://arxiv.org/abs/2309.01093). [CoTDet]
- <img alt="icml" src="https://img.shields.io/badge/ICML-2025-yellow?logo=icml" height="14" />[REFOCUS: Visual Editing as a Chain of Thought for Structured Image Understanding](https://icml.cc/virtual/2025/poster/44816). [REFOCUS]
- <img alt="iclr" src="https://img.shields.io/badge/ICLR-2024-purple?logo=iclr" height="14" />[VISUAL-O1: UNDERSTANDING AMBIGUOUS IN-STRUCTIONS VIA MULTI-MODAL MULTI-TURN CHAIN-OF-THOUGHTS REASONING](https://openreview.net/forum?id=v9CDpLpjiE). [VISUAL-O1]
- <img alt="corl" src="https://img.shields.io/badge/CoRL-2024-red?logo=robotframework" height="14" />[Robotic Control via Embodied Chain-of-Thought Reasoning](https://openreview.net/forum?id=S70MgnIA0v).
- <img alt="emnlp" src="https://img.shields.io/badge/EMNLP-2024-brown?logo=nlp" height="14" />[MedCoT: Medical Chain of Thought via Hierarchical Expert](https://arxiv.org/abs/2412.13736). [MedCoT]
- <img alt="acm mm" src="https://img.shields.io/badge/ACM%20MM-2024-blue?logo=acm" height="14" />[PanoSent: A Panoptic Sextuple Extraction Benchmark for Multimodal Conversational Aspect-based Sentiment Analysis](https://arxiv.org/abs/2408.09481). [PanSent]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2503.06232 -red?logo=arxiv" height="14" />[Integrating Chain-of-Thought for Multimodal Alignment: A Study on 3D Vision-Language Learning](https://arxiv.org/abs/2503.06232).
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2411.12591 -red?logo=arxiv" height="14" />[Thinking Before Looking:Improving Multimodal LLM Reasoning via Mitigating Visual Hallucination](https://arxiv.org/abs/2411.12591).
- <img alt="cvpr" src="https://img.shields.io/badge/CVPR-2025-blue?logo=cvpr" height="14" />[Insight-V: Exploring Long-Chain Visual Reasoning with Multimodal Large Language Models](https://arxiv.org/abs/2411.14432). [Insight-V]
- <img alt="cvpr" src="https://img.shields.io/badge/CVPR-2024-blue?logo=cvpr" height="14" />[Perception Tokens Enhance Visual Reasoning in Multimodal Language Models](https://arxiv.org/abs/2412.03548).
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2501.01904 -red?logo=arxiv" height="14" />[Virgo: A Preliminary Exploration on Reproducing o1-like MLLM](https://arxiv.org/abs/2501.01904). [Virgo]

#### Agent-based and Expert Integration

- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2502.09051 -red?logo=arxiv" height="14" />[AIDE: Agentically Improve Visual Language Model with Domain Experts](https://arxiv.org/abs/2502.09051).[AIDE]
- <img alt="NeurIPS" src="https://img.shields.io/badge/NeurIPS-2024-0596D3?logo=neurips" height="14" />[MoVA: Adapting Mixture of Vision Experts to Multimodal Context](https://openreview.net/forum?id=uHs6RJFDsg&referrer=%5Bthe%20profile%20of%20Dazhong%20Shen%5D(%2Fprofile%3Fid%3D~Dazhong_Shen1)).[MoVA]
- <img alt="iclr" src="https://img.shields.io/badge/ICLR-2025-purple?logo=iclr" height="14" />[Eagle: Exploring the design space for multimodal llms with mixture of encoders](https://openreview.net/forum?id=Y2RW9EVwhT).[Eagle]
- <img alt="cvpr" src="https://img.shields.io/badge/CVPR-2024-blue?logo=cvpr" height="14" />[Omni-SMoLA: Boosting Generalist Multimodal Models with Soft Mixture of Low-rank Experts](https://openaccess.thecvf.com/content/CVPR2024/papers/Wu_Omni-SMoLA_Boosting_Generalist_Multimodal_Models_with_Soft_Mixture_of_Low-rank_CVPR_2024_paper.pdf).[Omni-SMoLA]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2502.15381 -red?logo=arxiv" height="14" />[MOVE: A Mixture of Vision Encoders Approach for Domain Focused Vision Language Processing](https://arxiv.org/abs/2502.15381).[MOVE]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2503.23508 -red?logo=arxiv" height="14" />[Re-Aligning Language to Visual Objects with an Agentic Workflow](https://arxiv.org/abs/2503.23508).[Real-LOD]
- <img alt="iclr" src="https://img.shields.io/badge/ICLR-2025-purple?logo=iclr" height="14" />[ToVE: Efficient Vision Language Learning via Knowledge Transfer from Vision Experts](https://openreview.net/forum?id=EMMnAd3apQ).[ToVE]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2505.23830 -red?logo=arxiv" height="14" />[EvoMoE: Expert Evolution in Mixture of Experts for Multimodal Large Language Models](https://arxiv.org/abs/2505.23830).[EvoMoE]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2501.06986 -red?logo=arxiv" height="14" />[LEO: Boosting Mixture of Vision Encoders for Multimodal Large Language Models](https://arxiv.org/abs/2501.06986).[LEO]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2410.16400 -red?logo=arxiv" height="14" />[VipAct: Visual Perception Enhancement via Specialized VLM Agent Collaboration and Tool use](https://arxiv.org/abs/2410.16400).[VipAct]
- <img alt="cvpr" src="https://img.shields.io/badge/CVPR-2024-blue?logo=cvpr" height="14" />[CogAgent: A Visual Language Model for GUI Agents](https://arxiv.org/abs/2312.08914). [CogAgent]
- <img alt="iclr" src="https://img.shields.io/badge/ICLR-2025-purple?logo=iclr" height="14" />[VLM-Q Learning: Aligning Vision-Language Models for Interactive Decision-Making](https://arxiv.org/abs/2505.03181).
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2408.05478 -red?logo=arxiv" height="14" />[Multi-Agent Planning Using Visual Language Models](https://arxiv.org/abs/2408.05478).
- <img alt="icma" src="https://img.shields.io/badge/ICMA-2024-teal?logo=conference" height="14" />[InsightSee: Advancing Multi-agent Vision-Language Models for Enhanced Visual Understanding](https://arxiv.org/abs/2405.20795). [InsightSee]
- <img alt="iclr" src="https://img.shields.io/badge/ICLR-2024-purple?logo=iclr" height="14" />[Agentverse: Facilitating Multi - agent Collaboration and Exploring Emergent Behaviors](https://arxiv.org/abs/2308.10848). [Agentverse]
- <img alt="iclr" src="https://img.shields.io/badge/ICLR-2024-purple?logo=iclr" height="14" />[Routing Experts: Learning to Route Dynamic Experts in Multi-modal Large Language Models](https://arxiv.org/abs/2407.14093).
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2403.10568 -red?logo=arxiv" height="14" />[MoPE: Mixture of Prompt Experts for Parameter Efficient and Scalable Multimodal Fusion](https://arxiv.org/abs/2403.10568).
- <img alt="icml" src="https://img.shields.io/badge/ICML-2025-yellow?logo=icml" height="14" />[R2-T2: Re-Routing in Test-Time for Multimodal Mixture-of-Experts](https://arxiv.org/abs/2502.20395). [R2-T2]
- <img alt="cvpr" src="https://img.shields.io/badge/CVPR-2025-blue?logo=cvpr" height="14" />[Critic-V: VLM Critics Help Catch VLM Errors in Multimodal Reasoning](https://arxiv.org/abs/2411.18203). [Critic-V]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2505.23399 -red?logo=arxiv" height="14" />[GAM-Agent: Game-Theoretic and Uncertainty-Aware Collaboration for Complex Visual Reasoning](https://arxiv.org/abs/2505.23399). [GAM-Agent]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2505.20718 -red?logo=arxiv" height="14" />[VLM Can Be a Good Assistant: Enhancing Embodied Visual Tracking with Self-Improving Vision-Language Models](https://arxiv.org/abs/2505.20718).
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2505.07815 -red?logo=arxiv" height="14" />[Imagine, Verify, Execute: Memory-Guided Agentic Exploration with Vision-Language Models](https://arxiv.org/html/2505.07815v2).
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2403.09027 -red?logo=arxiv" height="14" />[VisionGPT: Vision‑Language Understanding Agent Using Generalized Multimodal Framework](https://arxiv.org/abs/2403.09027). [VisionGPT]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2401.17221 -red?logo=arxiv" height="14" />[MouSi: Poly-Visual-Expert Vision-Language Models](https://arxiv.org/abs/2401.17221). [MouSi]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2406.17770 -red?logo=arxiv" height="14" />[Mg-llava: Towards multi-granularity visual instruction tuning](http://arxiv.org/abs/2406.17770). [Mg-llava]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2409.13980 -red?logo=arxiv" height="14" />[Enhancing advanced visual reasoning ability of large language models](https://arxiv.org/abs/2409.13980).
- <img alt="iccv" src="https://img.shields.io/badge/ICCV-2025-orange?logo=cc" height="14" />[METEOR: Multi-Encoder Collaborative Token Pruning for Efficient Vision Language Models](https://arxiv.org/abs/2507.20842). [METEOR]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2506.21924 -red?logo=arxiv" height="14" />[SPAZER: Spatial-Semantic Progressive Reasoning Agent for Zero-shot 3D Visual Grounding](https://arxiv.org/abs/2506.21924). [SPAZER]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2507.22805 -red?logo=arxiv" height="14" />[MoCHA: Advanced Vision-Language Reasoning with MoE Connector and Hierarchical Group Attention](https://arxiv.org/abs/2507.22805). [MoCHA]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2507.21741 -red?logo=arxiv" height="14" />[MAGE: Multimodal Alignment and Generation Enhancement via Bridging Visual and Semantic Spaces](https://arxiv.org/abs/2507.21741). [MAGE]

#### Retrieval-Augmented Generation (RAG) for VLMs

- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2210.02928 -red?logo=arxiv" height="14" />[MuRAG: Multimodal Retrieval-Augmented Generator for Open Question Answering over Images and Text](https://arxiv.org/abs/2210.02928).[MuRAG]
- <img alt="cikm" src="https://img.shields.io/badge/CIKM-2024-navy?logo=cikm" height="14" />[iRAG: Advancing RAG for Videos with an Incremental Approach](https://arxiv.org/abs/2404.12309).[iRAG]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2411.04952 -red?logo=arxiv" height="14" />[M3DOCRAG: Multi-modal Retrieval is What You Need for Multi-page Multi-document Understanding](https://arxiv.org/abs/2411.04952).[M3DOCRAG]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2401.15884 -red?logo=arxiv" height="14" />[Corrective Retrieval Augmented Generation](https://arxiv.org/abs/2401.15884).
- <img alt="iclr" src="https://img.shields.io/badge/ICLR-2025-purple?logo=iclr" height="14" />[VISRAG: VISION-BASED RETRIEVAL-AUGMENTED  GENERATION ON MULTI-MODALITY DOCUMENTS](https://openreview.net/forum?id=zG459X3Xge).[VISRAG]

## Data

### Pre-Training Data



### Fine-Tuning Data
- <img alt="NeurIPS" src="https://img.shields.io/badge/NeurIPS-2024-0596D3?logo=neurips" height="14" /> [What matters when building vision-language models?](https://proceedings.neurips.cc/paper_files/paper/2024/hash/a03037317560b8c5f2fb4b6466d4c439-Abstract-Conference.html). [Idefics2]

### Benchmarks
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2406.10638 -red?logo=arxiv" height="14" /> [Seeing Clearly, Answering Incorrectly: A Multimodal Robustness Benchmark for Evaluating MLLMs on Leading Questions](https://arxiv.org/abs/2406.10638). [MMR]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2406.17126 -red?logo=arxiv" height="14" /> [MM-SpuBench: Towards Better Understanding of Spurious Biases in Multimodal LLMs](https://arxiv.org/abs/2406.17126). [MM-SpuBench]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2406.17806 -red?logo=arxiv" height="14" /> [MOSSBench: Is Your Multimodal Language Model Oversensitive to Safe Queries?](https://arxiv.org/abs/2406.17806). [MOSSBenchh]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2401.07529 -red?logo=arxiv" height="14" /> [MM-SAP: A Comprehensive Benchmark for Assessing Self-Awareness of Multimodal Large Language Models in Perception](https://arxiv.org/abs/2401.07529). [MM-SAP]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2308.04152 -red?logo=arxiv" height="14" /> [Fine-tuning Multimodal LLMs to Follow Zero-shot Demonstrative Instructions](https://arxiv.org/abs/2308.04152). [DEMON]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2403.08350 -red?logo=arxiv" height="14" /> [CoIN: A Benchmark of Continual Instruction tuNing for Multimodel Large Language Model](https://arxiv.org/abs/2403.08350). [CoIN]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2407.01509 -red?logo=arxiv" height="14" /> [MIA-Bench: Towards Better Instruction Following Evaluation of Multimodal LLMs](https://arxiv.org/abs/2407.01509). [MIA-Bench]

- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2311.17005 -red?logo=arxiv" height="14" /> [MVBench: A Comprehensive Multi-modal Video Understanding Benchmark](https://arxiv.org/abs/2311.17005). [MVBench]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2406.07057 -red?logo=arxiv" height="14" /> [Benchmarking Trustworthiness of Multimodal Large Language Models: A Comprehensive Study](https://arxiv.org/abs/2406.07057). [MultiTrust]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2406.04264 -red?logo=arxiv" height="14" /> [MLVU: A Comprehensive Benchmark for Multi-Task Long Video Understanding](https://arxiv.org/abs/2406.04264). [MLVU]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2406.09367 -red?logo=arxiv" height="14" /> [Needle In A Video Haystack: A Scalable Synthetic Framework for Benchmarking Video MLLMs](https://arxiv.org/abs/2406.09367). [VideoNIAH]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2406.14129 -red?logo=arxiv" height="14" /> [Towards Event-oriented Long Video Understanding](https://arxiv.org/abs/2406.14129). [Event-Bench]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2310.14566 -red?logo=arxiv" height="14" /> [HallusionBench: An Advanced Diagnostic Suite for Entangled Language Hallucination and Visual Illusion in Large Vision-Language Models](https://arxiv.org/abs/2310.14566). [HallusionBench]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2305.10355 -red?logo=arxiv" height="14" /> [Evaluating Object Hallucination in Large Vision-Language Models](https://arxiv.org/abs/2305.10355). [POPE]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2405.11985 -red?logo=arxiv" height="14" /> [MTVQA: Benchmarking Multilingual Text-Centric Visual Question Answering](https://arxiv.org/abs/2405.11985). [MTVQA]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-1903.02741 -red?logo=arxiv" height="14" /> [RAVEN: A Dataset for Relational and Analogical Visual rEasoNing](https://arxiv.org/abs/1903.02741). [RAVEN]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2405.12523 -red?logo=arxiv" height="14" /> [Single Image Unlearning: Efficient Machine Unlearning in Multimodal Large Language Models](https://arxiv.org/abs/2405.12523). [MMUBench]

- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2307.06281 -red?logo=arxiv" height="14" /> [MMBench: Is Your Multi-modal Model an All-around Player?](https://arxiv.org/abs/2307.06281). [MMBench]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2307.16125 -red?logo=arxiv" height="14" /> [Seed-bench: Benchmarking multimodal llms with generative comprehension](https://arxiv.org/abs/2307.16125). [SEED-Bench]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2308.02490 -red?logo=arxiv" height="14" /> [Mm-vet: Evaluating large multimodal models for integrated capabilities](https://arxiv.org/abs/2308.02490). [MM-Vet]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2308.02490 -red?logo=arxiv" height="14" /> [Referitgame: Referring to objects in photographs of natural scenes](https://www.mendeley.com/catalogue/2cf9f243-30db-3305-a464-9407e7bf6087/). [RefCoCo]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-1511.02283 -red?logo=arxiv" height="14" /> [Generation and comprehension of unambiguous object descriptions](https://arxiv.org/abs/1511.02283). [RefCoCog]
- <img alt="IEEE" src="https://img.shields.io/badge/IEEE-9009481-blue?logo=ieee" height="14" /> [Nocaps: Novel object captioning at scale](https://ieeexplore.ieee.org/document/9009481). [NoCaps]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2307.02499 -red?logo=arxiv" height="14" /> [mplug-docowl: Modularized multimodal large language model for document understanding](https://arxiv.org/abs/2307.02499). [mplug-docowl]
- <img alt="IEEE" src="https://img.shields.io/badge/IEEE-10656299-blue?logo=ieee" height="14" /> [Mmmu: A massive multi-discipline multimodal understanding and reasoning benchmark for expert agi](https://ieeexplore.ieee.org/document/10656299). [MMMU]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2401.11944 -red?logo=arxiv" height="14" /> [Cmmmu: A chinese massive multi-discipline multimodal understanding benchmark](https://arxiv.org/abs/2401.11944). [CMMMU]
- <img alt="arXiv" src="https://img.shields.io/badge/arXiv-2403.14624 -red?logo=arxiv" height="14" /> [Mathverse: Does your multi-modal llm truly see the diagrams in visual math problems?](https://arxiv.org/abs/2403.14624). [Mathverse]

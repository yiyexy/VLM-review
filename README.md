# VLM-review

视觉语言大模型综述

# 论文目录

- [Model](#Model)
  - [LLaVA](#LLaVA)
- [Data](#Data)
  - [ShareGPT4V](#ShareGPT4V)



# Model

## LLaVA 

Code: [Github](https://github.com/haotian-liu/LLaVA)

Weight: [Huggingface](https://huggingface.co/liuhaotian)

Demo: [Huggingface](https://huggingface.co/spaces/badayvedat/LLaVA)

LLaVA: [Visual Instruction Tuning](https://arxiv.org/abs/2304.08485)

- Date: 2023.04
- Core contribution: A simple framework for training VLM (Vision Language Model) has been proposed, achieving notable visual comprehension abilities with less data. Moreover, a batch of high-quality structured fine-tuning VLM data comprising 158K instances has been produced using existing open-source datasets.

LLaVA 1.5: [Improved Baselines with Visual Instruction Tuning](https://arxiv.org/abs/2310.03744)

- Date: 2023.10
- Core contribution: By increasing the amount of data for pre-training (558K) and fine-tuning (655K), as well as enhancing the resolution of the visual encoder and the size of the LLM, further evidence was provided for the key factors in improving the capabilities of VLMs.

LLaVA 1.6: [LLaVA-NeXT: Improved reasoning, OCR, and world knowledge](https://llava-vl.github.io/blog/2024-01-30-llava-next/)

- Date: 2024.01
- Core contribution: Selected subsets of datasets were curated, increasing the fine-tuning data volume to 760K; image clarity was enhanced by utilizing dynamic image segmentation techniques; furthermore, larger LLM models were employed for further improvements.







# Data

## ShareGPT4V

[ShareGPT4V: Improving Large Multi-Modal Models with Better Captions](https://arxiv.org/abs/2311.12793)

- Date: 2023.11
- Core contribution: The impact of using high-quality image captions during the pre-training phase of VLMs was proposed. Utilizing GPT-4V, 100K high-quality image caption data were generated, and based on this data, the ShareCaptioner model was trained to produce high-quality image captions. Ultimately, the ShareCaptioner model was used to create and contribute a total of 1.2 million data entries.
- Code: [Github](https://github.com/InternLM/InternLM-XComposer/tree/main/projects/ShareGPT4V)
- Weight: [[ShareGPT4V-7B](https://huggingface.co/Lin-Chen/ShareGPT4V-7B)] [[ShareCaptioner](https://huggingface.co/Lin-Chen/ShareCaptioner)]
- Demo: [Huggingface](https://huggingface.co/spaces/Lin-Chen/ShareGPT4V-7B)

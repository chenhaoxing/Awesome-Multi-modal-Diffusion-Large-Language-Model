# Awesome-Multi-modal-Diffusion-Large-Language-Model
✨✨Latest Papers on Multimodal dLLM and Related Areas

---

## Contents
- [Survey](#survey)
- [Leaderboard](#leaderboard)
- [Vision-language model](#vision-language-model)
- [Unified Generation and Understanding](#unified-generation-and-understanding)

---

## Survey
| Title                                                        | Venue         | Year | 
| :----------------------------------------------------------- | :-----------: | :--: |
| [A Survey on Diffusion Language Models](https://arxiv.org/pdf/2508.10875)| arXiv   | 2025 | 


---

## Leaderboard

### 🏆 Understanding
| Model | Type | Params | MMMU-val| MMMU-Pro-vision | MMStar | POPE  | MME-P| MMBench | MathVista | MMVet | SEEDBench | 
| :-----------: |:-----------: |:-----------: |:-----------: |:-----------: |:-----------: |:-----------:|:-----------: |:-----------:|:-----------: |:-----------: |:-----------: |
| LLaDA-V|VLM | 8B | 48.6 |**18.6**|**60.1**|- |1507 |- |- |- |74.8 |
| LaViDa |VLM | 8B|43.3 | - |- |- |1365.6 |70.5 |44.8 |- |- |
|MMaDA|Uni|8B|30.2 | - |- |86.1|1410.7|68.5|-|-|64.2|
|Lavida-O|Uni|8B|45.1| - | - | - | 1431|76.4|**56.9**|-|-|
|Lumina-DiMOO|Uni | 8B|**58.6**| - |- |**87.4**|**1534.2**|**84.5**|- |- |**83.1**|

### 🏆 Generation
| Model |  Params |  GenEval| DPG Bench | UniGenBench |
| :-----------: |:-----------: |:-----------: |:-----------: |:-----------: |
|MMaDA|8B| 0.63｜69.93 ｜41.35 ｜
|Lavida-O|8B|0.89 ｜83.2 |- |
|Lumina-DiMOO| 8B|**0.91**｜**86.04**｜**71.12**｜ 

---

## Vision-language model
| Title                                                        | Venue         | Year | Comment                                                     | Code                                           |
| :-----------------------------------------------------------: | :-----------: | :--: | :-----------------------------------------------------------: | :-----------------------------------------------------------: |
| [LLaDA-V: Large Language Diffusion Models with Visual Instruction Tuning](https://arxiv.org/pdf/2505.16933)| arXiv   | 2025 | First dVLM; based on LLaDA-8B-Base| [Code](https://ml-gsai.github.io/LLaDA-V-demo/) |
| [LaViDa: A Large Diffusion Language Model for Multimodal Understanding](https://arxiv.org/pdf/2505.16839)| NeurIPS Spotlight   | 2025 |Several training tricks: complementary masking, Prefix-DLM, and timestep shifting; based on LLaDA-8B-Base| [Code](https://github.com/jacklishufan/LaViDa) |

---

## Unified Generation and Understanding

| Title                                                        | Venue         | Year | Comment                                                     | Code                                                         |
| :----------------------------------------------------------- | :-----------: | :--: | :----------------------------------------------------------- | :----------------------------------------------------------- |
| [An Omni Diffusion Large Language Model for Multi-Modal Generation and Understanding](https://arxiv.org/pdf/2510.06308)| arXiv   | 2025 | Scaling dLLM for Unified model;SoTA performance in Generation; based on LLaDA-8B-Base| [Code](https://github.com/Alpha-VLLM/Lumina-DiMOO) |
| [Lavida-O: Elastic Large Masked Diffusion Models for Unified Multimodal Understanding and Generation](https://arxiv.org/pdf/2509.19244)| arXiv   | 2025 | Interleaved generation & image editing; based on LaViDa| -|
|[MMaDA: Multimodal Large Diffusion Language Models](https://arxiv.org/pdf/2509.19244) | NeurIPS Oral | 2025 | Scaling Uni dLLM; Unify GRPO; training from scratch| [Code](https://github.com/Gen-Verse/MMaDA) |


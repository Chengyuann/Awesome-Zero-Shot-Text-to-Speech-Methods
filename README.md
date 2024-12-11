
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity)
[![PR's Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](http://makeapullrequest.com) 
[![Survey Paper](https://img.shields.io/badge/Paper-arXiv-blue.svg?style=flat)](https://arxiv.org/abs/2403.04279) 
[![visitors](https://visitor-badge.laobi.icu/badge?page_id=Chengyuann.Awesome-Anomalous-Sound-Detection-Methods)](https://visitor-badge.laobi.icu/badge?page_id=Chengyuann.Awesome-Anomalous-Sound-Detection-Methods)


## Zero-Shot Text-to-Speech Synthesizers
| Publication |    Paper Title     |    Guidance Set      | Combination                                                                                                            | Code/Project                                                 |
|:----:|-----------------------------------------------------------------------------------------------------------------------|:---------------:|:-------:|--------------------------------------------------------------|
| CVPR 2024 | [EmotiVoice 😊: a Multi-Voice and Prompt-Controlled TTS Engine] |    instruction     | $F_{inv}^T+F_{edit}^{Attn}$|[Code](https://github.com/netease-youdao/EmotiVoice)|
| CVPR 2024  | [Doubly Abductive Counterfactual Inference for Text-based Image Editing](https://arxiv.org/abs/2403.02981) |  text  | $F_{inv}^T+F_{edit}^{Blend}$ |[Code](https://github.com/xuesong39/DAC)|
| CVPR 2024 | [ZONE: Zero-Shot Instruction-Guided Local Editing](https://arxiv.org/abs/2312.16794) |    instruction     | $F_{inv}^T+F_{edit}^{Blend}$|[Code](https://github.com/lsl001006/ZONE)|
|WACV 2024  |  [ProxEdit: Improving Tuning-Free Real Image Editing with Proximal Guidance](https://arxiv.org/pdf/2306.05414) |  text  | $F_{inv}^F+F_{edit}^{Attn}$ |[Code](https://github.com/phymhan/prompt-to-prompt)|
| ICLR 2024 | [PnP Inversion: Boosting Diffusion-based Editing with 3 Lines of Code](https://arxiv.org/abs/2310.01506) |  text  | $F_{inv}^F+F_{edit}^{Attn}$ |[Code](https://github.com/cure-lab/PnPInversion)|
| CVPR 2024 | [An Edit Friendly DDPM Noise Space: Inversion and Manipulations](https://arxiv.org/abs/2304.06140) |  text  | $F_{inv}^F+F_{edit}^{Attn}$ |[Code](https://github.com/inbarhub/DDPM_inversion)|
|CVPR 2024 |  [Towards Understanding Cross and Self-Attention in Stable Diffusion for Text-Guided Image Editing](https://arxiv.org/abs/2403.03431) |  text  | $F_{inv}^F+F_{edit}^{Attn}$ |[Code](https://github.com/alibaba/EasyNLP/tree/master/diffusion/FreePromptEditing)|
| ICLR 2024 |  [Object-aware Inversion and Reassembly for Image Editing](https://arxiv.org/abs/2310.12149) |  text  | $F_{inv}^F+F_{edit}^{Blend}$ |[Code](https://github.com/aim-uofa/OIR)|
|ICLR 2024  |   [Noise Map Guidance: Inversion with Spatial Context for Real Image Editing](https://arxiv.org/abs/2402.04625) |  text  | $F_{inv}^F+F_{edit}^{Score}$ |[Code](https://github.com/hansam95/NMG)|
| CVPR 2024 |   [LEDITS++: Limitless Image Editing using Text-to-Image Models](https://arxiv.org/abs/2311.16711)  |  text  | $F_{inv}^F+F_{edit}^{Score}$ |[Code](https://github.com/huggingface/diffusers/tree/main/src/diffusers/pipelines/ledits_pp)|
|ICLR 2024  |   [Noise Map Guidance: Inversion with Spatial Context for Real Image Editing](https://arxiv.org/abs/2402.04625) |  text  | $F_{inv}^F+F_{edit}^{Score}$ |[Code](https://github.com/hansam95/NMG)|
|ICLR 2024 | [Magicremover: Tuning-free Text-guided Image inpainting with Diffusion Models](https://arxiv.org/abs/2310.02848) |  text  | $F_{inv}^F+F_{edit}^{Score}$ |[Code]()|
|Arxiv 2023 |    [Region-Aware Diffusion for Zero-shot Text-driven Image Editing](https://arxiv.org/abs/2302.11797) |  text  | $F_{inv}^F+F_{edit}^{Optim}$ |[Code]()|
| ICCV 2023 |  [Delta Denoising Score](https://arxiv.org/abs/2304.07090) |  text  | $F_{inv}^F+F_{edit}^{Optim}$ |[Code](https://github.com/google/prompt-to-prompt/blob/main/DDS_zeroshot.ipynb)|
|CVPR 2024 |  [Contrastive Denoising Score for Text-guided Latent Diffusion Image Editing](https://arxiv.org/abs/2311.18608) |  text  | $F_{inv}^F+F_{edit}^{Optim}$ |[Code](https://github.com/HyelinNAM/ContrastiveDenoisingScore)|
|NeurIPS 2024 |  [Energy-Based Cross Attention for Bayesian Context Update in Text-to-Image Diffusion Models](https://arxiv.org/abs/2306.09869) |  text  | $F_{inv}^F+F_{edit}^{Optim}$ |[Code](https://github.com/EnergyAttention/Energy-Based-CrossAttention)|

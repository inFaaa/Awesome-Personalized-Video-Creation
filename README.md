<a name="top"></a>
# 🌟 Awesome Personalized Video Generation
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green) 

This repo is used for recording and tracking recent personalized video generation. ￼ ￼

PVG的目标是实现对视频生成过程的全方位定制，这不仅包括主体身份，还涵盖了艺术风格 、背景场景 、运动模式乃至镜头语言 。


- [🌟 Awesome Personalized Video Generation](#-awesome-personalized-video-generation)
  - [⚡ Contributing](#-contributing)
  - [📚 Key Techniques \& Foundational Models](#-key-techniques--foundational-models)
    - [🖼️ Personalized Image Generation](#️-personalized-image-generation)
    - [👤 Subject Identity Learning](#-subject-identity-learning)
    - [🎛️ Multi-Modal Control Signal](#️-multi-modal-control-signal)
    - [📽️ Foundation Video Generation Models](#️-foundation-video-generation-models)
  - [🌐 Open-Domain Personalized Video Generation Models](#-open-domain-personalized-video-generation-models)
    - [🎨 Subject-Driven Creation Models](#-subject-driven-creation-models)
      - [Test-time Fine-tuning](#test-time-fine-tuning)
      - [Pretrained Adaptation](#pretrained-adaptation)
    - [✂️ Video-Driven Editing Models](#️-editing-models)
      - [Text-Guided Editing](#text-guided-editing)
      - [Subject Replacement/Addition](#subject-replacementaddition)
      - [Video Stylization](#video-stylization)
    - [🎥 Motion / Structure / Pose-Driven Models](#-motion--structure--pose-transfer)
    - [🔄 Multi-Modal Driven Models](#-multi-modal-driving-models)
  - [🧑 Human-Domain Personalized Video Generation Models](#-human-domain-personalized-video-generation-models)
    - [🎨 ID-Driven Creation Models](#-id-driven-creation-models)
      - [Test-time Finetuning](#test-time-finetuning)
      - [Pretrained Adaptation](#pretrained-adaptation-1)
    - [✂️ Editing Models](#️-editing-models-1)
      - [Text-Guided Editing](#text-guided-editing-1)
      - [ID Replacement/Addition](#id-replacementaddition)
    - [🕺 Video Animation](#-video-animation)
      - [Audio-Driven Portrait Animation / Facial Animation](#portrait-animation--facial-animation)
      - [Pose-Driven Full-Body Animation](#full-body-animation)
  - [💼 Commercial Personalized Video Generation Models](#-commercial-s2v-models)
  - [📈 Evaluation](#-evaluation)
    - [📊 Personalized Video Generation Benchmarks](#-personalized-video-generation-benchmarks)
    - [📂 Personalized Video Generation Datasets](#-personalized-video-generation-datasets)
    - [📏 Key Evaluation Metrics](#-key-evaluation-metrics)
  - [👍 Acknowledgement](#-acknowledgement)



## ⚡ Contributing

If you want to add your work to this list, please do not hesitate to email jhuang90@ur.rochester.edu or [pull requests]([https://github.com/inFaaa/Awesome-Personalized-Video-Generation/pulls](https://github.com/inFaaa/Awesome-Personalized-Video-Generation/pulls)).
Markdown format:

```markdown
* | [**Paper Title**] | Venue | Date | [[paper]](link) [[code]](link) |
```

## 📚 Key Techniques & Foundational Models
### 🖼️ Personalized Image Generation
- [DreamO](https://github.com/bytedance/DreamO)
- [RealCustom](https://github.com/bytedance/RealCustom)
- [UNO](https://github.com/bytedance/UNO)
- [InfiniteYou](https://github.com/bytedance/InfiniteYou/tree/main)
- [UniPortrait](https://github.com/junjiehe96/UniPortrait)
- [PuLID](https://github.com/ToTheBeginning/PuLID)
- [InstantID](https://github.com/instantX-research/InstantID)
- [PhotoMaker](https://github.com/TencentARC/PhotoMaker)
- [IP-Adapter](https://github.com/tencent-ailab/IP-Adapter)

### 👤 Subject Identity Learning
### 🎛️ Multi-modal Control Signal
### 📽️ Foundation Video Generation Models
- [Wan 2.1](https://github.com/Wan-Video/Wan2.1)
- [Step-Video](https://github.com/stepfun-ai/Step-Video-T2V)
- [HunyuanVideo](https://github.com/Tencent/HunyuanVideo)
- [LTX-Video](https://github.com/Lightricks/LTX-Video)
- [Mochi](https://github.com/genmoai/mochi)
- [CogVideo-X](https://github.com/THUDM/CogVideo)
- [Open-Sora-Plan](https://github.com/PKU-YuanGroup/Open-Sora-Plan)
- [Open-Sora](https://github.com/hpcaitech/Open-Sora)
- [Stable Video Diffusion](https://github.com/Stability-AI/generative-models)

## 🌐 Open-Domain Personalized Video Generation Models

### 🎨 Subject-Driven Creation Models

#### Test-time Fine-tuning

#### Pretrained Adaptation

| Title                                                        | Venue     | Date             | Links                                                        |
| ------------------------------------------------------------ | --------- | ---------------- | ------------------------------------------------------------ |
| **PIA: Your Personalized Image Animator via Plug-and-Play Modules in Text-to-Image Models** | CVPR 2024 | Dec 2023 (arXiv) | [Paper](https://arxiv.org/abs/2312.13964v3) – [Project](https://pi-animator.github.io/)  - [Code](https://github.com/open-mmlab/PIA) |
| **VideoBooth: Diffusion-based Video Generation with Image Prompts** | CVPR 2024 | Dec 2023 (arXiv) | [Paper](https://arxiv.org/abs/2312.00777) – [Project](https://vchitect.github.io/VideoBooth-project/) – [Code](https://github.com/vchitect/VideoBooth) |
| **CustomVideo: Customizing Text-to-Video Generation with Multiple Subjects** | arXiv     | Jan 18 2024      | [Paper](https://arxiv.org/pdf/2401.09962) – [Project](https://kyfafyd.wang/projects/customvideo/) |
| **Movie Gen: A Cast of Media Foundation Models**             | arXiv     | Oct 17 2024      | [Paper](https://arxiv.org/abs/2410.13720) – [Project](https://ai.meta.com/research/movie-gen/) |
| **VideoMaker: Zero-shot Customized Video Generation with the Inherent Force of Video Diffusion Models** | arXiv     | Dec 27 2024      | [Paper](https://arxiv.org/abs/2412.19645) – [Project](https://wutao-cs.github.io) – [Code](https://github.com/WuTao-CS/VideoMaker) |
| **Multi-subject Open-set Personalization in Video Generation** | CVPR 2025 | Jan 2025 (arXiv) | [Paper](https://arxiv.org/abs/2501.06187) – [Project](https://snap-research.github.io/open-set-video-personalization/) – [Code](https://github.com/snap-research/open-set-video-personalization) |
| **Phantom: Subject-Consistent Video Generation via Cross-Modal Alignment** | arXiv     | Feb 16 2025      | [Paper](https://arxiv.org/abs/2502.11079) – [Project](https://phantom-video.github.io/Phantom/) – [Code](https://github.com/Phantom-video/Phantom) |
| **CINEMA: Coherent Multi-Subject Video Generation via MLLM-Based Guidance** | arXiv     | Mar 13 2025      | [Paper](https://arxiv.org/abs/2503.10391) |
| **VideoMage: Multi-Subject and Motion Customization of Text-to-Video Diffusion Models** | CVPR 2025     | Mar 13 2025      | [Paper](https://arxiv.org/abs/2503.21781) [Project](https://jasper0314-huang.github.io/videomage-customization/) |
| **SkyReels-A2: Compose Anything in Video Diffusion Transformers** | arXiv     | Apr 3 2025       | [Paper](https://arxiv.org/abs/2504.02436) – [Project](https://skyworkai.github.io/SkyReels-A2/) – [Code](https://github.com/SkyWorkAI/skyreels-a2) |
| **BridgeIV: Bridging Customized Image and Video Generation through Test-Time Autoregressive Identity Propagation** | arXiv     | May 11 2025      | [Paper](https://arxiv.org/pdf/2505.06985)                    |
| **MAGREF: Masked Guidance for Any-Reference Video Generation** | arXiv     | May 29 2025      | [Paper](https://arxiv.org/pdf/2505.23742) [Code](https://github.com/MAGREF-Video/MAGREF)                   |
| **AnyCharV: Bootstrap Controllable Character Video Generation with Fine-to-Coarse Guidance** | arXiv     | Feb 2025      | [Paper](https://arxiv.org/abs/2502.08189) – [Code](https://github.com/AnyCharV/AnyCharV)                   |
| **Movie Weaver: Tuning-Free Multi-Concept Video Personalization with Anchored Prompts** | arXiv     | Feb 2025      | [Paper](https://arxiv.org/abs/2502.07802)                  |
| **ConceptMaster: Multi-Concept Video Customization on Diffusion Transformer Models Without Test-Time Tuning** | arXiv     | Jan 2025     | [Paper](https://arxiv.org/abs/2501.04698)                  |
| **Customcrafter: Customized Video Generation with Preserving Motion and Concept Composition Abilities** | arXiv     | Feb 2025      | [Paper](https://arxiv.org/abs/2408.13239) – [Code](https://github.com/WuTao-CS/CustomCrafter)                   |

### ✂️ Editing Models

#### Text-Guided Editing

#### Subject Replacement/Addition

| Title                                                        | Venue     | Date         | Links                                                        |
| ------------------------------------------------------------ | --------- | ------------ | ------------------------------------------------------------ |
| **Get In Video: Add Anything You Want to the Video** | arXiv | May 2025  | [Code](https://zhuangshaobin.github.io/GetInVideo-project/) – [Paper](https://arxiv.org/abs/2503.06268) |

#### Video Stylization

| Title                                                        | Venue     | Date         | Links                                                        |
| ------------------------------------------------------------ | --------- | ------------ | ------------------------------------------------------------ |
| **Tune-A-Video: One-Shot Tuning of Image Diffusion Models for Text-to-Video Generation** | ICCV 2023 | Dec 22 2022  | [Code](https://github.com/showlab/Tune-A-Video) <br> [Paper](https://arxiv.org/abs/2212.11565) |
| **Structure and Content-Guided Video Synthesis with Diffusion Models** | ICCV 2023 | Feb 2023     | [Paper](https://openaccess.thecvf.com/content/ICCV2023/papers/Esser_Structure_and_Content-Guided_Video_Synthesis_with_Diffusion_Models_ICCV_2023_paper.pdf) |
| **Dreamix: Video Diffusion Models are General Video Editors** | arXiv     | Feb 2023     | [Paper](https://arxiv.org/abs/2302.01329) – [Project](https://dreamix-video-editing.github.io/) |
| **Make-A-Protagonist: Generic Video Editing with Visual and Textual Clues** | arXiv     | May 15  2023 | [Paper](https://arxiv.org/pdf/2305.08850) – [Code](https://github.com/HeliosZhao/Make-A-Protagonist) |
| **Cut-and-Paste: Subject-Driven Video Editing with Attention Control** | arXiv     | Nov 20 2023  | [Paper](https://arxiv.org/abs/2311.11697) – [Code](https://github.com/ZrrSkywalker/Cut-And-Paste) |
| **DIVE: Taming DINO for Subject-Driven Video Editing**       | arXiv     | Dec 4 2024   | [Paper](https://arxiv.org/abs/2412.03347) – [Project](https://dino-video-editing.github.io) – [Code](https://github.com/OpenDriveLab/DIVE) |


### 🎥 Motion / Structure / Pose Transfer
| Title                                                        | Venue     | Date         | Links                                                        |
| ------------------------------------------------------------ | --------- | ------------ | ------------------------------------------------------------ |
| **VideoComposer: Compositional Video Synthesis with Motion Controllability** | NeurIPS 2023 | Jun 2023 (arXiv) | [Paper](https://arxiv.org/pdf/2306.02018) – [Project](https://videocomposer.github.io/) - [Code](https://github.com/ali-vilab/videocomposer) |
| **DreamVideo: Composing Your Dream Videos with Customized Subject and Motion** | CVPR 2024 | Dec 2023 (arXiv) | [Paper](https://arxiv.org/abs/2312.04433) – [Project](https://vchitect.github.io/VideoBooth-project/) - [Code](https://github.com/Vchitect/VideoBooth) |
| **Customize-A-Video: One-Shot Motion Customization of Text-to-Video Diffusion Models** | ECCV2024  | Feb 2024     | — <br> [Paper](https://arxiv.org/abs/2402.14780) - [Project](https://ryx19th.github.io/customize-a-video/) - [Code](https://github.com/customize-a-video/customize-a-video) |
| **Subject-driven Video Generation via Disentangled Identity and Motion** | arXiv     | Apr 23 2025      | [Paper](https://arxiv.org/abs/2504.17816) – [Code](https://github.com/carpedkm/disentangled-subject-to-vid) |
| **DualReal: Adaptive Joint Training for Lossless Identity-Motion Fusion in Video Customization** | arXiv     | Mar 4 2025       | [Paper](https://arxiv.org/abs/2505.02192) – [Project](https://wenc-k.github.io/dualreal/) |
| **JointTuner: Appearance-Motion Adaptive Joint Training for Customized Video Generation** | arXiv     | Mar 31 2025      | [Paper](https://arxiv.org/abs/2503.23951) – [Project](https://fdchen24.github.io/JointTuner-Website/) |
| **PolyVivid: Vivid Multi-Subject Video Generation with Cross-Modal Interaction and Enhancement** | arXiv     | Jun 9 2025      | [Paper](https://sjtuplayer.github.io/projects/PolyVivid/)                    |



### 🔄 Multi-modal Driving Models 

| Title                                           | Venue | Date     | Links                                                        |
| ----------------------------------------------- | ----- | -------- | ------------------------------------------------------------ |
| **VACE: All-in-One Video Creation and Editing** | arxiv | Mar 2025 | [Code](https://github.com/ali-vilab/VACE) - [Project](https://ali-vilab.github.io/VACE-Page/) - [Paper](https://github.com/ali-vilab/VACE) |
| **HunyuanCustom: A Multimodal-Driven Architecture for Customized Video Generation** | arXiv     | May 8 2025       | [Paper](https://arxiv.org/pdf/2505.04512) – [Project](https://hunyuancustom.github.io/) – [Code](https://github.com/Tencent-Hunyuan/HunyuanCustom) |


## 🧑 Human-Domain Personalized Video Generation Models

### 🎨 ID-Driven Creation Models

#### Test-time Finetuning

#### Pretrained Adaptation

| Title                                                        | Venue     | Date        | Links                                                        |
| ------------------------------------------------------------ | --------- | ----------- | ------------------------------------------------------------ |
| **Magic-Me: Identity-Specific Video Customized Diffusion**   | arXiv     | Mar 20 2024 | [Paper](https://arxiv.org/pdf/2402.09368) – [Project](https://magic-me-webpage.github.io/) – [Code](https://github.com/PKU-Alignment/ID-Animator) |
| **ID-Animator: Zero-Shot Identity-Preserving Human Video Generation** | arXiv     | Apr 23 2024 | [Paper](https://arxiv.org/abs/2404.15275) – [Project](https://id-animator.github.io) – [Code](https://github.com/Zhen-Dong/Magic-Me) |
| **ConsisID: Identity-Preserving Text-to-Video Generation by Frequency Decomposition** | CVPR 2025 | Nov 26 2024 | [Paper](https://arxiv.org/pdf/2411.17383) – [Code](https://github.com/PKU-YuanGroup/ConsisID) |
| **AnchorCrafter: Animate CyberAnchors Saling Your Products via Human-Object Interacting Video Generation** | arXiv | Nov 26 2024 | [Paper](https://arxiv.org/abs/2411.17440) – [Code](https://github.com/cangcz/AnchorCrafter) |
| **Ingredients: Blending Custom Photos with Video Diffusion Transformers** | arXiv     | Jan 3 2025 | [Paper](https://arxiv.org/pdf/2501.01790?) – [Code](https://github.com/feizc/Ingredients) |
| **EchoVideo: Identity-Preserving Human Video Generation by Multimodal Feature Fusion** | arXiv     | Jan 23 2025 | [Paper](https://arxiv.org/abs/2501.13452) – [Code](https://github.com/JeremyWV/EchoVideo) |
| **FantasyID: Face Knowledge Enhanced ID-Preserving Video Generation** | arXiv     | Feb 25 2025 | [Paper](https://arxiv.org/abs/2502.13995) – [Project](https://fantasy-amap.github.io/fantasy-id/) – [Code](https://github.com/Fantasy-AMAP/fantasy-id) |
| **PersonalVideo: High ID-Fidelity Video Customization without Dynamic and Semantic Degradation** | arXiv     | Mar 16 2025 | [Paper](https://arxiv.org/pdf/2411.17048) – [Project](https://personalvideo.github.io/) –[Code](https://github.com/EchoPluto/PersonalVideo) |
| **MagicID: Hybrid Preference Optimization for ID-Consistent and Dynamic-Preserved Video Customization** | arXiv     | Mar 16 2025 | [Paper](https://arxiv.org/abs/2503.12689) – [Project](https://echopluto.github.io/MagicID-project/) –[Code](https://github.com/EchoPluto/MagicID) |
| **Concat-ID: Towards Universal Identity-Preserving Video Synthesis** | arXiv     | Mar 18 2025 | [Paper](https://arxiv.org/abs/2503.14151) – [Code](https://github.com/ML-GSAI/Concat-ID) |
| **InterActHuman: Multi-Concept Human Animation with Layout-Aligned Audio Conditions** | arXiv     | Jun 11 2025 | [Paper](https://arxiv.org/pdf/2506.09984) – [Project](https://zhenzhiwang.github.io/interacthuman/) |

### ✂️ Editing Models
#### Text-Guided Editing

#### ID Replacement/Addition

#### Video Stylization

| Title                                                        | Venue | Date        | Links                                                        |
| ------------------------------------------------------------ | ----- | ----------- | ------------------------------------------------------------ |
| **IP-FaceDiff: Identity-Preserving Facial Video Editing with Diffusion** | arXiv | Jan 13 2025 | [Paper](https://arxiv.org/abs/2501.07530) – [Code](https://github.com/ThoAce/IP-FaceDiff) |

### 🕺 Video Animation

#### Portrait Animation / Facial Animation

#### Full-Body Animation

## 💼 Commercial Personalized Video Generation Models

- Pika
- Keling
- Veo
- Vidu
- Hailuo

## 📈 Evaluation

### 📊 Personalized Video Generation Benchmarks

| Title / Benchmark                                            | Venue                 | Date        | Links                                                        |
| ------------------------------------------------------------ | --------------------- | ----------- | ------------------------------------------------------------ |
| **ConsisID-Bench** – 150 identities & 90 prompts (human-domain) | CVPR 2025 (Highlight) | Nov 2024    | [Project](https://pku-yuangroup.github.io/ConsisID) – [Data](https://huggingface.co/datasets/PKU-YuanGroup/ConsisID-Bench) |
| **MSRVTT-Personalization** (Alchemist-Bench) – Multi-subject personalization benchmark | CVPR 2025             | Jan 2025    | [Paper](https://arxiv.org/abs/2501.06187) – [Data/Code](https://github.com/snap-research/open-set-video-personalization) |
| **VACE-Benchmark**  – VACE: All-in-One Video Creation and Editing | arXiv 2025            | Mar 2025    | [Paper](https://arxiv.org/abs/2503.07598) – [Data/Code](https://huggingface.co/datasets/ali-vilab/VACE-Benchmark) |
| **A2 Bench** – “Elements-to-Video” evaluation benchmark for arbitrary subjects | arXiv  | Apr 2025    | [Paper](https://arxiv.org/abs/2504.02436) – [Data/Code](https://github.com/SkyWorkAI/skyreels-a2) |
| **OpenS2V-Eval** – Fine-grained S2V benchmark (180 prompts, real & synthetic) | arXiv                 | May 28 2025 | [Paper](https://arxiv.org/abs/2505.20292) – [Project](https://pku-yuangroup.github.io/OpenS2V-Nexus) – [Code](https://huggingface.co/spaces/BestWishYsh/OpenS2V-Eval) |

### 📂 Personalized Video Generation Datasets

| Title / Dataset | Venue | Date        | Links                                                        |
| --------------- | ----- | ----------- | ------------------------------------------------------------ |
| **OpenS2V-5M**  | Arxiv | May 28 2025 | [Paper](https://arxiv.org/abs/2505.20292) – [Project](https://pku-yuangroup.github.io/OpenS2V-Nexus) – [Data](https://huggingface.co/datasets/BestWishYsh/OpenS2V-5M) |
| **ConsisID-Data**  | CVPR 2025 (Highlight) | May 28 2025 | [Paper](https://arxiv.org/abs/2411.17440) – [Project](https://pku-yuangroup.github.io/ConsisID) – [Data](https://huggingface.co/datasets/PKU-YuanGroup/ConsisID-Bench) |

### 📏 Key Evaluation Metrics

## 👍 Acknowledgement

* [Awesome Personalization](https://github.com/zhangxulu1996/awesome-personalization)

* [Awesome-Personalized-Image-Generation](https://github.com/csyxwei/Awesome-Personalized-Image-Generation)

* [Awesome-Video-Diffusion](https://github.com/showlab/Awesome-Video-Diffusion)

* [Awesome-Controllable-Video-Generation](https://github.com/mayuelala/Awesome-Controllable-Video-Generation?tab=readme-ov-file#---personalized--motion)
  

  

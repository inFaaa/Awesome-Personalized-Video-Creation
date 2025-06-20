<a name="top"></a>

# 🌟 Awesome Personalized Video Generation and Editing

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green) 

This repo is used for recording and tracking recent personalized video generation. 

Subject Identity Learning 
+
Multi-modal Control Signal 
(Tokenization)
-> 
Injection Method (Adapter/Finetune)
->
Base Video Generation Models
-> 
Training Strategies

- [🌟 Awesome Personalized Video Generation and Editing](#-awesome-personalized-video-generation-and-editing)
  - [⚡ Contributing](#-contributing)
  - [📚 Key Techniques](#-key-techniques)
    - [🎛️ Multi-Modal Control Tokenization](#️-multi-modal-control-tokenization)
    - [🕳️ Controllable Video Generation](#️-controllable-video-generation)
    - [📽️ Foundation Video Generation Models](#️-foundation-video-generation-models)
  - [🌐 Open-Domain Personalized Video Generation Models](#-open-domain-personalized-video-generation-models)
    - [🎨 Subject-Driven Creation Models](#-subject-driven-creation-models)
      - [Test-time Fine-tuning](#test-time-fine-tuning)
      - [Pretrained Adaptation](#pretrained-adaptation)
    - [✂️ Video-Driven Editing Models](#️-video-driven-editing-models)
    - [🎥 Motion-Driven Generation](#-motion-driven-generation)
    - [🔄 Unified Generation and Editing Models](#-unified-generation-and-editing-models)
  - [🧑 Human-Domain Personalized Video Generation Models](#-human-domain-personalized-video-generation-models)
    - [🎨 ID-Driven Creation Models](#-id-driven-creation-models)
      - [Test-time Finetuning](#test-time-finetuning)
      - [Pretrained Adaptation](#pretrained-adaptation-1)
    - [✂️ Video-Driven Editing Models](#️-video-driven-editing-models-1)
    - [🎺 Audio-Driven Portrait Animation](#-audio-driven-portrait-animation)
    - [🕺 Pose-Driven Full-Body Animation](#-pose-driven-full-body-animation)
    - [🔄 Unified Generation and Editing Models](#-unified-generation-and-editing-models-1)
  - [💼 Commercial Personalized Video Generation Models](#-commercial-personalized-video-generation-models)
  - [📈 Evaluation](#-evaluation)
    - [📊 Personalized Video Generation Benchmarks](#-personalized-video-generation-benchmarks)
      - [Subject-to-Video Benchmarks](#subject-to-video-benchmarks)
    - [📂 Personalized Video Generation Datasets](#-personalized-video-generation-datasets)
      - [Subject-to-Video Datasets](#subject-to-video-datasets)
    - [📏 Key Evaluation Metrics](#-key-evaluation-metrics)
  - [👍 Acknowledgement](#-acknowledgement)



## ⚡ Contributing

If you want to add your work to this list, please do not hesitate to email jhuang90@ur.rochester.edu or [pull requests]([https://github.com/inFaaa/Awesome-Personalized-Video-Generation/pulls](https://github.com/inFaaa/Awesome-Personalized-Video-Generation/pulls)).
Markdown format:

```markdown
* | [**Paper Title**] | Venue | Date | [[paper]](link) [[code]](link) [[project]](link)|
```

## 📚 Key Techniques 


<!--
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
-->

### 🎛️ Multi-Modal Control Tokenization
- [CLIP-Like](https://github.com/openai/CLIP)
- [VAE](https://github.com/huggingface/diffusers/tree/main/src/diffusers/models/autoencoders)
- [ArcFace-Like](https://github.com/deepinsight/insightface)
- [ContorlNet-Like](https://github.com/lllyasviel/ControlNet)
- [T2I-Adapter-Like](https://github.com/TencentARC/T2I-Adapter)
- [SVD-Like](https://github.com/Stability-AI/generative-models)

### 🕳️ Controllable Video Generation
- [Controlnet](https://github.com/lllyasviel/ControlNet)
- [T2IAdapter](https://github.com/TencentARC/T2I-Adapter)


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
- [Make A Video](https://arxiv.org/abs/2209.14792)
- [Step-Video](https://github.com/stepfun-ai/Step-Video-TI2V)

## 🌐 Open-Domain Personalized Video Generation Models

### 🎨 Subject-Driven Creation Models

#### Test-time Fine-tuning

| Title                                                        | Venue     | Date             | Links                                                        |
| ------------------------------------------------------------ | --------- | ---------------- | ------------------------------------------------------------ |
| **PIA: Your Personalized Image Animator via Plug-and-Play Modules in Text-to-Image Models** | CVPR 2024 | Dec 2023 (arXiv) | [Paper](https://arxiv.org/abs/2312.13964v3) – [Project](https://pi-animator.github.io/)  - [Code](https://github.com/open-mmlab/PIA) |
| **VideoBooth: Diffusion-based Video Generation with Image Prompts** | CVPR 2024 | Dec 2023 (arXiv) | [Paper](https://arxiv.org/abs/2312.00777) – [Project](https://vchitect.github.io/VideoBooth-project/) – [Code](https://github.com/vchitect/VideoBooth) |
| **CustomVideo: Customizing Text-to-Video Generation with Multiple Subjects** | arXiv     | Jan 18 2024      | [Paper](https://arxiv.org/pdf/2401.09962) – [Project](https://kyfafyd.wang/projects/customvideo/) |
| **DisenStudio: Customized Multi-subject Text-to-Video Generation with Disentangled Spatial Control** | ACMMM 2024     | May 21 2024      | [Paper](https://mn.cs.tsinghua.edu.cn/xinwang/PDF/papers/2024_DisenStudio%20Customized%20Multi-Subject%20Text-to-Video%20Generation%20with%20Disentangled%20Spatial%20Control.pdf) – [Project](https://forchchch.github.io/disenstudio.github.io/) - [Code](https://github.com/forchchch/disenstudio.github.io) |
| **Customcrafter: Customized Video Generation with Preserving Motion and Concept Composition Abilities** | AAAI 2025    | Feb 2025         | [Paper](https://arxiv.org/abs/2408.13239) – [Code](https://github.com/WuTao-CS/CustomCrafter) |
| **Dynamic Concepts Personalization from Single Videos** | SIGGRAPH 2025 | Feb 20 2025      | [Paper](https://arxiv.org/pdf/2502.14844) – [Page](https://snap-research.github.io/dynamic_concepts/)|
| **BridgeIV: Bridging Customized Image and Video Generation through Test-Time Autoregressive Identity Propagation** | arXiv     | May 11 2025      | [Paper](https://arxiv.org/pdf/2505.06985)|


#### Pretrained Adaptation

| Title                                                        | Venue     | Date             | Links                                                        |
| ------------------------------------------------------------ | --------- | ---------------- | ------------------------------------------------------------ |
| **Movie Gen: A Cast of Media Foundation Models**             | arXiv     | Oct 17 2024      | [Paper](https://arxiv.org/abs/2410.13720) – [Project](https://ai.meta.com/research/movie-gen/) |
| **SUGAR: Subject-Driven Video Customization in a Zero-Shot Manner**             | arXiv     | Dec 13 2024      | [Paper](https://arxiv.org/pdf/2412.10533) – [Project](https://yufanzhou.com/SUGAR/) |
| **VideoMaker: Zero-shot Customized Video Generation with the Inherent Force of Video Diffusion Models** | arXiv     | Dec 27 2024      | [Paper](https://arxiv.org/abs/2412.19645) – [Code](https://github.com/WuTao-CS/VideoMaker) |
| **Multi-subject Open-set Personalization in Video Generation** | CVPR 2025 | Jan 2025 (arXiv) | [Paper](https://arxiv.org/abs/2501.06187) – [Project](https://snap-research.github.io/open-set-video-personalization/) – [Code](https://github.com/snap-research/open-set-video-personalization) |
| **Phantom: Subject-Consistent Video Generation via Cross-Modal Alignment** | arXiv     | Feb 16 2025      | [Paper](https://arxiv.org/abs/2502.11079) – [Project](https://phantom-video.github.io/Phantom/) – [Code](https://github.com/Phantom-video/Phantom) |
| **CINEMA: Coherent Multi-Subject Video Generation via MLLM-Based Guidance** | arXiv     | Mar 13 2025      | [Paper](https://arxiv.org/abs/2503.10391)                    |
| **SkyReels-A2: Compose Anything in Video Diffusion Transformers** | arXiv     | Apr 3 2025       | [Paper](https://arxiv.org/abs/2504.02436) – [Project](https://skyworkai.github.io/SkyReels-A2/) – [Code](https://github.com/SkyWorkAI/skyreels-a2) |                 |
| **MAGREF: Masked Guidance for Any-Reference Video Generation** | arXiv     | May 29 2025      | [Paper](https://arxiv.org/pdf/2505.23742) [Code](https://github.com/MAGREF-Video/MAGREF) |
| **AnyCharV: Bootstrap Controllable Character Video Generation with Fine-to-Coarse Guidance** | arXiv     | Feb 2025         | [Paper](https://arxiv.org/abs/2502.08189) – [Code](https://github.com/AnyCharV/AnyCharV) |
| **Movie Weaver: Tuning-Free Multi-Concept Video Personalization with Anchored Prompts** | arXiv     | Feb 2025         | [Paper](https://arxiv.org/abs/2502.07802)                    |
| **ConceptMaster: Multi-Concept Video Customization on Diffusion Transformer Models Without Test-Time Tuning** | arXiv     | Jan 2025         | [Paper](https://arxiv.org/abs/2501.04698) |

### ✂️ Video-Driven Editing Models

| Title                                                        | Venue     | Date         | Links                                                        |
| ------------------------------------------------------------ | --------- | ------------ | ------------------------------------------------------------ |
| **Tune-A-Video: One-Shot Tuning of Image Diffusion Models for Text-to-Video Generation** | ICCV 2023 | Dec 22 2022  | [Code](https://github.com/showlab/Tune-A-Video) <br> [Paper](https://arxiv.org/abs/2212.11565) |
| **Dreamix: Video Diffusion Models are General Video Editors** | arXiv     | Feb 2023     | [Paper](https://arxiv.org/abs/2302.01329) – [Project](https://dreamix-video-editing.github.io/) |
| **Make-A-Protagonist: Generic Video Editing with Visual and Textual Clues** | arXiv     | May 15  2023 | [Paper](https://arxiv.org/pdf/2305.08850) – [Code](https://github.com/HeliosZhao/Make-A-Protagonist) |
| **Make-Your-Video: Customized Video Generation Using Textual and Structural Guidance** | TVCG 2024 | Jun 2023 | [Paper](https://arxiv.org/abs/2306.00943) – [Code](https://github.com/AILab-CVC/Make-Your-Video) |
| **Cut-and-Paste: Subject-Driven Video Editing with Attention Control** | arXiv     | Nov 20 2023  | [Paper](https://arxiv.org/abs/2311.11697) – [Code](https://github.com/ZrrSkywalker/Cut-And-Paste) |
| **AnyV2V: A Tuning-Free Framework For Any Video-to-Video Editing Tasks**       | TMLR 2024     | Mar 21 2024   | [Paper](https://arxiv.org/abs/2403.14468) – [Project](https://tiger-ai-lab.github.io/AnyV2V/) – [Code](https://github.com/TIGER-AI-Lab/AnyV2V) |
| **ReVideo: Remake a Video with Motion and Content Control** | NeurIPS 2024   | May 22 2024         | — <br> [Paper](https://arxiv.org/abs/2405.13865) - [Project](https://mc-e.github.io/project/ReVideo/) - [Code](https://github.com/MC-E/ReVideo) |
| **DIVE: Taming DINO for Subject-Driven Video Editing**       | arXiv     | Dec 4 2024   | [Paper](https://arxiv.org/abs/2412.03347) – [Project](https://dino-video-editing.github.io)  |
| **DreamInsert: Zero-Shot Image-to-Video Object Insertion from A Single Image** | arXiv     | Mar 13 2025     | [Paper](https://arxiv.org/pdf/2503.10342)  |
| **Get In Video: Add Anything You Want to the Video** | arXiv | May 2025 | [Project](https://dreamix-video-editing.github.io/) – [Paper](https://arxiv.org/abs/2503.06268) |


### 🎥 Motion-Driven Generation

| Title                                                        | Venue        | Date             | Links                                                        |
| ------------------------------------------------------------ | ------------ | ---------------- | ------------------------------------------------------------ |
| **Structure and Content-Guided Video Synthesis with Diffusion Models** | ICCV 2023 | Feb 2023     | [Paper](https://openaccess.thecvf.com/content/ICCV2023/papers/Esser_Structure_and_Content-Guided_Video_Synthesis_with_Diffusion_Models_ICCV_2023_paper.pdf) |
| **VideoComposer: Compositional Video Synthesis with Motion Controllability** | NeurIPS 2023 | Jun 2023 (arXiv) | [Paper](https://arxiv.org/pdf/2306.02018) – [Project](https://videocomposer.github.io/) - [Code](https://github.com/ali-vilab/videocomposer) |
| **DreamVideo: Composing Your Dream Videos with Customized Subject and Motion** | CVPR 2024    | Dec 2023 (arXiv) | [Paper](https://arxiv.org/abs/2312.04433) – [Project](https://vchitect.github.io/VideoBooth-project/) - [Code](https://github.com/Vchitect/VideoBooth) |
| **Customize-A-Video: One-Shot Motion Customization of Text-to-Video Diffusion Models** | ECCV 2024     | Feb 2024         | [Paper](https://arxiv.org/abs/2402.14780) - [Project](https://ryx19th.github.io/customize-a-video/) - [Code](https://github.com/customize-a-video/customize-a-video) |
| **MotionBooth: Motion-Aware Customized Text-to-Video Generation** | NeurIPS 2024 (Spotlight)     | Jun 2024         | [Paper](https://arxiv.org/abs/2406.17758) - [Project](https://jianzongwu.github.io/projects/motionbooth/) - [Code](https://github.com/jianzongwu/MotionBooth) |
| **DreamVideo-2: Zero-Shot Subject-Driven Video Customization with Precise Motion Control** | arXiv   | Oct 17 2024      | [Paper](https://arxiv.org/abs/2410.13830) – [Page](https://dreamvideo2.github.io/#) |
| **MoTrans: Customized Motion Transfer with Text-driven Video Diffusion Models** | ACMMM 2024        | Dec 2 2024      | [Paper](https://arxiv.org/abs/2412.01343) – [Code](https://github.com/XiaominLi1997/MoTrans) |
| **Subject-driven Video Generation via Disentangled Identity and Motion** | arXiv        | Apr 23 2025      | [Paper](https://arxiv.org/abs/2504.17816) – [Code](https://github.com/carpedkm/disentangled-subject-to-vid) |
| **DualReal: Adaptive Joint Training for Lossless Identity-Motion Fusion in Video Customization** | arXiv        | Mar 4 2025       | [Paper](https://arxiv.org/abs/2505.02192) – [Project](https://wenc-k.github.io/dualreal/) |
| **VideoMage: Multi-Subject and Motion Customization of Text-to-Video Diffusion Models** | CVPR 2025 | Mar 13 2025      | [Paper](https://arxiv.org/abs/2503.21781) [Project](https://jasper0314-huang.github.io/videomage-customization/) |
| **DreamRunner: Fine-Grained Compositional Story-to-Video Generation with Retrieval-Augmented Motion Adaptation** | Arxiv | Mar 18 2025      | [Paper](https://arxiv.org/pdf/2411.16657) - [Project](https://zunwang1.github.io/DreamRunner) - [Code](https://github.com/wz0919/DreamRunner) |
| **JointTuner: Appearance-Motion Adaptive Joint Training for Customized Video Generation** | arXiv        | Mar 31 2025      | [Paper](https://arxiv.org/abs/2503.23951) – [Project](https://fdchen24.github.io/JointTuner-Website/) |
| **PolyVivid: Vivid Multi-Subject Video Generation with Cross-Modal Interaction and Enhancement** | arXiv        | Jun 9 2025       | [Paper](https://sjtuplayer.github.io/projects/PolyVivid/)|


### 🔄 Unified Generation and Editing Models 

| Title                                                        | Venue        | Date        | Links                                                        |
| ------------------------------------------------------------ | ------------ | ----------- | ------------------------------------------------------------ |
| **Few-shot Video-to-Video Synthesis**                        | NeurIPS 2019 | Oct 28 2019 | [Paper](https://arxiv.org/pdf/2505.04512) – [Project](https://nvlabs.github.io/few-shot-vid2vid/) – [Code](https://github.com/NVlabs/few-shot-vid2vid) |
| **Towards Consistent Video Editing with Text-to-Image Diffusion Models**      | NeurIPS 2023 | May 27 2023 | [Paper](https://arxiv.org/abs/2305.17431)  |
| **DragVideo: Interactive Drag-style Video Editing**      | ECCV 2024 | Dec 3 2023 | [Paper](https://arxiv.org/abs/2312.02216) - [Code](https://github.com/RickySkywalker/DragVideo-Official) |
| **HunyuanCustom: A Multimodal-Driven Architecture for Customized Video Generation** | arXiv        | May 8 2025  | [Paper](https://arxiv.org/pdf/2505.04512) – [Project](https://hunyuancustom.github.io/) – [Code](https://github.com/Tencent-Hunyuan/HunyuanCustom) |
| **VACE: All-in-One Video Creation and Editing**              | arxiv        | Mar 10 2025 | [Code](https://github.com/ali-vilab/VACE) - [Project](https://ali-vilab.github.io/VACE-Page/) - [Paper](https://arxiv.org/abs/2503.07598) |

## 🧑 Human-Domain Personalized Video Generation Models

### 🎨 ID-Driven Creation Models

#### Test-time Finetuning

| Title                                                        | Venue     | Date        | Links                                                        |
| ------------------------------------------------------------ | --------- | ----------- | ------------------------------------------------------------ |
| **Magic-Me: Identity-Specific Video Customized Diffusion**   | arXiv     | Mar 20 2024 | [Paper](https://arxiv.org/pdf/2402.09368) – [Project](https://magic-me-webpage.github.io/) – [Code](https://github.com/PKU-Alignment/ID-Animator) |
| **ID-Animator: Zero-Shot Identity-Preserving Human Video Generation** | arXiv     | Apr 23 2024 | [Paper](https://arxiv.org/abs/2404.15275) – [Project](https://id-animator.github.io) – [Code](https://github.com/Zhen-Dong/Magic-Me) |
| **FantasyID: Face Knowledge Enhanced ID-Preserving Video Generation** | arXiv     | Feb 25 2025 | [Paper](https://arxiv.org/abs/2502.13995) – [Project](https://fantasy-amap.github.io/fantasy-id/) – [Code](https://github.com/Fantasy-AMAP/fantasy-id)|
| **PersonalVideo: High ID-Fidelity Video Customization without Dynamic and Semantic Degradation** | arXiv     | Mar 16 2025 | [Paper](https://arxiv.org/pdf/2411.17048) – [Project](https://personalvideo.github.io/) –[Code](https://github.com/EchoPluto/PersonalVideo) |
| **MagicID: Hybrid Preference Optimization for ID-Consistent and Dynamic-Preserved Video Customization** | arXiv     | Mar 16 2025 | [Paper](https://arxiv.org/abs/2503.12689) – [Project](https://echopluto.github.io/MagicID-project/) –[Code](https://github.com/EchoPluto/MagicID) |


#### Pretrained Adaptation
| Title                                                        | Venue     | Date        | Links                                                        |
| ------------------------------------------------------------ | --------- | ----------- | ------------------------------------------------------------ |
| **ConsisID: Identity-Preserving Text-to-Video Generation by Frequency Decomposition** | CVPR 2025 | Nov 26 2024 | [Paper](https://arxiv.org/pdf/2411.17383) – [Code](https://github.com/PKU-YuanGroup/ConsisID) |
| **AnchorCrafter: Animate CyberAnchors Saling Your Products via Human-Object Interacting Video Generation** | arXiv     | Nov 26 2024 | [Paper](https://arxiv.org/abs/2411.17440) – [Code](https://github.com/cangcz/AnchorCrafter) |
| **Ingredients: Blending Custom Photos with Video Diffusion Transformers** | arXiv     | Jan 3 2025  | [Paper](https://arxiv.org/pdf/2501.01790?) – [Code](https://github.com/feizc/Ingredients) |
| **EchoVideo: Identity-Preserving Human Video Generation by Multimodal Feature Fusion** | arXiv     | Jan 23 2025 | [Paper](https://arxiv.org/pdf/2502.07802) – [Code](https://github.com/JeremyWV/EchoVideo) |
| **SkyReels-A1: Expressive Portrait Animation in Video Diffusion Transformers** | arXiv | Feb 15 2025 | [Paper](https://arxiv.org/pdf/2502.10841) – [Page](https://skyworkai.github.io/skyreels-a1.github.io/) - [Code](https://github.com/SkyworkAI/SkyReels-A1)|
| **Movie Weaver: Tuning-Free Multi-Concept Video Personalization with Anchored Prompts** | CVPR 2025 | Feb 4 2025 | [Paper](https://arxiv.org/abs/2501.13452) – [Page](https://jeff-liangf.github.io/projects/movieweaver/) |
| **FantasyID: Face Knowledge Enhanced ID-Preserving Video Generation** | arXiv     | Feb 25 2025 | [Paper](https://arxiv.org/abs/2502.13995) – [Project](https://fantasy-amap.github.io/fantasy-id/) – [Code](https://github.com/Fantasy-AMAP/fantasy-id)|
| **MagicID: Hybrid Preference Optimization for ID-Consistent and Dynamic-Preserved Video Customization** | arXiv     | Mar 16 2025 | [Paper](https://arxiv.org/abs/2503.12689) – [Project](https://echopluto.github.io/MagicID-project/) –[Code](https://github.com/EchoPluto/MagicID) |
| **Concat-ID: Towards Universal Identity-Preserving Video Synthesis** | arXiv     | Mar 18 2025 | [Paper](https://arxiv.org/abs/2503.14151) – [Code](https://github.com/ML-GSAI/Concat-ID) |


### ✂️ Video-Driven Editing Models

| Title                                                        | Venue | Date        | Links                                                        |
| ------------------------------------------------------------ | ----- | ----------- | ------------------------------------------------------------ |
| **IP-FaceDiff: Identity-Preserving Facial Video Editing with Diffusion** | arXiv | Jan 13 2025 | [Paper](https://arxiv.org/abs/2501.07530) – [Code](https://github.com/ThoAce/IP-FaceDiff) |



### 🎺 Audio-Driven Portrait Animation

| Title                                                        | Venue     | Date        | Links                                                        |
| ------------------------------------------------------------ | --------- | ----------- | ------------------------------------------------------------ |
| **EMO: Emote Portrait Alive -- Generating Expressive Portrait Videos with Audio2Video Diffusion Model under Weak Conditions** | ECCV 2024 | Feb 27 2024 | [Paper](https://arxiv.org/abs/2402.17485) – [Code](https://github.com/HumanAIGC/EMO) – [Page](https://humanaigc.github.io/emote-portrait-alive/) |
| **EMO2: End-Effector Guided Audio-Driven Avatar Video Generation** | ECCV 2024 | Jan 18 2025 | [Paper](https://arxiv.org/abs/2501.10687)                    |
| **SkyReels-Audio: Omni Audio-Conditioned Talking Portraits in Video Diffusion Transformers** | arXiv     | Jun 11 2025 | [Paper](https://arxiv.org/pdf/2506.00830) – [Project](https://skyworkai.github.io/skyreels-audio.github.io/) - [Code](https://github.com/SkyworkAI/SkyReels-A2) |
| **InterActHuman: Multi-Concept Human Animation with Layout-Aligned Audio Conditions** | arXiv     | Jun 11 2025 | [Paper](https://arxiv.org/pdf/2506.09984) – [Project](https://zhenzhiwang.github.io/interacthuman/) |

### 🕺 Pose-Driven Full-Body Animation

| Title                                                        | Venue     | Date        | Links                                                        |
| ------------------------------------------------------------ | --------- | ----------- | ------------------------------------------------------------ |
| **Follow Your Pose: Pose-Guided Text-to-Video Generation using Pose-Free Videos** | AAAI 2024 | Apr 3 2023 | [Paper](https://arxiv.org/abs/2304.01186) – [Code](https://github.com/mayuelala/FollowYourPose) – [Page](https://follow-your-pose.github.io/) |
| **DreamPose: Fashion Image-to-Video Synthesis via Stable Diffusion** | ICCV 2023 | Apr 12 2023 | [Paper](https://arxiv.org/pdf/2304.06025) – [Code](https://github.com/johannakarras/DreamPose) – [Page](https://grail.cs.washington.edu/projects/dreampose/) |
| **DisCo: Disentangled Control for Realistic Human Dance Generation** | CVPR 2024 | Jun 30 2023 | [Paper](https://arxiv.org/abs/2307.00040) – [Code](https://github.com/Wangt-CN/DisCo) – [Page](https://disco-dance.github.io/) |
| **MagicPose: Realistic Human Poses and Facial Expressions Retargeting with Identity-aware Diffusion** | ICML 2024 | Nov 18 2023 | [Paper](https://arxiv.org/abs/2311.12052) – [Code](https://github.com/Boese0601/MagicDance) – [Page](https://boese0601.github.io/magicdance/) |
| **MagicAnimate: Temporally Consistent Human Image Animation using Diffusion Model** | CVPR 2024 | Nov 27 2023 | [Paper](https://arxiv.org/abs/2311.16498) – [Code](https://github.com/magic-research/magic-animate) – [Page](https://showlab.github.io/magicanimate/) |
| **Animate Anyone: Consistent and Controllable Image-to-Video Synthesis for Character Animation** | CVPR 2024 | Nov 28 2023 | [Paper](https://arxiv.org/abs/2311.17117) – [Code](https://github.com/HumanAIGC/AnimateAnyone) – [Page](https://humanaigc.github.io/animate-anyone/) |
| **MimicMotion: High-Quality Human Motion Video Generation with Confidence-aware Pose Guidance** | ICML 2025 | Jun 28 2024 | [Paper](https://arxiv.org/abs/2406.19680) – [Code](https://github.com/tencent/MimicMotion) – [Page](https://tencent.github.io/MimicMotion/) |
| **MIMO: Controllable Character Video Synthesis with Spatial Decomposed Modeling** | CVPR 2025 | Sep 24 2024 | [Paper](https://arxiv.org/abs/2409.16160v2) – [Code](https://github.com/menyifang/MIMO) – [Page](https://menyifang.github.io/projects/MIMO/index.html) |
| **DisPose: Disentangling Pose Guidance for Controllable Human Image Animation** | ICLR 2025 | Dec 12 2024 | [Paper](https://arxiv.org/abs/2412.09349) – [Code](https://github.com/lihxxx/DisPose) - [Page](https://lihxxx.github.io/DisPose/) |
| **Consistent Human Image and Video Generation with Spatially Conditioned Diffusion** | arXiv | Dec 19 2024 | [Paper](https://arxiv.org/abs/2412.14531) – [Code](https://github.com/ljzycmd/scd) |
| **DirectorLLM for Human-Centric Video Generation** | arXiv | Dec 19 2024 | [Paper](https://arxiv.org/pdf/2412.14484) |
| **Animate Anyone 2: High-Fidelity Character Image Animation with Environment Affordance** | arXiv | Feb 10 2025 | [Paper](https://arxiv.org/abs/2502.06145)  – [Page](https://humanaigc.github.io/animate-anyone-2/) |


### 🔄 Unified Generation and Editing Models 

| Title                                                        | Venue        | Date        | Links                                                        |
| ------------------------------------------------------------ | ------------ | ----------- | ------------------------------------------------------------ |
| **FullDiT: Multi-Task Video Generative Foundation Model with Full Attention**                        | arXiv | Mar 25 2025 | [Paper](https://arxiv.org/pdf/2503.19907) – [Project](https://fulldit.github.io/) |
| **HunyuanVideo-HOMA: Generic Human-Object Interaction in Multimodal Driven Human Animation**                        | arXiv | Jun 10 2025 | [Paper](https://arxiv.org/pdf/2506.08797) – [Project](https://anonymous.4open.science/w/homa-page-0FBE/) |

## 💼 Commercial Personalized Video Generation Models

- [Pika](https://pika.art/)
- [Kling](https://app.klingai.com/)
- [Veo](https://deepmind.google/models/veo/)
- [Vidu](http://vidu.cn/)
- [Hailuo](https://hailuoai.video/)
- [Runway-Gen1](https://runwayml.com/)
- [Luma](https://lumalabs.ai/)

## Long Video Video Customization (> 5min)

| Title                                                        | Venue        | Date        | Links                                                        |
| ------------------------------------------------------------ | ------------ | ----------- | ------------------------------------------------------------ |
| **Vlogger: Make Your Dream A Vlog**  | CVPR 2024 | Jan 17 2024 | [Paper](https://arxiv.org/pdf/2401.09414) – [Code](https://github.com/zhuangshaobin/Vlogger) |


## 📈 Evaluation

### 📊 Personalized Video Generation Benchmarks

#### Subject-to-Video Benchmarks

| Title / Benchmark                                            | Venue                 | Date        | Links                                                        |
| ------------------------------------------------------------ | --------------------- | ----------- | ------------------------------------------------------------ |
| **ConsisID-Bench** – 150 identities & 90 prompts (human-domain) | CVPR 2025 (Highlight) | Nov 2024    | [Project](https://pku-yuangroup.github.io/ConsisID) – [Data](https://huggingface.co/datasets/PKU-YuanGroup/ConsisID-Bench) |
| **MSRVTT-Personalization** (Alchemist-Bench) – Multi-subject personalization benchmark | CVPR 2025             | Jan 2025    | [Paper](https://arxiv.org/abs/2501.06187) – [Data/Code](https://github.com/snap-research/open-set-video-personalization) |
| **VACE-Benchmark**  – VACE: All-in-One Video Creation and Editing | arXiv 2025            | Mar 2025    | [Paper](https://arxiv.org/abs/2503.07598) – [Data/Code](https://huggingface.co/datasets/ali-vilab/VACE-Benchmark) |
| **FullBench** - FullDiT: Multi-Task Video Generative Foundation Model with Full Attention | arXiv | Mar 25 2025 | [Paper](https://arxiv.org/pdf/2503.19907) – [Data](https://huggingface.co/datasets/KwaiVGI/FullBench) |
| **A2 Bench** – “Elements-to-Video” evaluation benchmark for arbitrary subjects | arXiv                 | Apr 2025    | [Paper](https://arxiv.org/abs/2504.02436) – [Data/Code](https://github.com/SkyWorkAI/skyreels-a2) |
| **OpenS2V-Eval** – Fine-grained S2V benchmark (180 prompts, real & synthetic) | arXiv                 | May 28 2025 | [Paper](https://arxiv.org/abs/2505.20292) – [Project](https://pku-yuangroup.github.io/OpenS2V-Nexus) – [Code](https://huggingface.co/spaces/BestWishYsh/OpenS2V-Eval) |

### 📂 Personalized Video Generation Datasets

#### Subject-to-Video Datasets

| Title / Dataset   | Venue                 | Date        | Links                                                        |
| ----------------- | --------------------- | ----------- | ------------------------------------------------------------ |
| **Any2CapIns** | Arxiv | Mar 2025 | [Paper](https://arxiv.org/abs/2503.24379) – [Project](https://sqwu.top/Any2Cap/) – [Data](https://huggingface.co/datasets/PKU-YuanGroup/ConsisID-Bench) |
| **ConsisID-Data** | CVPR 2025 (Highlight) | Oct 2024 | [Paper](https://arxiv.org/abs/2411.17440) – [Project](https://pku-yuangroup.github.io/ConsisID) – [Data](https://github.com/ChocoWu/Any2Caption) |
| **OpenS2V-5M**    | Arxiv                 | May 28 2025 | [Paper](https://arxiv.org/abs/2505.20292) – [Project](https://pku-yuangroup.github.io/OpenS2V-Nexus) – [Data](https://huggingface.co/datasets/BestWishYsh/OpenS2V-5M) |

### 📏 Key Evaluation Metrics

## 👍 Acknowledgement

* [Awesome Personalization](https://github.com/zhangxulu1996/awesome-personalization)

* [Awesome-Personalized-Image-Generation](https://github.com/csyxwei/Awesome-Personalized-Image-Generation)

* [Awesome-Video-Diffusion](https://github.com/showlab/Awesome-Video-Diffusion)

* [Awesome-Controllable-Video-Generation](https://github.com/mayuelala/Awesome-Controllable-Video-Generation?tab=readme-ov-file#---personalized--motion)

  

# A curated list of papers on **long-form video generation**.

Long-form video generation requires video models to produce multiple semantically coherent video segments while maintaining the ability to generate extended content.   
However, existing video foundation models are typically limited to short durations (around the 10-second level). This limitation arises because, under the DiT architecture, computational complexity grows rapidly with video length.   
Researchers have explored various approaches to circumvent this constraint, and this repository provides a curated summary of these methods.

## 📚 Table of Contents
1. [Survey & Overview](#1-survey--overview)
2. [Attention Mechanism Innovations](#2-attention-mechanism-innovations)
3. [Segmented Generation for Long-Form Videos](#3-segmented-generation-for-long-form-videos)
4. [Keyframe-Based Long Video Generation](#4-keyframe-based-long-video-generation)
5. [Training-free Long Videos Generation](#5-training-free-Long-Videos-Generation)
6. [AR Long Videos Generation](#6-ar-Long-Videos-Generation)
7. [Controllable Generation for Long-Form Videos](#7-controllable-generation-for-long-form-videos)
8. [Evaluation Metrics for Long Video](#8-evaluation-metrics-for-long-video)

---

## 1. Survey & Overview
- **Generative AI for Film Creation: A Survey of Recent Advances**  
  *Year:* 2024  [📄 Paper](https://arxiv.org/abs/2504.08296)
  
- **A Survey on Long-Video Storytelling Generation: Architectures, Consistency, and Cinematic Quality**  
  *Year:* 2025  [📄 Paper](https://arxiv.org/pdf/2507.07202)
  
---

## 2. Attention Mechanism Innovations
*Breaking the quadratic bottleneck in Transformers for long-form video generation.*

As mentioned earlier, the main reason why video generation length is difficult to **scale up** lies in the quadratic time complexity of Transformers. Consequently, a series of methods have been proposed to address this limitation.

- **Mixture of Contexts for Long Video Generation**  
  *Year:* 2025  [📄 Paper](https://arxiv.org/abs/2508.21058) | [💻 Code]()  | [🌐 Project](https://primecai.github.io/moc/)
  
- **Long Context Tuning for Video Generation**  
  *Year:* 2025  [📄 Paper](https://arxiv.org/abs/2503.10589) | [🌐 Project](https://guoyww.github.io/projects/long-context-video/)

- **One-Minute Video Generation with Test-Time Training**  
  *Year:* 2025  [📄 Paper](https://arxiv.org/abs/2504.05298) | [💻 Code](https://github.com/test-time-training/ttt-video-dit)  | [🌐 Project](https://test-time-training.github.io/video-dit/)

- **History-Guided Video Diffusion**  
  *Year:* 2025  [📄 Paper](https://arxiv.org/abs/2502.06764) | [💻 Code](https://github.com/kwsong0113/diffusion-forcing-transformer)  | [🌐 Project](https://www.boyuan.space/history-guidance/)

- **TODO**  
  *Year:* 2025  [📄 Paper]() | [💻 Code]()  | [🌐 Project]()
  
---

## 3. Segmented Generation for Long-Form Videos

- **TokensGen: Harnessing Condensed Tokens for Long Video Generation**  
  *Year:* 2025  [📄 Paper](https://arxiv.org/abs/2507.15728) | [💻 Code](https://github.com/Vicky0522/TokensGen) | [🌐 Project](https://vicky0522.github.io/tokensgen-webpage/)

- **AnimeShooter: A Multi-Shot Animation Dataset for Reference-Guided Video Generation**  
  *Year:* 2025  [📄 Paper](https://arxiv.org/abs/2506.03126) | [💻 Code](https://github.com/qiulu66/Anime-Shooter?tab=readme-ov-file)  | [🌐 Project](https://qiulu66.github.io/animeshooter/)

- **VideoRAG: Retrieval-Augmented Generation with Extreme Long-Context Videos**  
  *Year:* 2025  [📄 Paper](https://arxiv.org/abs/2502.01549) | [💻 Code](https://github.com/HKUDS/Vimo)
  
- **TALC: Time-Aligned Captions for Multi-Scene Text-to-Video Generation**  
  *Year:* 2024  [📄 Paper](https://arxiv.org/abs/2405.04682) | [💻 Code](https://github.com/Hritikbansal/talc)  | [🌐 Project](https://talc-mst2v.github.io/)

- **Mora: More like Sora for Generalist Video Generation**  
  *Year:* 2024  [📄 Paper](https://arxiv.org/abs/2403.13248) | [💻 Code](https://github.com/lichao-sun/Mora)  | [🌐 Project](https://llizhaoxu.github.io/moraframework/)
  
- **Vlogger: Make your dream a vlog**  
  *Year:* 2024  [📄 Paper](https://arxiv.org/abs/2401.09414) | [💻 Code](https://github.com/Vchitect/Vlogger)  | [🌐 Project](https://zhuangshaobin.github.io/Vlogger.github.io/)
  
- **VideoDirectorGPT: Consistent Multi-scene Video Generation via LLM-Guided Planning**  
  *Year:* 2023  [📄 Paper](https://arxiv.org/abs/2309.15091) | [🌐 Project](https://videodirectorgpt.github.io/)  

- **Animate-A-Story: Storytelling with Retrieval-Augmented Video Generation**  
  *Year:* 2023  [📄 Paper](https://arxiv.org/abs/2307.06940) | [💻 Code](https://github.com/AILab-CVC/Animate-A-Story)  | [🌐 Project](https://ailab-cvc.github.io/Animate-A-Story/)



---

## 4. Keyframe-Based Long Video Generation

- **Captain Cinema: Towards Short Movie Generation**  
  *Year:* 2025  [📄 Paper](https://arxiv.org/abs/2507.18634) | [🌐 Project](https://thecinema.ai/)

- **VideoAuteur: Towards Long Narrative Video Generation**  
  *Year:* 2025  [📄 Paper](https://arxiv.org/abs/2501.06173) | [💻 Code](https://github.com/lambert-x/VideoAuteur)  | [🌐 Project](https://videoauteur.github.io/)

- **MOVIEDREAMER: HIERARCHICAL GENERATION FOR COHERENT LONG VISUAL SEQUENCES**  
  *Year:* 2024  [📄 Paper](https://arxiv.org/abs/2407.16655) | [💻 Code](https://github.com/aim-uofa/MovieDreamer)| [🌐 Project](https://aim-uofa.github.io/MovieDreamer/)
   
- **STORYDIFFUSION: CONSISTENT SELF-ATTENTION FOR LONG-RANGE IMAGE AND VIDEO GENERATION**  
  *Year:* 2024  [📄 Paper](https://arxiv.org/abs/2405.01434) | [💻 Code](https://github.com/HVision-NKU/StoryDiffusion)  | [🌐 Project](https://storydiffusion.github.io/)

- **VideoStudio: Generating Consistent-Content and Multi-Scene Videos**  
  *Year:* 2024  [📄 Paper](https://arxiv.org/abs/2401.01256) | [💻 Code](https://github.com/FuchenUSTC/VideoStudio)  | [🌐 Project](https://vidstudio.github.io/)

- **VideoGen-of-Thought: Step-by-step generating multi-shot video with minimal manual intervention**  
  *Year:* 2025  [📄 Paper](https://arxiv.org/abs/2412.02259) | [💻 Code](https://github.com/DuNGEOnmassster/VideoGen-of-Thought)  | [🌐 Project](https://cheliosoops.github.io/VGoT/)

- **HoloCine: Holistic Generation of Cinematic Multi-Shot Long Video Narratives**  
  *Year:* 2025  [📄 Paper](https://arxiv.org/abs/2510.20822) | [💻 Code](https://github.com/yihao-meng/HoloCine)  | [🌐 Project](https://holo-cine.github.io/)

---

## 5. Training-free Long Videos Generation

- **Ouroboros-Diffusion: Exploring Consistent Content Generation in Tuning-free Long Video Diffusion**  
  *Year:* 2025  [📄 Paper](https://arxiv.org/abs/2501.09019)

- **RIFLEx: A Free Lunch for Length Extrapolation in Video Diffusion Transformers**
  *Year:* 2024  [📄 Paper](https://arxiv.org/abs/2502.15894) | [💻 Code](https://github.com/thu-ml/RIFLEx)  | [🌐 Project](https://riflex-video.github.io/)

---

## 6. AR Long Videos Generation

- **History-Guided Video Diffusion**  
  *Year:* 2025  [📄 Paper](https://arxiv.org/abs/2502.06764) | [💻 Code](https://github.com/kwsong0113/diffusion-forcing-transformer)  | [🌐 Project](https://www.boyuan.space/history-guidance/)

- **Self Forcing: Bridging the Train-Test Gap in Autoregressive Video Diffusion**  
  *Year:* 2025  [📄 Paper](https://arxiv.org/abs/2506.08009) | [💻 Code](https://github.com/guandeh17/Self-Forcing)  | [🌐 Project](https://self-forcing.github.io/)

- **Packing Input Frame Context in Next-Frame Prediction Models for Video Generation**  
  *Year:* 2025  [📄 Paper](https://arxiv.org/abs/2504.12626) | [💻 Code](https://github.com/lllyasviel/FramePack)  | [🌐 Project](https://lllyasviel.github.io/frame_pack_gitpage/)

- **WorldWeaver: Generating Long-Horizon Video Worlds via Rich Perception**  
  *Year:* 2025  [📄 Paper](https://arxiv.org/pdf/2508.15720) | [💻 Code]()  | [🌐 Project](https://johanan528.github.io/worldweaver_web/)

- **TODO**  
  *Year:* 2025  [📄 Paper]() | [💻 Code]()  | [🌐 Project]()
  
---

## 7. Controllable Generation for Long-Form Videos

- **ConsistDream: Maintaining Scene Consistency in Long Video Generation**  
  *Year:* 2023  
  [📄 Paper](link) | [💻 Code](link)  
  *Summary:* Ensures temporal and spatial consistency across multiple shots.

---

## 8. Evaluation Metrics for Long Video
- **LVG-Bench: Benchmark for Long Video Generation**  
  *Year:* 2024  
  [📄 Paper](link) | [🌐 Project](link)  
  *Summary:* Standardized benchmarks for evaluating long video generation.

---

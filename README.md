# A curated list of papers on **long-form video generation**.

Long-form video generation requires video models to produce multiple semantically coherent video segments while maintaining the ability to generate extended content.   
However, existing video foundation models are typically limited to short durations (around the 10-second level). This limitation arises because, under the DiT architecture, computational complexity grows rapidly with video length.   
Researchers have explored various approaches to circumvent this constraint, and this repository provides a curated summary of these methods.

## 📚 Table of Contents
1. [Survey & Overview](#survey--overview)
2. [Story-to-Video Generation](#story-to-video-generation)
3. [Text-to-Long-Video Generation](#text-to-long-video-generation)
4. [Image-to-Long-Video / Video Extension](#image-to-long-video--video-extension)
5. [Consistency & Scene Transition](#consistency--scene-transition)
6. [Evaluation Metrics for Long Video](#evaluation-metrics-for-long-video)

---

## 1. Survey & Overview
- **Generative AI for Film Creation: A Survey of Recent Advances**  
  *Year:* 2024 
  [📄 Paper](https://arxiv.org/abs/2504.08296) 

---

## 2. Attention Mechanism Innovations
*Breaking the quadratic bottleneck in Transformers for long-form video generation.*

As mentioned earlier, the main reason why video generation length is difficult to **scale up** lies in the quadratic time complexity of Transformers. Consequently, a series of methods have been proposed to address this limitation.

- **Long Context Tuning for Video Generation**  
  *Year:* 2025  
  [📄 Paper](https://arxiv.org/abs/2503.10589) | [🌐 Project](https://guoyww.github.io/projects/long-context-video/)


---

## 3. Text-to-Long-Video Generation
- **VideoPoet: A Large Language Model for Zero-Shot Video Generation**  
  *Year:* 2023  
  [📄 Paper](https://arxiv.org/abs/2312.14125) | [🌐 Project](https://videopoet.github.io/)  
  *Summary:* Uses LLMs for zero-shot text-to-video generation.

---

## 4. Image-to-Long-Video / Video Extension
- **Image2VideoXL: Extending Single Images into Minute-Long Videos**  
  *Year:* 2023  
  [📄 Paper](link) | [💻 Code](link)  
  *Summary:* Extends a single image into a coherent long video.

---

## 5. Consistency & Scene Transition
- **ConsistDream: Maintaining Scene Consistency in Long Video Generation**  
  *Year:* 2023  
  [📄 Paper](link) | [💻 Code](link)  
  *Summary:* Ensures temporal and spatial consistency across multiple shots.

---

## 6. Evaluation Metrics for Long Video
- **LVG-Bench: Benchmark for Long Video Generation**  
  *Year:* 2024  
  [📄 Paper](link) | [🌐 Project](link)  
  *Summary:* Standardized benchmarks for evaluating long video generation.

---

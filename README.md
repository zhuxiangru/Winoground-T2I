# A Contrastive Compositional Benchmark for Text-to-Image Synthesis: A Study with Unified Text-to-Image Fidelity Metrics

Xiangru Zhu<sup>1</sup>, Penglei Sun<sup>2</sup>, Chengyu Wang<sup>3</sup>, Jingping Liu<sup>4</sup>, Zhixu Li<sup>1</sup>, Yanghua Xiao<sup>1</sup>, Jun Huang<sup>3</sup>

<sup>1</sup>Fudan University, <sup>2</sup>The Hong Kong University of Science and Technology (Guangzhou),
<sup>3</sup>Alibaba Group, <sup>4</sup>East China University of Science and Technology

[Paper](https://arxiv.org/abs/2312.02338)

<img src="https://github.com/zhuxiangru/Winoground-T2I/blob/main/figures/figure1.png" alt="Failed cases on Stable Diffusion XL 1.0" width="300" title="Failed cases on Stable Diffusion XL 1.0" />

<!-- ![Failed cases on Stable Diffusion XL 1.0](https://github.com/zhuxiangru/Winoground-T2I/blob/main/figures/figure1.png) -->

<!-- ![The pipeline of data collection, quality control and labeling](https://github.com/zhuxiangru/Winoground-T2I/blob/main/figures/figure2.png) -->

<!-- ![Statistics of categories](https://github.com/zhuxiangru/Winoground-T2I/blob/main/figures/figure3.png) -->

![Evaluation results from SDXL and IF](https://github.com/zhuxiangru/Winoground-T2I/blob/main/figures/figure4.png)

# Updates

- ✅ Winoground-T2I Dataset and Templates
- ⬜ Images Generated (7 Benchmarks) and T2I Fidelity Metric Results (9 Metrics)
- ⬜ Code for Data Collection
- ⬜ Code for Evaluating the Reliability of Metrics from 4 Perspectives
- ⬜ Results of Human Evaluation and Code for the Annotation Interface
- ⬜ Code for the improved version of LLMs with self-verification 

# Dataset

Winoground-T2I Dataset: data/dataset/

Templates: data/template/

# Acknowledgments

We makes use of several T2I fidelity metrics to evaluate T2I synthesis models. 

- [CLIPScore/BLIP-ITM/ImageReward](https://github.com/THUDM/ImageReward)
- [PickScore](https://github.com/yuvalkirstain/PickScore)
- [VPEval](https://github.com/aszala/VPEval)
- [TIFA](https://github.com/Yushi-Hu/tifa)
- [DSG](https://github.com/j-min/DSG)
- [MiniGPT4-CoT](https://github.com/Karine-Huang/T2I-CompBench)
- [LLMScore](https://github.com/YujieLu10/LLMScore)


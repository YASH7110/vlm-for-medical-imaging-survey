

# Recent Progress in Vision–Language Models for Medical Imaging: A Comprehensive Survey

<div align="center">

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<img width="1408" height="768" alt="Firefly_GeminiFlash" src="https://github.com/user-attachments/assets/421a45c2-f9c1-4d9f-86a1-2806d7e95345" />







[![Last Updated](https://img.shields.io/badge/Last%20Updated-2025-red)](https://github.com/yourusername/VLM-Medical-Imaging-Survey)

</div>

> A curated and structured collection of resources on **Vision–Language Models (VLMs) for Medical Imaging**, with a focus on Medical Visual Question Answering (Med-VQA), Report Generation, Segmentation, and Foundation Models.  
> Papers are sourced from top venues: **IEEE TMI, NeurIPS, CVPR, ECCV, MICCAI, Frontiers in AI, arXiv** (post-2023).

---

##  Table of Contents

- [Survey Papers](#-survey-papers)
- [Medical VQA](#-medical-vqa)
- [Report Generation](#-report-generation)
- [Foundation Models](#-foundation-models)
- [Datasets & Benchmarks](#-datasets--benchmarks)
- [Evaluation Metrics](#-evaluation-metrics)
- [Open Challenges](#-open-challenges)
- [Citation](#-citation)


---


---

##  Survey Papers
## 📄 Survey Papers

| Title | Venue | Year |
|-------|-------|------|
| [Vision-Language Models for Medical Report Generation and Visual Question Answering: A Review](https://doi.org/10.3389/frai.2024.1430984) | Frontiers in AI | 2024 |
| [A Survey of Medical Vision-and-Language Applications and Their Techniques](https://arxiv.org/abs/2411.12195) | arXiv:2411.12195 | 2024 |
| [Vision-Language Models in Medicine](https://arxiv.org/abs/2503.01863) | arXiv:2503.01863 | 2025 |
| [Vision-Language Models in Medical Image Analysis: From Simple Fusion to General Large Models](https://doi.org/10.1016/j.inffus.2025.102995) | Information Fusion (Elsevier Q1) | 2025 |
| [Vision-Language Foundation Model for 3D Medical Imaging](https://www.nature.com/articles/s44387-025-00015-9) | npj AI (Nature) | 2025 |
| [Large Language Model for Medical Images: A Survey of Taxonomy](https://doi.org/10.26599/BDMA.2024.9020090) | Big Data Mining and Analytics | 2025 |
| [Vision-Language Foundation Models for Medical Imaging (2022–2024)](https://pmc.ncbi.nlm.nih.gov/articles/PMC12411343/) | PMC/NIH | 2024 |
| [LViT: Language Meets Vision Transformer in Medical Image Segmentation](https://arxiv.org/abs/2206.14718) | IEEE Transactions on Medical Imaging, Vol.43(1) | 2024 |
---

##  Medical VQA

### 2.1 Closed-Ended VQA (Classification-style)

| Title | Venue | Year | Modality | Links |
|-------|-------|------|----------|-------|
| Prompting Medical LVLMs to Diagnose Pathologies by VQA | arXiv:2407.21368 | 2024/2025 | CXR | [Paper](https://arxiv.org/abs/2407.21368) |
| GeMeX: A Large-Scale, Groundable, Explainable Med-VQA Benchmark | arXiv:2411.16778 | 2024 | Chest X-Ray | [Paper](https://arxiv.org/abs/2411.16778) |
| SLAKE: Semantically-Labeled Knowledge-Enhanced Dataset for Med-VQA | IEEE ISBI | 2021 | Multi-modal | [Paper](https://arxiv.org/abs/2102.09542) |
| Alignment, Mining and Fusion for Medical VQA | **CVPR** | 2025 | CXR/Multi-modal | [Paper](https://openaccess.thecvf.com/CVPR2025) |
| BiomedCoOp: Learning to Prompt for Biomedical Vision-Language Models | **CVPR** | 2025 | Multi-modal | [Paper](https://openaccess.thecvf.com/CVPR2025) |
| Bringing CLIP to the Clinic: Dynamic Soft Labels and Negation-Aware Learning | **CVPR** | 2025 | CXR | [Paper](https://openaccess.thecvf.com/CVPR2025) |

### 2.2 Open-Ended / Generative VQA

| Title | Venue | Year | Modality | Links |
|-------|-------|------|----------|-------|
| Targeted Visual Prompting for Medical VQA | arXiv:2408.03043 | 2024 | Radiology | [Paper](https://arxiv.org/abs/2408.03043) |
| AMANDA: Agentic Medical Knowledge Augmentation for VQA | EMNLP Findings | 2025 | Multi-modal | [Paper](https://aclanthology.org/2025.findings-emnlp.1350.pdf) |
| PMC-VQA: Visual Instruction Tuning for Medical VQA | arXiv | 2023 | Multi-modal | [Paper](https://arxiv.org/abs/2305.10415) |

### 2.3 Region-Grounded VQA

| Title | Venue | Year | Modality | Links |
|-------|-------|------|----------|-------|
| HEAL-MedVQA: Hallucination Evaluation via Localization | arXiv:2505.00744 | 2025 | Radiology | [Paper](https://arxiv.org/abs/2505.00744) |
| Localizing Before Answering: LobA Framework | arXiv | 2025 | CXR/Pathology | [Paper](https://arxiv.org/abs/2505.00744) |
| Dual Modality Prompt Learning for VQA in Robotic Surgery | Visual Computing | 2024 | Surgical | [Paper](https://doi.org/10.1007/s42979-024-02705-4) |
| MIMO: Medical VLM with Visual Referring Multimodal Input & Pixel Grounding Output | **CVPR** | 2025 | Multi-organ | [Paper](https://openaccess.thecvf.com/content/CVPR2025/papers/Chen_MIMO_A_Medical_Vision_Language_Model_with_Visual_Referring_Multimodal_CVPR_2025_paper.pdf) |

### 2.4 Hallucination & Robustness in Med-VQA

| Title | Venue | Year | Links |
|-------|-------|------|-------|
| Prompting Strategies to Reduce Hallucination in MLVLMs | arXiv:2407.21368 | 2025 | [Paper](https://arxiv.org/abs/2407.21368) |
| How Easy Is It to Fool Your Multimodal LLMs? | arXiv:2402.13220 | 2024 | [Paper](https://arxiv.org/abs/2402.13220) |

---

## Report Generation

| Title | Venue | Year | Modality | Links |
|-------|-------|------|----------|-------|
| R2GenGPT: Radiology Report Generation with Frozen LLMs | arXiv | 2023 | X-ray | [Paper](https://arxiv.org/abs/2309.09812) |
| BioViL-T: Learning to Follow Instructions in Radiology | MICCAI | 2023 | CXR | [Paper](https://arxiv.org/abs/2301.04558) |
| CheXagent: Towards a Foundation Model for CXR Analysis | arXiv | 2024 | CXR | [Paper](https://arxiv.org/abs/2401.12208) |
| Enhancing VLMs for Medical Imaging (BrainMD + Vote-MI) | NeurIPS | 2024 | Brain MRI | [Paper](https://proceedings.neurips.cc/paper_files/paper/2024/file/b53513b83232116ae25f57a174a7c993-Paper-Datasets_and_Benchmarks_Track.pdf) |

---

##  Foundation Models

### Pre-training Strategies

| Title | Venue | Year | Links |
|-------|-------|------|-------|
| BioMedCLIP: Multimodal Biomedical Foundation Model | arXiv:2303.00915 | 2023 | [Paper](https://arxiv.org/abs/2303.00915) |
| PMC-CLIP: Contrastive Pre-training using Biomedical Documents | MICCAI | 2023 | [Paper](https://arxiv.org/abs/2303.07240) |
| PubMedCLIP: How Much Does CLIP Benefit Medical VQA? | EACL Findings | 2023 | [Paper](https://arxiv.org/abs/2112.13906) |
| LLaVA-Med: Training a Large Language-and-Vision Assistant | NeurIPS | 2023 | [Paper](https://arxiv.org/abs/2306.00890) |

### Fine-tuning & PEFT

| Title | Venue | Year | Links |
|-------|-------|------|-------|
| PeFoMed: Parameter Efficient Fine-Tuning of Multimodal LLMs | arXiv | 2024 | [Paper](https://arxiv.org/abs/2401.02797) |
| Med-MoE: Mixture of Domain-Specific Experts | arXiv | 2024 | [Paper](https://arxiv.org/abs/2404.10237) |
| BioMedGPT: Open Multimodal Generative Pre-trained Transformer | arXiv | 2023 | [Paper](https://arxiv.org/abs/2308.09442) |

### Zero/Few-Shot

| Title | Venue | Year | Links |
|-------|-------|------|-------|
| Med-Flamingo: A Multimodal Medical Few-shot Learner | arXiv | 2023 | [Paper](https://arxiv.org/abs/2307.15189) |
| T3D: Towards 3D Medical Image Understanding via VL Pre-training | arXiv:2312.01529 | 2023 | [Paper](https://arxiv.org/abs/2312.01529) |

---

##  Datasets & Benchmarks

| Dataset | Year | Size | Task | Modality | Link |
|---------|------|------|------|----------|------|
| VQA-RAD | 2018 | 3,515 QA pairs | Closed/Open VQA | Radiology | [Link](https://osf.io/89kps/) |
| SLAKE | 2021 | 14,000 QA pairs | Bilingual VQA | Multi-modal | [Link](https://www.med-vqa.com/slake/) |
| PathVQA | 2020 | 32,799 QA pairs | VQA | Pathology | [Link](https://github.com/UCSD-AI4H/PathVQA) |
| PMC-VQA | 2023 | 227K QA pairs | Open VQA | Multi-modal | [Link](https://arxiv.org/abs/2305.10415) |
| GeMeX | 2024 | Large-scale | Grounded VQA | CXR | [Link](https://arxiv.org/abs/2411.16778) |
| HEAL-MedVQA | 2025 | 67K QA pairs | Grounded + Hallucination | CXR/Radiology | [Link](https://arxiv.org/abs/2505.00744) |
| BrainMD | 2024 | 2,453 MRI scans | VQA + Reports | Brain MRI | [Link](https://proceedings.neurips.cc/) |
| MIMIC-CXR-JPG | 2019 | 227K images | Report Gen + VQA | CXR | [Link](https://physionet.org/content/mimic-cxr-jpg/) |
| CheXpert | 2019 | 224K images | Classification + VQA | CXR | [Link](https://stanfordmlgroup.github.io/competitions/chexpert/) |

---


---

##  Citation

If you find this repository useful, please cite:

```bibtex
@article{yourlastname2025vlm_medical_survey,
  title     = {Recent Progress in Vision–Language Models for Medical Imaging: A Comprehensive Survey},
  author    = {Your Name},
  journal   = {arXiv preprint},
  year      = {2025},
  url       = {https://github.com/yourusername/VLM-Medical-Imaging-Survey}
}
```


---


---

## 📬 Contact

Maintained by **[YASH PRATAP SINGH]**  
📧 yashthakur1700@gmail.com 


---

<div align="center">
⭐ <b>Star this repo</b> if you find it useful! It helps others discover this resource. ⭐
</div>

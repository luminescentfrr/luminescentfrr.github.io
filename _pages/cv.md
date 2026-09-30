---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<div class="cv-download-links">
  <a href="{{ base_path }}/files/Tianyu_Cao_CV_2027Fall_v3.pdf" class="btn btn--primary">Download CV as PDF</a>
</div>

**Tianyu Cao** · [tianyucao@email.hbue.edu.cn](mailto:tianyucao@email.hbue.edu.cn) · [+86 159 2641 5821](tel:+8615926415821) · Wuhan, China · [GitHub](https://github.com/luminescentfrr)

Research interests: computational biology, generative modeling, representation learning, and biomedical AI.

Education
======
**Hubei University of Economics**, Wuhan, China  
Bachelor of Engineering in Artificial Intelligence · Sep 2023 – Jul 2027 (expected)  
GPA: 3.41/4.00 · Major core GPA: 3.70/4.00  
Canglong Student Scholarship, 2024, 2025, and 2026 academic years (top 15% of students)

Research Experience
======
**Research Assistant**, Hubei Key Laboratory of Digital Finance Innovation, Hubei University of Economics  
Advisor: Associate Professor Ruiheng Li · Wuhan, China

**Safety-Constrained Generative Modeling for Partial Cellular Reprogramming** · Jul 2026 – Present

- Study OSK/OSKM perturbations to balance cellular rejuvenation with cell-identity preservation and biological safety.
- Build a conditional flow-matching framework for continuous cell-state trajectories in multi-omics data and identify safe reprogramming windows.
- Formulate safety-constrained counterfactual optimization and gene-attribution analyses for plausible trajectories with minimized identity loss and risk.

**SegDrift: Prior-Guided Semantic Drifting for Medical Image Segmentation** · May 2026 – Jul 2026

- Introduced a DINOv3-guided semantic-drifting framework with a CLS calibration prior and prediction-aware hard-negative mining to address semantic inconsistencies overlooked by pixel-level losses.
- Designed a single-step conditional generative process that avoids iterative sampling while preserving semantic consistency. Accepted at IEEE BIBM 2026.

**Cold-Start Active Learning for Unlabeled Data** · Mar 2026 – Present

- Proposed MACS for high-value sample selection in cold-start active learning without labeled data.
- Used C-RADIOv4 to extract semantic, structural, and segmentation-related information in one forward pass; modeled uncertainty through cross-space inconsistency and multi-resolution features.
- Developed adaptive clustering and non-uniform budget allocation for informative sample selection under limited annotation budgets.

**Federated Learning Theory** · Feb 2026 – Jun 2026

- Studied JointCloud federated learning for privacy-preserving, cross-institutional medical image segmentation and identified persistent representation drift under non-IID data despite parameter-level correction.
- Developed a representation-level account of Spectral Representation Collapse using von Neumann entropy to quantify residual performance gaps. Manuscript submitted to ICLR 2027.

**RWKV-Based Medical Image Segmentation (SegRWKV)** · Sep 2025 – Jan 2026

- Proposed an efficient dense-prediction network with a hybrid CNN–RWKV encoder and lightweight decoder for long-range dependency modeling and feature reconstruction.
- Achieved 4.8× faster inference and 4.5× lower memory usage, with DSC/F1 improvements of 4–22% over CNNs, 8–58% over Transformers, 1–8% over Mamba, and 10–27% over RWKV-UNet.
- Published in the *Journal of Computational Design and Engineering*.

**Physics-Inspired Medical Image Segmentation (EMG-UNet)** · Jun 2025 – Nov 2025

- Proposed a heat-diffusion-inspired segmentation framework with interpretable feature propagation and edge enhancement for anatomical structures and boundaries.
- Designed and evaluated an efficient encoder–decoder across multiple medical image segmentation datasets.

Selected Project
======
**MultiAgent-Based CodeReviewer** · Mar 2026 – Jul 2026

- Built an AI-powered desktop application for multi-file code review and conversational repair using six LangGraph expert agents coordinated for issue deduplication and conflict resolution.
- Integrated Tree-sitter project analysis, cross-file symbol search, static analysis, test execution, automated editing, and rollback with a FastAPI/SSE backend and Electron interface.
- [GitHub profile](https://github.com/luminescentfrr)

Publications
======
<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

Competitions
======
- Honorable Mention, Mathematical Contest in Modeling / Interdisciplinary Contest in Modeling (MCM/ICM) · May 2025
- Third Prize (provincial level), Blue Bridge Cup (Software Competition) · May 2025
- Second Prize (provincial level), Chinese Collegiate Computing Competition · May 2026

Technical Skills
======
- **Machine Learning:** PyTorch, MONAI, nnU-Net, MMCV, generative modeling, representation learning, OpenCLIP, DINOv3, C-RADIOv4
- **Scientific Computing:** Python, C, NumPy, Pandas, Scanpy, AnnData
- **Systems and Development:** Linux, FastAPI, Electron, LangGraph, Tree-sitter, LaTeX

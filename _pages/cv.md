---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======

* **Ph.D.**, Pattern Recognition & Intelligence Systems, Beihang University, 2020.9 -- present
* **B.S.**, Control Science & Engineering, Beihang University, 2016.9 -- 2020.6

Research Interest
======

* Probabilistic and generative modeling for high-dimensional biological data
* Continuous and structured representations of spatial and single-cell systems
* Scalable learning frameworks for integrating multi-modal and partially observed data

Publications and Manuscripts
======

**Primary Research**

1. **Bohan Li**†, Yue Deng*, Qionghai Dai*, et al.  
   *Tissue characterization at an enhanced resolution across spatial omics platforms with deep generative model*  
   **Nature Communications**, 15:6541 (2024)  
   [https://doi.org/10.1038/s41467-024-50837-5](https://doi.org/10.1038/s41467-024-50837-5)

2. **Bohan Li**, Feng Bao*, Yue Deng*, et al.  
   *Reconstructing isotropic-resolution spatial transcriptomics from serial sections by modeling tissue continuity*  
   Under review at Nature Methods  
   [https://doi.org/10.1101/2025.08.15.670472](https://doi.org/10.1101/2025.08.15.670472)

**Collaborative Research**

3. M. Clevenger†, **Bohan Li**†, Feng Bao*, N. Chevrier*, et al.  
   *Whole-body molecular and cellular mapping of the laboratory mouse*  
   **Cell** (2026)  
   [https://doi.org/10.1016/j.cell.2026.03.006](https://doi.org/10.1016/j.cell.2026.03.006)

† Co-first author; * Corresponding author

Research Experience
======

My research develops generative modeling frameworks to enhance the effective resolution of spatial omics data, addressing both lateral and depth-wise sparsity by reconstructing continuous molecular landscapes from discrete measurements.

### I. Lateral resolution enhancement for spatial omics (soScope)

**Advisor:** Yue Deng, Feng Bao

Proposed **soScope**, a generative framework that models spatial omics measurements as aggregated observations of latent cellular states.

* Formulated spatial aggregation within a variational inference framework
* Designed model architecture and learning objective
* Integrated histological morphology with molecular measurements in a unified probabilistic model

[https://github.com/deng-ai-lab/soScope](https://github.com/deng-ai-lab/soScope)

### II. Depth-wise resolution enhancement (isoST)

**Advisor:** Yue Deng, Feng Bao

Developed **isoST**, a generative framework that models spatial gene expression as a continuous process across tissue depth using stochastic differential equations.

* Developed continuous modeling framework based on stochastic differential equations
* Designed learning objectives for reconstruction from sparse sections
* Implemented scalable inference and reconstruction pipeline

[https://github.com/deng-ai-lab/isoST](https://github.com/deng-ai-lab/isoST)

### III. Cross-scale annotation transfer (LABEL)

**Advisor:** Feng Bao, Nicolas Chevrier

Developed **LABEL**, a framework for transferring molecular annotations from spatial transcriptomics data to histological images.

* Developed the LABEL module for cross-scale annotation transfer
* Contributed to model design and system integration
* Participated in large-scale data processing and validation

[https://github.com/chevrierlab/WMST-paper](https://github.com/chevrierlab/WMST-paper)

Academic Service
======

* Invited reviewer for *Briefings in Bioinformatics*

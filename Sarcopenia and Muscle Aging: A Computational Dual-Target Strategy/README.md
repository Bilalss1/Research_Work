# Age-Related Sarcopenia  
## A Dual-Target Computational Strategy Targeting FAK Signaling and Mitochondrial Function

**Keywords:** sarcopenia · muscle aging · FAK signaling · mitochondrial dysfunction · systems biology · computational biology · in silico modeling  protein–protein interaction

---

## Overview

**Age-related sarcopenia** is a progressive muscle-wasting condition driven by impaired mechanotransduction, mitochondrial dysfunction, oxidative stress, and disrupted protein homeostasis. Despite its clinical importance, most current interventions focus on lifestyle modification and do not directly target the underlying molecular mechanisms.

This repository presents a **computational systems biology framework** proposing a **dual-target therapeutic strategy** for sarcopenia. The study introduces a novel **TI-A–CISD3 fusion protein** designed to simultaneously restore **FAK-mediated anabolic signaling** and **mitochondrial proteostasis**.

All results are derived from **in silico modeling and network-based inference** and are intended to guide future experimental validation.

---

## Conceptual Framework

![Conceptual overview of sarcopenia targeting strategy](./figures/sarcopenia_framework.png)

**Figure:** Conceptual overview of the computational framework used in this study. All relationships shown are based on *in silico* modeling, network analysis, and pathway inference, and represent **proposed mechanisms rather than experimentally validated outcomes**.

---

## Research Rationale

Sarcopenia arises from the convergence of two major failures in aging skeletal muscle:

### 1. Loss of FAK Signaling
- Reduced mechanosensitivity and anabolic resistance  
- Impaired **PI3K–Akt–mTOR** and **MAPK** pathway activation  
- Cytoskeletal instability and reduced regenerative capacity  

### 2. Mitochondrial Dysfunction
- Reduced ATP production  
- Increased reactive oxygen species (ROS)  
- Defective mitophagy and accumulation of damaged mitochondria  

Targeting either pathway in isolation is unlikely to be sufficient. This project explores a **dual-target strategy** that addresses both extracellular signaling and intracellular metabolic dysfunction.

---

## Proposed Therapeutic Concept

### TI-A–CISD3 Fusion Protein

The fusion construct integrates two functional domains:

- **Trypsin Inhibitor A (TI-A)**  
  A plant-derived Kunitz-type protease inhibitor selected for its structural stability and ability to interact with exposed protein interfaces. In this design, TI-A is modeled to bind the integrin-associated **FAK interface**, supporting restoration of anabolic signaling.

- **CISD3**  
  A mitochondrial NEET protein involved in redox balance, iron–sulfur cluster transfer, and mitochondrial quality control. CISD3 is incorporated to preserve **mitochondrial proteostasis** and mitigate oxidative stress.

**Proposed functional outcomes:**
- Support restoration of FAK-mediated mechanotransduction  
- Enhance PI3K–Akt and MAPK signaling  
- Reduce oxidative stress  
- Improve mitochondrial quality control  

---

## Computational Methods

This study follows a fully **in silico workflow**, including:

- Gene and protein sequence retrieval (Ensembl, NCBI)  
- Physicochemical profiling (ProtParam)  
- Secondary structure prediction (PSIPRED)  
- Tertiary structure modeling (SWISS-MODEL)  
- Fusion protein assembly with flexible linker design  
- Protein–protein docking with the **FAK FERM domain**  
- Binding free energy estimation  
- Molecular dynamics simulations (GROMACS)  
- Protein–protein interaction (PPI) network analysis (STRING, Cytoscape)  
- Pathway enrichment analysis (KEGG, Gene Ontology)  

All results are **predictive** and intended to guide experimental work.

---

## Key Findings (*In Silico*)

- Stable binding of the **TI-A domain** to the FAK integrin-associated interface  
- Preservation of **CISD3 structural integrity** within the fusion construct  
- Favorable docking scores and binding energetics  
- Molecular dynamics simulations indicating conformational stability  
- Network analysis identifying **FAK as a central signaling hub**  
- Pathway enrichment supporting coordinated modulation of anabolic signaling and mitochondrial quality control  

---

## Limitations

- This work is **entirely computational**
- No *in vitro* or *in vivo* validation is included  
- Immunogenicity, delivery, and pharmacokinetics are not assessed  
- Results should be interpreted as **hypothesis-generating**, not therapeutic proof  

---

## Future Directions

- Experimental validation in myotube and aged muscle models  
- Binding kinetics studies (e.g., SPR)  
- Functional assays for FAK activation and mitochondrial health  
- Optimization of linker length and domain orientation  
- Exploration of delivery strategies  

---

**🔗 External Links**  
 - [_Read the Article on IJBR_](https://www.ijbr.com.pk/IJBR/article/view/2620)

-  [_View on Google Scholar_](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Biostatistical+Modeling+of+TI-A%E2%80%93CISD3+Fusion+to+Restore+FAK+Signaling+and++Mitochondrial+Function+in+Age-Related+Sarcopenia&btnG=)

## Citation

If you use or reference this work, please cite:

> **Shafiq, B.** *Biostatistical Modeling of TI-A–CISD3 Fusion to Restore FAK Signaling and Mitochondrial Function in Age-Related Sarcopenia.*

---

## License

This project is shared for **academic and research purposes**.  
Please contact me for reuse beyond citation or non-commercial use.

© 2025 Bilal Shafiq — All rights reserved.


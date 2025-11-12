# 🧬 Bioinformatics Project

This repository contains scripts and data analysis workflows related to my bioinformatics research.  
The project focuses on analyzing single-cell RNA sequencing (scRNA-seq) data to explore molecular differences between treatment-sensitive and treatment-resistant colorectal cancer (CRC) samples.

---

## 🧠 Objectives
- Perform quality control, normalization, and clustering of single-cell RNA-seq data.  
- Identify differentially expressed genes between treatment-sensitive and treatment-resistant samples.  
- Conduct pathway and functional enrichment analyses.  
- Characterize the tumor microenvironment composition at single-cell resolution.

---

## 🧰 Tools and Technologies
- **Python:** Scanpy, Decoupler, PyDESeq2, Pandas, NumPy, Matplotlib  
- **Salmon / Alevin:** Transcript quantification  
- **Linux:** Arch-based system for computational analysis  
- **Git:** Version control and project tracking

---

## 🧾 Dataset
- **NCBI BioProject:** [PRJNA932556](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA932556)  
  Single-cell RNA-seq dataset from colorectal cancer patients treated with anti–PD-1 immunotherapy, including both treatment-sensitive and treatment-resistant samples.

---

## 🧩 Conclusion
High **CTSE** expression in colorectal tumors (cancerous epithelial cells) is associated with reduced T-cell infiltration and diminished effector activity, suggesting an immune-evasive phenotype. CTSE is co-expressed with goblet-cell–related genes (**SPDEF**, **MUC2**, **AGR2**, **ERN2**), implicating it in mucin-mediated barrier formation that may restrict immune access and contribute to therapy resistance.  

in other studies CTSE has been shown to enhance **des-γ-carboxy prothrombin (DCP)** production by disrupting ubiquinone and vitamin K–dependent redox pathways. Elevated DCP levels, in turn, promote an immunosuppressive microenvironment by inducing T-cell exhaustion markers and apoptosis.

While both sensitive and resistant tumors contain CD8⁺ T cells with effector signatures, resistant tumors display heightened exhaustion and limited clonal expansion. 

Other differentially expressed genes, including those linked to metastasis and cell proliferation, highlight broader pathways driving tumor progression and treatment resistance.  

These findings, derived from **PRJNA932556**, suggest that CTSE-mediated mucin remodeling and DCP-driven immunosuppression may represent novel mechanisms of immune escape in treatment-resistant colorectal cancer.

---







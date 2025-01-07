---
layout: page
title: research
permalink: /projects/
subtitle: "<br>"
nav: true
nav_order: 2
---

### **Study of CD4+ T-cell subsets distribution in antigen-activated PBMC-derived CD4+ T-cells and in tumor microenvironment**

Oct 2024 - Dec 2024  
**IBCh RAS**  
**Advisor**: [Dmitriy Chudakov](https://scholar.google.ru/citations?user=eJPnGEEAAAAJ&hl=en), Danill Lukianov   

- GEX and TCR library preprocessing  
- Cell type annotation with label transfer and vertical integration with reference dataset  
- DEG identification  
- Paired scTCR-seq and scRNA-seq of atherosclerotic T-cell data analysis  

---

### **Development of an automated pipeline for quality control of immune repertoire sequencing (RepSeq kit)**

Jun 2024 - Oct 2024  
**Milaboratory**  
**Advisor**: Mikhail Myshkin  

The immune repertoire sequence refers to the diverse collection of antigen receptor sequences present in an individual's immune system, including T-cell receptors (TCRs) and B-cell receptors (BCRs). Immunosequencing reagent kits must pass quality control (QC) as one of the development stages before reaching the customer. My main goals were to create:

- Python script for running MIXCR and output processing  
- R script for results visualization  
- LATEX script for PDF report generation  
- Integration of all components in one Jupyter Notebook  

Currently I maintain key features and work on the developments.

Read More [on poster](https://SuleimanovShakir.github.io/assets/pdf/industrial_day_poster.pdf)

---

### **Study of the transcriptional activity of immunoregulatory genes in immune cells during activation of 2 types of TNF receptors in normal conditions and in rheumatoid arthritis using scRNA-seq (CITE-seq)**

Aug 2024 - Present  
**Laboratory of Immune Engineering, Sechenov University**  
**Advisor**: [Sergei V. Sennikov](https://www.researchgate.net/lab/Sergey-V-Sennikov-Lab), Alina A. Alshevskaya  

Changes in the expression levels of TNF receptors are closely associated with the pathogenesis of rheumatoid arthritis (RA). The aim of this study was to compare the expression profiles of genes and surface proteins associated with receptor activation at the single-cell level in peripheral blood mononuclear cells (PBMCs) from healthy donors and patients with RA. Another important task was to identify activatory thresholds of TNFR1 and TNFR2 and compare them between healthy donors and patients with RA.

**I have performed**:  
- GEX and ADT library preprocessing  
- Count matrices preprocessing (filtration, normalization, batch correction, modality integration)  
- Manual and automated cell type annotation
- Downstream analysis: DGA, geneset enrichment, compositional analysis, threshold identification

---

### **Investigation of Empty Droplets Detection in SUMseq**

Feb 2024 - Jul 2024  
**Bioinformatics Institute**  
**Advisor**: [Maxim Kholmatov](https://www.embl.org/people/person/maksim-kholmatov/)  

SUM-seq (Single-cell Ultra-high-throughput Multiomic sequencing) is introduced as a cost-effective and scalable sequencing technique designed for multiplexed multiomics profiling. This method enables the simultaneous profiling of chromatin accessibility and gene expression in single nuclei at an ultra-high-throughput scale, accommodating up to millions of cells and hundreds of samples. The technique refines the two-step combinatorial indexing approach, initially introduced by [Datlinger et al.](https://www.nature.com/articles/s41592-021-01153-z) for snRNA-seq, adapting it specifically for a multiomic context.

**Specific aim**: To assess the impact of uneven coverage distribution among samples on droplet classification

**Objectives**:  
1. Get familiarized with the combinatorial indexing methodology in single-cell sequencing experiments and combinatorial indexing approach
2. Evaluate the distribution of UMIs across sample indices within droplets containing more than one nucleus.
3. Visualize the joint distribution of total coverage and the proportion of UMIs originating from each sample.
4. Identify samples exhibiting consistently lower coverage levels.
5. Investigate the impact of uneven UMI distribution between nuclei from different samples on EmptyDrops output.

**I have performed**:  
- Writing core functions for quality checks, plotting, statistical analysis for benchmarking in R  
- Running empty droplets on raw data  
- Analysis of correlation between log probabilities of empty droplets with the sample coverage  

Read More [in presentation](https://SuleimanovShakir.github.io/assets/pdf/empty_droplets.pdf)  
Read More [in GitHub](https://github.com/maxim-h/bi-kho2-2024)

---

### **Identification of genes associated with immune response using open database ImmuneSpace**

Nov 2022 - Jan 2023  
**Bioinformatics Institute**  
**Advisor**: Evgeny Bakin  

Vaccination activates specific gene expression and molecular pathways, leading to immunity against pathogens, though antibody titers alone may not always reflect vaccine efficacy. This study analyzed transcriptomics data from Zostavax vaccine research to identify early transcriptional markers that predict the quality of vaccine-induced immunity, leveraging high-throughput immunological data from the ImmuneSpace database.

**The aim of our project** is to find genes with expression significantly related to the strong immune response to Zoster vaccination, as well as those biological processes which are overrepresented by these genes.

**Objectives**:  
1. Literature review on the basics of RNA transcription, process of immune response to vaccination and results of other studies realized on the same dataset.
2. Descriptive statistics for the baseline characteristics of the study participants.
3. Analysis of differential gene expression (revealing genes with expression that differs significantly between participants with the strong and weak response, before vaccination and over time after it).
4. Analysis of the relation between the probability of the strong immune response and gene expression at different time points (revealing genes with expression associated with the probability of the strong response).
5. Gathering annotations for biological processes represented by gene sets revealed at the previous two steps, listing the most represented biological processes.

**I have performed**:  
- Exploratory analysis of vaccination dataset and data cleaning and filtration  
- Identification of DEGs using pairwise comparisons with Mann-Whitney test  
- Biological interpretation from immunological prospective

Read More [in GitHub](https://github.com/SuleimanovShakir/ImmuneSpace_SDY984)

---

### **Study of functional activity of human macrophages and effect of MSC secretome on their polarization**

2021 - 2023 
**Laboratory of Clinical Smart Nanotechnologies, Sechenov University**  
**Advisor**: [Irina I. Vlasova](https://www.researchgate.net/profile/Irina-Vlasova), Natasya V. Kosheleva  

In this study we have investigated the functional activities and mechanical properties of human macrophages differentiated into four phenotypes: M0_GM (GM-CSF derived), M0_M (M-CSF derived), M1, and M2. We utilized biochemical and biophysical methods to assess radical-generating activity, phagocytic capacity, and mechanical characteristics. Findings indicate that macrophage polarization significantly influences these functions, with M1 macrophages exhibiting higher radical-generating activity and stiffness, while M2 macrophages showed enhanced phagocytic activity. 

Read More [in article](https://www.mdpi.com/1422-0067/25/3/1860)

Also, we analysed the cytokine and growth factor profiles of conditioned media from mesenchymal stromal cells (MSCs) derived from various human tissues, including adipose tissue, bone marrow, gingiva, placenta, and umbilical cord. Conditioned media from umbilical cord-derived MSCs exhibited the highest levels of cytokines and growth factors, so we aimed to understand how this secretome may influence macrophages polarizetion. Despite a predominantly pro-inflammatory cytokine profile, this conditioned media promoted anti-inflammatory (M2) polarization in human macrophages. Thus, umbilical cord-derived MSCs' conditioned media hold significant potential for modulating inflammatory responses.

Read More [in article](https://stemcellres.biomedcentral.com/articles/10.1186/s13287-023-03381-w)

**I have performed**:  
- Human PBMC isolation, differentiation, and polarization  
- Analysis of functional activity with chemiluminescence, expression of markers with flow cytometry, phagocytic activity with fluorescence and confocal microscopy  
- All statistical data analysis and fluorescence image processing  

---

### **StopCOVID Research**

2020
**Stop COVID research Team, Sechenov University**  
**Advisor**: [Daniel Munblit](https://scholar.google.co.uk/citations?user=XAmJMHoAAAAJ&hl=en)

This was a large-scale study aimed to aimed to present demographic characteristics, symptoms, comorbidities, clinical test results, outcomes, and risk factors associated with mortality in a cohort of consecutively admitted patients with COVID-19 at the Sechenov University Hospital Network in Moscow.

Read More [in article](https://academic.oup.com/cid/article/73/1/1/5920244)  
Read More [in article](https://bmcmedicine.biomedcentral.com/articles/10.1186/s12916-022-02448-4)

**I have performed**:  
- Data extraction from patient medical cards

---

### **Redox Optimization of Phagocyte/Scaffold Interactions in Tissue Regeneration**

2019 - 2022
**Laboratory of Clinical Smart Nanotechnologies, Sechenov University**  
**Advisor**: [Irina I. Vlasova](https://www.researchgate.net/profile/Irina-Vlasova), [Valerian E. Kagan](https://scholar.google.com/citations?user=fC2MlOEAAAAJ&hl=en)  

Implantation of biomaterials causes the local inflammatory response. Neutrophils are the first immune cells recruited at the site of tissue damage and activated to generate reactive oxygen species (ROS) and oxidants. The subject of this research was to study neutrophil activation in whole blood by two different types of scaffolds (natural and synthetic materials), and evaluate the degradation of the biomaterial by oxidizing agents released by activated neutrophils.

Read More [in article](https://www.mdpi.com/1422-0067/23/24/15468)

**I have performed**:  
- Human neutrophils isolation and purification
- Preparation of biomaterials (scaffolds) 
- Analysis of functional activity with chemiluminescence and flow cytometry
- All statistical data analysis 
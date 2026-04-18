<div align="center">

# ZEYNEP AKDENIZ · PhD

**Senior Bioinformatician · Pharma & Drug Discovery**

AI / ML &nbsp;·&nbsp; Multi-Omics &nbsp;·&nbsp; NGS &nbsp;·&nbsp; Pipeline Engineering &nbsp;·&nbsp; HPC · Reproducible Research

<br>

![](https://img.shields.io/badge/9_years_experience-111111?style=flat-square)
![](https://img.shields.io/badge/4_production_pipelines-111111?style=flat-square)
![](https://img.shields.io/badge/3_Nature--family_papers-cc0000?style=flat-square)
![](https://img.shields.io/badge/3_de_novo_genomes-111111?style=flat-square)
![](https://img.shields.io/badge/1k+_students_reached-111111?style=flat-square)

[![Email](https://img.shields.io/badge/zeynep.hitay.akdeniz%40gmail.com-111111?style=flat-square&logo=gmail&logoColor=white)](mailto:zeynep.hitay.akdeniz@gmail.com)
&nbsp;
[![GitHub](https://img.shields.io/badge/github.com/zeyak-111111?style=flat-square&logo=github&logoColor=white)](https://github.com/zeyak)
&nbsp;
[![Location](https://img.shields.io/badge/Gothenburg,_Sweden-111111?style=flat-square)](https://github.com/zeyak)

</div>

---

9 years building reproducible pipelines across Multi-Omics, NGS, and AI/ML. From HPC clusters to one-line Snakemake deploys: 4 production pipelines, 3 Nature-family papers, 3 de novo genomes assembled. Reproducible research is the difference between a result and knowledge.

---

## Publications

| Date | Journal | Title | Authors |
|---|---|---|---|
| Dec 2025 | **Nature Communications** | GlyContact analyzes glycan 3D structures at scale | Thomès · Joeres · Akdeniz · Bojar |
| Aug 2024 | **Scientific Data** | Expanded genome of *Hexamita inflata*, a free-living diplomonad | Akdeniz et al. |
| Sep 2022 | **Scientific Data** | Chromosome-scale reference genome — *Spironucleus salmonicida* | Xu · Jiménez-González · Akdeniz et al. |

---

## Projects

### [GenoDiplo](https://github.com/zeyak/GenoDiplo)

Snakemake pipeline for de novo genome assembly and annotation of diplomonad eukaryotes. Applied to *Spironucleus barkhanus*; underpins the *Hexamita inflata* Scientific Data 2024 paper. Covers raw read QC through structural and functional annotation to comparative genomics.

| Stage | Tools |
|---|---|
| Quality Control | FastQC · MultiQC · Trimmomatic |
| Assembly | Flye (Nanopore long reads) |
| Evaluation | QUAST · Meryl · Winnowmap · DeepTools |
| Structural Annotation | Prodigal · GlimmerHMM |
| Functional Annotation | DIAMOND BLASTp · eggNOG-mapper · InterProScan |
| Repeat & ncRNA | RepeatModeler · RepeatMasker · tRNAscan-SE · Barrnap |
| Comparative Genomics | CD-HIT · OrthoFinder |

![](https://img.shields.io/badge/Snakemake-111111?style=flat-square)
![](https://img.shields.io/badge/Python-111111?style=flat-square)
![](https://img.shields.io/badge/Nanopore-111111?style=flat-square)
![](https://img.shields.io/badge/Conda-111111?style=flat-square)
![](https://img.shields.io/badge/Sci._Data_2024-cc0000?style=flat-square)

---

### [CompareDiplo](https://github.com/zeyak/CompareDiplo)

Comparative genomics pipeline extending GenoDiplo across diplomonad species (free-living vs. parasitic). Clusters protein families by OrthoFinder, maps InterPro/PFAM/KEGG domains, and traces evolutionary trajectories. Revealed protein family expansions correlated with lifestyle adaptation in anaerobic environments.

![](https://img.shields.io/badge/OrthoFinder-111111?style=flat-square)
![](https://img.shields.io/badge/InterProScan-111111?style=flat-square)
![](https://img.shields.io/badge/eggNOG--mapper-111111?style=flat-square)
![](https://img.shields.io/badge/Comparative_Genomics-111111?style=flat-square)

---

### [Deep-Bio](https://github.com/zeyak/Deep-Bio)

M.Sc. thesis (Kadir Has University, 2016–2018). Applies Softmax Regression, FFNN, and LSTM to four biological and clinical datasets, benchmarking model complexity against classification accuracy.

| Dataset | Task | Softmax | FFNN |
|---|---|---|---|
| Anuran Call (15 frog species) | Multiclass classification | 78% | **95%** |
| Thyroid Patients (72k records) | Diagnostic classification | baseline | — |
| E. coli Protein Localization | Subcellular site prediction (8 classes) | baseline | — |
| HIV Cleavage Sites (6,590 sequences) | Binary classification | 81% | improved with LSTM |

![](https://img.shields.io/badge/TensorFlow-111111?style=flat-square)
![](https://img.shields.io/badge/Keras-111111?style=flat-square)
![](https://img.shields.io/badge/FFNN-111111?style=flat-square)
![](https://img.shields.io/badge/LSTM-111111?style=flat-square)
![](https://img.shields.io/badge/Clinical_Data-111111?style=flat-square)

---

### [Bioinformatics-Bootcamp](https://github.com/zeyak/Bioinformatics-Bootcamp)

Teaching materials from the Miuul Data Science Bioinformatics Bootcamp (2023–2025), 2 cohorts, 50+ graduates.

| Module | Topics |
|---|---|
| Foundations | Python · Linux · Git · Anaconda |
| Workflow Management | Snakemake — tRNA scanning, wildcards |
| Sequencing & Assembly | Nanopore · Illumina · PacBio · FASTA/GFF formats |
| Annotation | BLAST · InterProScan · IPR domains |
| Comparative Genomics | OrthoFinder · orthologs/paralogs · heatmaps · UpSet plots |
| Transposable Elements | RepeatMasker · stained glass visualisation |

![](https://img.shields.io/badge/Python-111111?style=flat-square)
![](https://img.shields.io/badge/Snakemake-111111?style=flat-square)
![](https://img.shields.io/badge/NGS-111111?style=flat-square)
![](https://img.shields.io/badge/50+_graduates-cc0000?style=flat-square)

---

### Between Data & Dreams *(in development)*

An education platform in engineering and life sciences — currently in active development. Covers bioinformatics, AI/ML, and data science for students across Turkey, Sweden, and Japan. 1,000+ students reached through bootcamps, webinars (300+ attendees), and outreach at the Stockholm Natural History Museum and Vetenskapsfestivalen, Gothenburg.

![](https://img.shields.io/badge/Education_Platform-111111?style=flat-square)
![](https://img.shields.io/badge/1k+_students-cc0000?style=flat-square)
![](https://img.shields.io/badge/In_Development-111111?style=flat-square)

---

## Pipeline Engineering

The core of my work over 9 years has been designing, building, and maintaining production-grade bioinformatics pipelines — from raw sequencing data to publishable results. Snakemake is my primary orchestration framework; every pipeline I ship is modular, conda-managed, HPC-ready, and version-controlled.

| Capability | Detail |
|---|---|
| Orchestration | Snakemake (90%) — rule graphs, wildcards, checkpoints, cluster profiles |
| Environment Management | Conda / Docker per-rule environments (88%) |
| HPC / SLURM | Job scheduling, resource allocation, parallel execution (85%) |
| Version Control | Git — structured commit history, reproducible deploys (92%) |
| Languages | Python (95%) · Bash / Linux (88%) · R (35%) |
| AI / ML Stack | TensorFlow · Keras · scikit-learn · GPU inference (82%) |
| Cloud / DevOps | Early-stage (40%) — actively expanding |

![](https://img.shields.io/badge/Snakemake_90%25-cc0000?style=flat-square)
![](https://img.shields.io/badge/Python_95%25-111111?style=flat-square)
![](https://img.shields.io/badge/HPC_/_SLURM_85%25-111111?style=flat-square)
![](https://img.shields.io/badge/Git_92%25-111111?style=flat-square)
![](https://img.shields.io/badge/Docker_/_Conda_88%25-111111?style=flat-square)

---

## Omics Exposure

```mermaid
pie title Active Research Domains
    "Genomics" : 25
    "Proteomics" : 23
    "AI / ML" : 21
    "Transcriptomics" : 17
    "Glycomics" : 14
```

---

## What I Am Curious About Next

The field is moving fast. These are the areas I am actively following, reading, and looking to contribute to next.

| Area | Why it matters |
|---|---|
| Spatial transcriptomics | Adding tissue-level coordinates to gene expression — bridging omics and morphology |
| Single-cell multi-omics | scRNA-seq, scATAC-seq, CITE-seq — resolving cell-type heterogeneity at scale |
| Multimodal AI integration | Combining genomics, proteomics, and clinical layers in unified ML models |
| Biological foundation models | DNA/protein language models (ESM, Evo, Nucleotide Transformer) for zero-shot prediction |
| Graph neural networks on omics | Protein interaction networks, metabolic graphs — structure-aware learning |
| Long-read single-cell | Nanopore/PacBio scRNA — isoform-resolved, direct RNA at single-cell resolution |
| Drug target discovery pipelines | Multi-omics integration for target ID and biomarker stratification in pharma |

![](https://img.shields.io/badge/Spatial_Transcriptomics-111111?style=flat-square)
![](https://img.shields.io/badge/Single--cell_Multi--omics-111111?style=flat-square)
![](https://img.shields.io/badge/Multimodal_AI-111111?style=flat-square)
![](https://img.shields.io/badge/Biological_Foundation_Models-111111?style=flat-square)
![](https://img.shields.io/badge/GNNs_on_Omics-111111?style=flat-square)

---

## GitHub Stats

<div align="center">

<img height="155" src="https://github-readme-stats.vercel.app/api?username=zeyak&show_icons=true&theme=graywhite&hide_border=true&count_private=true&title_color=cc0000&icon_color=111111&text_color=111111" />
&nbsp;
<img height="155" src="https://github-readme-stats.vercel.app/api/top-langs/?username=zeyak&layout=compact&theme=graywhite&hide_border=true&title_color=cc0000&text_color=111111" />

</div>

<div align="center">
<sub>Public activity reflects open teaching and research repos. Production pipelines run on institutional HPC clusters and private repositories. Current low-commit periods correspond to full-time development of Between Data & Dreams and prior teaching-intensive roles.</sub>
</div>

---

<div align="center">
<sub>Gothenburg, Sweden · ORCID available on request · Last updated April 2026</sub>
</div>

# NGS-DNA-Seq-Triple-Negative-Breast-Cancer-Variant-Analysis
## 🎯 Project Overview
Analysis of BRCA1 and BRCA2 variants using NGS bioinformatics pipeline. A total of 530 variants were detected in the  VCF file. Among these, 107 variants were classified as important frameshift, missense, splice donor variant &amp; intron variant and upstream gene variant, which may have potential biological significance. 

🧬 **BRCA1** — Chromosome 17
🧬 **BRCA2** — Chromosome 13


### 📊 Key Results

| Metric | Result |
|---|---:|
| 🔬 Total variants detected | **530** |
| ⭐ Important variants | **107** |
| 🧬 Genes analyzed | **BRCA1 & BRCA2** |
| 🧪 Data type | **NGS DNA-seq** |

The 107 important variants included **frameshift, missense, splice donor, intron, and upstream gene variants**, which may have potential biological significance.



## 🔄 NGS Bioinformatics Pipeline


        🧬 Raw NGS Reads
              │
              ▼
      📥 NCBI-SRA Download
              │
              ▼
        🔍 FastQC
      Quality Assessment
              │
              ▼
          ✂️ fastp
    Adapter & Quality Trimming
              │
              ▼
          🧭 BWA
       Read Alignment
              │
              ▼
    ⚙️ SAMtools + Picard
    Sorting & Duplicate Removal
              │
              ▼
        🧬 GATK
   Variant Calling
   ├── HaplotypeCaller
   └── Mutect2
              │
              ▼
       📝 VCF File
              │
              ▼
   🔎 Ensembl-VEP / SnpEff
      Variant Annotation
              │
              ▼
      📊 Variant Analysis
       BRCA1 & BRCA2


## 🛠️ Tools & Technologies

| Stage           | Tools               |
| --------------- | ------------------- |
| Data Retrieval  | NCBI-SRA            |
| Quality Control | FastQC              |
| Read Trimming   | fastp               |
| Alignment       | BWA                 |
| BAM Processing  | SAMtools, Picard    |
| Variant Calling | GATK                |
| Annotation      | Ensembl-VEP, SnpEff |
| Reference       | Human genome hg38   |
| Analysis        | Python / Linux      |

---

## 📈 Variant Categories

The important variants were categorized into:


Missense              ████████████████████
Frameshift             ███████████
Splice Donor           █████
Intron                 ████
Upstream Gene          █████



## 🔍 Key Findings

✨ **530 variants** were detected from the VCF file.

⭐ **107 variants** were classified into potentially important functional categories.

🧬 Variant annotation provided information about the possible effects of variants on genes and transcripts.

🎯 The analysis provides a computational starting point for investigating **BRCA1/BRCA2 variation in TNBC**.


## 📂 Project Structure


NGS-DNA-Seq-Triple-Negative-Breast-Cancer-Variant-Analysis/
│
├── 📁 raw_data/
├── 📁 quality_control/
├── 📁 trimmed_reads/
├── 📁 alignment/
├── 📁 variant_calling/
├── 📁 annotation/
├── 📁 results/
├── 📁 plots/
├── 📄 README.md
└── 📄 workflow/
```

### 🧬 From Raw Reads → Variants → Biological Insights

**NGS • Bioinformatics • Variant Calling • BRCA1 • BRCA2 • TNBC • GATK • BWA • SnpEff • Ensembl-VEP**

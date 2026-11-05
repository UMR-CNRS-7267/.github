
<picture>
  <source media="(prefers-color-scheme: dark)"
          srcset="./banner_02.PNG">
  <source media="(prefers-color-scheme: light)"
          srcset="./banner_02.PNG">
  <img src="./banner-light.svg"
       width="100%"
       alt="eBIOINF Bioinformatics Core Facility">


<h1 align="center">eBIOINF</h1>

<h3 align="center">
  BIOINFORMATICS CORE FACILITY
</h3>

<p align="center">
  <b>EBI · UMR CNRS 7267</b><br>
  Computational Biology | Omics | HPC | Data Science
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Genomics-Bioinformatics-00BCD4?style=for-the-badge">
  <img src="https://img.shields.io/badge/NGS-Analysis-009688?style=for-the-badge">
  <img src="https://img.shields.io/badge/HPC-Computing-1565C0?style=for-the-badge">
  <img src="https://img.shields.io/badge/Research-CNRS-673AB7?style=for-the-badge">
</p>

---

## 🧬 About eBIOINF

**eBIOINF** is the bioinformatics core facility of EBI,
UMR CNRS 7267.

Founded in 2012, the platform provides computational
resources, bioinformatics expertise, and analytical
support for high-throughput sequencing and omics data.

Our expertise covers:

| Domain | Expertise |
|---|---|
| 🧬 Genomics | Genome assembly, annotation and comparative genomics |
| 🦠 Metagenomics | Microbial community analysis |
| 🧪 Transcriptomics | RNA-seq and differential expression |
| 🔬 Metatranscriptomics | Functional microbial activity |
| 📊 Bioinformatics | Statistical analysis and data visualization |
| 💻 HPC | High-performance computing and workflow development |

---

## 🖥️ Computing Infrastructure

Our platform provides dedicated computational resources
for demanding bioinformatics analyses.

### Computing servers

| Infrastructure | CPU Cores | RAM | Storage | Access |
|---|---:|---:|---:|---|
| Small Node | 12 | 144 GB | 22 TB | Interactive |
| Medium Node | 24 | 265 GB | 10 TB | Interactive |
| Big Node 1 | 40 | 1 TB | 22 TB | Interactive |
| Big Node 2 |128 | 1TB  |50TB   | Interactive |

### HPC Cluster

| Resource | Specification |
|---|---:|
| Computing nodes | 8 |
| Total CPU cores | 272 |
| Shared RAM | 3 TB |
| Computing power | 13 TFLOPS |
| Storage | 20 TB |
| Job scheduler | SLURM |

### Storage & Virtualization

| Infrastructure | Specification |
|---|---|
| NAS | 28 TB |
| Backup & Archiving | 300 TB |
| Virtual Machines | On demand |

---

## 🧰 Software Catalogue

This catalogue lists bioinformatics software available on the platform. Software is provided through environment modules, Conda environments, and/or Singularity/Apptainer containers, depending on the tool.
Software is regularly maintained and updated. Availability can vary between computing nodes and environments. If a tool is not available or you need a particular version, please contact the platform administrator.

---

## 🧬 Genome assembly and reconstruction

<details>
<summary><strong>Show genome assembly tools</strong></summary>

| Software | Description | Project |
|---|---|---|
| ABySS | De novo genome assembler based on de Bruijn graphs, commonly used for short-read data. | [GitHub](https://github.com/bcgsc/abyss) |
| Canu | De novo assembler for noisy long reads, including PacBio and Oxford Nanopore data. | [GitHub](https://github.com/marbl/canu) |
| DENTIST | Tool for detecting and correcting assembly errors using long-read alignments. | [GitHub](https://github.com/ksahlin/DENTIST) |
| FMLRC2 | Hybrid error correction of long reads using accurate short reads. | [GitHub](https://github.com/hanfang/FMLRC2) |
| hifiasm | Fast assembler for PacBio HiFi reads, including phased and haplotype-resolved assemblies. | [GitHub](https://github.com/chhylp123/hifiasm) |
| MEGAHIT | Fast, memory-efficient assembler designed for large and complex metagenomic datasets. | [GitHub](https://github.com/voutcn/megahit) |
| minipolish | Polishes long-read assembly graphs using read-to-assembly alignments. | [GitHub](https://github.com/rrwick/Minipolish) |
| PECAT | Long-read genome assembly pipeline with error correction and assembly refinement. | [GitHub](https://github.com/lemene/PECAT) |
| Peregrine | Fast assembler for long, accurate sequencing reads. | [GitHub](https://github.com/cschin/Peregrine) |
| Raven | De novo genome assembler for long sequencing reads. | [GitHub](https://github.com/lbcb-sci/raven) |
| rust-mdbg | Genome assembly based on a minimizer-space de Bruijn graph approach. | [GitHub](https://github.com/ekimb/rust-mdbg) |
| Verkko | Builds high-quality, often haplotype-resolved assemblies using long-read data, particularly HiFi and ultra-long reads. | [GitHub](https://github.com/marbl/verkko) |

</details>

## 🧬 Genome annotation and repeat analysis

<details>
<summary><strong>Show annotation tools</strong></summary>

| Software | Description | Project |
|---|---|---|
| AGAT | Toolkit for parsing, converting, validating and manipulating genome annotation files such as GFF and GTF. | [GitHub](https://github.com/NBISweden/AGAT) |
| DRAM | Functional annotation and metabolic reconstruction of microbial genomes and metagenome-assembled genomes. | [GitHub](https://github.com/WrightonLabCSU/DRAM) |
| Earl Grey | Automated identification and annotation of transposable elements and other repetitive sequences in eukaryotic genomes. | [GitHub](https://github.com/TobyBaril/EarlGrey) |
| Funannotate | Genome annotation pipeline, particularly designed for fungal genomes. | [GitHub](https://github.com/nextgenusfs/funannotate) |
| Miniprot | Protein-to-genome aligner useful for identifying protein-coding genes and supporting genome annotation. | [GitHub](https://github.com/lh3/miniprot) |
| Prokka | Rapid annotation of bacterial and archaeal genome assemblies. | [GitHub](https://github.com/tseemann/prokka) |

</details>

## 📊 Genome quality control and assembly assessment

<details>
<summary><strong>Show quality-control tools</strong></summary>

| Software | Description | Project |
|---|---|---|
| BUSCO | Assesses genome, transcriptome or protein-set completeness using evolutionarily conserved single-copy orthologs. | [GitHub](https://github.com/busco-phylogenomics/BUSCO) |
| CheckM | Estimates the completeness and contamination of microbial genomes using marker genes. | [GitHub](https://github.com/Ecogenomics/CheckM) |
| CheckM2 | Estimates microbial genome quality using machine-learning-based models. | [GitHub](https://github.com/chklovski/CheckM2) |
| CheckV | Evaluates the quality and completeness of viral genomes and metagenome-derived viral sequences. | [GitHub](https://github.com/AnantharamanLab/CheckV) |
| KAT | K-mer analysis toolkit for genome assembly assessment and sequencing-data quality control. | [GitHub](https://github.com/TGAC/KAT) |
| LongQC | Quality-control and evaluation toolkit for long-read sequencing data. | [GitHub](https://github.com/yfukasawa/LongQC) |
| Merqury | Reference-free assessment of genome assemblies using k-mer analysis and high-accuracy sequencing reads. | [GitHub](https://github.com/marbl/merqury) |
| QUAST | Evaluates and compares genome assembly quality using a range of assembly statistics. | [GitHub](https://github.com/ablab/quast) |
| Smudgeplot | Estimates genome ploidy and heterozygosity patterns from k-mer frequency distributions. | [GitHub](https://github.com/KamilSJaron/smudgeplot) |

</details>

## 🦠 Metagenomics, microbiome and microbial genomics

<details>
<summary><strong>Show metagenomics and microbiome tools</strong></summary>

| Software | Description | Project |
|---|---|---|
| Bracken | Estimates taxonomic abundance from Kraken classification results. | [GitHub](https://github.com/jenniferlu717/Bracken) |
| Centrifuge | Rapid classification of metagenomic reads against large collections of reference genomes. | [GitHub](https://github.com/DaehwanKimLab/centrifuge) |
| CoverM | Calculates coverage and relative abundance of genomes or contigs in metagenomic datasets. | [GitHub](https://github.com/wwood/CoverM) |
| dRep | Dereplicates and clusters microbial genomes, including metagenome-assembled genomes (MAGs). | [GitHub](https://github.com/MrOlm/drep) |
| GTDB-Tk | Assigns bacterial and archaeal genome taxonomy using the Genome Taxonomy Database. | [GitHub](https://github.com/Ecogenomics/GTDBTk) |
| Kaiju | Classifies metagenomic sequencing reads using protein-level comparisons. | [GitHub](https://github.com/bioinformatics-centre/kaiju) |
| Kraken2 | Fast taxonomic classification of metagenomic reads using k-mer-based matching. | [GitHub](https://github.com/DerrickWood/kraken2) |
| KrakenTools | Utilities for processing, summarizing and extracting information from Kraken and Bracken results. | [GitHub](https://github.com/jenniferlu717/KrakenTools) |
| MaxBin2 | Bins metagenomic contigs into draft genomes using sequence composition and coverage information. | [GitHub](https://github.com/berkeleylab/MaxBin) |
| MetaBAT2 | Metagenomic binning tool for reconstructing microbial genomes from assembled contigs. | [GitHub](https://github.com/berkeleylab/metabat) |
| MetaPhlAn | Marker-gene-based profiling of microbial community composition and relative abundance. | [GitHub](https://github.com/biobakery/MetaPhlAn) |
| VirSorter2 | Identifies and classifies viral sequences in genomic and metagenomic data. | [GitHub](https://github.com/jiarong/VirSorter2) |
| vContact2 | Groups and classifies viral genomes using gene-sharing networks. | [Bitbucket](https://bitbucket.org/MAVERICLab/vcontact2/) |
| Whokaryote | Distinguishes eukaryotic and prokaryotic sequences in metagenomic assemblies. | [GitHub](https://github.com/JLSteenwyk/Whokaryote) |
| VSEARCH | Open-source tool for sequence searching, clustering, dereplication, chimera detection and related analyses. | [GitHub](https://github.com/torognes/vsearch) |

</details>

## 🧪 Transcriptomics and RNA-seq

<details>
<summary><strong>Show transcriptomics tools</strong></summary>

| Software | Description | Project |
|---|---|---|
| deepTools | Suite for analysis and visualization of high-throughput sequencing data, including RNA-seq and ChIP-seq. | [GitHub](https://github.com/deeptools/deepTools) |
| DADA2 | Infers exact amplicon sequence variants (ASVs) from marker-gene sequencing data. | [GitHub](https://github.com/benjjneb/dada2) |
| HTSeq | Assigns sequencing reads to genomic features, commonly for RNA-seq gene-count generation. | [GitHub](https://github.com/htseq/htseq) |
| R | Statistical computing and graphics environment, widely used for omics data analysis. | [Official website](https://www.r-project.org/) |
| SortMeRNA | Filters ribosomal RNA sequences from metatranscriptomic and other sequencing datasets. | [GitHub](https://github.com/biocore/sortmerna) |

</details>

## 🧬 Long-read sequencing: Nanopore and PacBio

<details>
<summary><strong>Show long-read sequencing tools</strong></summary>

| Software | Description | Project |
|---|---|---|
| Chopper | Filters Oxford Nanopore reads by length and quality. | [GitHub](https://github.com/wdecoster/chopper) |
| Medaka | Neural-network-based consensus polishing for Oxford Nanopore assemblies. | [GitHub](https://github.com/nanoporetech/medaka) |
| NanoPack | Collection of tools for processing, filtering and visualizing long-read sequencing data. | [GitHub](https://github.com/wdecoster/nanopack) |
| NanoPlot | Generates quality-control plots for long-read sequencing data. | [GitHub](https://github.com/wdecoster/NanoPlot) |
| NanoPolish | Signal-level analysis and polishing of Oxford Nanopore sequencing reads and assemblies. | [GitHub](https://github.com/jts/nanopolish) |
| PycoQC | Quality-control and visualization reports for Oxford Nanopore sequencing runs. | [GitHub](https://github.com/a-slide/pycoQC) |
| Porechop | Detects and trims adapters in Oxford Nanopore reads and can identify chimeric reads. | [GitHub](https://github.com/rrwick/Porechop) |
| Racon | Consensus-generation and polishing tool for long-read genome assemblies. | [GitHub](https://github.com/isovic/racon) |
| Winnowmap | Long-read mapper designed to improve mapping in repetitive genomic regions. | [GitHub](https://github.com/marbl/Winnowmap) |
| Minimap2 | Fast sequence mapper for long DNA and RNA reads and whole-genome alignments. | [GitHub](https://github.com/lh3/minimap2) |
| Sniffles | Structural-variant caller for long-read sequencing data. | [GitHub](https://github.com/fritzsedlazeck/Sniffles) |
| SVIM | Detects structural variants from long-read alignments. | [GitHub](https://github.com/eldariont/svim) |
| RagTag | Reference-guided scaffolding, correction and comparison of genome assemblies. | [GitHub](https://github.com/malonge/RagTag) |

</details>

## 🧬 Comparative genomics and phylogenetics

<details>
<summary><strong>Show comparative genomics and phylogenetics tools</strong></summary>

| Software | Description | Project |
|---|---|---|
| BEAST | Bayesian evolutionary analysis of molecular sequences, including phylogenetic inference and molecular dating. | [BEAST 1 GitHub](https://github.com/beast-dev/beast-mcmc) · [BEAST 2 GitHub](https://github.com/CompEvol/beast2) |
| ETE Toolkit | Python toolkit for manipulating, analyzing and visualizing phylogenetic trees. | [GitHub](https://github.com/etetoolkit/ete) |
| GToTree | Builds phylogenomic trees from selected conserved marker genes. | [GitHub](https://github.com/AstrobioMike/GToTree) |
| Gubbins | Detects regions of recombination in bacterial genome alignments for phylogenetic analysis. | [GitHub](https://github.com/nickjcroucher/gubbins) |
| IQ-TREE | Maximum-likelihood phylogenetic inference, model selection and branch support analysis. | [GitHub](https://github.com/iqtree/iqtree2) |
| OrthoFinder | Identifies orthogroups, orthologs and gene duplications and infers species-level phylogenetic relationships. | [GitHub](https://github.com/davidemms/OrthoFinder) |
| PhyloBayes-MPI | Bayesian phylogenetic inference using site-heterogeneous evolutionary models. | [GitHub](https://github.com/bayesiancook/phylobayesmpi) |
| MEGA | Molecular evolutionary genetics analysis, including sequence alignment, evolutionary distance estimation and phylogenetics. | [Official website](https://www.megasoftware.net/) |

</details>

## 🧫 Variant calling, population genomics and antimicrobial resistance

<details>
<summary><strong>Show variant analysis tools</strong></summary>

| Software | Description | Project |
|---|---|---|
| ABRicate | Screens assembled bacterial genomes for antimicrobial-resistance, virulence and other sequence markers using reference databases. | [GitHub](https://github.com/tseemann/abricate) |
| PoolSNP | Calls SNPs from pooled sequencing data. | [GitHub](https://github.com/capoony/PoolSNP) |
| Snippy | Rapid variant calling and core-genome alignment for bacterial genomes. | [GitHub](https://github.com/tseemann/snippy) |
| SVIM | Identifies structural variants from long-read sequencing alignments. | [GitHub](https://github.com/eldariont/svim) |
| VCFtools | Utilities for filtering, processing and analyzing VCF files and genetic variation data. | [GitHub](https://github.com/vcftools/vcftools) |
| vcflib | C++ library and command-line tools for manipulating and analyzing VCF files. | [GitHub](https://github.com/vcflib/vcflib) |
| PoolParty | Toolkit for analysis of pooled sequencing data; confirm the specific installed project before linking. | [Project search](https://github.com/search?q=PoolParty+bioinformatics&type=repositories) |

</details>

## 🧬 Genome comparison, structural variation and scaffolding

<details>
<summary><strong>Show genome comparison tools</strong></summary>

| Software | Description | Project |
|---|---|---|
| Assemblytics | Detects and characterizes structural variants from genome assembly alignments. | [GitHub](https://github.com/MariaNattestad/Assemblytics) |
| MUMmer | Suite for fast alignment and comparison of large DNA sequences and genome assemblies. | [GitHub](https://github.com/mummer4/mummer) |
| Purge_Dups | Identifies and removes haplotypic duplications from diploid genome assemblies. | [GitHub](https://github.com/dfguan/purge_dups) |
| Purge_Haplotigs | Identifies and removes redundant haplotigs from genome assemblies. | [GitHub](https://github.com/pdgenomics/purge_haplotigs) |
| RagTag | Uses a reference genome to scaffold, correct and compare genome assemblies. | [GitHub](https://github.com/malonge/RagTag) |

</details>

## 🧩 Hi-C analysis and genome scaffolding

<details>
<summary><strong>Show Hi-C tools</strong></summary>

| Software | Description | Project |
|---|---|---|
| HiC-Pro | Processes Hi-C sequencing data, including read mapping, filtering and contact-map generation. | [GitHub](https://github.com/nservant/HiC-Pro) |
| HiCStuff | Processes and visualizes Hi-C data and contact maps. | [GitHub](https://github.com/koszullab/HiC-Box) |
| HALC | Corrects long reads using information from Hi-C data. | [GitHub](https://github.com/lanlanla/halc) |
| Bandage | Interactive visualization of assembly graphs, including graphs produced by de Bruijn-graph assemblers. | [GitHub](https://github.com/rrwick/Bandage) |
| CGView | Generates circular maps and visualizations of genomes and their annotated features. | [GitHub](https://github.com/paulstothard/cgview) |

</details>

## 🧹 Read quality control, mapping and sequence utilities

<details>
<summary><strong>Show read-processing and mapping tools</strong></summary>

| Software | Description | Project |
|---|---|---|
| BWA-MEM | Aligns short sequencing reads to reference genomes. | [GitHub](https://github.com/lh3/bwa) |
| Cutadapt | Finds and removes adapters and primers from sequencing reads. | [GitHub](https://github.com/marcelm/cutadapt) |
| FastQC | Provides quality-control metrics and reports for raw sequencing reads. | [GitHub](https://github.com/s-andrews/FastQC) |
| KMC | Fast and memory-efficient k-mer counting for large sequencing datasets. | [GitHub](https://github.com/refresh-bio/KMC) |
| Mosdepth | Rapidly calculates sequencing coverage and depth across genomic regions. | [GitHub](https://github.com/brentp/mosdepth) |
| MultiQC | Aggregates and summarizes quality-control reports from many bioinformatics tools into a single report. | [GitHub](https://github.com/MultiQC/MultiQC) |
| Picard Tools | Collection of utilities for manipulating, validating and analyzing high-throughput sequencing data. | [GitHub](https://github.com/broadinstitute/picard) |
| SeqKit | Cross-platform toolkit for manipulating FASTA and FASTQ files. | [GitHub](https://github.com/shenwei356/seqkit) |

</details>

## 🧪 Data visualization and reporting

<details>
<summary><strong>Show visualization and reporting tools</strong></summary>

| Software | Description | Project |
|---|---|---|
| Bandage | Interactive visualization of genome assembly graphs. | [GitHub](https://github.com/rrwick/Bandage) |
| CGView | Circular visualization of genomes and annotated genomic features. | [GitHub](https://github.com/paulstothard/cgview) |
| MultiQC | Combines outputs from multiple analysis tools into a single interactive quality-control report. | [GitHub](https://github.com/MultiQC/MultiQC) |
| Qualimap | Quality-control and visualization tool for sequencing alignment data, including RNA-seq. | [GitHub](https://github.com/qualimap/qualimap) |

</details>

## 🧪 Sequencing simulation and reference-data retrieval

<details>
<summary><strong>Show simulation and database utilities</strong></summary>

| Software | Description | Project |
|---|---|---|
| InSilicoSeq | Simulates Illumina sequencing reads from reference genomes or metagenomic communities. | [GitHub](https://github.com/HadrienG/InSilicoSeq) |
| NCBI Datasets | Command-line interface for downloading and accessing NCBI genome, gene and sequence data. | [GitHub](https://github.com/ncbi/datasets) |
| NCBI Genome Download | Downloads genome assemblies and associated data from NCBI. | [GitHub](https://github.com/kblin/ncbi-genome-download) |

</details>

## 🌳 Other scientific and specialist tools

<details>
<summary><strong>Show additional tools</strong></summary>

| Software | Description | Project |
|---|---|---|
| BEAST | Bayesian evolutionary analysis of molecular sequences. | [BEAST website](https://beast.community/) |
| Kegg/eggNOG-related tools | Functional and pathway annotation utilities; the exact installed package name should be confirmed. | — |

</details>

## 🧰 Software environments and supporting packages

<details>
<summary><strong>Show environments and supporting software</strong></summary>

| Name in platform inventory | Description |
|---|---|
| R / R base | Statistical programming language and environment for data analysis and visualization. Multiple R installations are maintained where required by workflows. |
| HDF tools | Utilities and libraries for handling Hierarchical Data Format (HDF) files. |
| PacBio tools | PacBio-specific utilities; the exact package collection depends on the installed environment. |
| R packages (including `rgdal` and `chili`) | R packages used by specific analytical workflows. Package availability depends on the corresponding R environment. |
| Snakemake | Workflow management system for reproducible and scalable data analysis. [GitHub](https://github.com/snakemake/snakemake) |
| hicstuff | Hi-C data processing utilities. See the Hi-C section above. |
| KeggANOG | This tool KEGGaNOG makes eggNOG-mapper meet KEGG-Decoder! It parses eggNOG-mapper output, make it fit for the input to KEGG-Decoder, and then visualizes KEGG Pathways as a heatmap.[GitHub](https://github.com/ilypopv/KEGGaNOG) |

</details>

---

## 📚 Citing software

Please cite the original publication associated with each software whenever it is used in scientific work. The project documentation or repository usually provides the recommended citation.

For reproducible analyses, record the software name, version, parameters and relevant database versions used in each workflow. For software developed or maintained by eBIOINF, please also cite the corresponding repository and publication when available.

## ⚙️ Software availability and support

Bioinformatics software and tools are provided through environment modules, Conda environments, and Singularity/Apptainer containers. All software is regularly maintained and updated. If the software or tools you require are not currently installed or available, please contact the platform administrator.

---

<p align="center">
  <strong>eBIOINF · Bioinformatics Core Facility · EBI · UMR CNRS 7267</strong>
</p>
        







## 📚 Citing software

Please cite the original publication associated with each software
whenever it is used in scientific work. The project documentation or
repository usually provides the recommended citation.

For reproducible analyses, record the software name, version, parameters
and relevant database versions used in each workflow. For software
developed or maintained by eBIOINF, please also cite the corresponding
repository and publication when available.


## 🔧 Software Availability & Support

Bioinformatics software and tools are provided through environment modules, Conda environments, and Singularity/Apptainer containers. 
All software is regularly maintained and updated. If the software or tools you need aren't currently installed or available, 
contact the platform administrator to request installation.


## 🧑‍💻 In-house Development

Scripts, pipelines, and tools developed by eBIOINF.

Coming soon...

---

## 👨‍🔬 Platform Team

**Bouziane MOUMEN**:   Bioinformatics Platform Manager
**CNRS Bioinformatics Research Engineer**  

📧 bouziane.moumen[at]cnrs.fr
📧 bouziane.moumen[at]univ-poitiers.fr

**Jean-baptiste BERTHELOT**: University (SFA) IT support

📧 jean.baptiste.berthelot[at]univ-poitiers.fr

---

<p align="center">
  <img src="https://www.cnrs.fr/themes/custom/cnrs/logo.svg" height="45">
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://www.univ-poitiers.fr/wp-content/uploads/sites/10/2021/10/logo-up.svg" height="45">
</p>

<p align="center">
  <b>eBIOINF · EBI · UMR CNRS 7267</b><br>
  Bioinformatics for Life Sciences
</p>

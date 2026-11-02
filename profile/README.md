
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

## 🧬 Genome assembly and reconstruction

```{=html}
<details>
```
```{=html}
<summary>
```
`<strong>`{=html}Show genome assembly tools`</strong>`{=html}
```{=html}
</summary>
```
  ------------------------------------------------------------------------------------------------
  Software                Description             Project
  ----------------------- ----------------------- ------------------------------------------------
  ABySS                   De novo genome          [GitHub](https://github.com/bcgsc/abyss)
                          assembler based on de   
                          Bruijn graphs, commonly 
                          used for short-read     
                          data.                   

  Canu                    De novo assembler for   [GitHub](https://github.com/marbl/canu)
                          noisy long reads,       
                          including PacBio and    
                          Oxford Nanopore data.   

  DENTIST                 Tool for detecting and  [GitHub](https://github.com/ksahlin/DENTIST)
                          correcting assembly     
                          errors using long-read  
                          alignments.             

  FMLRC2                  Hybrid error correction [GitHub](https://github.com/hanfang/FMLRC2)
                          of long reads using     
                          accurate short reads.   

  hifiasm                 Fast assembler for      [GitHub](https://github.com/chhylp123/hifiasm)
                          PacBio HiFi reads,      
                          including phased and    
                          haplotype-resolved      
                          assemblies.             

  MEGAHIT                 Fast, memory-efficient  [GitHub](https://github.com/voutcn/megahit)
                          assembler designed for  
                          large and complex       
                          metagenomic datasets.   

  minipolish              Polishes long-read      [GitHub](https://github.com/rrwick/Minipolish)
                          assembly graphs using   
                          read-to-assembly        
                          alignments.             

  PECAT                   Long-read genome        [GitHub](https://github.com/lemene/PECAT)
                          assembly pipeline with  
                          error correction and    
                          assembly refinement.    

  Peregrine               Fast assembler for      [GitHub](https://github.com/cschin/Peregrine)
                          long, accurate          
                          sequencing reads.       

  Raven                   De novo genome          [GitHub](https://github.com/lbcb-sci/raven)
                          assembler for long      
                          sequencing reads.       

  rust-mdbg               Genome assembly based   [GitHub](https://github.com/ekimb/rust-mdbg)
                          on a minimizer-space de 
                          Bruijn graph approach.  

  Verkko                  Builds high-quality,    [GitHub](https://github.com/marbl/verkko)
                          often                   
                          haplotype-resolved      
                          assemblies using        
                          long-read data,         
                          particularly HiFi and   
                          ultra-long reads.       
  ------------------------------------------------------------------------------------------------

```{=html}
</details>
```
## 🧬 Genome annotation and repeat analysis

```{=html}
<details>
```
```{=html}
<summary>
```
`<strong>`{=html}Show annotation tools`</strong>`{=html}
```{=html}
</summary>
```
  ------------------------------------------------------------------------------------------------------
  Software                Description             Project
  ----------------------- ----------------------- ------------------------------------------------------
  AGAT                    Toolkit for parsing,    [GitHub](https://github.com/NBISweden/AGAT)
                          converting, validating  
                          and manipulating genome 
                          annotation files such   
                          as GFF and GTF.         

  DRAM                    Functional annotation   [GitHub](https://github.com/WrightonLabCSU/DRAM)
                          and metabolic           
                          reconstruction of       
                          microbial genomes and   
                          metagenome-assembled    
                          genomes.                

  Earl Grey               Automated               [GitHub](https://github.com/TobyBaril/EarlGrey)
                          identification and      
                          annotation of           
                          transposable elements   
                          and other repetitive    
                          sequences in eukaryotic 
                          genomes.                

  Funannotate             Genome annotation       [GitHub](https://github.com/nextgenusfs/funannotate)
                          pipeline, particularly  
                          designed for fungal     
                          genomes.                

  Miniprot                Protein-to-genome       [GitHub](https://github.com/lh3/miniprot)
                          aligner useful for      
                          identifying             
                          protein-coding genes    
                          and supporting genome   
                          annotation.             

  Prokka                  Rapid annotation of     [GitHub](https://github.com/tseemann/prokka)
                          bacterial and archaeal  
                          genome assemblies.      
  ------------------------------------------------------------------------------------------------------

```{=html}
</details>
```
## 📊 Genome quality control and assembly assessment

```{=html}
<details>
```
```{=html}
<summary>
```
`<strong>`{=html}Show quality-control tools`</strong>`{=html}
```{=html}
</summary>
```
  ---------------------------------------------------------------------------------------------------------
  Software                Description              Project
  ----------------------- ------------------------ --------------------------------------------------------
  BUSCO                   Assesses genome,         [GitHub](https://github.com/busco-phylogenomics/BUSCO)
                          transcriptome or         
                          protein-set completeness 
                          using evolutionarily     
                          conserved single-copy    
                          orthologs.               

  CheckM                  Estimates the            [GitHub](https://github.com/Ecogenomics/CheckM)
                          completeness and         
                          contamination of         
                          microbial genomes using  
                          marker genes.            

  CheckM2                 Estimates microbial      [GitHub](https://github.com/chklovski/CheckM2)
                          genome quality using     
                          machine-learning-based   
                          models.                  

  CheckV                  Evaluates the quality    [GitHub](https://github.com/AnantharamanLab/CheckV)
                          and completeness of      
                          viral genomes and        
                          metagenome-derived viral 
                          sequences.               

  KAT                     K-mer analysis toolkit   [GitHub](https://github.com/TGAC/KAT)
                          for genome assembly      
                          assessment and           
                          sequencing-data quality  
                          control.                 

  LongQC                  Quality-control and      [GitHub](https://github.com/yfukasawa/LongQC)
                          evaluation toolkit for   
                          long-read sequencing     
                          data.                    

  Merqury                 Reference-free           [GitHub](https://github.com/marbl/merqury)
                          assessment of genome     
                          assemblies using k-mer   
                          analysis and             
                          high-accuracy sequencing 
                          reads.                   

  QUAST                   Evaluates and compares   [GitHub](https://github.com/ablab/quast)
                          genome assembly quality  
                          using a range of         
                          assembly statistics.     

  Smudgeplot              Estimates genome ploidy  [GitHub](https://github.com/KamilSJaron/smudgeplot)
                          and heterozygosity       
                          patterns from k-mer      
                          frequency distributions. 
  ---------------------------------------------------------------------------------------------------------

```{=html}
</details>
```
## 🦠 Metagenomics, microbiome and microbial genomics

```{=html}
<details>
```
```{=html}
<summary>
```
`<strong>`{=html}Show metagenomics and microbiome
tools`</strong>`{=html}
```{=html}
</summary>
```
  ----------------------------------------------------------------------------------------------------------
  Software                Description             Project
  ----------------------- ----------------------- ----------------------------------------------------------
  Bracken                 Estimates taxonomic     [GitHub](https://github.com/jenniferlu717/Bracken)
                          abundance from Kraken   
                          classification results. 

  Centrifuge              Rapid classification of [GitHub](https://github.com/DaehwanKimLab/centrifuge)
                          metagenomic reads       
                          against large           
                          collections of          
                          reference genomes.      

  CoverM                  Calculates coverage and [GitHub](https://github.com/wwood/CoverM)
                          relative abundance of   
                          genomes or contigs in   
                          metagenomic datasets.   

  dRep                    Dereplicates and        [GitHub](https://github.com/MrOlm/drep)
                          clusters microbial      
                          genomes, including      
                          metagenome-assembled    
                          genomes (MAGs).         

  GTDB-Tk                 Assigns bacterial and   [GitHub](https://github.com/Ecogenomics/GTDBTk)
                          archaeal genome         
                          taxonomy using the      
                          Genome Taxonomy         
                          Database.               

  Kaiju                   Classifies metagenomic  [GitHub](https://github.com/bioinformatics-centre/kaiju)
                          sequencing reads using  
                          protein-level           
                          comparisons.            

  Kraken2                 Fast taxonomic          [GitHub](https://github.com/DerrickWood/kraken2)
                          classification of       
                          metagenomic reads using 
                          k-mer-based matching.   

  KrakenTools             Utilities for           [GitHub](https://github.com/jenniferlu717/KrakenTools)
                          processing, summarizing 
                          and extracting          
                          information from Kraken 
                          and Bracken results.    

  MaxBin2                 Bins metagenomic        [GitHub](https://github.com/berkeleylab/MaxBin)
                          contigs into draft      
                          genomes using sequence  
                          composition and         
                          coverage information.   

  MetaBAT2                Metagenomic binning     [GitHub](https://github.com/berkeleylab/metabat)
                          tool for reconstructing 
                          microbial genomes from  
                          assembled contigs.      

  MetaPhlAn               Marker-gene-based       [GitHub](https://github.com/biobakery/MetaPhlAn)
                          profiling of microbial  
                          community composition   
                          and relative abundance. 

  VirSorter2              Identifies and          [GitHub](https://github.com/jiarong/VirSorter2)
                          classifies viral        
                          sequences in genomic    
                          and metagenomic data.   

  vContact2               Groups and classifies   [Bitbucket](https://bitbucket.org/MAVERICLab/vcontact2/)
                          viral genomes using     
                          gene-sharing networks.  

  Whokaryote              Distinguishes           [GitHub](https://github.com/JLSteenwyk/Whokaryote)
                          eukaryotic and          
                          prokaryotic sequences   
                          in metagenomic          
                          assemblies.             

  VSEARCH                 Open-source tool for    [GitHub](https://github.com/torognes/vsearch)
                          sequence searching,     
                          clustering,             
                          dereplication, chimera  
                          detection and related   
                          analyses.               
  ----------------------------------------------------------------------------------------------------------

```{=html}
</details>
```
## 🧪 Transcriptomics and RNA-seq

```{=html}
<details>
```
```{=html}
<summary>
```
`<strong>`{=html}Show transcriptomics tools`</strong>`{=html}
```{=html}
</summary>
```
  --------------------------------------------------------------------------------------------------
  Software                Description             Project
  ----------------------- ----------------------- --------------------------------------------------
  deepTools               Suite for analysis and  [GitHub](https://github.com/deeptools/deepTools)
                          visualization of        
                          high-throughput         
                          sequencing data,        
                          including RNA-seq and   
                          ChIP-seq.               

  DADA2                   Infers exact amplicon   [GitHub](https://github.com/benjjneb/dada2)
                          sequence variants       
                          (ASVs) from marker-gene 
                          sequencing data.        

  HTSeq                   Assigns sequencing      [GitHub](https://github.com/htseq/htseq)
                          reads to genomic        
                          features, commonly for  
                          RNA-seq gene-count      
                          generation.             

  R                       Statistical computing   [Official website](https://www.r-project.org/)
                          and graphics            
                          environment, widely     
                          used for omics data     
                          analysis.               

  SortMeRNA               Filters ribosomal RNA   [GitHub](https://github.com/biocore/sortmerna)
                          sequences from          
                          metatranscriptomic and  
                          other sequencing        
                          datasets.               
  --------------------------------------------------------------------------------------------------

```{=html}
</details>
```
## 🧬 Long-read sequencing: Nanopore and PacBio

```{=html}
<details>
```
```{=html}
<summary>
```
`<strong>`{=html}Show long-read sequencing tools`</strong>`{=html}
```{=html}
</summary>
```
  ------------------------------------------------------------------------------------------------------
  Software                Description             Project
  ----------------------- ----------------------- ------------------------------------------------------
  Chopper                 Filters Oxford Nanopore [GitHub](https://github.com/wdecoster/chopper)
                          reads by length and     
                          quality.                

  Medaka                  Neural-network-based    [GitHub](https://github.com/nanoporetech/medaka)
                          consensus polishing for 
                          Oxford Nanopore         
                          assemblies.             

  NanoPack                Collection of tools for [GitHub](https://github.com/wdecoster/nanopack)
                          processing, filtering   
                          and visualizing         
                          long-read sequencing    
                          data.                   

  NanoPlot                Generates               [GitHub](https://github.com/wdecoster/NanoPlot)
                          quality-control plots   
                          for long-read           
                          sequencing data.        

  NanoPolish              Signal-level analysis   [GitHub](https://github.com/jts/nanopolish)
                          and polishing of Oxford 
                          Nanopore sequencing     
                          reads and assemblies.   

  PycoQC                  Quality-control and     [GitHub](https://github.com/a-slide/pycoQC)
                          visualization reports   
                          for Oxford Nanopore     
                          sequencing runs.        

  Porechop                Detects and trims       [GitHub](https://github.com/rrwick/Porechop)
                          adapters in Oxford      
                          Nanopore reads and can  
                          identify chimeric       
                          reads.                  

  Racon                   Consensus-generation    [GitHub](https://github.com/isovic/racon)
                          and polishing tool for  
                          long-read genome        
                          assemblies.             

  Winnowmap               Long-read mapper        [GitHub](https://github.com/marbl/Winnowmap)
                          designed to improve     
                          mapping in repetitive   
                          genomic regions.        

  Minimap2                Fast sequence mapper    [GitHub](https://github.com/lh3/minimap2)
                          for long DNA and RNA    
                          reads and whole-genome  
                          alignments.             

  Sniffles                Structural-variant      [GitHub](https://github.com/fritzsedlazeck/Sniffles)
                          caller for long-read    
                          sequencing data.        

  SVIM                    Detects structural      [GitHub](https://github.com/eldariont/svim)
                          variants from long-read 
                          alignments.             

  RagTag                  Reference-guided        [GitHub](https://github.com/malonge/RagTag)
                          scaffolding, correction 
                          and comparison of       
                          genome assemblies.      
  ------------------------------------------------------------------------------------------------------

```{=html}
</details>
```
## 🧬 Comparative genomics and phylogenetics

```{=html}
<details>
```
```{=html}
<summary>
```
`<strong>`{=html}Show comparative genomics and phylogenetics
tools`</strong>`{=html}
```{=html}
</summary>
```
  ---------------------------------------------------------------------------------------------------------
  Software                Description             Project
  ----------------------- ----------------------- ---------------------------------------------------------
  BEAST                   Bayesian evolutionary   [BEAST 1 GitHub](https://github.com/beast-dev/beast-mcmc)
                          analysis of molecular   · [BEAST 2 GitHub](https://github.com/CompEvol/beast2)
                          sequences, including    
                          phylogenetic inference  
                          and molecular dating.   

  ETE Toolkit             Python toolkit for      [GitHub](https://github.com/etetoolkit/ete)
                          manipulating, analyzing 
                          and visualizing         
                          phylogenetic trees.     

  GToTree                 Builds phylogenomic     [GitHub](https://github.com/AstrobioMike/GToTree)
                          trees from selected     
                          conserved marker genes. 

  Gubbins                 Detects regions of      [GitHub](https://github.com/nickjcroucher/gubbins)
                          recombination in        
                          bacterial genome        
                          alignments for          
                          phylogenetic analysis.  

  IQ-TREE                 Maximum-likelihood      [GitHub](https://github.com/iqtree/iqtree2)
                          phylogenetic inference, 
                          model selection and     
                          branch support          
                          analysis.               

  OrthoFinder             Identifies orthogroups, [GitHub](https://github.com/davidemms/OrthoFinder)
                          orthologs and gene      
                          duplications and infers 
                          species-level           
                          phylogenetic            
                          relationships.          

  PhyloBayes-MPI          Bayesian phylogenetic   [GitHub](https://github.com/bayesiancook/phylobayesmpi)
                          inference using         
                          site-heterogeneous      
                          evolutionary models.    

  MEGA                    Molecular evolutionary  [Official website](https://www.megasoftware.net/)
                          genetics analysis,      
                          including sequence      
                          alignment, evolutionary 
                          distance estimation and 
                          phylogenetics.          
  ---------------------------------------------------------------------------------------------------------

```{=html}
</details>
```
## 🧫 Variant calling, population genomics and antimicrobial resistance

```{=html}
<details>
```
```{=html}
<summary>
```
`<strong>`{=html}Show variant analysis tools`</strong>`{=html}
```{=html}
</summary>
```
  -------------------------------------------------------------------------------------------------------------------------------------
  Software                Description                 Project
  ----------------------- --------------------------- ---------------------------------------------------------------------------------
  ABRicate                Screens assembled bacterial [GitHub](https://github.com/tseemann/abricate)
                          genomes for                 
                          antimicrobial-resistance,   
                          virulence and other         
                          sequence markers using      
                          reference databases.        

  PoolSNP                 Calls SNPs from pooled      [GitHub](https://github.com/capoony/PoolSNP)
                          sequencing data.            

  Snippy                  Rapid variant calling and   [GitHub](https://github.com/tseemann/snippy)
                          core-genome alignment for   
                          bacterial genomes.          

  SVIM                    Identifies structural       [GitHub](https://github.com/eldariont/svim)
                          variants from long-read     
                          sequencing alignments.      

  VCFtools                Utilities for filtering,    [GitHub](https://github.com/vcftools/vcftools)
                          processing and analyzing    
                          VCF files and genetic       
                          variation data.             

  vcflib                  C++ library and             [GitHub](https://github.com/vcflib/vcflib)
                          command-line tools for      
                          manipulating and analyzing  
                          VCF files.                  

  PoolParty               Toolkit for analysis of     [Project
                          pooled sequencing data;     search](https://github.com/search?q=PoolParty+bioinformatics&type=repositories)
                          confirm the specific        
                          installed project before    
                          linking.                    
  -------------------------------------------------------------------------------------------------------------------------------------

```{=html}
</details>
```
## 🧬 Genome comparison, structural variation and scaffolding

```{=html}
<details>
```
```{=html}
<summary>
```
`<strong>`{=html}Show genome comparison tools`</strong>`{=html}
```{=html}
</summary>
```
  ----------------------------------------------------------------------------------------------------------
  Software                Description             Project
  ----------------------- ----------------------- ----------------------------------------------------------
  Assemblytics            Detects and             [GitHub](https://github.com/MariaNattestad/Assemblytics)
                          characterizes           
                          structural variants     
                          from genome assembly    
                          alignments.             

  MUMmer                  Suite for fast          [GitHub](https://github.com/mummer4/mummer)
                          alignment and           
                          comparison of large DNA 
                          sequences and genome    
                          assemblies.             

  Purge_Dups              Identifies and removes  [GitHub](https://github.com/dfguan/purge_dups)
                          haplotypic duplications 
                          from diploid genome     
                          assemblies.             

  Purge_Haplotigs         Identifies and removes  [GitHub](https://github.com/pdgenomics/purge_haplotigs)
                          redundant haplotigs     
                          from genome assemblies. 

  RagTag                  Uses a reference genome [GitHub](https://github.com/malonge/RagTag)
                          to scaffold, correct    
                          and compare genome      
                          assemblies.             
  ----------------------------------------------------------------------------------------------------------

```{=html}
</details>
```
## 🧩 Hi-C analysis and genome scaffolding

```{=html}
<details>
```
```{=html}
<summary>
```
`<strong>`{=html}Show Hi-C tools`</strong>`{=html}
```{=html}
</summary>
```
  --------------------------------------------------------------------------------------------------
  Software                Description             Project
  ----------------------- ----------------------- --------------------------------------------------
  HiC-Pro                 Processes Hi-C          [GitHub](https://github.com/nservant/HiC-Pro)
                          sequencing data,        
                          including read mapping, 
                          filtering and           
                          contact-map generation. 

  HiCStuff                Processes and           [GitHub](https://github.com/koszullab/HiC-Box)
                          visualizes Hi-C data    
                          and contact maps.       

  HALC                    Corrects long reads     [GitHub](https://github.com/lanlanla/halc)
                          using information from  
                          Hi-C data.              

  Bandage                 Interactive             [GitHub](https://github.com/rrwick/Bandage)
                          visualization of        
                          assembly graphs,        
                          including graphs        
                          produced by de          
                          Bruijn-graph            
                          assemblers.             

  CGView                  Generates circular maps [GitHub](https://github.com/paulstothard/cgview)
                          and visualizations of   
                          genomes and their       
                          annotated features.     
  --------------------------------------------------------------------------------------------------

```{=html}
</details>
```
## 🧹 Read quality control, mapping and sequence utilities

```{=html}
<details>
```
```{=html}
<summary>
```
`<strong>`{=html}Show read-processing and mapping
tools`</strong>`{=html}
```{=html}
</summary>
```
  ----------------------------------------------------------------------------------------------------
  Software                Description             Project
  ----------------------- ----------------------- ----------------------------------------------------
  BWA-MEM                 Aligns short sequencing [GitHub](https://github.com/lh3/bwa)
                          reads to reference      
                          genomes.                

  Cutadapt                Finds and removes       [GitHub](https://github.com/marcelm/cutadapt)
                          adapters and primers    
                          from sequencing reads.  

  FastQC                  Provides                [GitHub](https://github.com/s-andrews/FastQC)
                          quality-control metrics 
                          and reports for raw     
                          sequencing reads.       

  KMC                     Fast and                [GitHub](https://github.com/refresh-bio/KMC)
                          memory-efficient k-mer  
                          counting for large      
                          sequencing datasets.    

  Mosdepth                Rapidly calculates      [GitHub](https://github.com/brentp/mosdepth)
                          sequencing coverage and 
                          depth across genomic    
                          regions.                

  MultiQC                 Aggregates and          [GitHub](https://github.com/MultiQC/MultiQC)
                          summarizes              
                          quality-control reports 
                          from many               
                          bioinformatics tools    
                          into a single report.   

  Picard Tools            Collection of utilities [GitHub](https://github.com/broadinstitute/picard)
                          for manipulating,       
                          validating and          
                          analyzing               
                          high-throughput         
                          sequencing data.        

  SeqKit                  Cross-platform toolkit  [GitHub](https://github.com/shenwei356/seqkit)
                          for manipulating FASTA  
                          and FASTQ files.        
  ----------------------------------------------------------------------------------------------------

```{=html}
</details>
```
## 🧪 Data visualization and reporting

```{=html}
<details>
```
```{=html}
<summary>
```
`<strong>`{=html}Show visualization and reporting
tools`</strong>`{=html}
```{=html}
</summary>
```
  --------------------------------------------------------------------------------------------------
  Software                Description             Project
  ----------------------- ----------------------- --------------------------------------------------
  Bandage                 Interactive             [GitHub](https://github.com/rrwick/Bandage)
                          visualization of genome 
                          assembly graphs.        

  CGView                  Circular visualization  [GitHub](https://github.com/paulstothard/cgview)
                          of genomes and          
                          annotated genomic       
                          features.               

  MultiQC                 Combines outputs from   [GitHub](https://github.com/MultiQC/MultiQC)
                          multiple analysis tools 
                          into a single           
                          interactive             
                          quality-control report. 

  Qualimap                Quality-control and     [GitHub](https://github.com/qualimap/qualimap)
                          visualization tool for  
                          sequencing alignment    
                          data, including         
                          RNA-seq.                
  --------------------------------------------------------------------------------------------------

```{=html}
</details>
```
## 🧪 Sequencing simulation and reference-data retrieval

```{=html}
<details>
```
```{=html}
<summary>
```
`<strong>`{=html}Show simulation and database
utilities`</strong>`{=html}
```{=html}
</summary>
```
  ---------------------------------------------------------------------------------------------------------
  Software                Description             Project
  ----------------------- ----------------------- ---------------------------------------------------------
  InSilicoSeq             Simulates Illumina      [GitHub](https://github.com/HadrienG/InSilicoSeq)
                          sequencing reads from   
                          reference genomes or    
                          metagenomic             
                          communities.            

  NCBI Datasets           Command-line interface  [GitHub](https://github.com/ncbi/datasets)
                          for downloading and     
                          accessing NCBI genome,  
                          gene and sequence data. 

  NCBI Genome Download    Downloads genome        [GitHub](https://github.com/kblin/ncbi-genome-download)
                          assemblies and          
                          associated data from    
                          NCBI.                   
  ---------------------------------------------------------------------------------------------------------

```{=html}
</details>
```
## 🌳 Other scientific and specialist tools

```{=html}
<details>
```
```{=html}
<summary>
```
`<strong>`{=html}Show additional tools`</strong>`{=html}
```{=html}
</summary>
```
  ------------------------------------------------------------------------------------
  Software                Description             Project
  ----------------------- ----------------------- ------------------------------------
  BEAST                   Bayesian evolutionary   [BEAST
                          analysis of molecular   website](https://beast.community/)
                          sequences.              

  Kegg/eggNOG-related     Functional and pathway  ---
  tools                   annotation utilities;   
                          the exact installed     
                          package name should be  
                          confirmed.              
  ------------------------------------------------------------------------------------

```{=html}
</details>
```
## 🧰 Software environments and supporting packages

```{=html}
<details>
```
```{=html}
<summary>
```
`<strong>`{=html}Show environments and supporting
software`</strong>`{=html}
```{=html}
</summary>
```
  --------------------------------------------------------------------------------------
  Name in platform inventory          Description
  ----------------------------------- --------------------------------------------------
  R / R base                          Statistical programming language and environment
                                      for data analysis and visualization. Multiple R
                                      installations are maintained where required by
                                      workflows.

  HDF tools                           Utilities and libraries for handling Hierarchical
                                      Data Format (HDF) files.

  PacBio tools                        PacBio-specific utilities; the exact package
                                      collection depends on the installed environment.

  R packages (including `rgdal` and   R packages used by specific analytical workflows.
  `chili`)                            Package availability depends on the corresponding
                                      R environment.

  Snakemake                           Workflow management system for reproducible and
                                      scalable data analysis.
                                      [GitHub](https://github.com/snakemake/snakemake)

  hicstuff                            Hi-C data processing utilities. See the Hi-C
                                      section above.

  KeggANOG                            Local environment name; confirm whether this
                                      refers to a KEGG/eggNOG annotation workflow or a
                                      specific package.
  --------------------------------------------------------------------------------------

```{=html}
</details>



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

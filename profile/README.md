
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

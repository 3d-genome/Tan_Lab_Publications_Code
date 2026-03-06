# Tan Lab Publications Code

Code accompanying publications from the [Tan Lab](https://tanlab.stanford.edu/) at Stanford University. The Tan Lab develops and applies single-cell genome structure technologies, including **Dip-C** (Diploid Chromatin Conformation Capture), to study 3D genome organization in neuroscience, development, and human health.

This repository collects paper-specific analysis scripts that were previously hosted in the [tanlongzhi/dip-c](https://github.com/tanlongzhi/dip-c) repository. The main Dip-C tool and its documentation remain in that repo.

## Contents

### [Tan_et_al_Science_2018](Tan_et_al_Science_2018/)

Python 2 scripts for the analysis in the original Dip-C paper:

> Tan, Longzhi\*; Xing, Dong\*; Chang, Chi-Han; Li, Heng; Xie, X. Sunney "Three-dimensional genome structures of single diploid human cells," *Science* **361**, 924-928. DOI:[10.1126/science.aat5641](https://doi.org/10.1126/science.aat5641) (2018).

This paper introduced the Dip-C method and algorithm for reconstructing 3D diploid genomes from single cells. It studied human B-lymphoblastoid cells (GM12878), peripheral blood mononuclear cells, and mouse embryonic stem cells.

These scripts represent the original standalone workflow before the development of [hickit](https://github.com/lh3/hickit). For the current maintained tool, see the [dip-c](https://github.com/tanlongzhi/dip-c) repository.

- Raw data: [SRP149125](https://www.ncbi.nlm.nih.gov/sra/SRP149125)
- Processed data: [GSE117876](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE117876)

### [Tan_et_al_Science_2023](Tan_et_al_Science_2023/)

R scripts for the multiomics analysis in the fourth Dip-C paper, which introduced Pop-C and vDip-C:

> Tan, Longzhi\*†; Shi, Jenny\*; Moghadami, Siavash; Parasar, Bibudha; Wright, Cydney P.; Seo, Yunji; Vallejo, Kristen; Cobos, Inma; Duncan, Laramie; Chen, Ritchie; Deisseroth, Karl† "Lifelong restructuring of 3D genome architecture in cerebellar granule cells," *Science* **381**, 1112-1119. DOI:[10.1126/science.adh3253](https://doi.org/10.1126/science.adh3253) (2023).

This paper resolved the first 3D genome structures of single cerebellar cells and created life-spanning 3D genome atlases for both humans and mice. The R scripts here cover multiome analysis using ArchR, LIGER, and Seurat.

- Raw and processed data: [PRJNA933352](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA933352)

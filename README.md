# shaikh-sears-clin-cancer-research-2021
This repository is intended to served as a resource with supporting statistical code and processed microbiome data from Shaikh et al. (2021, *Clinical Cancer Research*) "A uniform computational approach improved on existing pipelines to reveal microbiome biomarkers of non-response to immune checkpoint inhibitors."

# Full citation: Shaikh FY, White JR, Gills JJ, Hakozaki T, Richard C, Routy B, Okuma Y, Usyk M, Pandey A, Weber JS, Ahn J, Lipson EJ, Naidoo J, Pardoll DM, Sears CL. A Uniform Computational Approach Improved on Existing Pipelines to Reveal Microbiome Biomarkers of Nonresponse to Immune Checkpoint Inhibitors. Clin Cancer Res. 2021 May 1;27(9):2571-2583. doi: 10.1158/1078-0432.CCR-20-4834. Epub 2021 Feb 16. PMID: 33593881; PMCID: PMC9053858.

# This is a copy of the original github directory link in the manuscript at https://github.com/resphera-jrwhite/shaikh-sears-clin-cancer-research-2021

* Top-level directory: `shaikh-sears-clin-cancer-research-2021/`
```
./shaikh-sears-clin-cancer-research-2021/
├── README.md  <-- this readme file
├── code      
│   ├── A01-merge-profiles-across-studies.pl <-- merges WGS and 16S rRNA profiles from the data/processed directory
│   ├── A02-meta-analysis-forest-plots.pl    <-- random effects modeling + forest plots for species and PICRUSt features (figure 2, and supplementary figs)
│   ├── A03-compile-indicator-taxa.pl        <-- compilation of indicator taxa derived from A02 and metadata
│   ├── figure03.pl  <-- elements of fig 3 from Shaikh et al.
│   ├── figure04.r   <-- elements of fig 4 from Shaikh et al.
│   ├── figure05.r   <-- elements of fig 5 from Shaikh et al.
│   └── figureS1.r   <-- elements of fig S1 from Shaikh et al.
├── analysis         <-- outputs generated by scripts in code/
│   ├── A01-merge-profiles-across-studies
│   ├── A02-meta-analysis-forest-plots
│   ├── A03-compile-indicator-taxa
│   ├── figure03
│   ├── figure04
│   ├── figure05
│   └── figureS1
└── data            <-- contains WGS Metaphlan2 profiles and Resphera Insight 16S rRNA profiles per study
    ├── final
    │   ├── metadata.2019-04-22.txt
    │   ├── pre-E01 <-- input data for validation cohorts
    │   └── pre-S1  <-- input data for paired WGS/16S rRNA correlation analysis (figure S1)
    └── processed <-- contains metadata / WGS Metaphlan2 profiles / Resphera Insight 16S rRNA profiles / PICRUSt functional profiles per study
         ├── Chaput.2017
         │   ├── 16SrRNA
         │   └── Metadata
         ├── Frankel.2017
         │   ├── 16SrRNA
         │   ├── METADATA
         │   └── WGS
         ├── Gopalakrishnan.2017
         │   ├── 16SrRNA
         │   ├── METADATA
         │   └── WGS
         ├── Matson.2018
         │   ├── 16SrRNA
         │   ├── METADATA
         │   └── WGS
         ├── Routy.2017
         │   ├── 16SrRNA
         │   ├── METADATA
         │   └── WGS
         ├── Peters.2019
         │   ├── 16SrRNA
         │   └── METADATA         
         ├── Hakozaki.2020  <-- (aka Richard et al.)
         │   ├── 16SrRNA
         │   └── METADATA
         └── Zheng.2019
             ├── SRA
             └── WGS
```

## Authors

* **James Robert White PhD** - *Initial work* - [GitHub](https://github.com/resphera-jrwhite)

Why is it important to organize data and code in a bioinformatic project?



What is the difference between relative and absolute file paths?



What is wrong with this R code?

x <- read.table("~/Downloads/data.txt");
y <- read.table("/usr/James/Documents/data.txt");


What can cause this code to break?

x <- read.table("/usr/James/project/data.txt");


What can cause this code to break?

x <- read.table("../expr/expr.tsv")


What do file extensions tell us?



Can you tell how a file is comma, tab, or space separated by the following file names?
Can you tell what the file contains?

data.txt
data.csv
data.tsv
data.flat
data.gct
data.rds
data.rda
expr.tsv
expr.csv
pheno.csv
expr.rds
image.rda
expr.feather
expr.pickle
expr.hdf5
expr.h5
doc.html
thing.css
read.js
read.cpp
read.py
read.r
functions.R
model.R


Given the following directory tree, how can you find out how each data file was generated?

.
├── data
│   ├── comparison_vs_data.txt
│   ├── data_rsem_filtered.txt
│   ├── data_rsem.txt
│   ├── data.txt
│   ├── gsva-table.txt
│   ├── gsva.txt
│   ├── ovca-cisp_rsem_dseq2_resistant-vs-sensitive.tsv
│   └── ovca-cisp_sample-info_stage3.tsv
└── R code
    ├── analyze.R
    ├── clean_rsem.R
    ├── gsva.R
    └── rsem.R


What is the difference between running an R script using R from the command line vs. using RStudio in terms of file paths?


Should you have the following code in your R script?

setwd("/usr/James/project")

setwd("~/project")

setwd("../ovca")


What is the advantage of the following project organization?

.
├── annot
│   ├── patient-info.tsv
│   └── sample-info.tsv
├── bam
│   └── align.sh
├── deseq
│   └── analyze.R
├── fq
│   └── get.sh
├── gsva
│   └── analyze.R
└── rsem
    └── quant.sh


Before you run an R script in Rstudio, what do you need to do first?



Examine the following projects and identify principles of how the data and code are organized:
https://github.com/djhshih/analysis-parpir-sum149-amp-seq
https://github.com/djhshih/analysis-parpir-sum149-rna-seq
https://github.com/djhshih/analysis-egfrir

Before you contribute to an existing bioinformatic project, what do you need to do first?




Examine the package names for different Linux distributions and devise file naming rules for new packages:

https://archlinux.org/packages/
https://packages.ubuntu.com/bionic/
https://koji.fedoraproject.org/koji/packages

How are such naming rules useful?


Should you use spaces or tabs for indentation?


Should you use `<-` or `=` in your R code?



Which is more important? The process or the outcomes?


What are the advantages of having a 'good' process? What is 'good'?


What are the advantages of having a 'good' outcome? What is 'good'?



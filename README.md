# Single Cell Analysis Toolbox

This repository contains data and notebooks for the single-cell session in the [2022 EMBL-EBI T-cell bioinformatics course](https://www.ebi.ac.uk/training/events/bioinformatics-t-cell-immunology-2022/)

## Objectives 

The goal of these two sessions will be to introduce basic concepts for exploratory analysis of single-cell RNA and paired TCR sequencing data.

## Data

We will use a dataset from the HCA [Tissue Immune Cell Atlas](https://www.science.org/doi/10.1126/science.abl5197) containing human T cells across a range of lymphoid and non-lymphoid tissues. This will allow us to cover a broad spectrum of T cell types.

* **scRNA-seq data**

* **scVDJ-seq data** request access to TCR contigs in [GDrive](https://drive.google.com/drive/folders/1wgd8WAsr_SAdM8eaeumm42V6CHLJ8XVk?usp=share_link)

## notebooks

```T-cell-bioinformatics-course_scRNAseq.ipynb``` - workflow to perform QC, integration and annotation of single-cell gene expression (GEX)

```T-cell-bioinformatics-course_scTCRseq.ipynb``` - workflow to integrate VDJ and GEX data, determine clonotypes and repertoire sharing

## Python_intro

### Python packages

```pip3 install```

pandas 
numpy
scipy
matplotlib
seaborn

### Python object creation

```dict = dict(zip(keys, values))```

```df = pd.DataFrame()```

```list = []```

```AnnData``` https://anndata.readthedocs.io/en/latest/

### Reading in and writing out the data

```pd.read_csv()``` ```.to_csv()```

### Investigating objects

```type()``` 

Dataframes:
```df.columns``` ```df.shape``` ```df['column'].unique()``` ```df['column'].nunique()``` ```df.head(2)``` ```df.tail(2)```
```df['column.value_counts```

### Python courses
https://www.w3schools.com/python/python_intro.asp

https://www.bioinformatics.babraham.ac.uk/training.html

https://swcarpentry.github.io/python-novice-inflammation/

http://swcarpentry.github.io/python-novice-gapminder/

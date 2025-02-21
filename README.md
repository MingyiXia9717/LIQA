# Long-read Isoform Quantification and Analysis 

[![DOI](https://zenodo.org/badge/257630000.svg)](https://zenodo.org/badge/latestdoi/257630000)

LIQA (Long-read Isoform Quantification and Analysis) is an Expectation-Maximization based statistical method to quantify isoform expression and detect differential alternative splicing (DAS) events using long-read RNA-seq data. LIQA incorporates base-pair quality score and isoform-specific read length information to assign different weights across reads instead of summarizing isoform-specific read counts directly. Moreover, LIQA can detect DAS events between conditions using isoform usage estimates.

## Computational pipeline of LIQA
<p align="center">
  <img width="575" height="406" src="doc/liqa_flowchart.png">
</p>

## Inputs of LIQA
The input of LIQA is long-read RNA-seq read data in BAM format together with a refrence isoform annotation file.

## Installation
Please refer to [Installation](https://github.com/WGLab/LIQA/blob/master/doc/Install.md) for how to install LIQA.

## Usage
Please refere to [Usage](https://github.com/WGLab/LIQA/blob/master/doc/Usage.md) for how to use LIQA.

## Examples of isoform analysis using LIQA.

Please refer to [Demo and Examples](https://github.com/WGLab/LIQA/blob/master/doc/Examples.md) for examples of how to use LIQA.

## Contact

If you have any questions/issues/bugs, please post them on [GitHub](https://github.com/WGLab/LIQA/issues). They would also be helpful to other users. 

## Citation

Yu Hu, Li Fang, Xuelian Chen, Jiang F. Zhong, Mingyao Li, Kai Wang. LIQA: Long-read Isoform Quantification and Analysis. 2020. bioRxiv doi: [https://doi.org/10.1101/2020.09.09.289793](https://www.biorxiv.org/content/10.1101/2020.09.09.289793v1)

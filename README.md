## Guide for the Differential Expression Analysis of RNAseq data using DEseq2

Made by David Requena (drequena@rockefeller.edu) and James Saltsman (jsaltsman@rockefeller.edu).

-------------------------------------------------------------------------

This code includes some basic steps:
1. SET UP:
* Install and/or call the required libraries
* Input sample metadata
* Create the DEseq2 object
2. Exploring the data:
* Transformations of the Data
* PCA plot
* tSNE plot
* HeatMap
3. Data Analysis:
* Model matrix
* Comparison
* Annotation and output tables
4. Plots:
* Volcano Plot
* HeatMap with genes
* BoxPlot and ScatterPlot

To run this script, two tables are required:
* A table with the samples' data, containing features of interest (e.g. cases/controls, gender, etc...)
* A table with the gene counts by sample

And two optional tables:
* A table with genes to be filtered out (e.g. ribosomal genes)
* A table with genes of interest, prepare individual plots by gene

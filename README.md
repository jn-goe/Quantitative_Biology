# Quantitative_Biology
Datasets - Exercises for the Course "Fundamentals of Quantitative Biology"

## STATS

**For Stats_01-04:** Filtered and subset scRNA-seq dataset with raw reads based on "3k PBMCs from a Healthy Donor" data available on [10x Genomics](http://cf.10xgenomics.com/samples/cell-exp/1.1.0/pbmc3k/pbmc3k_filtered_gene_bc_matrices.tar.gz)[^1]

- ``adata_raw.csv``

**For Stats_02:** 2 Channels of a sample microscopy image "Rat_Hippocampal_Neuron.tif" provided with image software ImageJ/Fiji[^2] 

- ``C1-Rat_Hippocampal_Neuron.txt``
- ``C2-Rat_Hippocampal_Neuron.txt``

[^1]: 3k PBMCs from a Healthy Donor, Chromium Demonstration (v2 Chemistry) by Cell Ranger 1.1.0, 10x Genomics.
[^2]: Schindelin, J., Arganda-Carreras, I., Frise, E. et al. Fiji: an open-source platform for biological-image analysis. Nat Methods 9, 676–682 (2012). https://doi.org/10.1038/nmeth.2019

**For Stats_04:** Cell labeling by k-means clustering (obtained by `sklearn.cluster.KMeans()`) on the first 50 Principal Components of the PBMC scRNA-seq dataset.

- ``cluster_labels.txt``

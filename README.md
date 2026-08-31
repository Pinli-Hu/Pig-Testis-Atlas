# Pig-Testis-Atlas   [![DOI](https://zenodo.org/badge/1185322126.svg)](https://doi.org/10.5281/zenodo.22207686)

A high-resolution single-cell and spatial omics atlas of testis reveals developmental transitions across the pig lifespan.

## Spatial Transcriptomics Analysis Note

The spatial transcriptomics data used in this study were generated using Stereo-seq technology by BGI Genomics. Processing of the raw spatial data requires alignment with the corresponding SAW (Stereo-seq Analysis Workflow) version.

Due to differences between SAW versions, some preprocessing steps and output formats may vary. Therefore, users are recommended to ensure compatibility between CellBin outputs and the corresponding SAW environment.

For CellBin v2 data, we recommend using:

SAW ≥ 8.0
StereoMap ≥ 4.0

Using compatible versions is important to ensure consistent spatial coordinate parsing, cell segmentation, and downstream analysis.

## Dependencies

### Python

The analysis was performed using Python with the following packages:

scanpy==1.9.6
scvelo==0.3.3
stereo==1.6.2
infercnvpy==0.6.1
pandas==1.2.4
numpy==1.23.5
scipy==1.10.1
matplotlib==3.7.1
seaborn==0.12.2
tqdm==4.65.0
loompy==3.0.6
geopandas==0.13.2
rasterio==1.3.11
shapely==2.0.7

### R

The analysis was performed using R with the following packages:

Augur==1.0.3
tidyverse==2.0.0
patchwork==1.2.0
ggplot2==3.5.1
dplyr==1.1.4
SeuratWrappers==0.3.4
anndata==0.7.5.6
sceasy==0.0.7
SeuratData==0.2.2.9001
Seurat==5.1.0
SeuratDisk==0.0.0.9021
SingleCellExperiment==1.24.0
CBNplot==1.2.1
stringr==1.5.1
clusterProfiler==4.10.1
enrichplot==1.22.0
org.Ss.eg.db==3.18.0
igraph==2.0.3
ggraph==2.2.1
reshape==0.8.9
purrr==1.0.2
AUCell==1.24.0
ComplexHeatmap==2.15.4
SCopeLoomR==0.13.0
SCENIC==1.3.1
BiocParallel==1.36.0
data.table==1.15.4
KernSmooth==2.23-24
monocle3==1.3.5
pheatmap==1.0.12
plotly==4.10.4
RColorBrewer==1.1-3
spacexr==2.2.1
Matrix==1.6-5
doParallel==1.0.17
harmony==1.2.0




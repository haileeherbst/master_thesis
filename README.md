# master_thesis
all relevant data files (qCLASH, RNAseq, smallRNAseq, count_tables, etc) are available upon request, but have been omitted from GitHub intentionally


## total_network
workflow from pre-processed qCLASH and RNAseq data to the reduced, 93-node network and the cell line-specific networks for IPC298 and SKMel30 treatment-resistant cells

## threshold_network
workflow from raw counts of qCLASH reads and RNAseq (total and small RNAseq) to a threshold-based network composed of 1181 nodes

## pathfindR
enrichment analysis for both the reduced network and threhold network using RNAseq-gathered log2foldchange and p-value data for genes within the network

## qCLASH_exploration
a look at the binding regions and seed regions of miRNA-mRNA hybrids for both the total qCLASH data and the reduced network data

## qCLASH_PCA_Venn_tables
a variety of venn diagrams, euler diagrams, and PCA plots for total qCLASH data and threshold-based network data, with and without MelJuso data included


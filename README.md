File name = "markers2sep"
Import libraries = "matrixStats","circlize","ComplexHeatmap","data.table".
Create SSGSE function
Then calculate rank of genes
Then calculate enrichment score for each sample
Calculate the (es) for each gene set
Then normalize by gene number
Then normalize by absolute diff between max and min
Then prapare output
Read the dataset (readRDS)
Then import the marker dataset
Convert it into the list
Use ssgea function
Then transpose the res
Conver it into matrix
Then plot the Heatmap

SSGSEA : Single-sample GSEA (ssGSEA), an extension of Gene Set Enrichment Analysis (GSEA), calculates separate enrichment scores for each pairing of a sample and gene set.  Each ssGSEA enrichment score represents the degree to which the genes in a particular gene set are coordinately up- or down-regulated within a sample.

Name: Arkaj Parkhe (Msc.bioinfo)2nd year

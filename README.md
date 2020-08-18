# Supplementary data Gordon et al. transcriptome *Polycarpa mytiligera*


**This repository contains supplemental materials from:**  
Tal Gordon, Arnav Kumar Upadhyay, Lucia Manni, Dorothee Huchon, Noa Shenkar. Extreme regeneration capacity of the solitary ascidian Polycarpa mytiligera reveals its affinity to colonial species. Submitted.  
  
*These datasets are based on data from Alié A, Hiebert LS, Simion P, et al. Convergent Acquisition of Nonembryonic Development in Styelid Ascidians. Mol Biol Evol. 2018;35(7):1728-1743. doi:10.1093/molbev/msy068.*

## Datasets

**Gordon_genes_raw.zip**  
This zipped folder contains the 3,341 initial single-gene alignments (fasta format) before any post-processing.

**Gordon_genes_guidance.zip**  
This zipped folder contains the 3,341 initial single-gene alignments (fasta format) after Guidance trimming.

**Gordon_all_genes_supermatrix.phy**  
Supermatrix based on 3,341 genes used in the study. Phylip format.

**Gordon_reduced_supermatrix.phy**  
Supermatrix based on 3,341 genes used in the study. Phylip format. Matrix used to build the tree presented in Figure 6.


## Trees

**Gordon_all_genes_ML.tre**  
Phylogenetic tree reconstructed based on the all_genes_supermatrix under the LG+C60+F+G model of IQtree (version 1.6.12). Newick format.

**Gordon_reduced_ML.tre**  
Phylogenetic tree presented in Figure 6 reconstructed based on the reduced_supermatrix under the LG+C60+F+G model of IQtree (version 1.6.12). Newick format.


## Transcriptome assembly

**Polycarpa_mytiligera_transcriptome_assembly_120.zip**  
Zipped transcriptome assembly of *Polycarpa mytiligera*. The transcriptome was assembled from Illumina reads using Trinity (v2.8.4). Transcripts shorter than 120 bp were deleted. Fasta format.






## Common statistical tests for microbiome
  - Rarefaction
  - Composition of samples at phylum / genus / species level
  - Differential abundance test between groups
  - Intra-sample diversity (Alpha diversity) and inter-sample distance (Beta diversity)
  - Volatility (if longitudinal samples available)
  - Inidividual group (clustering)
  - Bacterial group (clustering)
  - Association tests for groups
  - Phylogenetic analysis


## Alpha diversity
* Evenness
* Shannon
* Inverse Simpson
* Richness
* Chao1

## Beta diversity: Distance (Dissimiliarity) between samples
* Bray-Curis dissimilarity
* Aitchison distance: Euclidean distance of CLR-transformed abundance
* Unweighted UniFrac
* Weighted UniFrac


## Microbiome analysis framework
> QIIME2 <https://qiime2.org/> 
* 

> phyloseq (R) <https://github.com/joey711/phyloseq>
*

> biobakery libraries (R) <https://github.com/biobakery>
* MaAsLin2, MaAsLin3
* MetaPhlAn


## Differential abundance analysis
> MaAsLin2, MaAsLin3 (R, bash)

> ANCOM-BC, ANCOM-BC2

> LinDA
* uses CLR transformed data

> LEfSe
* 
> ALDEx2

## Statistical tests
> PERMANOVA
* Implemented in `adonis`
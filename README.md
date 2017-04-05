# Blackman_et_al_Gfossarum_UK

Data processing workflow and supplementary data for: 

__Blackman et al. 2017__ - Detection of a new non-native freshwater species by DNA metabarcoding of environmental samples - first record of Gammarus fossarum in the UK. _Aquatic Invasions_. In press.

This Repository has been archived permanently: [![DOI](https://zenodo.org/badge/68293017.svg)](https://zenodo.org/badge/latestdoi/68293017) 

The repo contains the entire workflow as Jupyter notebooks:
 - [1](https://github.com/HullUni-bioinformatics/Blackman_et_al_Gfossarum_UK/blob/master/1-download_references/prepare_reference.ipynb) - downloading of reference data
 - [2](https://github.com/HullUni-bioinformatics/Blackman_et_al_Gfossarum_UK/blob/master/2-metaBEAT/clip-trim-30_merge_forw-only_c0.97m3_blast_min0.85_GLOBAL-latest/run_metaBEAT.ipynb) - processing of metabarcoding data and taxonomic assignment
 - [3](https://github.com/HullUni-bioinformatics/Blackman_et_al_Gfossarum_UK/tree/master/3-extract_haplotypes/extract_hts.ipynb) - extracting of COI haplotypes from metabarcoding data for subsequent tree inference
 - [4](https://github.com/HullUni-bioinformatics/Blackman_et_al_Gfossarum_UK/tree/master/4-infer_phylogeny/Gammarus_phylogeny.ipynb) - Phylogenetic tree inference.

All analyses were performed in the self contained docker container of metaBEAT [v0.97.7](https://github.com/HullUni-bioinformatics/metaBEAT/releases/tag/v0.97.7), available from [here](https://hub.docker.com/r/chrishah/metabeat/).

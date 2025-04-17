# CyanoMarks - Genetic markers for marine picocyanobacteria
[![Release](https://img.shields.io/badge/release-1.0-blue.svg)
![Date](https://img.shields.io/badge/date-01%20July%202020-lightgrey.svg)
![Github Downloads
(total)](https://img.shields.io/github/downloads/roskobaz/cyanomarks/total.svg)](https://github.com/roskobaz/cyanomarks/releases)

## Welcome to the CyanoMarks database!
CyanoMarks is a curated database for reliable taxonomic assignment of marine cyanobacteria based on several commonly used core phylogenetic markers, which display different advantages and drawbacks: 

* 16S rDNA, a universal marker for prokaryotes encoding the small ribosomal RNA subunit
* the 16S-23S internal transcribed spacer (ITS; [1])
* *petB*, encoding the *b6* subunit of the of cytochrome *b6/f* complex [2,3] 
* *rpoC1*, encoding the gamma subunit of RNA polymerase [4] 
* *psbO*, encoding a subunit of the oxygen evolving complex of Photosystem II [5] 

as well as *Synechococcus* pigment type markers, including:

* *cpcBA*, encoding the phycocyanin alpha and beta subunits [6] 
* *cpeBA*, encoding the phycoerythrin-I alpha and beta subunits [7]
* *mpeBA*, encoding the phycoerythrin-II alpha and beta subunits [6] 
* *mpeW*, encoding the phycoerythrobilin:Cys-83 alpha-phycoerythrin II lyase, specific of pigment type 3dB [6]  

CyanoMarks gathers most published cyanobacterial sequences with an emphasis on alpha-cyanobacteria (*Prochlorococcus*, *Synechococcus* and *Cyanobium*), the most abundant phototrophic prokaryotes in aquatic ecosystems, as well as representative sequence homologs from other marine and freshwater cyanobacteria and photosynthetic eukaryotes to be used as outgroups. These databases also include extensive contextual data such as sequence origin (strain, clone, etc.), sampling location and physico-chemical parameters of their isolation site. This database takes part of the RoskoBaz initiative, which aims at unifying three banks of reference markers developed at the Station Biologique de Roscoff (CyanoMarks, MicRhoDE for microbial rhodopsins and PhytoRef for chloroplastic 16S rDNA) to ensure their quality and longevity using semi-automated update and curation tools.

[1] Rocap G. et al., 2002. AEM 68: 1180–1191. https://doi.org/10.1128/AEM.68.3.1180-1191.2002

[2] Mazard S. et al. 2012. Env. Microbiol. 14:372-86. https://doi.org/10.1002/9781118010549.ch30

[3] Farrant G.K., Doré H. et al. 2016. PNAS 113:E3365–74. https://doi.org/10.1073/pnas.1524865113

[4] Gutiérrez-Rodríguez A. et al. Limnol. oceanogr. 59: 705‑23. https://doi.org/10.4319/lo.2014.59.3.0705

[5] Pierella Karlusich et al., 2022. Mol Ecol. Res. 1755-0998.13592 https://doi.org/10.1111/1755-0998.13592

[6] Grébert T et al., 2018. PNAS 115: E2010‑19. https://doi.org/10.1073/pnas.1717069115

[7] Everroad C.R. and Wood A.M. 2006. J. Phycology 42: 1300‑1311. https://doi.org/10.1111/j.1529-8817.2006.00282.x.


## What do we provide ?
The current public version encompasses 721 petB sequences carefully assigned at up to 5 taxonomic ranks (cluster, sub-cluster, genus, clade, sub-clade) and covering most of the genetic diversity known so far within alpha-cyanobacteria. The other markers will be released upon publication of the manuscript describing RoskoBaz/CyanoMarks 

Numerous supporting data are also provided including:
* deep phylogenetic classification down to the subclade level, unified between markers,
* phenotypic information (e.g., pigment type)
* organism information (e.g., biological interaction, culture collections)
* sequence sources (accession number, sequencing strategy, etc.)
* genome information (size, nb of CDS, rRNA, GC%, taxonomic assignment, etc.)
*	contextual data including isolation or sampling dates and sites, cruise, GPS coordinates, physico-chemical parameters, etc.
*	publications for gene or genome sequences, cruises, etc.


## Current version
* Current version : 1.0
* Last update : 1st of July, 2020 
* DOI
* [Link](https://github.com/roskobaz/cyanomarks/releases)
* Documentation

## Curators
* [Laurence GARCZAREK](mailto:laurence.garczarek@sb-roscoff.fr), senior scientist, CNRS-Sorbonne Université, Station Biologique, Roscoff FRANCE
* [Gregory K. FARRANT](mailto:gregory.farrant@pm.me), PhD, Reykjavík, ICELAND.
* [Perrine KERGOAT](mailto:perrine.kergoat@sb-roscoff.fr), PhD student Sorbonne Université, Station Biologique, Roscoff FRANCE

## How to Cite
Authors et al. CyanoMarks a database of genetic markers for marine picocyanobacteria. To be submitted

## Provided Files

|File suffix             |File Content                                                                          |
|------------------------|--------------------------------------------------------------------------------------|
|contextual_data.csv.gz  |A tabulated file containing all contextual data, including environmental parameters.  |
|dada2.fasta.gz          |A fasta of all reference sequences with DADA2-formatted headers                       |
|mothur.fasta.gz         |A fasta of all reference sequences with MOTHUR-formatted headers                      |
|mothur.tax.gz           |A text file of taxonomies for MOTHUR                                                  |
|taxo_long.fasta.gz      |A fasta of all reference sequences with long "n-ranked" taxonomy                      |
|UTAX.fasta.gz           |A fasta of all reference sequences with VSEARCH-formatted headers                     |


## Report issues
* Please report any issue on [GitHub](https://github.com/roskobaz/cyanomarks/issues)

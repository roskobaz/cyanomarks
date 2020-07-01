# CyanoMarks
[![Release](https://img.shields.io/badge/release-1.0-blue.svg)
![Date](https://img.shields.io/badge/date-01%20July%202020-lightgrey.svg)
![Github Downloads
(total)](https://img.shields.io/github/downloads/roskobaz/cyanomarks/total.svg)](https://github.com/roskobaz/cyanomarks/releases)

## Welcome to the CyanoMarks database!
<p>Marine picocyanobacteria _Synechococcus_ _Prochlorococcus_ and _Cyanobium_ are the most abundant phototrophic prokaryotes in the oceans.</p>

<p>CyanoMarks is a comprehensive database of curated markers _petB_, _rpoC1_, 16S and ITS with curated an unified taxonomy.</p>

## What we provide ?
<p>We provide about 7900 manually curated sequences of type-1 rhodopsins from more than 450 environmental samples and organisms. All sequences were aligned according to the predicted secondary structure of the protein and a robust phylogenetic tree was constructed. Based on a robust phylogenetic analysis, we introduce an operational classification system with multiple phylogenetic levels ranging from superclusters to species-level operational taxonomic units.</p>

<p>MicRhoDE tools allow sequence searches either by keywords, taxonomic unit, or sequence similarity (BLAST). Results can be sorted in raw or aligned nucleic or amino-acid sequences or visualized on a map.</p>

Numerous supporting data are also provided including:
* deep phylogenetic classification down to the subclade level, unified between markers,
* physiological information (e.g. pigment type),
* contextual data (e.g. isolation site, GPS coordinates, physico-chemical parameters),
* literature citations, year of isolation and publication

## Current version
* Current version : 1.0
* Last update : 1st of July, 2020 
* DOI
* [Link](https://github.com/roskobaz/cyanomarks/releases)
* Documentation

## Curators
* [Laurence GARCZAREK, Ph.D.](mailto:laurence.garczarek@sb-roscoff.fr), CNRS-Sorbonne Université · Station Biologique, 29680 Roscoff FRANCE
* Gregory K. FARRANT, Ph.D.
* Patricia KEMBIA, M.Sc.

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

---
layout: page
permalink: /software/
title: software
description: Some tools that I have developed, or helped to develop.  
---

- [smcsmc](https://github.com/luntergroup/smcsmc) [`c++`, `python`] Inference of the ancestral recombination graph and demographic events from whole genome sequence data.
	- Install with [conda](https://anaconda.org/luntergroup/smcsmc).
- [stdpopsim](https://github.com/popsim-consortium/stdpopsim) [`python`] A community-maintained standard library of population genetic models.
	- Install from [Pypi](https://pypi.org/project/stdpopsim/).
- [aavcf](https://github.com/Chris1221/aavcf) [`c++`] Convert allelic encodings from major/minor to ancestral/derived in VCF files.
	- Install from source.
- [goldi](https://github.com/Chris1221/goldi) [`c++`, `R`] Identification of multi-word terms (such as in Gene Ontology) in free form text with application to the biomedical literature.
	- Install from [CRAN](https://cran.r-project.org/web/packages/goldi/index.html).
- [yamldoc](https://github.com/Chris1221/yamldoc) [`python`] A dependency free documentation generator for YAML formatted data. 
	- Install from [Pypi](https://pypi.org/project/yamldoc/).
- [genomic_interval_pipeline](https://github.com/Chris1221/genomic_interval_pipeline) [`Rust`] Creates an HDF5 database for Keras out of genomic regions and their annotations. A (much faster) drop in replacement for the Basset pre-processing pipeline. 
	- Install from [crates.io](https://crates.io/crates/genomic_interval_pipeline).
- [scJaccard](https://github.com/Chris1221/scJaccard) [`Rust`] Pure rust computation of the continuous Jaccard index at a single cell level
	- Install from source.

### Work in progress

These packages are either incomplete or undocumented, but are public and still contain some useful code for anyone who likes a little digging.

- [deepstab](https://github.com/Chris1221/deepstab) [`python`] All in one processing tool and deep learning model to predict RNA stability from sequence. 
	- The entire pipeline is usable but almost completely undocumented.  
- [ancient_african_admixture](https://github.com/Chris1221/ancient_african_admixture) Processing pipelines and analysis for all of results shown in Cole et al 2021, currently under review.
	- This code may be useful for those wanting a real world example of using SMCSMC and is documented, but may change before the publication of my paper.

### Fun projects

- [allerID](https://github.com/Chris1221/allerID) [`R`, `shiny`] Web application to identify allergens in lists of ingredients using [goldi](https://github.com/Chris1221/goldi).
	- Hosted on [shinyapps.io](https://ccole.shinyapps.io/allerID/)
- [rpg_epic_converter](https://github.com/Chris1221/epic_rpg_converter) [`python`] A small discord bot implementing a graph-based conversion strategy between resources in a role playing game, EPIC RPG.
	- Install from [top.gg](https://top.gg/bot/773260807638089768).

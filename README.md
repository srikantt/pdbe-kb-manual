# PDBe-KB User Guide

This User Guide provides information on the various types of data that is available from the [Protein Data Bank in Europe - Knowledge Base](https://pdbe-kb).

PDBe-KB (Protein Data Bank in Europe - Knowledge Base) is a community-driven resource managed by the [PDBe team](https://pdbe.org/), collating functional annotations and predictions for structure data in the PDB archive. PDBe-KB is a collaborative effort between PDBe and a diverse group of [bioinformatics resources and research teams](https://www.ebi.ac.uk/pdbe/pdbe-kb/partners).

PDBe-KB contains data contributed by projects such as [SIFTS](http://www.ebi.ac.uk/pdbe/docs/sifts/index.html) and [FunPDBe](http://www.ebi.ac.uk/pdbe/pdbe-kb/funpdbe) and aims to place structures from the PDB in their biological context.

Please cite PDBe-KB as: [PDBe-KB consortium, PDBe-KB: collaboratively defining the biological context of structural data. Nucleic Acids Research, Database Issue (2022)](https://academic.oup.com/nar/advance-article/doi/10.1093/nar/gkab988/6424755)

Previous publications: [PDBe-KB consortium, PDBe-KB: a community-driven resource for structural and functional annotations. Nucleic Acids Research, Database Issue (2020)](https://academic.oup.com/nar/article/48/D1/D344/5580911)

***

### Wiki pages

#### Data and Service Guides
These are documentations for data and services provided by PDBe-KB

* [Sequence conservation scores](https://github.com/PDBe-KB/pdbe-kb-manual/wiki/Sequence-conservation-scores)
* [Superposition](https://github.com/PDBe-KB/pdbe-kb-manual/wiki/Superposition)
* [Secondary structure variance](https://github.com/PDBe-KB/pdbe-kb-manual/wiki/Secondary-structure-variance)

***

### Web Components Library
These are repositories of reusable web components developed for PDBe-KB

#### PDBe-KB Header Component

This repository is for the codebase of a lightweight Angular v7 web component that provides a header/banner and some basic navigation.

This component is used on the PDBe-KB Aggregated Views of Proteins and PDBe-KB Aggregated Views of Ligands.

<img src="https://raw.githubusercontent.com/PDBe-KB/component-pdbe-kb-header/main/pdbe-kb-app-header.png">

|Code Repository|Status|Test Coverage|Maintainability|
|---|---|---|---|
|[PDBe-KB Header Component](https://github.com/PDBe-KB/component-pdbe-kb-header)|[![Build Status](https://www.travis-ci.com/PDBe-KB/component-pdbe-kb-header.svg?branch=main)](https://www.travis-ci.com/PDBe-KB/component-pdbe-kb-header)|[![codecov](https://codecov.io/gh/PDBe-KB/component-pdbe-kb-header/branch/main/graph/badge.svg?token=WVIZESHBOK)](https://codecov.io/gh/PDBe-KB/component-pdbe-kb-header)|[![Maintainability](https://api.codeclimate.com/v1/badges/55b0af0ca2064502aae5/maintainability)](https://codeclimate.com/github/PDBe-KB/component-pdbe-kb-header/maintainability)|

***

#### Summary Text Component

This repository is for the codebase of a lightweight Angular v7 web component that displays textual summary information.

This web component is used on the PDBe-KB Aggregated Views of Proteins to display summary information on a particular UniProt accession, including:

1. protein name
2. gene name
3. species
4. biological function

It also supports flags (for example enzyme classification ids) and has an embedded "tutorial" web component.

<img src="https://raw.githubusercontent.com/PDBe-KB/component-summary-text/main/pdbe-kb-summary-text.png">

|Code Repository|Status|Test Coverage|Maintainability|
|---|---|---|---|
|[Summary Text Component](https://github.com/PDBe-KB/component-summary-text)|[![Build Status](https://www.travis-ci.com/PDBe-KB/component-summary-text.svg?branch=main)](https://www.travis-ci.com/PDBe-KB/component-summary-text)|[![codecov](https://codecov.io/gh/PDBe-KB/component-summary-text/branch/main/graph/badge.svg?token=XGRVGF9LDY)](https://codecov.io/gh/PDBe-KB/component-summary-text)|[![Maintainability](https://api.codeclimate.com/v1/badges/c757f22f7c1635df3ef8/maintainability)](https://codeclimate.com/github/PDBe-KB/component-summary-text/maintainability)|

***

#### Summary Icons Component

This repository is for the codebase of a lightweight Angular v7 web component that displays icons and item counts for data such as the number of available PDB entries or the number of associated publications.

This web component is used on PDBe-KB Aggregated Views of Proteins to display such summary information.

<img src="https://raw.githubusercontent.com/PDBe-KB/component-summary-icons/main/pdbe-kb-summary-icons.png">

|Code Repository|Status|Test Coverage|Maintainability|
|---|---|---|---|
|[Summary Icons Component](https://github.com/PDBe-KB/component-summary-icons)|[![Build Status](https://www.travis-ci.com/PDBe-KB/component-summary-icons.svg?branch=main)](https://www.travis-ci.com/PDBe-KB/component-summary-icons)|[![codecov](https://codecov.io/gh/PDBe-KB/component-summary-icons/branch/main/graph/badge.svg?token=ZE5F4YID7I)](https://codecov.io/gh/PDBe-KB/component-summary-icons)|[![Maintainability](https://api.codeclimate.com/v1/badges/97aa515784475bfac9e1/maintainability)](https://codeclimate.com/github/PDBe-KB/component-summary-icons/maintainability)|

***

#### Polyprotein Component

This repository is for the codebase of a lightweight Angular v7 web component that displays all the processed proteins for a UniProt accession.

This web component is used on the PDBe-KB Aggregated Views of Proteins.

<img src="https://raw.githubusercontent.com/PDBe-KB/component-polyprotein-section/main/pdbe-kb-polyprotein-section.png">

|Code Repository|Status|Test Coverage|Maintainability|
|---|---|---|---|
|[Polyprotein Section Component](https://github.com/PDBe-KB/component-polyprotein-section)|[![Build Status](https://www.travis-ci.com/PDBe-KB/component-polyprotein-section.svg?branch=main)](https://www.travis-ci.com/PDBe-KB/component-polyprotein-section)|[![codecov](https://codecov.io/gh/PDBe-KB/component-polyprotein-section/branch/main/graph/badge.svg?token=2PM8M83ZHN)](https://codecov.io/gh/PDBe-KB/component-polyprotein-section)|[![Maintainability](https://api.codeclimate.com/v1/badges/5c699aa188766841b5c8/maintainability)](https://codeclimate.com/github/PDBe-KB/component-polyprotein-section/maintainability)|

***

#### Representative Structures Component

This repository is for the codebase of a lightweight Angular v7 web component that displays a carousel of images with labels and tooltips.

This web component is used on PDBe-KB Aggregated Views of Proteins and Aggregated Views of Ligands to display the best representative structures for a UniProt accessions, and various highlights of a small molecule, respectively.

<img src="https://raw.githubusercontent.com/PDBe-KB/component-representative-structures/main/pdbe-kb-representative-structures.png">

|Code Repository|Status|Test Coverage|Maintainability|
|---|---|---|---|
|[Representative Structures Component](https://github.com/PDBe-KB/component-representative-structures)|[![Build Status](https://www.travis-ci.com/PDBe-KB/component-representative-structures.svg?branch=main)](https://www.travis-ci.com/PDBe-KB/component-representative-structures)|[![codecov](https://codecov.io/gh/PDBe-KB/component-representative-structures/branch/main/graph/badge.svg?token=3ZCLLYC7fJ)](https://codecov.io/gh/PDBe-KB/component-representative-structures)|[![Maintainability](https://api.codeclimate.com/v1/badges/d755f853ff8e067d0eb9/maintainability)](https://codeclimate.com/github/PDBe-KB/component-representative-structures/maintainability)|

***

#### Image Gallery Component

This repository is for the codebase of a lightweight Angular v7 web component that displays images for molecular entities in a gallery.

This web component is used on PDBe-KB Aggregated Views of Proteins and Aggregated Views of Ligands to display macromolecular interaction partners and ligands.

<img src="https://raw.githubusercontent.com/PDBe-KB/component-image-gallery/main/pdbe-kb-gallery.png">

|Code Repository|Status|Test Coverage|Maintainability|
|---|---|---|---|
|[Image Gallery Component](https://github.com/PDBe-KB/component-image-gallery)|[![Build Status](https://www.travis-ci.com/PDBe-KB/component-image-gallery.svg?branch=main)](https://www.travis-ci.com/PDBe-KB/component-image-gallery)|[![codecov](https://codecov.io/gh/PDBe-KB/component-image-gallery/branch/main/graph/badge.svg?token=CjBzPrqddz)](https://codecov.io/gh/PDBe-KB/component-image-gallery)|[![Maintainability](https://api.codeclimate.com/v1/badges/87a94f87fe1c42776b7c/maintainability)](https://codeclimate.com/github/PDBe-KB/component-image-gallery/maintainability)|

***

#### Similar Proteins Component

This repository is for the codebase of a lightweight Angular v7 web component that displays information on similar proteins to an input UniProt accession.

This web component is used on PDBe-KB Aggregated Views of Proteins to display PDB entries where the PDB sequence is similar to any PDB sequence of a UniProt accession, and any UniProt accessions in the same UniRef90 cluster as the protein of interest.

<img src="https://raw.githubusercontent.com/PDBe-KB/component-similar-proteins/main/pdbe-kb-similar-proteins.png">

|Code Repository|Status|Test Coverage|Maintainability|
|---|---|---|---|
|[Similar Proteins Component](https://github.com/PDBe-KB/component-similar-proteins)|[![Build Status](https://www.travis-ci.com/PDBe-KB/component-similar-proteins.svg?branch=main)](https://www.travis-ci.com/PDBe-KB/component-similar-proteins)|[![codecov](https://codecov.io/gh/PDBe-KB/component-similar-proteins/branch/main/graph/badge.svg?token=0VDtWybneZ)](https://codecov.io/gh/PDBe-KB/component-similar-proteins)|[![Maintainability](https://api.codeclimate.com/v1/badges/9fa3b1ec78b88d5f47ba/maintainability)](https://codeclimate.com/github/PDBe-KB/component-similar-proteins/maintainability)|

***

#### Literature Panel Component

This repository is for the codebase of a lightweight Angular v7 web component that provides information on literature, generally from PubMed/EuropePMC.

This component is used on the PDBe-KB Aggregated Views of Proteins to display publications related to all the PDB entries of a UniProt accession.

<img src="https://raw.githubusercontent.com/PDBe-KB/component-literature-panel/main/pdbe-kb-literature-panel.png">

|Code Repository|Status|Test Coverage|Maintainability|
|---|---|---|---|
|[Literature Panel Component](https://github.com/PDBe-KB/component-literature-panel)|[![Build Status](https://www.travis-ci.com/PDBe-KB/component-literature-panel.svg?branch=main)](https://www.travis-ci.com/PDBe-KB/component-literature-panel)|[![codecov](https://codecov.io/gh/PDBe-KB/component-literature-panel/branch/main/graph/badge.svg?token=LE7P93G7A5)](https://codecov.io/gh/PDBe-KB/component-literature-panel)|[![Maintainability](https://api.codeclimate.com/v1/badges/3df9aa685e8b62072d28/maintainability)](https://codeclimate.com/github/PDBe-KB/component-literature-panel/maintainability)|

***

#### CSV/JSON/BibTeX Exporter Component

This repository is for the codebase of a lightweight Angular v7 web component that allows the users to download data in CSV, JSON and BibTeX formats.

The component is used on the PDBe-KB Aggregated Views of Proteins to provide download at various sections of these pages.

<img src="https://raw.githubusercontent.com/PDBe-KB/component-csv-exporter/main/pdbe-kb-csv-exporter.png">

|Code Repository|Status|Test Coverage|Maintainability|
|---|---|---|---|
|[CSV Exporter Component](https://github.com/PDBe-KB/component-csv-exporter)|[![Build Status](https://www.travis-ci.com/PDBe-KB/component-csv-exporter.svg?branch=main)](https://www.travis-ci.com/PDBe-KB/component-csv-exporter)|[![codecov](https://codecov.io/gh/PDBe-KB/component-csv-exporter/branch/main/graph/badge.svg?token=SADIB9IIC1)](https://codecov.io/gh/PDBe-KB/component-csv-exporter)|[![Maintainability](https://api.codeclimate.com/v1/badges/32945c274a482e312448/maintainability)](https://codeclimate.com/github/PDBe-KB/component-csv-exporter/maintainability)|

***

#### Download Component

This repository is for the codebase of a lightweight Angular v6.1 web component that provides download functionality for coordinate files, validation reports and sequences.

The web component is used on PDBe-KB Aggregated Views of Proteins to provide download options for coordinate files, sequences and validation reports.

<img src="https://raw.githubusercontent.com/PDBe-KB/component-download/main/pdbe-kb-download-component.png">

|Code Repository|Status|Test Coverage|Maintainability|
|---|---|---|---|
|[Download Component](https://github.com/PDBe-KB/component-download)|[![Build Status](https://www.travis-ci.com/PDBe-KB/component-download.svg?branch=main)](https://www.travis-ci.com/PDBe-KB/component-download)|[![codecov](https://codecov.io/gh/PDBe-KB/component-download/branch/main/graph/badge.svg?token=4493EGB4A3)](https://codecov.io/gh/PDBe-KB/component-download)|[![Maintainability](https://api.codeclimate.com/v1/badges/0ea50de6bcc06953d8f4/maintainability)](https://codeclimate.com/github/PDBe-KB/component-download/maintainability)|

***

#### Superpose Component

This repository is for the codebase of a lightweight Angular v7 web component that displays a button that can open a MolStar dialog window.

This web component is used on PDBe-KB Aggregated Views of Proteins to display superposed macromolecular structures and ligands.

<img src="https://raw.githubusercontent.com/PDBe-KB/component-superpose/main/pdbe-kb-superpose.png">

|Code Repository|Status|Test Coverage|Maintainability|
|---|---|---|---|
|[Superpose Component](https://github.com/PDBe-KB/component-superpose)|[![Build Status](https://www.travis-ci.com/PDBe-KB/component-superpose.svg?branch=main)](https://www.travis-ci.com/PDBe-KB/component-superpose)|[![codecov](https://codecov.io/gh/PDBe-KB/component-superpose/branch/master/graph/badge.svg?token=wDmfiy2Cje)](https://codecov.io/gh/PDBe-KB/component-superpose)|[![Maintainability](https://api.codeclimate.com/v1/badges/c47cb6b2a01acfa1b4fa/maintainability)](https://codeclimate.com/github/PDBe-KB/component-superpose/maintainability)|

***

#### Tutorials Component

This repository is for the codebase of a lightweight Angular v7 web component that displays embedded YouTube videos.

This component is used on the PDBe-KB Aggregated Views of Proteins to display tutorial videos which describe the various functionality of these pages.

<img src="https://raw.githubusercontent.com/PDBe-KB/component-tutorial/main/pdbe-kb-tutorial-component.png">

|Code Repository|Status|Test Coverage|Maintainability|
|---|---|---|---|
|[Tutorials Component](https://github.com/PDBe-KB/component-tutorial)|[![Build Status](https://travis-ci.com/PDBe-KB/component-tutorial.svg?branch=main)](https://travis-ci.com/PDBe-KB/component-tutorial)|[![codecov](https://codecov.io/gh/PDBe-KB/component-tutorial/branch/main/graph/badge.svg?token=BkbaUkNjUw)](https://codecov.io/gh/PDBe-KB/component-tutorial)|[![Maintainability](https://api.codeclimate.com/v1/badges/db7b6f4b831ec5bac982/maintainability)](https://codeclimate.com/github/PDBe-KB/component-tutorial/maintainability)|

***

#### Multi-entry View Component

This repository is for the codebase of a lightweight Angular v7 web component that lists all the UniProt accessions for a PDB entry, i.e. PDB chains may belong to different UniProt accessions.

This component is used on the PDBe-KB Aggregated Views of Proteins to display a table of all the UniProt accessions and processed protein identifiers (PRO id) for a particular PDB entry.

<img src="https://raw.githubusercontent.com/PDBe-KB/component-multi-view/main/pdbe-kb-multi-view.png">

|Code Repository|Status|Test Coverage|Maintainability|
|---|---|---|---|
|[Multi-View Component](https://github.com/PDBe-KB/component-multi-view)|[![Build Status](https://www.travis-ci.com/PDBe-KB/component-multi-view.svg?branch=main)](https://www.travis-ci.com/PDBe-KB/component-multi-view)|[![codecov](https://codecov.io/gh/PDBe-KB/component-multi-view/branch/main/graph/badge.svg?token=XYSKQV18FH)](https://codecov.io/gh/PDBe-KB/component-multi-view)|[![Maintainability](https://api.codeclimate.com/v1/badges/1852ac5538a63c058263/maintainability)](https://codeclimate.com/github/PDBe-KB/component-multi-view/maintainability)|

***

#### Structure Coverage Component

This repository is for the codebase of a lightweight Angular v7 web component that displays all the available PDB entries for a particular UniProt accession in a tabular format.

This component is used on the PDBe-KB Aggregated Views of Proteins to display information on devices that are to small to use the standard sequence feature viewer, ProtVista.

<img src="https://raw.githubusercontent.com/PDBe-KB/component-coverage-table/main/pdbe-kb-coverage-table.jpg">

|Code Repository|Status|Test Coverage|Maintainability|
|---|---|---|---|
|[Structure Coverage Component](https://github.com/PDBe-KB/component-coverage-table)|[![Build Status](https://www.travis-ci.com/PDBe-KB/component-coverage-table.svg?branch=main)](https://www.travis-ci.com/PDBe-KB/component-coverage-table)|[![codecov](https://codecov.io/gh/PDBe-KB/component-coverage-table/branch/main/graph/badge.svg?token=QA6OCNOB1E)](https://codecov.io/gh/PDBe-KB/component-coverage-table)|[![Maintainability](https://api.codeclimate.com/v1/badges/4de133cf4cdd7ce170eb/maintainability)](https://codeclimate.com/github/PDBe-KB/component-coverage-table/maintainability)|

***

#### Ping Component

This repository is for the codebase of a lightweight Angular v7 web component that makes GET requests to specified URLs.

This web component is used on the PDBe-KB Aggregated Views of Proteins to generate web traffic for PDBe-KB partner resources who have contributed annotations for a particular protein of interest.

|Code Repository|Status|Test Coverage|Maintainability|
|---|---|---|---|
|[Ping Component](https://github.com/PDBe-KB/component-ping-resources)|[![Build Status](https://www.travis-ci.com/PDBe-KB/component-ping-resources.svg?branch=master)](https://www.travis-ci.com/PDBe-KB/component-ping-resources)|[![codecov](https://codecov.io/gh/PDBe-KB/component-ping-resources/branch/master/graph/badge.svg?token=GLYUFFF6QX)](https://codecov.io/gh/PDBe-KB/component-ping-resources)|[![Maintainability](https://api.codeclimate.com/v1/badges/cf98b84b88b21a3e6fb5/maintainability)](https://codeclimate.com/github/PDBe-KB/component-ping-resources/maintainability)|

***

#### Annotations provided by PDBe-KB Consortium Members
These are documentations for data providers who contribute annotations to PDBe-KB

##### 1-9
* [14-3-3-pred](https://github.com/PDBe-KB/pdbe-kb-manual/wiki/14-3-3-pred)
* [3DComplex](https://github.com/PDBe-KB/pdbe-kb-manual/wiki/3DComplex)
* [3DLigandSite](https://github.com/PDBe-KB/pdbe-kb-manual/wiki/3DLigandSite)
##### A
* [AKID](https://github.com/PDBe-KB/pdbe-kb-manual/wiki/AKID)
##### C
* [CaMKiNet](https://github.com/PDBe-KB/pdbe-kb-manual/wiki/CaMKiNet)
* [canSAR](https://github.com/PDBe-KB/pdbe-kb-manual/wiki/canSAR)
* [CATH-FunSites](https://github.com/PDBe-KB/pdbe-kb-manual/wiki/CATH-FunSites)
* [ChannelsDB](https://github.com/PDBe-KB/pdbe-kb-manual/wiki/ChannelsDB)
* [Covalentizer](https://github.com/PDBe-KB/pdbe-kb-manual/wiki/Covalentizer)
##### D
* [DEPTH](https://github.com/PDBe-KB/pdbe-kb-manual/wiki/DEPTH)
* [DynaMine](https://github.com/PDBe-KB/pdbe-kb-manual/wiki/DynaMine)
##### E
* [EFoldMine](https://github.com/PDBe-KB/pdbe-kb-manual/wiki/EFoldMine)
* [ELM](https://github.com/PDBe-KB/pdbe-kb-manual/wiki/ELM)
* [EMV](https://github.com/PDBe-KB/pdbe-kb-manual/wiki/EMV)
##### F
* [FireProt DB](https://github.com/PDBe-KB/pdbe-kb-manual/wiki/FireProt-DB)
* [FoldX](https://github.com/PDBe-KB/pdbe-kb-manual/wiki/FoldX)
##### K
* [KinCore](https://github.com/PDBe-KB/pdbe-kb-manual/wiki/KinCore)
* [KnotProt](https://github.com/PDBe-KB/pdbe-kb-manual/wiki/KnotProt)
##### M
* [Mechanism And Catalytic Site Atlas](https://github.com/PDBe-KB/pdbe-kb-manual/wiki/Mechanism-And-Catalytic-Site-Atlas)
* [MetalPDB](https://github.com/PDBe-KB/pdbe-kb-manual/wiki/MetalPDB)
* [Missense3D](https://github.com/PDBe-KB/pdbe-kb-manual/wiki/Missense3D)
* [MolMeDB](https://github.com/PDBe-KB/pdbe-kb-manual/wiki/MolMeDB)
##### P
* [P2rank](https://github.com/PDBe-KB/pdbe-kb-manual/wiki/P2rank)
* [POPScomp](https://github.com/PDBe-KB/pdbe-kb-manual/wiki/POPScomp)
* [ProKinO](https://github.com/PDBe-KB/pdbe-kb-manual/wiki/ProKinO)
##### S
* [Scop3P](https://github.com/PDBe-KB/pdbe-kb-manual/wiki/Scop3P)
* [SKEMPI2](https://github.com/PDBe-KB/pdbe-kb-manual/wiki/SKEMPI2)
##### W
* [WEBnm@](https://github.com/PDBe-KB/pdbe-kb-manual/wiki/WEBnm@)

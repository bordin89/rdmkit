---
title: Structural Bioinformatics
keywords: optional
search: exclude
contributors: [<!---REPLACE THIS with comma separated list of contributors--->]
tags: [<!---REPLACE THIS with comma separated list of (outgoing) tags to other pages related to this page--->]
---

<!--- Domain pages should detail the particular data management challenges of the domain, typically by complementing and extending one or more existing Problem pages.
In the event that no adequate Problem page exists for a problem that can be generalized across domains, consider first contributing to create one or raising a GitHub issue. However, if a problem is entirely domain specific, then it should be fully detailed within the respective Domain page. --->

## Introduction

<!--- In this section you should provide a brief overview of the domain from the data management perspective, mentioning and putting into context the challenges that are particular to the domain, which will be the object of sections below. --->


## Structure Prediction

## Introduction
 
### Description
<!--- Sections within Domain pages (aside from "Introduction" at the start and "Relevant tools and resources " at the end) should focus on particular data management problems, which should be described in this first sub-section.
For problems that are fully domain-specific, a detailed description is merited.
For detailing the domain-specific challenges of a problem that is generic, please link to the corresponding generic Problem page before going into the domain-specific challenges. --->

### Considerations <!--- (optional) --->
<!---  Direct and concise considerations, structured in bullet points and typically framed as questions RDMKit reader should ask themselves in order to arrive at the best solution among those listed below. One level of nesting of bullet points within considerations is fine, but more levels should be avoided. --->

- Identifying the protein (UniProtID)
- Is the structure already available? Whole -> PDB, part of it -> domain databases
Where do we get the templates(PDBid).
Map structure over sequence (known)
Predict structure from sequence (unknown, yet)
 - Various levels of model quality (gen.idea of structure -> drug design).



### Solutions
<!--- Detail, either in normal text or in bullet points, the domain-specific solutions to the problem. Do not merely list tools or resources, as they will be automatically listed in the bottom section, but you can and should mention tools and resources listed below if you detail their usage to solve the problem. --->

<!--- ## Section 2 Title --->
<!--- Add more sections as needed, with the same subsections as above. --->
...

Underlying methodology (co-variation)
Library optimization tools
Multiple Sequence Alignment (incl. Sequence databases) (Sometimes users need to provide alignments) - Informative alignments (DOPS, Neffs)
Quality measurements (NDOPE, QMEAN, QMEAN-DISCO)



## Relevant tools and resources  
<!--- Automatically generated table; edit the TAG below to the tag for this page, so that tools that have this page's tag are listed here. You can get the tag for this page from the [list of tags](https://github.com/elixir-europe/rdmkit/blob/master/_data/tags.yml). If it isn't listed there, please raise an issue.--->

    Public repositories of structural data: Protein Data Bank (PDB) and Electron Microscopy Data Bank (EMDB), and tools to search and analyse information in these   repositories from PDBe (Protein Data Bank in Europe) including PDBe-KB
    UniProt and basic Sequence alignment tools
    Protein structure analysis and classification: HMMER, InterPro, Pfam, CATH, PDBeFold, PDBePISA
    Protein structure prediction and docking: PHYRE2 and HADDOCK
    Structure validation and assessment tools and strategies
    Tools and resources for drug discovery: ChEMBL

Add links and one-liner with description and group leader

SWISSMODEL
Rosetta - Gremlin
CASP
PHYRE
GenThreader
DOMSERF
GENE3D
FUGUE
SUPERFAMILY
3DBeacons
Genome3D


{% include toollist.html tag="<!---TAG--->" %}

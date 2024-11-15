---
title: 'BioHackEU24 report: Recognising research software contributions leveraging the ELIXIR infrastructure'
title_short: 'BioHackEU24 #25: Software contributions in APICURON'
tags:
  - APICURON
  - research recognition
  - OpenEBench
  - ELIXIR
authors:
  - name: Adel Bouhraoua
    orcid: 0000-0001-9531-6339
    affiliation: 1
  - name: Gavin Farrel
    orcid: 
    affiliation: 1
  - name: José M. Fernández
    orcid: 0000-0002-4806-5140
    affiliation: 2
affiliations:
  - name: BioComputingUP, University of Padova
    index: 1
  - name: Barcelona Supercomputing Center (BSC), ELIXIR Spain, Barcelona, Spain
    index: 2
date: 8 November 2024
cito-bibliography: paper.bib
event: BH24EU
biohackathon_name: "BioHackathon Europe 2024"
biohackathon_url:   "https://biohackathon-europe.org/"
biohackathon_location: "Barcelona, Spain, 2024"
group: Project 25
# URL to project git repo --- should contain the actual paper.md:
git_url: https://github.com/inab/BioHackEU24_project_25_preprint
# This is the short authors description that is used at the
# bottom of the generated paper (typically the first two authors):
authors_short: Bouhraoua \emph{et al.}
---


# Introduction

As part of the BioHackathon Europe 2024, the proposed project has aimed to enhance the capabilities of the ELIXIR infrastructure to track, credit, and recognise software contributions made by research software engineers. The project has sought to foster collaboration and engagement within the ELIXIR Communities and platforms by working with different stakeholders, including individual contributors to research software, to indicators that help measure the value of these contributions.

The primary objective of this project is to promote a strong sense of community by recognising individual software contributions. We plan to connect APICURON and GitHub to track open-source research software contributions and reward each contributor for their efforts. We will also link OpenEBench evaluation data to this process by crosslinking GitHub repositories available in the Software Observatory section with APICURON. This will involve retrieving activity data from GitHub and OpenEBench, processing it, and integrating it into the APICURON platform. Recognition items will be pushed to ORCID from APICURON and made available for third-party services.

We will leverage the involvement of APICURON and OpenEBench in the Data and Tools platforms and in the ELIXIR STEERS and EVERSE projects. These platforms and projects provide a network of stakeholders and guidance for implementing a fair recognition infrastructure.

The project's usefulness lies in its ability to address a significant gap in the recognition and valuation of research software contributions. By providing a framework for recognition, we can incentivise and motivate developers to contribute to open-source software projects, leading to improved software quality and reproducibility and positively impacting the environment by reducing the carbon footprint.

# Formatting

This document use Markdown and you can look at [this tutorial](https://www.markdowntutorial.com/).

## Subsection level 2

Please keep sections to a maximum of only two levels.

## Tables and figures

Tables can be added in the following way, though alternatives are possible:

Table: Note that table caption is automatically numbered and should be
given before the table itself.

| Header 1 | Header 2 |
| -------- | -------- |
| item 1 | item 2 |
| item 3 | item 4 |

A figure is added with:

![Caption for BioHackrXiv logo figure](./biohackrxiv.png)

# Other main section on your manuscript level 1

Lists can be added with:

1. Item 1
2. Item 2

# Citation Typing Ontology annotation

You can use [CiTO](http://purl.org/spar/cito/2018-02-12) annotations, as explained in [this BioHackathon Europe 2021 write up](https://raw.githubusercontent.com/biohackrxiv/bhxiv-metadata/main/doc/elixir_biohackathon2021/paper.md) and [this CiTO Pilot](https://www.biomedcentral.com/collections/cito).
Using this template, you can cite an article and indicate _why_ you cite that article, for instance DisGeNET-RDF [@citesAsAuthority:Queralt2016].

The syntax in Markdown is as follows: a single intention annotation looks like
`[@usesMethodIn:Krewinkel2017]`; two or more intentions are separated
with colons, like `[@extends:discusses:Nielsen2017Scholia]`. When you cite two
different articles, you use this syntax: `[@citesAsDataSource:Ammar2022ETL; @citesAsDataSource:Arend2022BioHackEU22]`.

Possible CiTO typing annotation include:

* citesAsDataSource: when you point the reader to a source of data which may explain a claim
* usesDataFrom: when you reuse somehow (and elaborate on) the data in the cited entity
* usesMethodIn
* citesAsAuthority
* citesAsEvidence
* citesAsPotentialSolution
* citesAsRecommendedReading
* citesAsRelated
* citesAsSourceDocument
* citesForInformation
* confirms
* documents
* providesDataFor
* obtainsSupportFrom
* discusses
* extends
* agreesWith
* disagreesWith
* updates
* citation: generic citation


# Results


# Discussion

...

## Acknowledgements

...

## References

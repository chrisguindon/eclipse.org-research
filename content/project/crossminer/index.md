---
title: "CROSSMINER"
date: 2020-03-12T09:24:17-04:00
logo: "/images/research/crossminer.png"
tags: []
homepage: "https://www.crossminer.org/"
facebook: ""
linkedin: ""
twitter: "http://www.twitter.com/crossminer"
youtube: ""
funding_bodies: ["horizon2020"]
eclipse_projects: ["technology.scava"]
project_type: success
summary: "Developer-Centric Knowledge Mining from Large Open-Source Software Repositories"
---
# OVERVIEW

Implementing a new system by mining open source software (OSS) repositories helps reduce development effort and concurrently increase productivity. Furthermore, as the OSS ecosystem facilitates vibrant expert and user communities, developers can get practical supports which allow them to fix bugs as well as to find probable solutions to various issues alongside the development cycle. Nevertheless, to help developers effectively mine the existing data, it is crucial to equip them with suitable machineries.

Eclipse SCAVA is an open-source platform for automatically analysing the source code, bug tracking systems, and communication channels of open source software projects. Eclipse SCAVA provides techniques and tools for extracting knowledge from existing open source components and use such knowledge to support the selection and reuse of existing software to develop new systems, and to provide developers with real-time recommendations that are relevant to the current development task.

As shown below Eclipse SCAVA is conceptually in between the developer and all the different and heterogenous data sources that one needs to interact with when understanding and using existing open source components.
{{< figure src="crossminer.png" alt="CROSSMINER Architecture" class="vertical-align" width="600">}}


The developer context is used as query sent to the knowledge base that answers with recommendations that are relevant with respect to the developer contexts. Machine learning techniques are used to infer knowledge underpinning the creation of relevant real-time recommendations. The knowledge base infers more insights from raw data produced by the different mining tools, which are the following:

* Source code miners to extract and store actionable knowledge from the source code of a collection of open-source projects;
* NLP miners to extract quality metrics related to the communication channels, and bug tracking systems of OSS projects by using Natural Language Processing and text mining techniques;
* Configuration miners to gather and analyse system conﬁguration artefacts and data to provide an integrated DevOps-level view of a considered open source project;
* Cross-project miners to infer cross-project relationships and additional knowledge underpinning the provision of real-time recommendations;

Additionally, Eclipse SCAVA provide the means to simplify the development of bespoke analysis and knowledge extraction tools by contributing a framework that will shield engineers from technological issues and allow them to concentrate on the core analysis tasks instead.

# USEFUL LINKS
* EU CROSSMINER **home project**: http://www.crossminer.org  


* Eclipse Scava **code repository**: https://github.com/eclipse-researchlabs/scava (*)
* Eclipse Scava **deployment repository**: https://github.com/eclipse-researchlabs/scava-deployment (*)
* Eclipse Scava **documentation repository**: https://github.com/eclipse-researchlabs/scava-docs (*)
* Eclipse Scava **datasets** - Clone: https://github.com/eclipse-scava/scava-datasets.git


(*) Repositories under the umbrella of Eclipse Research Labs have not (yet) completed the Eclipse IP review to ensure they provide sufficient IP terms to be considered "business-friendly" for use in a product.

This project was running from January 2017 - December 2019.

# Consortium
* X/OPEN COMPANY LIMITED - United Kingdom
* UNIVERSITY OF YORK YORK - United Kingdom
* UNIVERSITA DEGLI STUDI DELL'AQUILA - Italy
* EDGE HILL UNIVERSITY - United Kingdom
* STICHTING CENTRUM VOOR WISKUNDE EN INFORMATICA - Netherlands
* ATHENS UNIVERSITY OF ECONOMICS AND BUSINESS - RESEARCH CENTER - Greece
* UNPARALLEL INNOVATION LDA - Portugal
* SOFTEAM - France
* FRONTENDART SZOFTVER KFT - Hungary
* BITERGIUM SLL - Spain
* OW2 CONSORTIUM ASSOCIATION  - France
* ECLIPSE FOUNDATION EUROPE GMBH - Germany
* CASTALIA SOLUTIONS - France

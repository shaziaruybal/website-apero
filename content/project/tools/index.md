---
author: Shazia Ruybal-Pesántez
description: ""
layout: single
show_author_byline: false
show_post_date: false
show_post_thumbnail: false
excerpt: "I focus on developing computational tools, training resources, and collaborative frameworks for public health surveillance"
subtitle: "I aim to develop tools that help ensure that molecular (genomics and serology) methods are not
only scientifically robust, but also feasible, interpretable, and useful for disease control programs."
thumbnail_left: false
featured: yes
title: Open-source tools and informing policy
---

### Transmission chain inference for malaria outbreak analytics
Advanced methods that extract meaningful genetic signals from pathogen genomic data, combined with 
epidemiological data, enabled reconstruction of transmission chains and significantly strengthened 
COVID-19 response strategies. While these methods are well-established for viral pathogens, they are not 
directly applicable to malaria because *Plasmodium* parasites evolve in fundamentally different ways. 
These unique biological features, including the non-linear accumulation of genetic diversity due to sexual 
recombination in the mosquito vector, and the potential reactivation of dormant hypnozoites in the 
liver, causing relapses in the case of *P. vivax*, require novel approaches to ‘unlock’ the parasite’s 
genetic signals. My [La Caixa Junior Leader fellowship](/research_projects/caixa_fellowship) research program focuses
on developing open-source tools to support public health applications in malaria molecular surveillance, including:

- **{malariafwd}**: a simulation-based framework for *Plasmodium* genetic epidemiology, in particular this focuses on development 
of a population genetic simulator for *P. vivax* to ground truth expected genetic signals of *P. vivax* relapses
- **{plasmodiff}**: a diffusion network-based framework for reconstructing malaria transmission networks and estimating effective 
reproduction numbers from genomic and epidemiological data 


### *Plasmodium* genomic epidemiology analysis resources 
As genomic surveillance becomes more widely used in malaria research and control, there is growing need for
community resources that improve software discoverability, standardization, benchmarking, and practical usability. 
My work has contributed to this area by helping develop simulation-based approaches to evaluate the “power” of malaria genomic
surveillance designs and co-leading development of the [SIMPLEGEN simulation framework](/blog/simplegen) (Ruybal-Pesántez and Verity,
unpublished), as well as by spearheading [PGEforge](/blog/pgeforge), a centralized resource for malaria genomic analysis tools, workflows, and
documentation ([Ruybal-Pesántez et al., 2025](https://doi.org/10.1101/2025.04.01.25325032)). 
This work aims to make malaria genomic methods not only scientifically rigorous, but also more transparent, interoperable, and easier for researchers and surveillance teams to use in practice. 

- **PGEforge**: community-led effort to improve accessability and public health application of *Plasmodium* genomic epidemiology
- **RADISH** and other hackathons: in close collaboration with the [Plasmodium Genomic Epidemiology Network](https://plasmogenepi.org) we have organized
several [hackathons](https://mrc-ide.github.io/PGEforge/website_docs/radish23.html) to jointy tackle issues in *Plasmodium* genomic epidemiology analysis, 
including landscaping available analysis software, building end-to-end analysis workflows, and benchmarking available tools.

[Read more →](https://mrc-ide.github.io/PGEforge) 

### Decision-support tools to inform policy
A focus of my work is the design of practical, policy-relevant approaches to malaria genomic surveillance. In direct collaboration with the 
WHO Global Malaria Programme I have worked on statistical and analytical decision-support
tools to support study design and powering malaria molecular surveillance studies. The ([DRpower *pfhrp2/3* planner](https://shiny.dide.ic.ac.uk/DRpower-app)) 
supports researchers and control programme officers with a robust statistical tool for designing studies for parasite diagnostic resistance surveillance.
This decision-support tool has been integrated into WHO malaria surveillance policy.

My previous work has also supported serosurveillance efforts, including development of the [covidClassifyR](/blog/covidclassifyr) decision-support tool, which embeds a machine learning classification algorithm with data quality and control processing functionalities to enable an end-to-end workflow for determining prior exposure to SARS-CoV-2 from unknown Luminex sample data. This was applied during the COVID-19 
emergency response in Papua New Guinea, and continue to be used for research, including spin-off versions of the app for similar malaria serosurveillance efforts. I have also been involved
in seroanalytics tool development, including the LIMES hackathon (Landscaping Inferential Modeling and Epidemiological tools for Serology) organized by my collaborators at the Johns Hopkins Seroanalytics Hub. 


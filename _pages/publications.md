---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Below is a list of selected publications and preprints. For a full list, please visit my [Google Scholar page](https://scholar.google.be/citations?user=3PHGkxkAAAAJ&hl=en). My work has mostly focussed on differential expression analysis of high-throughput sequencing datasets.

# Statistical methodology

 - [Trajectory-based differential expression analysis for single-cell sequencing data](https://www.biorxiv.org/content/10.1101/623397v1).
 - (Review) [RNA Sequencing Data: Hitchhiker's Guide to Expression Analysis](https://www.annualreviews.org/doi/10.1146/annurev-biodatasci-072018-021255)
 - [Observation weights unlock bulk RNA-seq tools for zero inflation and single-cell applications](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-018-1406-4)
 - [stageR: a general stage-wise method for controlling the gene-level false discovery rate in differential expression and differential transcript usage](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-017-1277-0)
 
 # Collaborative papers
 
  - [A sex-inducing pheromone triggers cell cycle arrest and mate attraction in the diatom Seminavis robusta](https://www.nature.com/articles/srep19252)
  - [Neurogenomic profiling reveals distinct gene expression profiles between brain parts that are consistent in Ophthalmotilapia cichlids](https://www.frontiersin.org/articles/10.3389/fnins.2018.00136/full?report=reader)
 


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

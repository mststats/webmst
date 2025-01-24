+++
title = "Computational modelling of Chromosomally Clustering Protein Domains In Bacteria"
date = 2021-12-13T00:00:00

# Authors. Comma separated list
authors = ["Chiara E Cotroneo", "Isobel Claire Gormley", "Denis C Shields", "Michael Salter-Townshend"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "BMC Bioinformatics"
#publication_short = "In "

# Abstract and optional shortened version.
abstract = "Background: In bacteria, genes with related functions - such as those involved in the metabolism of the same compound or in infection processes - are often physically close on the genome and form groups called clusters. The enrichment of such clusters over various distantly related bacteria can be used to predict the roles of genes of unknown function that cluster with characterised genes. There is no obvious rule to define a cluster, given their variability in size and intergenic distances, and the definition of what comprises a “gene”, since genes can gain and lose domains over time. Protein domains can cluster within a gene, or in adjacent genes of related function, and in both cases these are chromosomally clustered. Here, we model the distances between pairs of protein domain coding regions across a wide range of bacteria and archaea via a probabilistic two component mixture model, without imposing arbitrary thresholds in terms of gene numbers or distances.  Results: We trained our model using matched Gene Ontology terms to label functionally related pairs and assess the stability of the parameters of the model across 14, 178 archaeal and bacterial strains. We found that the parameters of our mixture model are remarkably stable across bacteria and archaea, except for endosymbionts and obligate intracellular pathogens. Obligate pathogens have smaller genomes, and although they vary, on average do not show noticeably different clustering distances; the main difference in the parameter estimates is that a far greater proportion of the genes sharing ontology terms are clustered. This may reflect that these genomes are enriched for complexes encoded by clustered core housekeeping genes, as a proportion of the total genes. Given the overall stability of the parameter estimates, we then used the mean parameter estimates across the entire dataset to investigate which gene ontology terms are most frequently associated with clustered genes.  Conclusions: Given the stability of the mixture model across species, it may be used to predict bacterial gene clusters that are shared across multiple species, in addition to giving insights into the evolutionary pressures on the chromosomal locations of genes in different species."
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
featured = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = ["statgen"]

# Links (optional).
#url_pdf = "#"
#url_preprint = "#"
#url_code = "#"
#url_dataset = "#"
#url_project = "#"
#url_slides = "#"
#url_video = "#"
#url_poster = "#"
#url_source = "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
links = [{name = "DOI", url = "https://doi.org/10.1186/s12859-021-04512-x"},
{name="preprint",url="https://www.researchsquare.com/article/rs-646589/latest.pdf"}]


# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
#[header]
#image = "headers/bubbles-wide.jpg"
#caption = "My caption :smile:"

+++


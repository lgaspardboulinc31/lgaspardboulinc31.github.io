---
layout: page
title: Blood cancer
description: Leukemia stem cell resistance
img: assets/img/project_preview/AML.png
importance: 2
category: work
giscus_comments: false
---

# Introduction
Acute myeloid leukemia (AML) is a deadly disease characterised by the abnormal
proliferation of undifferentiated leukemia blasts and the impairment of haematopoiesis. Due to
high relapse and poor prognosis, current therapies fail to definitively cure patients leaving
behind the highly proliferating and self-renewing leukemia stem cells (LSCs). The crucial role
of Growth arrest and DNA-damage inducible protein (GADD45a), a tumour suppressor gene,
has been shown to have self-renewal capacities in LSCs. However, little is known about the
gene network and regulation of GADD45a in AML.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/project_preview/LSC.png" title="Leukemia stemm cells" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
Conventional therapy removes the bulk of the disease whereas chemoresistant leukemia stem cells remain. Self-renewal and high proliferation allow LSC to re-establish the tumour, causing disease relapse. Targeting specifically LSC may efficiently kill LSC resulting in tumour degeneration. Adapted from Reya et al. 2001.
</div>

# Uncovering GADD45A KO effects in Leukemia Stem cells
Using CRISPR-induced GADD45a knockout patient-derived xenograft cells, regulation of GADD45a and its gene network are under investigation through the use of a novel single-cell technology, Cellular Indexing of Transcriptome and Epitopes by sequencing (CITE-seq). Data analysis using Seurat R package allows us to identify LSC population and probe differential gene expression.
We uncovered that 27 genes are upregulated upon GADD45a KO. Ten genes, BIRC7, CD37, CD69, DPEP1, DUSP1, FOS, LYL1, eEF1A2, FTH1, and FTL were already characterised in different subtypes of leukemia. Many of the others are also involved in cancer-related pathways and may potentially participate in the enhanced aggressivity of AML. This study provides new insights into the potential genes that are mediated by GADD45a and are associated with LSC function. Thus, molecular analyses of LSCs warrant further investigation to uncover new potential therapeutic targets, which may continue to be a rich source of exciting new discoveries.

# Related related_publications

Nunki Hassan, Hangyu Yi, Bilal Malik, **Lucie Gaspard-Boulinc**, Saumya E. Samaraweera, Debora A. Casolari, Janith Seneviratne, Anushree Balachandran, Tracy Chew, Alastair Duly, Daniel R. Carter, Belamy B. Cheung, Murray Norris, Michelle Haber, Maria Kavallaris, Glenn M. Marshall, Xu Dong Zhang, Tao Liu, Jianlong Wang, Dan A. Liebermann, Richard J. D’Andrea, Jenny Y. Wang; Loss of the stress sensor GADD45A promotes stem cell activity and ferroptosis resistance in LGR4/HOXA9-dependent AML. Blood 2024; 144 (1): 84–98. doi: <a href="https://doi.org/10.1182/blood.2024024072"> https://doi.org/10.1182/blood.2024024072 </a>

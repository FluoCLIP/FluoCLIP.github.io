---
layout: project_page
permalink: /

title: "FluoCLIP: Stain-Aware Focus Quality Assessment in Fluorescence Microscopy"
authors: "Hyejin Park<sup>1*</sup>, Jiwon Yoon<sup>1*</sup>, Sumin Park<sup>1</sup>, Suree Kim<sup>2</sup>, Sinae Jang<sup>1</sup>, Eunsoo Lee<sup>1</sup>,<br>Dongmin Kang<sup>1&dagger;</sup>, Dongbo Min<sup>1&dagger;</sup> (*: Equal Contribution, &dagger;: Corresponding Author)"
affiliations: "<sup>1</sup>Ewha Womans University, <sup>2</sup>Daesang"
paper: https://arxiv.org/abs/2602.23791
code: https://github.com/FluoCLIP/FluoCLIP
data: TBU
---

<!-- Using HTML to center the abstract -->
<div class="columns is-centered has-text-centered">
    <div class="column is-four-fifths">
        <h2>Abstract</h2>
        <div class="content has-text-justified">
Accurate focus quality assessment (FQA) in fluorescence microscopy remains challenging, as the stain-dependent optical properties of fluorescent dyes cause abrupt and heterogeneous focus shifts. However, existing datasets and models overlook this variability, treating focus quality as a stain-agnostic problem. In this work, we formulate the task of stain-aware FQA, emphasizing that focus behavior in fluorescence microscopy must be modeled as a function of staining characteristics. Through quantitative analysis of existing datasets (FocusPath, BBBC006) and our newly curated FluoMix, we demonstrate that focus–rank relationships vary substantially across stains, underscoring the need for stain-aware modeling in fluorescence microscopy. To support this new formulation, we propose FluoMix, the first dataset for stain-aware FQA that encompasses multiple tissues, fluorescent stains, and focus variations. Building on this dataset, we propose FluoCLIP, a two-stage vision-language framework that leverages CLIP’s alignment capability to interpret focus quality in the context of biological staining. In the stain-grounding phase, FluoCLIP learns general stain representations by aligning textual stain tokens with visual features, while in the stain-guided ranking phase, it optimizes stain-specific rank prompts for ordinal focus prediction. Together, our formulation, dataset, and framework establish the first foundation for stain-aware FQA, and FluoCLIP achieves strong generalization across diverse fluorescence microscopy conditions.
        </div>
    </div>
</div>

---


## Background


## Objective


## Key Contributions
1. We propose **FluoCLIP**, a two-stage ordinal vision–language framework that learns stain-specific grounding and stain-guided ranking for robust FQA.
2. We introduce **FluoMix**, a new dataset featuring diverse fluorescent stains and tissue-level focus variations, providing the first dataset for stain-aware FQA in fluorescence microscopy.
3. We formulate the task of **Stain-Aware FQA** in fluorescence microscopy, highlighting the need to model stain-dependent focus behavior. 


**TBU**

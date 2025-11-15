---
title: "Environmental detection of Burkholderia pseudomallei and associated melioidosis risk: a molecular detection and case-control cohort study"
authors:
- Barbara Kronsteiner
- Clement Twumasi
- Priyanka Abraham
- Suchintana Chumseng
- Panjaporn Chaichana
- Phumrapee Boonklang
- admin
- Kesorn Angchagun
- Narisara Chantratita
- Direk Limmathurotsakul
- Nicholas PJ Day
- Parinya Chamnan
- Claire Chewapreecha
- Susanna J Dunachie
date: "2025-11-15T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-11-15T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "medRxiv"
publication_short: "medRxiv"

abstract: "**Background:** Diabetes mellitus (DM) is a major risk factor for acquiring infections. Metformin, the first-line treatment for type 2 DM, is associated with beneficial outcome from various infectious diseases. The neglected tropical disease melioidosis has up to 50% in-hospital mortality rate and the highest risk association of DM with any infectious disease (12-fold increased risk). A better understanding of the impact of anti-hyperglycaemic drug treatment on disease outcome is needed.

**Methods:** We analysed the association of anti-hyperglycaemic treatment on outcome from acute melioidosis in 273 Thai patients with known DM using logistic regression and classification tree modelling while controlling for age, sex, HbA1c and history of renal impairment. Immunological parameters including T-cell and humoral responses to the pathogen as well as cytokine levels in blood were measured in a subset of individuals.

**Results:** We report higher survival rates in acute melioidosis patients with DM who were taking the glucose-lowering drug metformin prior to infection. Metformin use was associated with a 50% decrease in 28-day mortality whilst renal impairment was associated with a doubling of mortality after adjusting for covariates. Unsupervised classification tree modelling further identified glycaemic control and age as modifying factors of outcome. Furthermore, metformin treatment was associated with greater T-cell responsiveness and the presence of T-cell modulating cytokines.

**Conclusions:** We provide evidence for a protective effect of metformin in melioidosis and identify HbA1c and age as additional clinically relevant predictors of outcome. Further mechanistic research and randomized controlled trials are required to explore a causal link between metformin and protection from infectious diseases."

# Summary. An optional shortened abstract.
summary: ""

tags:
- Infectious disease
- Melioidosis
- Diabetes
- Machine learning
featured: false

hugoblox:
  ids:
    doi: 10.1101/2025.10.29.25338967

links:
- type: preprint
  provider: medRxiv
  url: https://www.medrxiv.org/content/10.1101/2025.10.29.25338967v1.full.pdf
#- type: code
#  url: https://github.com/arinwongprommoon/wongprommoonSinglecellMetabolicOscillations2024
#- type: slides
#  url: https://www.slideshare.net/
#- type: dataset
#  url: https://doi.org/10.7488/ds/7845
#- type: poster
#  url: "#"
#- type: source
#  url: "#"
#- type: video
#  url: https://youtube.com
#- type: custom
#  label: Custom Link
#  url: http://example.org

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

## Lay summary
Melioidosis is a neglected tropical disease caused by the bacterium _Burkholderia pseudomallei_, which can be acquired from the environment through contact with soil or water.  Type 2 diabetes is a major risk factor in acquiring the infection, though some past studies showed that some diabetes medications prevent deaths from melioidosis.  However, although metformin is the most common treatment for diabetes, we don't know whether it specifically prevents deaths from melioidosis.

To answer this question, we collected data from diabetes patients infected with melioidosis in northeast Thailand, an endemic area for melioidosis.  We show that metformin is indeed associated with a decreased risk of death from melioidosis, more so than other diabetes medications.  Furthermore, we built a classification tree model, a type of machine learning model, to find the best way to predict whether a patient dies based on their properties.  The model identifies metformin usage as the most important factor in helping predict whether a melioidosis patient dies, alongside blood sugar levels and age.

To explain why metformin helps melioidosis patients survive, we investigated the patients' immune response.  We observe that patients on metformin had a greater T-cell response, allowing them to target _Burkholderia pseudomallei_ antigens.  These patients also had higher levels of proteins in the blood that allow communication between immune cells to help them defend against bacteria.

Knowing that metformin helps melioidosis patients survive is important because this emphasises why we should help diabetes patients stay on medication as much as possible.

## My role
I curated the clinical data to allow the statistical analysis and building of machine learning models.

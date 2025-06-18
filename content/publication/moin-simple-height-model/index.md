---
# Documentation: https://docs.hugoblox.com/managing-content/

title: "Development and Validation of a Simple Model to Predict Patient Height"
authors: [moin, admin, Scott D. Halpern]
date: 2025-03-13T00:00:00-04:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2025-04-09T10:51:19-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "medrXiv"
publication_short: ""

abstract: |
  **Background**: Height recorded in electronic health records (EHRs) is used extensively in diagnosis and treatment, either in isolation or as a component of body-mass index (BMI), but is often falsely high because many adults overestimate their height. Statistical models to predict height could therefore improve population health, but to date models have required extensive input and have not been externally validated.
  
  **Methods**: We used the National Health and Nutrition Examination Survey (NHANES) to develop sex-stratified predictive models for examiner-measured height based on self-reported height and age in a random 90% sample of data. We internally validated the model in a held-out 10% sample and externally validated the model in two cohorts: The National Adolescent to Adult Longitudinal Health Study (Add Health) and the University of Michigan Health and Retirement Study (HRS). We assessed discrimination with C-index, calibration by visual inspection of calibration plots, and accuracy using root mean square error (RMSE). 
  
  **Results**: Models were trained using 62,032 NHANES subjects (51.9% women, 21.7% Black, 23.9% Hispanic or Latino, with median age 48 [IQR 31 - 64]), and evaluated in the NHANES held-out test set (n=6,846), Add Health (n=5,749), and HRS (n=5,655). Models demonstrated excellent discrimination in all validation cohorts (C-index range 0.88 - 0.89). Models were well-calibrated in all validation cohorts. Model-predicted height demonstrated lower root mean square error (RMSE) compared to self-reported height in all validation cohorts and when stratified by race and ethnicity, with greatest improvements in participants aged 45 and over. 
  
  **Conclusions and Relevance**: A model requiring minimal input data improves estimation of height over self-reported height at least as much as more complex models across stratifications of sex, age, race and ethnicity in internal validation, and is the first model to improve height estimation that has demonstrated external validity.

# Summary. An optional shortened abstract.
summary: ""

tags: [collaboration]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: medRxiv
  url: https://www.medrxiv.org/content/10.1101/2025.03.12.25323846v1
  icon_pack: ai
  icon: biorxiv

url_pdf:
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
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

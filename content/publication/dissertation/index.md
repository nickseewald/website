---
# Documentation: https://docs.hugoblox.com/managing-content/

title: "Design and Analytic Considerations for Sequential, Multiple-Assignment Randomized Trials with Longitudinal Outcomes"
authors: [admin]
date: 2021-05-10T13:13:00-04:00
doi: "n4r2"

# Schedule page publish date (NOT publication's date).
publishDate: 2025-04-13T13:13:00-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["thesis"]

# Publication name and optional abbreviated publication name.
publication: "University of Michigan"
publication_short: ""

abstract: |
  Clinicians and researchers alike are increasingly interested in how best to personalize interventions. A dynamic treatment regimen (DTR) is a sequence of pre-specified decision rules which can be used to guide the delivery of a sequence of treatments or interventions that are tailored to the changing needs of the individual. The sequential multiple-assignment randomized trial (SMART) is a research tool which allows for the construction of effective DTRs. SMARTs are multi-stage randomized trials in which some or all participants are randomized more than once, with each randomization corresponding to an open scientific question which will aid in the development of a high-quality DTR. In this dissertation, we develop a suite of tools which aid investigators in the design and analysis of SMARTs with continuous, longitudinal outcomes which are collected throughout the multiple stages of the trial. We begin by deriving easy-to-use formulae for computing the total sample size for three common two-stage SMART designs in which the primary aim is to compare mean end-of-study outcomes for two embedded DTRs which recommend different first-stage treatments. The formulae are derived in the context of a regression model which leverages information from a longitudinal outcome collected over the entire study. We show that the sample size formula for a SMART can be written as the product of the sample size formula for a standard two-arm randomized trial, a deflation factor that accounts for the increased statistical efficiency resulting from a longitudinal analysis, and an inflation factor that accounts for the design of a SMART. The SMART design inflation factor is typically a function of the anticipated probability of response to first-stage treatment. We review modeling and estimation for DTR effect analyses using a longitudinal outcome from a SMART, as well as the estimation of standard errors. We also present estimators for the covariance matrix for a variety of common working correlation structures. Methods are motivated using the ENGAGE study, a SMART aimed at developing a DTR for increasing motivation to attend treatments among alcohol- and cocaine-dependent patients. Randomized trials are often constrained by limited financial resources; SMARTs are no different. The longitudinal deflation factor we develop allows for reduction in sample size requirements via both within-person correlation and the repeated measurements of the outcome over time. We provide guidance on how to balance sample size and the number of measurement occasions to minimize total cost of recruitment and measurement while achieving a target power. Finally, we introduce a procedure to generate data from a longitudinal SMART that will achieve an arbitrary desired covariance structure on potential outcomes, averaged over response status. This procedure, as well as user-friendly sample size tools which solve the cost optimization problems, are available in an R package called longsmart. 

# Summary. An optional shortened abstract.
summary: "A dissertation submitted in partial fulfillment of the requirements for the degree of Doctor of Philosophy (Statistics)in the University of Michigan."

tags: [SMARTs, DTRs]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

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
projects: ["smart-longitudinal"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

Doctoral Committee:
- Research Associate Professor Daniel Almirall, Co-Chair
- Professor Kerby Shedden, Co-Chair
- Associate Professor Kelley M. Kidwell
- Professor Naisyin Wang

This work was supported by the Eunice Kennedy Shriver National Institute of Child Health and
Human Development [grant number R01HD073975]; the National Institute of Biomedical Imaging
and Bioengineering [grant number U54EB020404]; the National Institute of Mental Health [grant
number R03MH097954]; the National Institute on Alcohol Abuse and Alcoholism [grant numbers
P01AA016821, RC1AA019092]; and the National Institute on Drug Abuse [grant numbers
R01DA039901, P50DA039838]. The content of this dissertation is solely the responsibility of the
authors and does not necessarily represent the official views of the National Institutes of Health.
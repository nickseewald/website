---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Ready to roll? Practical guidance on whether and when to aggregate data in health policy evaluation
event: AcademyHealth Annual Research Meeting 2022
event_url: https://academyhealth.org/events/2022-06/2022-annual-research-meeting
location: Washington, DC, USA
address:
  street:
  city:
  region: 
  postcode:
  country: 
authors: 
  - admin 
  - Kayla Tormohlen
  - Beth McGinty
  - Elizabeth A. Stuart
summary: A poster at AcademyHealth Annual Research Meeting 2022. I describe a simulation study investigating performance of difference-in-differences methods using hierarchical data for state-level health policy evaluation. 
abstract: |
  **Research Objective:** Health policy researchers often have questions about the effects of state policy on individual-level outcomes collected over multiple time periods. For example, limited evidence suggests that medical cannabis may be an effective substitute for opioids in pain management, which raises a question about the effect of medical cannabis laws on receipt of opioid treatment among individuals with chronic non-cancer pain. This question might be addressed using, for example, a large health insurance claims database which would track individuals’ receipt of such treatment. An open question in this setting is whether the researcher can or should “roll-up” (i.e., aggregate, average, or pool) this individual-level data to the state level when assessing the effects of state policy. Rolling up the data offers a clear computational advantage since it makes the individual-level big data question much smaller. However, existing literature does not sufficiently address whether and when aggregation is disadvantageous due to loss of individual-level information.
  
  **Study Design:** We examine the statistical performance of a variety of common methods in health policy evaluation (two-way fixed effects, difference-in-differences with staggered adoption methods, trial emulation, and marginal structural models) which permit the use of either individual- or aggregate-level data to offer practical guidance on whether and when to roll up.  Our guidance is based on simulation models which allow us to make fair comparisons between analytic methods under a variety of controlled conditions.

  **Population Studied:** We discuss our recommendations in the context of a study designed to assess the effects of state medical cannabis laws on opioid prescribing among patients with chronic non-cancer pain. The study sample consists of individuals 18+ with a chronic non-cancer pain condition who live in a “treated” (i.e., law-enacting) or “comparison” (no law) state and are continuously enrolled in a UnitedHealthcare insurance plan for the 7 years around the treated state's implementation of the law. 

  **Principal Findings:** Preliminary results indicate that rolling up does not yield loss of statistical efficiency in simple settings in which the analysis does not sufficiently take advantage of individual-level data and when standard errors are clustered at the state level. 

  **Conclusions:** Investigators and analysts may, in some settings, be able to roll up individual level data for computational efficiency without meaningful loss of statistical efficiency.
  
  **Implications for Policy or Practice:** This work seeks to reduce uncertainty among investigators and analysts about whether and how to leverage individual-level information in policy evaluation data.

slug: arm2022
category: Poster

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2022-06-06T15:00:00-04:00
date_end: 2022-05-18T16:00:00-04:00
all_day: false

# Schedule page publish date (NOT event date).
publishDate: 2022-05-01T00:00:00-04:00

tags: [policy evaluation, postdoc, hierarchical data]
categories: [posters]

# Is this a featured event? (true/false)
featured: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: Poster
  url: https://slides.nickseewald.com/academyhealth2022.pdf
  icon_pack: fas
  icon: chalkboard-teacher
- name: Supplementary Materials
  url: https://slides.nickseewald.com/academyhealth2022-supplement.pdf
  icon_pack: fas
  icon: puzzle-piece

# Optional filename of your slides within your event's folder or a URL.
url_slides:

url_code:
url_pdf:
url_video:

# Markdown Slides (optional).
#   Associate this event with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: [policy-data-aggregation]
---

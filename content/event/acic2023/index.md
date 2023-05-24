---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Handling Correlation in Stacked Difference-in-Differences Estimates with Application to Medical Cannabis Policy"
event: "American Causal Inference Conference 2023"
event_url: https://sci-info.org/annual-meeting/
location: "Austin, TX, USA"
address:
  street:
  city:
  region:
  postcode:
  country:
summary:
abstract: "Health policy researchers often have questions about the effects of state policy on individual-level
outcomes collected over multiple time periods. In some cases, these studies are conducted using
large-scale, individual-level administrative data such as health insurance claims. However, there are
multiple open questions about the use of such individual-level data in difference-in-differences (DiD)
analyses. “Stacked” DiD is one approach to estimate treatment effects when units implement the
policy of interest at different times: for each unit enacting a policy, we construct a comparison group
of units that never enact (or had not yet enacted) the policy, analyze each treated unit separately
with its comparison group, then pool effect estimates. However, when individual-level data is
available, some individuals in untreated units can contribute to comparison groups for multiple
treated states, producing correlation between stacked estimates. Existing methods do not quantify
or account for this sharing of controls: this leads to incorrect inference. Here, we present a
framework for estimating and managing this correlation when pooling stacked effect estimates. We
explore the statistical properties of this approach, examine its performance in realistic simulations
and with real data, and explain its occasionally counterintuitive effects on variance estimates. This is
motivated by a study investigating the effects of state medical cannabis laws on opioid prescribing
for pain."

slug: acic2023

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2023-05-24T13:45:00-06:00
date_end: 2023-05-24T15:00:00-06:00
all_day: false

# Schedule page publish date (NOT event date).
publishDate: 2023-05-24T07:04:54-05:00

authors: [Nicholas J. Seewald, Beth McGinty, Kayla Tormohlen, Elizabeth A. Stuart]
tags: [postdoc, health policy]

# Is this a featured event? (true/false)
featured: true

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
  - name: Slides
    url: https://slides.nickseewald.com/acic2023.pdf
    icon_pack: fas
    icon: users

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
projects: []
---

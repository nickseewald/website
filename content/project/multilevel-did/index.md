---
# Documentation: https://docs.hugoblox.com/managing-content/

title: "Difference-in-Differences with Multilevel Data"
summary: |
  Health policy evaluations often use difference-in-differences to estimate effects. However, interesting practical questions arise when using this approach with multilevel administrative data.
authors: [admin]
tags: ["health policy", "methods"]
categories: []
date: 2025-04-17T20:23:21-04:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

Difference-in-differences compares changes in longitudinal outcome trajectories
from before and after some exposure between exposed and unexposed units. 
Oftentimes, in health policy application, data is sourced from existing administrative databases (e.g., health insurance claims) that have multilevel structures. This work investigates practical analytic challenges and opportunities that arise because of that multilevel data structure.
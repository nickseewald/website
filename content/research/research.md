+++
widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 15  # Order that this section will appear.

title = "Research Interests"
subtitle = ""

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "1"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  #color = "white"

  # Background gradient.
  # gradient_start = "DeepSkyBlue"
  # gradient_end = "SkyBlue"

  # Background image.
  #image = "headers/bubbles-wide.jpg"  # Name of image in `static/img/`.
  #image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
  #image_size = "cover"  #  Options are `cover` (default), `contain`, or `actual` size.
  #image_position = "center"  # Options include `left`, `center` (default), or `right`.
  #image_parallax = true  # Use a fun parallax-like fixed background effect? true/false

  # Text color (true=light or false=dark).
  #text_color_light = false

[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
  padding = ["2em", "0", "1em", "0"]

[advanced]
 # Custom CSS.
 css_style = ""

 # CSS class.
 css_class = ""
+++

### Causal Inference for Health Policy Evaluation
Causal inference is hard. Causal inference in health policy evaluation is *very* hard. Important challenges in this area include heterogeneity across policies implemented by different units, the sometimes rapidly-changing contexts in which those policies are implemented, and small sample sizes (particularly if evaluating U.S. state-level policies). Additionally, there is often mismatch between available data, the estimands we as statisticians are able to identify from that data, and the needs of policymakers and other interested parties. I am interested in methodological and translational research that addresses practical questions faced by policy scholars doing evaluation work. 

A long-term goal of my work is to help applied researchers develop a toolkit of methods for policy evaluation by clearly articulating methods’ strengths, weaknesses, and data requirements. Many methods papers in the space do not make clear their assumed data structure, creating a barrier for applied scholars seeking to use the method. My work pushes the field towards a culture of clarity around which methods to use and when.

### Sequentially Randomized Trials
Intervention developers across fields, including precision medicine, are increasingly interested in developing sequences of treatments that can adapt to an individual's changing needs, much like standard clinical practice does. These sequences, commonly called dynamic treatment regimens (DTRs), can be developed using a sequential, multiple-assignment, randomized trial (SMART). SMARTs consist of multiple stages, each corresponding to a scientific question about treatment recommendations made by a DTR.6 As with any randomized trial, power and sample size considerations are critical in the design stage of a SMART; my work thus far has focused on building easy-to-use methods and tools for power analyses for SMARTs with longitudinal outcomes collected over the course of multiple stages of the trial.

I developed the [first sample size method](/publication/seewald-sample-size-considerations-2019/) for two-stage SMARTs in which the primary aim is to compare the mean end-of-study outcomes of two embedded DTRs that recommend different first-stage treatments. Ongoing work involves studying the trade-offs between adding measurement occasions and increasing sample size to maximize power subject to an overall budget constraint.

I was the primary data analyst on HeartSteps, the first ever micro-randomized trial (MRT), and co-developed a Shiny app for computing sample size for MRTs, under the direction of [Susan A. Murphy, Ph.D.](http://people.seas.harvard.edu/~samurphy/). Through this work, I was also able to develop guidance on how to use automated systems to collect and manage research-grade data for MRTs.

### Dissemination and Impact

Statisticians are uniquely positioned to impact the scientific process, and disseminating methods is a large component of that. I am dedicated to developing methods that can be used by a wide range of researchers. I have designed and (co-)facilitated several [workshops](tags/workshops/) on SMARTs and policy evaluation methods, and have 

I have a strong record of cross-disciplinary collaboration, serving as a trainee on an NIH-funded training grant for cancer biostatistics (NIH 5T32CA083654-12, P.I. [Jeremy M.G. Taylor, Ph.D.](https://sph.umich.edu/faculty-profiles/taylor-jeremy.html)) under the supervision of [Kelley M. Kidwell, Ph.D.](https://sites.google.com/umich.edu/kidwell/home). As an undergraduate at the University of Notre Dame, I worked with [Seth N. Brown, Ph.D.](https://chemistry.nd.edu/people/seth-n-brown/) on kinetics of reduction-oxidation reactions involving molybdenum complexes. I wrote my undergraduate thesis on Shannon entropy and its applications in combinatorics under the direction of [David Galvin, Ph.D.](https://www3.nd.edu/~dgalvin1/).

<div style="text-align: center;">
  <a class="btn btn-primary btn-lg" style="color: #fff;" href="../files/NJS_Research_Statement.pdf">
    <i class="fas fa-download" style="padding-right: .5em;"></i>
    Research Statement
  </a>
</div>

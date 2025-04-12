---
# title: About Nick
# summary: Learn more about Nick Seewald
# date: "2019-01-01T00:00:00Z"
# type: landing
title: My page
type: landing


sections:
  - block: hero
    content:
      title: About Nick
      # Add your Call-To-Action (CTA) button and optional icon
      cta:
        label: Curriculum Vitae
        url: https://raw.githubusercontent.com/nickseewald/seewaldCV/main/Seewald-Curriculum-Vitae.pdf
        icon_pack: fas
        icon: file-pdf
      # Optionally, add an alternative CTA link
    #   cta_alt:
    #     label: Ask a question
    #     url: https://discord.gg/z8wNYzb
      # Add your Hero text here
      text: |-
        <pre>
        <hr style="border: 1px solid white; background-image: none; background-color: white; border-radius: 1pt">
        
        </pre>
    design:
      # Choose an optional background color, gradient, image, or video
      background:
        image:
            filename: banner.jpg
            filters:
                brightness: .45
            size: cover
            position: top left
        text_color_light: true

  - block: experience
    content:
      title: Experience & Education
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many experience `items` below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Assistant Professor of Biostatistics
          company: University of Pennsylvania Perelman School of Medicine
          company_url: 'https://www.med.upenn.edu/'
          company_logo: penn_shield
          location: Philadelphia, PA
          date_start: '2023-09-01'
          date_end: ''
        - title: Postdoctoral Fellow
          company: Johns Hopkins Bloomberg School of Public Health
          company_url: https://publichealth.jhu.edu/
          company_logo: bsph
          location: Baltimore, MD
          date_start: 2021-07-01
          date_end: 2023-07-31
          description: >-
            Mentored by 
              [Elizabeth A. Stuart, PhD](https://www.elizabethstuart.org/) and 
              [Beth McGinty, PhD](https://vivo.weill.cornell.edu/display/cwid-emm4010), I 
              developed tools to help practitioners design better health policy evaluation 
              studies and better understand the causal inference tools used to do so.
        - title: PhD, Statistics
          company: University of Michigan
          company_url: https://lsa.umich.edu/stats
          company_logo: block_m
          location: Ann Arbor, MI
          date_start: 2015-09-01
          date_end: 2021-05-10
          description: >-
            Supervised by 
              [Daniel Almirall, PhD](https://websites.umich.edu/~dalmiral/), my 
              [dissertation](https://dx.doi.org/10.7302/2671) was titled "Design and 
              Analytic Considerations for Sequential, Multiple-Assignment Randomized Trials
              with Continuous Longitudinal Outcomes." I also received an MA in statistics in
              2018.
        - title: MA, Statistics
          company: University of Michigan
          company_url: https://lsa.umich.edu/stats
          company_logo: block_m
          location: Ann Arbor, MI
          date_start: 2015-09-01
          date_end: 2018-04-28
        - title: MS, Biostatistics
          company: University of Michigan
          company_url: https://sph.umich.edu/biostat/index.html
          company_logo: block_m
          date_start: 2013-09-01
          date_end: 2015-04-30
          description: >-
            I worked with 
              [Kelley Kidwell, PhD](https://sites.google.com/umich.edu/kidwell/home) on 
              design and analysis methods for SMARTs with binary outcomes and on 
              collaborative projects as part of the 
              [Cancer Biostatistics Training
              Program](https://sph.umich.edu/ccb/training/index.html)
              supported by the National Cancer Institute.
        - title: BS, Mathematics with Life Science
          company: University of Notre Dame
          company_logo: ndmonogram
          location: Notre Dame, IN
          date_start: 2009-08-25
          date_end: 2013-05-10
          description: >-
            I studied pure mathematics with a concentration in life sciences. My undergraduate thesis was 
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'

  - block: markdown
    content:
      title: My Commitment to Diversity, Equity, and Inclusion
      text: |-
        I am firmly committed to efforts to increase the diversity of Statistics as a field. We as statisticians benefit from and value the tremendous *intellectual* diversity in our field, but we must do more to improve the representation of minoritized racial and gender identities among our ranks. I strive to foster a more welcoming, inclusive culture in Statistics which supports and centers the contributions of Black, Indigenous, and Latino/a statisticians.

        I believe statisticians have a unique ethical responsibility in the movement for racial justice, both in the United States and beyond. The increasing ubiquity of so-called artificial intelligence has the potential to entirely change the world, and yet we too often see it being used to reinforce and reify existing social structure. I have committed myself to a process of continual learning about the way these structures are created, strengthened, and maintained in order to understand my role in the perpetuation of racial injustice, and work to correct it.

        In 2020, I completed the [Rackham Professional Development Diversity, Equity, and Inclusion Certificate](https://rackham.umich.edu/professional-development/dei-certificate/) at the University of Michigan, and co-founded a graduate student working group on DEI in our Statistics department.
        
---

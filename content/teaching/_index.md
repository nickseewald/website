---
title: Teaching
type: landing

sections:
  - block: hero
    content:
      title: Teaching
      # Add your Call-To-Action (CTA) button and optional icon
    #   cta:
    #     label: Curriculum Vitae
    #     url: https://raw.githubusercontent.com/nickseewald/seewaldCV/main/Seewald-Curriculum-Vitae.pdf
    #     icon_pack: fas
    #     icon: file-pdf
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
            filename: lectureHall2.jpg
            filters:
                brightness: .45
            size: contain
            position: top left
        text_color_light: true

  - block: markdown
    content: 
      title: Teaching Philosophy
      text: |-
        > The best thing about being a statistician is that you get to play in everyone's backyard.
        
        The (probably overused) above quote from John Tukey captures not only what I love most about statistics, but also my approach to teaching undergraduate statistics. My teaching seeks to connect statistics to students' lives and interests, and I am focused on helping them understand the bigger picture of their work. In an introductory course, this involves having students work together and think deeply about what conclusions they can and cannot draw from their analyses, and the non-statistical impact those conclusions might have. Similarly, in an upper-level undergraduate data mining course, I encouraged students to think carefully about tradeoffs between model performance and interpretability, and brought in news stories highlighting ethical issues in data science.
        
        Over summer 2020, I worked with [Jack Miller, Ph.D.](https://lsa.umich.edu/stats/people/faculty/jackie-miller.html), to redesign the University of Michigan's introductory statistics course (STATS 250) to focus on simulation-based inference, and to move labs and other activities to more deeply integrate R via RStudio. Through this work, I'm able to make a strong impact on how we engage learners in statistics, and get them excited about a course they may have been told to fear. Concurrently, I am working with other graduate students at Michigan to develop a mentorship program for Graduate Student Instructors to focus on evidence-based and inclusive teaching strategies to better cultivate the next generation of statisticians.

        <div style="text-align: center;">
        <a class="btn btn-primary btn-lg" style="color: #fff; margin-right:1em;" href="../files/seewaldTeachingStatement.pdf" target="_blank">
            <i class="fas fa-download" style="padding-right: .5em;"></i>
            Teaching Statement
        </a>
        <a class="btn btn-primary btn-lg" style="color: #fff; margin-left:1em;" href="../files/seewaldTeachingReviews.pdf" target="_blank">
            <i class="fas fa-download" style="padding-right: .5em;"></i>
            Selected Teaching Reviews
        </a>
        </div>

  - block: experience
    content:
      title: Courses Taught
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many experience `items` below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: "BSTA 6100: Biostatistical Methods for Epidemiology"
          company: University of Pennsylvania Perelman School of Medicine
          company_logo: penn_shield
          date_start: 2024-08-27
          description: |-
            *Course designer and instructor of record.*
            
            Introductory biostatistics course for students in Epidemiology PhD and MPH programs.
        - title: SMART Designs for Developing Adaptive Interventions
          company: Statistical Horizons
          company_logo: statHorizons
          company_url: https://statisticalhorizons.com
          date_start: 2024-08-12
          description: |-
            A 4-day synchronous virtual seminar series on designing and
            analyzing sequential, multiple-assignment, randomized trials to build
            effective adaptive interventions.

            *Next session begins July 8, 2025.* 
            Register [here](https://statisticalhorizons.com/seminars/smart-designs-for-developing-adaptive-interventions/).
        - title: Seminar on Statistical Methods for Mental Health
          company: Johns Hopkins Bloomberg School of Public Health
          company_logo: bsph
          location: First Term, AY 2022-2023
          date_start: 2022-09-01
          date_end: 2022-10-20
          description: |-
            *Primary instructor with [Trang Q. Nguyen](https://trang-q-nguyen.weebly.com/)*.
            
            8-week hour-long seminar for masters and doctoral students in mental health. The topic was "Promises and Pitfalls of Prediction Models in Mental Health".
        - title: "STATS 250: Introduction to Statistics and Data Analysis"
          company: University of Michigan
          company_logo: block_m
          location: Spring 2018, AY 2019-20, AY 2020-21
          date_start: 2019-09-01
          date_end: 2021-04-24
          description: |-
            *Graduate Student Instructor*      
            
            Large, non-calculus-based, cross-disciplinary introductory statistics course. Taught 2-3 weekly lab sessions of 30 students each.

            *Course Instructors: Jack Miller, Ph.D.; Brenda Gunderson, Ph.D.*
         
            [Fall 2020 Slides](/250fa20-slides)
        - title: "Multilevel Models I: Introduction and Application"
          company: Summer Program in Quantitative Methods of Social Research, ICPSR
          company_logo: icpsr
          location: Summer 2018, Summer 2019
          date_start: 2018-06-01
          date_end: 2019-07-30
          description: |-
            *Teaching Assistant*
           
            Four-week project-based course for political and social scientists interested in mixed modeling. Held daily office hours to assist students with project-based learning.

            *Course Instructor: Mark Manning, Ph.D.*
        - title: Introduction to the R Statistical Computing Environment
          company: Summer Program in Quantitative Methods of Social Research, ICPSR
          company_logo: icpsr
          location: Summer 2018, Summer 2019
          date_start: 2018-06-01
          date_end: 2019-07-30
          description: |-
            *Teaching Assistant*
         
            Two-week lecture series on graphics, data management, modeling, etc., in R. Held daily office hours.
            
            *Course Instructor: [John Fox, Ph.D.](https://www.john-fox.ca/)*
        - title: "STATS 415: Data Mining"
          company: University of Michigan
          company_logo: block_m
          location: Winter 2018
          date_start: 2018-01-01
          date_end: 2018-04-30
          description: |-
            *Graduate Student Instructor*

            Upper-level undergraduate introductory machine learning course
            using *An Introduction to Statistical Learning* (James, Witten, Hastie,
            Tibshirani). Taught weekly lab session for approximately 45 students.


            *Course Instructor: [Liza Levina, Ph.D.](https://sites.google.com/umich.edu/elevina)*
        - title: "STATS 500: Statistical Learning I: Regression"
          company: University of Michigan
          company_logo: block_m
          location: Fall 2017
          date_start: 2017-09-01
          date_end: 2017-12-22
          description: |-
            *Graduate Student Instructor*
            
            First graduate-level regression course for Applied Statistics masters students, using *Linear Models with R, 2nd ed.* (Faraway). Held weekly office hours and graded homework and exams.
            
            *Course Instructor: Brian Thelan, Ph.D.*
        - title: "BIOS 40411: Biostatistics"
          company: University of Notre Dame
          company_logo: ndmonogram
          location: Fall 2017
          date_start: 2017-09-01
          date_end: 2017-12-22
          description: |-
            *Undergraduate Teaching Assistant*
         
            Senior undergraduate-level introductory biostatistics course for biology and life science majors. Co-taught weekly lab sessions with a graduate TA, graded lab reports.
            
            *Course Instructor: Gary Lamberti, Ph.D.*

    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
---

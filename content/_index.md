---
# Leave the homepage title empty to use the site title
title: 
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: Yacine's Blog

      cta:
        label: '**Read My Latest Posts**'
        url: /post
      cta_alt:
        label: Know more about me
        url: https://discord.gg/z8wNYzb

      text: |-
        **Welcome to my Blog!**

        <!--Custom spacing-->
        <div class="mb-3"></div>
        <!--GitHub Button JS-->
        <script async defer src="https://buttons.github.io/buttons.js"></script>
    design:
      background:
        image: 
          filename: ai.png
        text_color_light: true
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin

  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Machine Learning Engineer
          company: Valeo
          company_url: ''
          company_logo: valeo
          location: Paris
          date_start: '2022-10-01'
          date_end: ''
          description: |2-
              Responsibilities:

              * Deep Learning based Visual Inspection
              * Predictive Maintenance
              * MLOps and Model Monitoring
              * Cloud Pipeline Development
        - title: Machine Learning & Image Processing Intern
          company: GoPro
          company_url: ''
          company_logo: gopro
          location: Paris
          date_start: '2022-04-01'
          date_end: '2022-09-30'
          description: |2-
              Responsibilities:

              * Deep Learning based Image Deblurring
              * Research on Blur Generation Techniques
              * Development of an end-to-end image processing pipeline
        - title: Deep Learning and Image Processing Research Intern
          company: Polytechnic School of Algiers
          company_url: ''
          company_logo: enp
          location: Algiers
          date_start: '2021-02-01'
          date_end: '2021-07-15'
          description: |2-
              Responsibilities:

              * Research on hybrid deep learning methods for audio source separation in the time frequency domain
              * Research on deep unfolding applied to non-negative matrix factorization
              * Stacking neural networks and non-negative matrix factorization for source separation
        - title: Machine Learning Research Intern
          company: Gustave Eiffel University
          company_url: ''
          company_logo: gustave
          location: Paris
          date_start: '2020-06-01'
          date_end: '2021-02-01'
          description: |2-
              Responsibilities:

              * Research on driving patterns recognition and time series segmentation
              * Development of an end-to-end unsupervised framework for driving patterns recognition
              * Proposed a method to interpret driving patterns causality using graph theory metrics
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://www.coursera.org/account/accomplishments/verify/68NU7STL25S4?utm_source=linkutm_medium=certificate&utm_content=cert_image&utm_campaign=pdf_header_button&utm_product=course
          date_end: ""
          date_start: "2021-08-01"
          description: ""
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Sequences, Time Series and Prediction
          url: ""
        - certificate_url: https://coursera.org/share/4d6623bdf7a229affdba5ef7ec2186cd
          date_end: ""
          date_start: "2020-04-20"
          description: ""
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Convolutional Neural Networks 
          url: ""
        - certificate_url: https://www.cloudskillsboost.google/public_profiles/c5ef9a0e-508e-4bce-bf8c-75239964a7c6
          date_end: ""
          date_start: "2023-06-26"
          description: Generative AI, Transformers, Diffusion Models, Large Language Models, Generative AI Studio
          organization: google
          organization_url: https://www.cloudskillsboost.google/journeys
          title: Generative AI Learning Path
          url: https://www.cloudskillsboost.google/public_profiles/c5ef9a0e-508e-4bce-bf8c-75239964a7c6
        - certificate_url: https://www.coursera.org/account/accomplishments/verify/PMG7RMNHCNLZ?utm_campaign=copybutton_certificate&utm_content=cert_image&utm_medium=certificate&utm_source=link
          date_end: ""
          date_start: "2020-03-15"
          description: ""
          organization: coursera
          organization_url: https://www.coursera.org
          title: 'Improving Deep Neural Networks: Hyperparameter Tuning, Regularization and Optimization'
          url: ""
        - certificate_url: https://www.coursera.org/account/accomplishments/certificate/8ETS67TFYSHW
          date_end: ""
          date_start: "2019-08-19"
          description: ""
          organization: coursera
          organization_url: https://www.coursera.org
          title: 'Neural Networks and Deep Learning'
          url: ""
        - certificate_url: https://university.mongodb.com/course_completion/ae3edf7f-0690-4ebb-a51a-8e071685d3d3
          date_end: ""
          date_start: "2020-03-27"
          description: ""
          organization: mongo
          organization_url: https://learn.mongodb.com/
          title: 'M001: MongoDB Basics'
          url: ""
        - certificate_url: https://www.coursera.org/account/accomplishments/verify/9CRJXGELD9CW?utm_source=link&utm_medium=certificate&utm_content=cert_image&utm_campaign=sharing_cta&utm_product=course
          date_end: ""
          date_start: "2020-09-12"
          description: 
          organization: google
          organization_url: https://www.cloudskillsboost.google/journeys
          title: Introduction to Git and Github
          url: ""
    design:
      columns: '2'
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Deep Learning
          tag: Deep Learning
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: collection
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'
  
---

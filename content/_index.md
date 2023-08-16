---
# Leave the homepage title empty to use the site title
title: 
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: features
    content:
      title: Computer skills
      items:
        - name: Python
          description: Advanced
          icon: python
          icon_pack: fab
        - name: Google Earth Engine
          description: Intermediate
          icon: GEE
          icon_pack: custom
        - name: R
          description: Intermediate
          icon: r-project
          icon_pack: fab
  - block: experience
    content:
      title: Professional Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: GIS technology advisor
          company: Avinal S.A.
          company_url: https://avinal.com.co/
          company_logo: Avinal
          location: Medellín, Antioquia, Colombia
          date_start: '2022-05-01'
          date_end: '2022-07-01'
          description: Theorical and practical consulting in Geo-Information Systems (QGIS) for helping in the building of an Environmental Master Plan for Granja Aurora a farm part of Avinal S.A.
        - title: Independent Professional on research project
          company: Universidad de Los Andes
          company_url: https://uniandes.edu.co/
          company_logo: Uniandes
          location: Bogotá D.C., Colombia
          date_start: '2021-11-01'
          date_end: '2022-01-01'
          description: |2-
              Conducting the study ["Residential radon concentrations in Bogota and neighbouring municipalities, Colombia: Results of an exploratory study"](https://goldschmidtabstracts.info/2022/9273.pdf) under the supervision of professor [C. Huguet](https://www.linkedin.com/in/carme-huguet-7769b991/)
        - title: Technical advisor on [Agrosat](https://agrosat.cl/) services
          company: Nutrición de plantas S.A.
          company_url: ''
          company_logo: NDP
          location: Tuluá, Valle del Cauca, Colombia
          date_start: '2021-07-01'
          date_end: '2021-11-01'
          description: |2-
              Responsible of:
              * The making of "Pilot study of Heavy Metal contamination in Avocado crops (Var. Hass) and feasibility analysis of Crosscheck methodology in Heavy Metal distribution"
              * Support in the implementation of soil diagnostic services for agriculture (Nutricheck)
      columns: '1'
  - block: experience
    content:
      title: Academic Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Teaching Assistant of *Geophysics* 
          company: Universidad de Los Andes
          company_url: https://uniandes.edu.co/
          company_logo: Uniandes
          location: Bogotá D.C., Colombia
          date_start: '2021-07-01'
          date_end: '2022-12-01'
          description: |2-
            Responsible of:
            * Creating deliverable workshops and grade them.
            * Assisting students during question hours.
        - title: Teaching Assistant *Environmental Fluid Mechanics*
          company: Universidad de Los Andes
          company_url: https://uniandes.edu.co/
          company_logo: Uniandes
          location: Bogotá D.C., Colombia
          date_start: '2018-07-01'
          date_end: '2019-05-01'
          description: |2-
            Responsible of:
            * Creating deliverable workshops and grade them.
            * Assisting students during question hours.
            * Assisting during field work
      columns: '1'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: Professional Development
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://coursera.org/share/ca9977bc6a6c478ea000fd4b0c5ec41c
          date_end: ''
          date_start: '2022-01-01'
          description: A program of three courses offered by [Imperial College London](https://www.imperial.ac.uk/) that covered topics regarding the use of **Linear Algebra**, **Multivariate Calculus** and **Principal Component Analysis** in **Machine Learning** algorithms.
          organization: Coursera
          organization_url: https://www.coursera.org/specializations/mathematics-machine-learning
          title: Mathematics for Machine Learning
          url: ''
        - certificate_url: https://coursera.org/share/fc3f45e471da05c95af607e01785478e
          date_end: ''
          date_start: '2021-01-01'
          description: Specialization program covering data science related topics going all the way from **text mining** and **social network analysis** to **machine learning** and **data visualization**. The program is offered by [University of Michigan](https://umich.edu/)
          organization: Coursera
          organization_url: https://www.coursera.org/specializations/data-science-python
          title: Applied Data Science with Python
        - certificate_url: https://coursera.org/share/faa072c15279b7921f02a14e8459ac55
          date_end: ''
          date_start: '2021-10-01'
          description: Course offered by [University of Michigan](https://umich.edu/) covering the basics of Environmental Health.
          organization: Coursera
          organization_url: https://www.coursera.org/specializations/data-science-python
          title: 'Environmental Health: the Foundation of Global Public Health'
    design:
      columns: '2'
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 2
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
  - block: markdown
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
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
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: test@example.org
      phone: 888 888 88 88
      appointment_url: 'https://calendly.com'
      address:
        street: 450 Serra Mall
        city: Stanford
        region: CA
        postcode: '94305'
        country: United States
        country_code: US
      directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      office_hours:
        - 'Monday 10:00 to 13:00'
        - 'Wednesday 09:00 to 10:00'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/Twitter'
        - icon: skype
          icon_pack: fab
          name: Skype Me
          link: 'skype:echo123?call'
        - icon: video
          icon_pack: fas
          name: Zoom Me
          link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---

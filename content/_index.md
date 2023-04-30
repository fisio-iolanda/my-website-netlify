---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content: 
      text: '![Logo](/media/logo/logo.cinza.transp.svg#center)'
  
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - section_id: experience
    template: _experience.md
  - block: features
    content:
      title: Hobbys
      items:
        - name: Fahrradfahren
          description: ''
          icon: biking
          icon_pack: fas
        - name: Schwimmen
          description: ''
          icon: swimmer
          icon_pack: fas
        - name: Akademie
          description: ''
          icon: dumbbell
          icon_pack: fas
        - name: Tanzen und Musik
          description: ''
          icon: guitar
          icon_pack: fas
        - name: Reisen
          description: ''
          icon: plane
          icon_pack: fas
        - name: Fotografieren
          description: ''
          icon: camera-retro
          icon_pack: fas
  # - block: accomplishments
  #   content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      # title: 'Accomplish&shy;ments'
      # subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      # date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
    #   items:
    #     - certificate_url: https://www.coursera.org
    #       date_end: ''
    #       date_start: '2021-01-25'
    #       description: ''
    #       organization: Coursera
    #       organization_url: https://www.coursera.org
    #       title: Neural Networks and Deep Learning
    #       url: ''
    #     - certificate_url: https://www.edx.org
    #       date_end: ''
    #       date_start: '2021-01-01'
    #       description: Formulated informed blockchain models, hypotheses, and use cases.
    #       organization: edX
    #       organization_url: https://www.edx.org
    #       title: Blockchain Fundamentals
    #       url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
    #     - certificate_url: https://www.datacamp.com
    #       date_end: '2020-12-21'
    #       date_start: '2020-07-01'
    #       description: ''
    #       organization: DataCamp
    #       organization_url: https://www.datacamp.com
    #       title: 'Object-Oriented Programming in R'
    #       url: ''
    # design:
    #   columns: '2'
  - block: collection
    id: posts
    content:
      title: Neueste Beiträge
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
  # - block: portfolio
  #   id: projects
  #   content:
  #     title: Projects
  #     filters:
  #       folders:
  #         - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      # default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
    #   buttons:
    #     - name: All
    #       tag: '*'
    #     - name: Deep Learning
    #       tag: Deep Learning
    #     - name: Other
    #       tag: Demo
    # design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      # columns: '1'
      # view: showcase
      # For Showcase view, flip alternate rows?
      # flip_alt_rows: false
  # - block: markdown
  #   content:
  #     title: Gallery
  #     subtitle: ''
  #     text: 
  #   design:
  #     columns: '1'
  # - block: collection
  #   id: featured
  #   content:
  #     title: Ausgewählte Veröffentlichungen
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     columns: '2'
  #     view: card
  # - block: collection
  #   content:
  #     title: Recent Publications
  #     text: |-
  #       {{% callout note %}}
  #       Quickly discover relevant content by [filtering publications](./publication/).
  #       {{% /callout %}}
  #     filters:
  #       folders:
  #         - publication
  #       exclude_featured: true
  #   design:
  #     columns: '2'
  #     view: citation
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     columns: '2'
  #     view: compact
  # - block: tag_cloud
  #   content:
  #     title: Popular Topics
  #   design:
  #     columns: '2'
  - block: contact
    id: contact
    content:
      title: Kontakt
      subtitle: 'Wie Sie mich erreichen können:'
      text: |-
        
      # Contact (add or remove contact options as necessary)
      # email: 'iolanda@ios-physiotherapie.de'
      # phone: '+55 71 994 045 183'
      # appointment_url: 'https://calendly.com'
      # address:
      #  city: Salvador
      #  region: Bahia, Brasilien
      #  country: Brasilien
      #  country_code: BR
      # office_hours:
      #   - 'Wochentage 08:00 to 16:00 (UTC/GMT -3)'
      #   - 'Samstags 08:00 to 12:00 (UTC/GMT -3)'
      # contact_links:
        # - icon: linkedin
        #   icon_pack: fab
        #   name: iolanda-santiago
        #   link: 'https://www.linkedin.com/in/iolanda-santiago/'
        # - icon: skype
        #   icon_pack: fab
        #   name: Skype Me
        #   link: 'skype:iolanda.oliveira?call'
        # - icon: video
        #   icon_pack: fas
        #   name: Zoom Me
        #   link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      # autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: true
    design:
      columns: '1'
---

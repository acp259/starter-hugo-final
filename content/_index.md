---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:

  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: features
    content:
      title: Skills
      items:
        - name: Greenhouse ATS
          icon: GH
          icon_pack: fab
        - name: Scheduling
          icon: cal
          icon_pack: fas
        - name: Microsoft Office Suite
          icon: Microsoft office
          icon_pack: fas
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
        - title: Talent Acquisition Intern
          company: Minitab
          company_url: 'https://www.minitab.com/en-us/'
          company_logo: mini
          location: State College
          date_start: '2022-08-01'
          date_end: ''
          description: |2-
              Responsibilities include:

              * Facilitated onboarding and delivered comprehensive learning and development trainings to a group of 50 interns
              * Developed the first intern handbook and intern manager trainings, liaising with legal experts to ensure credibility.
              * Effectively managed intern positions and entry-level sales requisitions, holding an average time-to-fill period of 30 days.
              * Analyzed the 2021 and 2022 intern program metrics, establishing it’s value as a valuable pipeline.
        - title: Loss Prevention Customer Service Associate
          company: TJMaxx
          company_url: 'https://tjmaxx.tjx.com/store/index.jsp'
          company_logo: tjmaxxx
          location: State College
          date_start: '2021-10-01'
          date_end: '2022-04-01'
          description: |2-
              Responsibilities include:

              * Implemented shrink awareness training and fostered a culture of information sharing among staff and management
              * Analyzed CCTV surveillance for suspicious activity and documented findings, reducing theft by 40%.
              * Secured the confidentiality of over 35 employees identification numbers, transaction records, and work schedules.
    
        - title: Community Assistant
          company: The View
          company_url: 'https://www.theviewstatecollege.com'
          company_logo: penn
          location: State College
          date_start: '2021-05-01'
          date_end: '2021-09-01'
          description: |2-
              Responsibilities include:

              * Coordinated with property vendors to arrange maintenance appointments and effectively addressed tenant concerns, holding a 98% satisfaction rate.
              * Facilitated 200 move-ins within a 3-month timeframe and earned a 96% satisfaction rate on the move-in feedback survey.
              * Prepared comprehensive financial breakdowns of tenant bills and leases, amounts exceeding $7,000.
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
        - certificate_url: 
          date_end: ''
          date_start: '2022-12-01'
          description: Developed a case solution employing the Change Kaleidoscope model to optimize female talent retention at plant sites for PepsiCo. Delivered a 15-minute presentation of the case solution to a panel of 5 judges.
          organization: Purdue University
          organization_url: https://www.purdue.edu
          title: Purdue University HR Case Competition
          url: 
        - certificate_url: 
          date_end: ''
          date_start: '2022-09-01'
          description: Collaborated with human resources master’s students from other colleges to generate interest in studying the field. Produced a TikTok within 48-hours, securing 9,000+ views in under 2 months and the award of "Most Creative TikTok”.
          organization: University of South Carolina
          organization_url: https://sc.edu
          title: The Future of HR Conference
          url: ''
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
  - block: markdown
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
  - block: contact
    id: contact
    content:
      title: Contact Information
      subtitle:
      text: |-
      # Contact (add or remove contact options as necessary)
      email: acp259@psu.edu
      contact_links:
        - icon: LinkedIn
          icon_pack: fab
          name: Let's connect!
          link: https://www.linkedin.com/in/alexisparra00/
      # Automatically link email and phone or display as text?
      autolink: true

    design:
      columns: '2'
---

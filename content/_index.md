---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: true

      # Name heading sizing to accommodate long or short names
      name:
        size: md # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: collection
    id: papers
    content:
      title: Recent Publications
      filters:
        folders:
          - publications
      count: 6
      order: desc
    design:
      view: article-grid
      columns: 3
  - block: collection
    id: grants
    content:
      title: Grants & Funded Projects
      text: Selected research grants and industry-funded projects as Principal Investigator, Project Leader, or Co-Researcher.
      filters:
        folders:
          - projects
      count: 6
      order: desc
    design:
      view: article-grid
      fill_image: false
      columns: 3
      show_date: false
      show_read_time: false
      show_read_more: false
  - block: resume-awards
    id: accomplishments
    content:
      title: Accomplishments
      username: me
  - block: collection
    id: events
    content:
      title: Upcoming Talks & Events
      filters:
        folders:
          - events
      count: 0
      order: asc
    design:
      view: article-grid
      columns: 1
  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: blog
      # Choose how many pages you would like to display (0 = all pages)
      count: 10
      # Filter on criteria
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: card
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
  - block: markdown
    id: talks
    content:
      title: Talks & Invited Presentations
      subtitle: ''
      text: |-
        Selected international invited talks and keynotes. *(See [Services](/experience/#services) for a fuller list of professional service and committee roles, or [Accomplishments](#accomplishments) for awards and recognitions.)*

        - **2026** — "Tracking the Unseen: Monitoring and Investigating P2P Botnets" (Workshop), [GISEC Global 2026](https://gisec.ae/agenda), Dubai Exhibition Centre, UAE
        - **2026** — "Cybersecurity Awareness" (Ceramah Kesedaran Keselamatan Siber), Penang International Halal Expo (PIHEX) 2026, Politeknik Seberang Perai
        - **2025** — "Cybersecurity Concerns for Energy Domain", ERIA/ERAB Cyber and Physical System Security Workshop, Kuala Lumpur
        - **2024** — "Cybersecurity Best Practices in Academic Environment", Universitas Brawijaya (Launch of UB-CSIRT)
        - **2024** — "Building Cyber Resilience through Defending against Social Engineering Attacks", IEEE Computational Intelligence Society / Universitas Nusa Putra
        - **2024** — "Cybersecurity Guest Lecture", Universitas Brawijaya, Fakultas Vokasi
        - **2023** — "The P2P Botnet Threat Mitigation Lifecycle", IEEE Indonesia / Universitas Nusa Putra
        - **2023** — "Understanding the Botnet Threat Mitigation Lifecycle", TU Darmstadt (PNS: Protection in Networked Systems)
        - **2022** — "Introduction to Cyber Hygiene", Intel Security Conference
        - **2020** — "Botnet Mitigation Best Practices and System Evaluation", Universitas Brawijaya (DCNDS Workshop Series 2)
        - **2019** — "Cloud-Based Web Security Best Practices and System Configuration Overview", Bangladesh University of Engineering and Technology (DCNDS Workshop Series 1)
        - **2019** — "The Importance of Data Analytics in the Era of Industry 4.0", Universitas Brawijaya
        - **2018** — "Data Analytics with Pandas", Nehru Arts & Science College, Coimbatore, India
        - **2017** — "Advanced Monitoring of P2P Botnets", Bina Nusantara University (BINUS), Indonesia
        - **2017** — "Awareness of Internet Security in Digital Era", Universitas Brawijaya
    design:
      columns: '1'
  - block: markdown
    id: contact
    content:
      title: Contact
      subtitle: ''
      text: |-
        **Email:** kshankar [at] usm [dot] my

        **Phone:** +604 653 4632

        **Book an appointment:** [calendly.com/kshankar_usm](https://calendly.com/kshankar_usm)

        **Other ways to reach me:**
        - [Telegram](https://telegram.me/@skusm)
    design:
      columns: '1'
---

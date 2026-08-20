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
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: card
      columns: 3
  - block: resume-awards
    id: accomplishments
    content:
      title: Accomplishments
      username: me
  - block: markdown
    id: teaching
    content:
      title: Teaching and Supervision
      subtitle: ''
      text: |-
        ## **2020 @ TU Darmstadt**
        - PNS: Protection in Networked Systems ‒ Trust, Resilience, and Privacy
        - Seminar: Protection in Infrastructures and Networks (PIN)
            - Topic supervisor
        - Thesis Supervision
        - Bachelor Students Traineeship / Bachelorpraktikum
        - Internet Praktikum

        ## **2019**
        - Introduction To Real Time Operating Systems And Applications
        - Internet Governance
        - Internet Security
        - Dissertation

        ## **2018**
        - Introduction To Real Time Operating Systems And Applications
        - Special Topics in Next Generation Internet
        - Dissertation
        - Final Year Project - CS@USM
        - Internship / Research Project

        ## **2017**
        - Introduction To Real Time Operating Systems And Applications
        - Special Topics in Next Generation Internet
        - Internet Communications Protocol
        - Dissertation
        - Final Year Project - CS@USM
        - Internship / Research Project

        ## **2016 @ USM**
        - Internet Communications Protocol
        - Final Year Project - CS@USM
        - Internship / Research Project

        ## **Prior to 2016 @ TU Darmstadt**
        - Simulation and Evaluation of Computer Networks (SECoN)
        - Seminar Telekooperation
        - Seminar Security, Privacy, and Trust
        - Projectpraktikum
        - Bachelor Students Traineeship / Bachelorpraktikum
    design:
      columns: '2'
  - block: markdown
    id: services
    content:
      title: Services
      subtitle: ''
      text: |-
        ## **Membership**
        - Asia Pacific Advanced Network (APAN) - Security Working Group, *Chair*
        - Institute of Electrical and Electronics Engineers (IEEE), *Member*
        - Malaysian Research and Education Network (MyREN) - Internet Security Working Group, *Deputy Head*
        - Malaysian Board of Technologists (MBOT), *Professional Technologist*

        ## **Journal Reviewer**
        - [ACM Computing Surveys (CSUR)](https://dl.acm.org/journal/csur)
        - [IEEE Transactions on Information Forensics & Security (T-IFS)](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=10206)
        - [IEEE Journal on Selected Areas in Communications (JSAC)](https://www.comsoc.org/publications/journals/ieee-jsac)
        - [PeerJ Computer Science](https://peerj.com/computer-science/)
        - [Journal of Information Security and Applications (JISA) - Elsevier](https://www.journals.elsevier.com/journal-of-information-security-and-applications)
        - [Computers and Electrical Engineering - Elsevier](https://www.journals.elsevier.com/computers-and-electrical-engineering)

        ## **Committees**
        - MRANTI Cybersecurity Technical Advisory Panel, AV Living Lab
        - USM Mobile Access Coordinator (COVID-19)
        - USM Industry Liaison Fellow
        - USM Cyber Security Awareness Program - Subject Matter Expert
    design:
      columns: '2'
  - block: collection
    content:
      title: Recent Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
      count: 8
      order: desc
    design:
      view: article-grid
      columns: 3
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
    id: contact
    content:
      title: Contact
      subtitle: ''
      text: |-
        **Email:** [kshankar@usm.my](mailto:kshankar@usm.my)

        **Phone:** +604 653 4632

        **Book an appointment:** [calendly.com/kshankar_usm](https://calendly.com/kshankar_usm)

        **Other ways to reach me:**
        - [Skype](skype:shankar.karuppayah?call)
        - [Telegram](https://telegram.me/@skusm)
    design:
      columns: '1'
---

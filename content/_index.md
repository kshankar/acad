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
    id: talks
    content:
      title: Talks & Invited Presentations
      subtitle: ''
      text: |-
        Selected international invited talks and keynotes. *(See [Recognition](#accomplishments) for a fuller list of professional service and committee roles.)*

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
    id: teaching
    content:
      title: Teaching and Supervision
      subtitle: ''
      text: |-
        *Courses taught at Universiti Sains Malaysia, by academic session — Postgraduate Supervision has [its own page](/supervision/).*

        ## **2025/2026**
        - Science and Engineering Research Methodology (EKC500/3)
        - Ethical Hacking (CYY514/4)

        ## **2024/2025**
        - Science and Engineering Research Methodology (EKC500/3)
        - Cyber Operations (CYY519/4)
        - Cyber Security Audit and Assessment (CYY517/4)
        - Cybersecurity Research Methodology (CYY515/4)
        - Advanced Internet Security (CYY512/4)
        - Internet Governance (CYY511/4)

        ## **2023/2024**
        - Science and Engineering Research Methodology (EKC500/3)

        ## **2021/2022 – 2022/2023**
        - Information Security Management and Assurance (CST339/3)
        - Information Security & Assurance (CST233/3)
        - Microprocessors & Embedded Systems (CST432/3)
        - Principles of Computer Networks and Information Security (CST235/4, CSM335/4)
        - Data Communications & Networks (CST231/3, CSM331/3)

        ## **2018/2019 – 2019/2020**
        - Introduction to Real Time Operating Systems and Applications (EES502/4)
        - Internet Governance (CYY508/4)
        - Internet Security (CYY503/4)

        ## **2016/2017 – 2017/2018**
        - Introduction to Real Time Operating Systems and Applications (EES502/4)
        - Special Topics in Next Generation Internet (CYY505/4)
        - Internet Communications Protocols (CYY502/4)

        ## **Prior to 2016 @ TU Darmstadt**
        - PNS: Protection in Networked Systems ‒ Trust, Resilience, and Privacy
        - Seminar: Protection in Infrastructures and Networks (PIN) — Topic Supervisor
        - Simulation and Evaluation of Computer Networks (SECoN)
        - Seminar Telekooperation
        - Seminar Security, Privacy, and Trust
        - Projectpraktikum
        - Bachelor Students Traineeship / Bachelorpraktikum
        - Internet Praktikum
    design:
      columns: '2'
  - block: markdown
    id: services
    content:
      title: Services
      subtitle: ''
      text: |-
        ## **Membership**
        - Asia Pacific Advanced Network (APAN) - Security Working Group, *Chair (2026–2028; Co-Chair 2024–2026)*
        - Malaysian Research and Education Network (MyREN) - Internet Security Working Group, *Deputy Head*
        - Malaysian Board of Technologists (MBOT), *Professional Technologist*
        - Cyber Security Academia Malaysia, *Member*
        - Institute of Electrical and Electronics Engineers (IEEE), *Member (2013–2017)*

        ## **Journal Reviewer**
        - [ACM Computing Surveys (CSUR)](https://dl.acm.org/journal/csur)
        - [IEEE Transactions on Information Forensics & Security (T-IFS)](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=10206)
        - [IEEE Access](https://ieeeaccess.ieee.org/)
        - [IEEE Communications Magazine](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=35)
        - [Computer Networks - Elsevier](https://www.journals.elsevier.com/computer-networks)
        - [Information Systems - Elsevier](https://www.journals.elsevier.com/information-systems)
        - [Journal of Information Security and Applications (JISA) - Elsevier](https://www.journals.elsevier.com/journal-of-information-security-and-applications)
        - [Computers and Electrical Engineering - Elsevier](https://www.journals.elsevier.com/computers-and-electrical-engineering)
        - [International Journal of Network Management](https://onlinelibrary.wiley.com/journal/10991190)
        - [Wireless Communications and Mobile Computing](https://onlinelibrary.wiley.com/journal/15308677)
        - [PeerJ Computer Science](https://peerj.com/computer-science/)

        ## **Committees & Assessor Roles**
        - MRANTI Cybersecurity Technical Advisory Panel, AV Living Lab
        - MDEC Project Monitoring Assessor / Grant Recommendation Committee
        - USM Mobile Access Coordinator (COVID-19)
        - USM Industry Liaison Fellow
        - USM Cyber Security Awareness Program - Subject Matter Expert
        - HRD Corp Accredited Trainer, Human Resource Development Corporation
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

---
title: About
layout: PageLayout
sections:
  - type: DividerSection
    colors: colors-d
    styles:
      self:
        width: wide
        padding:
          - pt-0
          - pb-4
          - pl-0
          - pr-0
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: FeaturedPeopleSection
    colors: colors-c
    elementId: ''
    variant: variant-c
    title: About Me
    actions: []
    people:
      - content/data/team/desmond-eagle.json
      - content/data/team/hilary-ouse.json
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: center
        textDecoration: underline
      subtitle:
        textAlign: center
      actions:
        justifyContent: center
  - type: TextSection
    colors: colors-c
    variant: variant-a
    title: About our business
    text: "Hi, I am Sahil Sinha and thanx for visit my portfolio website.\n\nSo, I am from Gaya, Bihar, currently taking up Bachelor's Degree in Information Technology from Veltech University Chennai, waiting for my degree in 2023.\n\nApart from that, I am working as a Academic Writing Intern at the Paperpedia pvt. ltd. where I am honing my skills in related fields.  I am also working on data analysis tools such as PowerBl and Tableau.\n\nOther than that, I have a HackerRank certification in Basic Python & SQL. Apart from that, I have excellent communication skills and am always willing to adapt to new technologies and skills.\n\nI have also completed projects such as cryptocurrency price prediction and smart homes using iot with cloud computing where I am a researcher and implements Python and machine learning\_modules.\n\nMy other hobbies are writing, exploring nature and enjoying\_the\_moment.\n\n## Why Should You Hire Me?\n\nAs I have just started my career in data science, I don’t have many practical achievements to talk about. This gives me the liberty to explore my potential by giving my best to this organization. I am confident that I can make significant contributions to the team and help achieve the company’s goals.\n\nApart from this I have always been dedicated to my academics and data science projects, and I always complete them well in time. In college, I was appreciated for my dedication and hard work. I am confident that I can bring the same level of dedication and commitment to this organization. I am also willing to learn new things and explore my potential. I believe that I have the skills and abilities to be a successful data scientist.\nI am excited to start my career in data science, and I am confident that I will be a valuable asset to this organization. I am looking forward to working with you and contributing to the success of the company. Thank you for your time and\_consideration.\n\n## Strength\n\n*   I am a self-motivated well-desciplined and interactive person.\n\n<!---->\n\n*   Apart from that, I also have excellent communication skills and am always willing to adapt new technologies and skills.\n    Other that than I have done several projects in machine learning, deep learning and artificial intelligence.\n\n*   As a data science professional, I can always work in statistics and analytics. Apart from that, I am good at data storytelling and critical\_thinking.\n\n## Weakness\n\n*   Sometimes I hesitate to ask for help.\n\n<!---->\n\n*   I aways try to do things Perfectly which sometimes consumes\_a\_lot\_of\_time.\n\n### Technical Skills\n\n*   SQL\n\n*   Python\n\n*   HTML\n\n### Tool Skill\n\n*   Numpy\n\n*   Pandas\n\n*   PowerBI\n\n*   Tableau\n\n*   Matplotlip\n\n### Soft Skill\n\n*   Team Work\n\n*   Adaptability\n\n*   Communication\n\n*   Critical Thinking\n\n*   Problem Solving\n\n*   Time Management\n\n#### Languages\n\n*   English(Fluent)\n\n*   Hindi(Native)\n\n*   French(Beginner)\n\n#### **INTERNSHIP**\n\n**Academic Writing Intern**\n\n```\nPaperpedia Pvt Ltd\nJan 2023- Present\n```\n\n#### **EDUCATION**\n\n**B.Tech, Information Technology**\n\n```\nVeltech University\n2019-2023\nGrade-8.07 (Till 6 Semester)\n\n \n```\n\n**Intermidiate**\n\n```\nSri Chaitanya\n2017-2019\nGrade-87.2%\n\n \n```\n\n**SSC**\n\n```\nDAV Public School\n2005-2017\nGrade-7.0\n```\n\n#### **Co Curriculam Activity**\n\n**French Language & Tourism**\n\n```\nIHM Bodhgaya\nAug 2022-Sept 2022\n```\n\n"
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-32
          - pb-56
          - pr-4
          - pl-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
  - elementId: ''
    variant: variant-c
    colors: colors-c
    title: Our Team
    subtitle: >-
      We’re a group of proffesional fisherman & friends, who love exploring the
      seas and sharing our experiences with the world.
    people:
      - content/data/team/hilary-ouse.json
      - content/data/team/dianne-ameter.json
      - content/data/team/desmond-eagle.json
      - content/data/team/hugh-saturation.json
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-36
          - pb-72
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
      actions:
        justifyContent: center
    type: FeaturedPeopleSection
  - type: ContactSection
    colors: colors-d
    title: Join our club
    text: >
      We will notify you every time a shipment is heading to your neighborhood,
      and you could immediatly let us know if you want in or not
    form:
      type: FormBlock
      elementId: sign-up-form
      destination: ''
      action: /.netlify/functions/submission_created
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: address
          label: Address
          hideLabel: true
          placeholder: Address
          isRequired: true
          width: full
          type: TextFormControl
        - name: updatesConsent
          label: Sign me up to recieve updates
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: Submit form
      styles:
        submitLabel:
          textAlign: center
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-4
          - mr-4
        padding:
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: center
      text:
        textAlign: center
  - type: DividerSection
    colors: colors-d
    styles:
      self:
        width: wide
        padding:
          - pt-4
          - pb-4
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
addTitleSuffix: true
---

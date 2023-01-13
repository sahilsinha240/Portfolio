---
layout: PageLayout
sections:
  - type: DividerSection
    colors: colors-d
    styles:
      self:
        width: wide
        padding:
          - pt-0
          - pb-6
          - pl-0
          - pr-0
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: HeroSection
    colors: colors-d
    elementId: ''
    backgroundSize: full
    title: Welcome to my portfolio website!
    subtitle: Python. Analytics. PowerBI. SQL.
    text: ''
    actions:
      - type: Button
        label: Resume
        showIcon: false
        icon: arrowRight
        style: primary
        url: >-
          https://drive.google.com/file/d/1DNQlny9XpDNxlTcOBbEglimdV3c8_S6x/view?usp=share_link
      - type: Button
        label: Projects
        altText: ''
        url: /blog
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
      - type: Link
        altText: ''
        url: 'https://www.linkedin.com/in/sahil-sinha-432773185'
        showIcon: true
        icon: linkedin
        iconPosition: right
        elementId: ''
      - type: Link
        altText: ''
        url: 'https://github.com/sahilsinha240'
        showIcon: true
        icon: github
        iconPosition: right
        elementId: ''
      - type: Link
        altText: ''
        url: 'https://t.me/+919128689082'
        showIcon: true
        icon: send
        iconPosition: right
        elementId: ''
      - type: Link
        altText: ''
        url: 'mailto:sahilsinha240@gmail.com'
        showIcon: true
        icon: mail
        iconPosition: right
        elementId: ''
      - type: Link
        altText: ''
        url: 'https://join.skype.com/invite/u0j9wRyacBQg'
        showIcon: true
        icon: playCircle
        iconPosition: right
        elementId: ''
    media:
      type: ImageBlock
      url: /images/Homepic.jpg
      altText: Hero image
    backgroundImage:
      type: BackgroundImage
      url: /images/layered-steps-haikei (1).svg
      backgroundSize: cover
      backgroundPosition: center
      backgroundRepeat: no-repeat
      opacity: 100
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
  - type: FeaturedPostsSection
    colors: colors-a
    elementId: ''
    showDate: true
    showAuthor: false
    showExcerpt: false
    showReadMoreLink: true
    variant: variant-d
    actions:
      - type: Link
        label: See all Projects
        altText: See all adventures
        url: /blog
        showIcon: true
        icon: arrowRight
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-start
    title: Top Projects
    subtitle: ''
    posts:
      - content/pages/blog/post-three.md
      - content/pages/blog/post-two.md
      - content/pages/blog/post-four.md
    readMoreLinkLabel: Know More
  - type: FeatureHighlightSection
    colors: colors-d
    backgroundSize: full
    title: Visualize Dashboard
    actions:
      - type: Link
        label: See all Dashboards
        url: /dashboard
        showIcon: true
        icon: arrowRight
    backgroundImage:
      type: BackgroundImage
      url: /images/bg2.gif
      backgroundSize: cover
      backgroundPosition: center
      backgroundRepeat: no-repeat
      opacity: 90
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-36
          - pb-72
          - pr-4
          - pl-4
        justifyContent: flex-start
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
  - type: TextSection
    colors: colors-d
    variant: variant-a
    text: |+
      # Skills

      #### **Technical Skills**

      ```
      SQL
      Python
      Analytics
      HTML
      ```

      #### **Tools/Package**

      ```
      Numpy
      Pandas
      Tableau
      PowerBI
      Matplotlip
      Wordpress
      ```

      #### **Soft Skills**

      ```
      Team Work
      Adaptability
      Communication
      Critical Thinking
      Problem Solving
      ```

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
          - pb-36
          - pr-4
          - pl-4
        justifyContent: center
      text:
        textAlign: center
  - type: FeaturedItemsSection
    colors: colors-c
    elementId: ''
    subtitle: ''
    items:
      - type: FeaturedItem
        title: Internship
        text: |+
          ###### **Academic Writing Intern**

          ```
          Paperpedia Pvt. Ltd
          Jan 2023-Present
          ```



        actions: []
        styles:
          self:
            textAlign: left
          title:
            fontWeight: 500
            textDecoration: underline
      - type: FeaturedItem
        title: Education
        text: |+
          ###### **B.Tech, Information Technology**

          ```
          Veltech University
          2019-2023
          Grade:-8.06(Till 6th sem)
          ```

          ###### **Intermidiate**

          ```
          Sri Chaitanya
          2017-2019
          Grade:-87.2%
          ```

          ###### **SSC**

          ```
          DAV Public School
          2005-2017
          Grade:-7.0
          ```

        actions: []
        styles:
          self:
            textAlign: left
          title:
            fontWeight: 500
            textDecoration: underline
      - type: FeaturedItem
        title: Co Curricular Activity
        text: >-
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed ante
          lorem, tincidunt ac leo efficitur, feugiat tempor odio. Maecenas
          pharetra ipsum dolor, et iaculis elit ornare ac.
        actions:
          - type: Button
            label: Learn more
            showIcon: true
            icon: arrowRight
            url: /
            style: primary
        styles:
          self:
            textAlign: left
          title:
            textDecoration: underline
    actions: []
    columns: 1
    spacingX: 16
    spacingY: 16
    enableHover: false
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-36
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-start
  - type: TextSection
    colors: colors-c
    elementId: ''
    variant: variant-a
    subtitle: ''
    text: |+
      ## **INTERNSHIP**

      ###### **Academic Writing Intern**

      ```
      Paperpedia Pvt. Ltd
      Jan 2023-Present
      ```

      ## **EDUCATION**

      ###### **B.Tech, Information Technology**

      ```
      Veltech University
      2019-2023
      Grade:-8.06(Till 6th sem)
      ```

      ###### **Intermidiate**

      ```
      Sri Chaitanya
      2017-2019
      Grade:-87.2%
      ```

      ###### **SSC**

      ```
      DAV Public School
      2005-2017
      Grade:-7.0
      ```

      ## **Co Curriculam Activity**

      ###### **French Language & Tourism**

      ```
      IHM Gaya
      July 2021-Sept 2021
      ```

    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-28
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
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
metaTags: []
title: Sahil Sinha
---

---
title: Home
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
          https://drive.google.com/file/d/1mQg5RIM7Q9SB0vb07eI3_5OV6Fitm832/view?usp=share_link
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
    readMoreLinkLabel: Join adventure
    variant: variant-d
    actions:
      - type: Link
        label: See all adventures
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
      - content/pages/blog/post-one.md
  - type: FeatureHighlightSection
    colors: colors-d
    backgroundSize: full
    title: Visualize Dashboard
    actions:
      - type: Link
        label: See all Dashboard
        url: 'https://www.stackbit.com/'
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
  - type: QuoteSection
    colors: colors-d
    quote: >-
      “It’s great to see someone taking action while still maintaining a
      sustainable fish supply to home cooks.”
    name: Isabelle Parks
    title: Head chef at Parks
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-28
          - pb-36
          - pr-4
          - pl-4
        justifyContent: center
      quote:
        textAlign: center
      name:
        textAlign: center
      title:
        textAlign: center
  - type: TextSection
    colors: colors-e
    variant: variant-a
    text: '## [Follow us on Instagram](https://www.stackbit.com/)'
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
          - ml-0
          - mr-0
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
metaTags: []
---

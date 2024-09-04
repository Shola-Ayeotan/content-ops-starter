---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: Welcome to my portfolio!
      color: text-dark
      type: TitleBlock
    subtitle: ''
    text: >
      I’m a data scientist with a passion for solving problems through data. My
      work focuses on analyzing patterns, building predictive models, and
      delivering actionable insights that help businesses and organizations make
      informed decisions.
    actions:
      - label: ''
        altText: Linkedin
        url: 'https://www.linkedin.com/in/oluwanishola/'
        showIcon: true
        icon: linkedin
        iconPosition: right
        style: primary
        elementId: ''
        type: Link
      - type: Link
        altText: GitHub
        url: 'https://github.com/Shola-Ayeotan'
        showIcon: true
        icon: github
        iconPosition: left
        style: secondary
        elementId: ''
      - type: Link
        altText: Instagram
        url: 'https://www.instagram.com/theoluwanishola'
        showIcon: true
        icon: instagram
        iconPosition: right
        style: secondary
        elementId: ''
      - type: Link
        altText: Twitter
        url: 'https://twitter.com/theoluwanishola'
        showIcon: true
        icon: twitter
        iconPosition: left
        style: secondary
        elementId: ''
    media:
      altText: Oluwanishola Ayeotan
      elementId: ''
      type: ImageBlock
      url: /images/7.png
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        margin:
          - mr-0
  - type: DividerSection
    title: Divider
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-3
          - pl-3
          - pb-3
          - pr-3
  - subtitle: A snapshot of my technical skills and proficiencies
    images:
      - url: /images/5.png
        altText: Python  logo
        type: ImageBlock
      - url: /images/3.png
        altText: SQL logo
        type: ImageBlock
      - url: /images/4 (2).png
        altText: R logo
        type: ImageBlock
      - url: /images/1.png
        altText: PowerBI logo
        type: ImageBlock
      - url: /images/1 (2).png
        altText: Looker logo
        type: ImageBlock
      - url: /images/Untitled design (1).png
        altText: Tensorflow logo
        type: ImageBlock
      - type: ImageBlock
        url: /images/3 (3).png
        altText: Image alt text placeholder
        elementId: ''
        styles:
          self:
            borderRadius: medium
      - type: ImageBlock
        url: /images/5 (2).png
        altText: SKLearn alt text placeholder
        elementId: ''
        styles:
          self:
            borderRadius: medium
      - url: /images/1 (3).png
        altText: Azure logo
        type: ImageBlock
      - type: ImageBlock
        url: /images/2 (3).png
        altText: GCP  alt text placeholder
        elementId: ''
        styles:
          self:
            borderRadius: medium
      - type: ImageBlock
        url: /images/4 (3).png
        altText: Image alt text placeholder
        elementId: ''
        styles:
          self:
            borderRadius: medium
    motion: move-to-left
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
    type: ImageGallerySection
  - type: GenericSection
    subtitle: ABOUT ME
    text: >
      With an MSc in Data Science from the University of Salford and an MBA in
      Business Intelligence, I specialize in transforming complex data into
      strategic assets. My expertise spans machine learning, predictive
      modelling, and data visualization, all aimed at solving real-world
      problems and adding tangible business value. I thrive on challenges that
      require innovative thinking, and I’m committed to continuous learning and
      staying ahead in this fast-evolving field.
    actions:
      - type: Link
        label: Learn more about me
        altText: ''
        url: /About
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
    media:
      type: VideoBlock
      title: Title of the video
      url: /images/placeholder-video.mp4
      autoplay: true
      loop: true
      muted: true
      controls: false
      aspectRatio: '16:9'
      styles:
        self:
          padding:
            - pt-1
            - pb-1
            - pl-1
            - pr-1
          borderColor: border-neutral
          borderStyle: solid
          borderWidth: 1
          borderRadius: medium
    colors: bg-light-fg-dark
    styles:
      self:
        flexDirection: row
        justifyContent: flex-start
        padding:
          - pt-16
          - pr-16
          - pl-16
          - pb-16
        alignItems: center
      subtitle:
        textAlign: left
        fontWeight: 700
      text:
        textAlign: left
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - posts:
      - content/pages/blog/ecommerce.md
      - content/pages/blog/case-study-2.md
      - content/pages/blog/case-study-3.md
    showThumbnail: true
    showDate: true
    showAuthor: true
    variant: three-col-grid
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
    type: FeaturedPostsSection
    hoverEffect: shadow-plus-move-up
    title:
      type: TitleBlock
      text: My Work
      color: text-dark
    actions:
      - type: Button
        label: Explore More Projects
        altText: ''
        url: /projects
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
      - type: Button
        label: Github Repo
        altText: ''
        url: 'https://github.com/Shola-Ayeotan'
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
    subtitle: Here’s a showcase of some of my published projects.
    showExcerpt: true
  - title:
      text: Get in touch
      color: text-dark
      type: TitleBlock
    subtitle: ''
    text: >
      I’d love to hear from you. Kindly feel free to reach out, anytime, through
      [ayeotanofficial@gmail.com.](mailto:ayeotanofficial@gmail.com)
    media:
      fields:
        - name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          isRequired: true
          width: full
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Your email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Your message
          width: full
          type: TextareaFormControl
      elementId: contact-form
      styles:
        self:
          padding:
            - pt-6
            - pb-6
            - pl-6
            - pr-6
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
      type: FormBlock
      submitButton:
        type: SubmitButtonFormControl
        label: Submit
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: null
    colors: bg-light-fg-dark
    type: GenericSection
    badge:
      type: Badge
      label: CONTACT ME
      color: text-primary
    styles:
      self:
        padding:
          - pt-16
          - pr-16
          - pb-16
          - pl-16
type: PageLayout
seo:
  type: Seo
  metaTitle: Shola Ayeotan
  metaDescription: This is a portfolio of all my published projects
---

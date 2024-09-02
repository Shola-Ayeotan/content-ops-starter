---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: Welcome to my portfolio!
      color: text-dark
      type: TitleBlock
    subtitle: Data nerd. Learning. Creativity.
    text: >
      I’m a data scientist with a passion for solving problems through data. My
      work focuses on analyzing patterns, building predictive models, and
      delivering actionable insights that help businesses and organizations make
      informed decisions.
    actions:
      - label: ''
        altText: Linkedin
        url: /www.linkedin.com/in/oluwanishola/
        showIcon: true
        icon: linkedin
        iconPosition: right
        style: primary
        elementId: ''
        type: Link
      - type: Link
        altText: GitHub
        url: /github.com/Shola-Ayeotan
        showIcon: true
        icon: github
        iconPosition: left
        style: secondary
        elementId: ''
      - type: Link
        altText: Instagram
        url: /www.instagram.com/theoluwanishola
        showIcon: true
        icon: instagram
        iconPosition: right
        style: secondary
        elementId: ''
      - type: Link
        altText: Twitter
        url: /twitter.com/theoluwanishola
        showIcon: true
        icon: twitter
        iconPosition: left
        style: secondary
        elementId: ''
    media:
      altText: Oluwanishola Ayeotan
      elementId: ''
      type: ImageBlock
      url: /images/1 (4).png
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
          - pr-1
        margin:
          - mr-0
    badge:
      type: Badge
      label: Data nerd. Learning. Creativity.
      color: text-primary
  - type: GenericSection
    title:
      text: Welcome to my portfolio!
      color: text-dark
      styles:
        self:
          textAlign: left
      type: TitleBlock
    subtitle: Section with a video subtitle
    text: |-
      Aenean eros ipsum, interdum quis dignissim non, sollicitudin vitae nisl.
      Aenean vel aliquet elit, at blandit ipsum. Sed eleifend felis sit amet
      erat molestie, hendrerit malesuada justo ultrices. Nunc volutpat at erat
      vitae interdum. Ut nec massa eget lorem blandit condimentum et at risus.
    actions: []
    media:
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
            - pt-2
            - pb-2
            - pl-2
            - pr-2
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
      type: VideoBlock
    elementId: null
    colors: bg-light-fg-dark
    styles:
      self:
        flexDirection: row
        justifyContent: center
      subtitle:
        textAlign: left
  - subtitle: A snapshot of my technical skills and proficiencies
    images:
      - url: /images/1 (2).png
        altText: Looker logo
        type: ImageBlock
      - url: /images/2 (2).png
        altText: Tensorflow logo
        type: ImageBlock
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
      - type: ImageBlock
        url: /images/5 (2).png
        altText: SKLearn alt text placeholder
        elementId: ''
        styles:
          self:
            borderRadius: medium
      - type: ImageBlock
        url: /images/3 (3).png
        altText: Image alt text placeholder
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
            - pt-2
            - pb-2
            - pl-2
            - pr-2
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
    colors: bg-light-fg-dark
    styles:
      self:
        flexDirection: row
        justifyContent: center
      subtitle:
        textAlign: left
        fontWeight: 700
  - type: GenericSection
    subtitle: ''
    text: >+
      With an MSc in Data Science from the University of Salford and an MBA in
      Business Intelligence, I am proficient at transforming complex data into
      strategic assets. My expertise spans machine learning, predictive
      modelling, and data visualization, all aimed at solving real-world
      problems and adding tangible business value. I thrive on challenges that
      require innovative thinking, and I’m committed to continuous learning and
      staying ahead in this fast-evolving field.

    actions:
      - type: Link
        label: Learn more about me
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
    media:
      type: ImageBlock
      url: /images/4 (4).png
      altText: Dope design preview
    badge:
      type: Badge
      label: ABOUT ME
      color: text-primary
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row-reverse
  - posts:
      - content/pages/blog/case-study-1.md
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
    hoverEffect: move-up
    title:
      type: TitleBlock
      text: My Work
      color: text-dark
    actions:
      - type: Button
        label: Explore More Projects
        altText: ''
        url: /Projects
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
    subtitle: Here’s a showcase of some of my published projects.
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
  - type: CarouselSection
    title: null
    subtitle: What our customers say about us
    items:
      - title: >-
          “A designer knows he has achieved perfection not when there is nothing
          left to add, but when there is nothing left to take away.”
        tagline: Testimonial 1
        subtitle: 'Maria Walters, Company'
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        image:
          url: /images/person-placeholder-light.png
          altText: Maria Walters
          styles:
            self:
              borderRadius: full
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
        type: FeaturedItem
      - title: >-
          "Design is a plan for arranging elements in such a way as best to
          accomplish a particular purpose."
        tagline: Testimonial 2
        subtitle: 'John Doe, Company'
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        image:
          url: /images/person-placeholder-light.png
          altText: John Doe
          styles:
            self:
              borderRadius: full
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
        type: FeaturedItem
      - title: >-
          "Design is how it works, how it functions. Good design doesn't just
          make a product aesthetically pleasing, it makes it a pleasure to use."
        tagline: Testimonial 3
        subtitle: 'Maria Walters, Company'
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        image:
          url: /images/person-placeholder-light.png
          altText: Maria Walters
          styles:
            self:
              borderRadius: full
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
        type: FeaturedItem
      - title: >-
          “A designer knows he has achieved perfection not when there is nothing
          left to add, but when there is nothing left to take away.”
        tagline: Testimonial 4
        subtitle: 'Maria Walters, Company'
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        image:
          url: /images/person-placeholder-light.png
          altText: Maria Walters
          styles:
            self:
              borderRadius: full
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
        type: FeaturedItem
      - title: >-
          "Design can be art. Design can be aesthetics. Design is so simple,
          that's why it is so complicated."
        tagline: Testimonial 5
        subtitle: 'Jane Walters, Company'
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        image:
          url: /images/person-placeholder-light.png
          altText: Maria Walters
          styles:
            self:
              borderRadius: full
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
        type: FeaturedItem
      - title: >-
          “Quote from some important person goes right here. I love using
          Netlify Create.”
        tagline: Testimonial 6
        subtitle: 'Jane Doe, Company'
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        image:
          url: /images/img-placeholder-dark.png
          altText: Jane Doe
          styles:
            self:
              borderRadius: full
          type: ImageBlock
        actions: []
        colors: bg-dark-fg-light
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
        type: FeaturedItem
    elementId: null
    variant: next-prev-nav
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
  - title:
      text: Get in touch
      color: text-dark
      type: TitleBlock
    subtitle: ''
    text: "You can reach out to me via my email -\_ayeotanofficial\\@gmail.com\_at any time.\n\n\n\n\n"
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
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---

---
title: Home
slug: /
sections:
  - type: CarouselSection
    items:
      - type: FeaturedItem
        title: Welcome to Samir's Store
        tagline: Lost
        subtitle: Increase your reach
        text: ''
        image:
          type: ImageBlock
          url: /images/1000079965.jpg
          altText: Featured item
          styles:
            self:
              borderRadius: medium
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
    variant: tabs-nav
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
  - type: GenericSection
    title:
      text: >-
        Discover the best online deals in fashion, electronics, beauty & more.
        Handpicked products just for you – shop smart, save big!
      color: text-dark
      type: TitleBlock
    subtitle: ''
    text: |
      1\. Best Deals, Smart Shopping – Shop Now!

      2\. Daily Discounts on Top Brands – Check It Out!

      3\. Save More, Shop Smarter – Tap Here!

      4\. Online Shopping Offers You Can’t Miss!

      5\. Your One-Stop Shop for Trending Products!
    actions: []
    media:
      url: /images/1000079950.jpg
      altText: >-
        Discover the best online deals in fashion, electronics, beauty & more.
        Handpicked products just for you – shop smart, save big!
      elementId: ''
      type: ImageBlock
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
      subtitle:
        fontWeight: 700
        textAlign: justify
  - type: GenericSection
    title:
      type: TitleBlock
      text: ''
      color: text-dark
    subtitle: ''
    text: ''
    actions:
      - type: Button
        label: SHOP NOW
        url: 'https://samir1845.github.io/online-store/'
        icon: arrowRight
        iconPosition: right
        style: secondary
        showIcon: true
    media:
      type: ImageBlock
      altText: Fun feature preview
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
  - type: DividerSection
    title: Divider
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-12
          - pl-12
          - pb-12
          - pr-12
  - subtitle: ''
    images:
      - url: /images/1000079951.jpg
        altText: Empathy logo
        type: ImageBlock
      - url: /images/1000079955.jpg
        altText: Wellster logo
        type: ImageBlock
      - altText: Vise logo
        type: ImageBlock
      - altText: Telus logo
        type: ImageBlock
      - altText: Contentful logo
        type: ImageBlock
      - altText: Sanity logo
        type: ImageBlock
      - altText: Rangle logo
        type: ImageBlock
    motion: move-to-left
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
    type: ImageGallerySection
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
  - title:
      text: Generic Section With A Form
      color: text-dark
      type: TitleBlock
    subtitle: Section with a form subtitle
    text: |-
      Aenean eros ipsum, interdum quis dignissim non, sollicitudin vitae nisl.
      Aenean vel aliquet elit, at blandit ipsum. Sed eleifend felis sit amet
      erat molestie, hendrerit malesuada justo ultrices. Nunc volutpat at erat
      vitae interdum. Ut nec massa eget lorem blandit condimentum et at risus.
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
          placeholder: Your Email
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
        icon: chevronDown
        iconPosition: right
        style: primary
        elementId: null
    badge:
      label: Contact Us
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    type: GenericSection
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---

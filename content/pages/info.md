---
type: PageLayout
title: About
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: >-
    http://res.cloudinary.com/dd4d1ezxa/image/upload/v1723852944/abme3_qicpky.png
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    text: >+
      ### Hey, I'm Evan and i'm a freelance visual artist. I've been making art
      for many years across several different mediums. Nowadays I focus on
      digital art but I often find myself using my photography skills or various
      of the other physical tools at my disposal to make something that truly
      stands out. 

    media:
      type: ImageBlock
      url: >-
        https://res.cloudinary.com/dd4d1ezxa/image/upload/v1723854682/games_crt_2_keq7zb.jpg
      altText: Hero image
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
          - pt-16
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
    subtitle: ''
  - type: CtaSection
    title: ''
    text: >+
      #### Check out the projects page to read about the interesting stories
      behind some of my pieces

    actions:
      - type: Button
        label: Projects
        altText: ''
        url: /projects
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
    colors: colors-f
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-4
          - pb-4
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: FeaturedItemsSection
    colors: colors-f
    items:
      - type: FeaturedItem
        actions:
          - type: Link
            label: Instagram
            url: 'https://www.instagram.com/evolvewithevan.co/'
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        actions:
          - type: Link
            label: Discord
            url: 'https://discord.com/'
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        actions:
          - type: Link
            label: Artstation
            url: 'https://www.artstation.com/evolve-with-evan'
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        title: ''
        subtitle: ''
        text: ''
        elementId: ''
        styles:
          self:
            textAlign: left
        actions:
          - type: Link
            label: email
            altText: ''
            url: 'mailto:evolvewithevan@gmail.com'
            showIcon: false
            icon: arrowRight
            iconPosition: right
            elementId: ''
    columns: 4
    spacingX: 120
    spacingY: 0
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        textAlign: left
    subtitle: 'You can find me here:'
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: LabelsSection
    colors: colors-f
    subtitle: 'Skills:'
    items:
      - type: Label
        label: Video Editing
      - type: Label
        label: 3D Animation
      - type: Label
        label: SVG Design
      - type: Label
        label: Image Editing
      - type: Label
        label: Python 2&3
      - type: Label
        label: Photography
      - type: Label
        label: Painting
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: TextSection
    variant: variant-a
    subtitle: 'Contact:'
    colors: colors-f
    text: |
      <evolvewithevan@gmail.com>
---

---
type: PageLayout
title: Lets make something awesome  ✦˚
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: >-
    https://res.cloudinary.com/dd4d1ezxa/image/upload/v1723688505/Untitled9_urlht1.png
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - type: CtaSection
    title: ''
    text: |+
      ## Let's make something awesome   ✦˚

    actions:
      - type: Button
        label: Order a commision
        altText: Order a commision button
        url: 'https://tally.so/r/m6xgkY'
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
      - type: Link
        label: Learn more
        altText: ''
        url: /learn-more
        showIcon: true
        icon: arrowRight
        iconPosition: right
        elementId: ''
    colors: colors-f
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-32
          - pb-20
          - pl-4
          - pr-4
        alignItems: flex-start
        justifyContent: center
        flexDirection: row
        borderWidth: 0
        borderStyle: solid
        borderRadius: none
      title:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
  - type: DividerSection
    title: Divider
    elementId: ''
    styles:
      self:
        width: full
        padding:
          - pt-4
          - pb-4
          - pl-24
          - pr-24
        justifyContent: center
        borderWidth: 1
  - type: QuoteSection
    quote: >
      "When the medium fails conspicuously, and especially if it fails in new
      ways, the listener believes something is happening beyond its limits."
    name: Johnna Doe
    title: Product Marketing Manager at Acme
    colors: colors-d
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-11
          - pb-11
          - pl-4
          - pr-4
        justifyContent: center
      quote:
        textAlign: left
      name:
        fontWeight": 500
        textAlign: left
      title:
        fontWeight": 400
        textAlign: left
  - type: MediaGallerySection
    title: Gallery
    subtitle: This is the subtitle
    images:
      - type: ImageBlock
        url: /images/gallery-1.jpg
        altText: Image one
        caption: Image one caption
        elementId: ''
    colors: colors-c
    spacing: 16
    columns: 1
    aspectRatio: auto
    showCaption: false
    enableHover: false
    elementId: ''
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
      subtitle:
        textAlign: center
  - type: FeaturedProjectsSection
    subtitle: ''
    actions:
      - type: Link
        label: See all projects
        altText: See all projects
        url: /projects
        showIcon: false
        icon: arrowRight
        iconPosition: right
        elementId: ''
    projects:
      - content/pages/projects/project-two.md
      - content/pages/projects/project-one.md
      - content/pages/projects/project-three.md
    colors: colors-f
    variant: variant-b
    elementId: ''
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
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
        justifyContent: center
    title: Recent Projects
  - type: MediaGallerySection
    title: Portfolio
    subtitle: ''
    images:
      - type: ImageBlock
        url: >-
          https://res.cloudinary.com/dd4d1ezxa/image/upload/v1723523368/bzr3kkwdnnycwycrvcic.jpg
        altText: Image one
        caption: Image one caption
        elementId: ''
      - type: ImageBlock
        url: >-
          https://res.cloudinary.com/dd4d1ezxa/image/upload/v1723524629/yuhxfnjzsizj9jomczyc.png
        altText: Image two
        caption: Image two caption
        elementId: ''
      - type: ImageBlock
        url: >-
          https://res.cloudinary.com/dd4d1ezxa/image/upload/v1723525323/tjnjxapbrr2k8qmoknqs.png
        altText: Image three
        caption: Image three caption
        elementId: ''
      - type: ImageBlock
        url: >-
          https://res.cloudinary.com/dd4d1ezxa/image/upload/v1723523462/pdhluttm6w6rbvumw9hy.png
        altText: Image four
        caption: Image four caption
        elementId: ''
      - type: ImageBlock
        url: >-
          https://res.cloudinary.com/dd4d1ezxa/image/upload/v1723516924/HBTherapy-small_mejlmc.jpg
        altText: Image five
        caption: Image five caption
        elementId: ''
      - type: ImageBlock
        url: >-
          https://res.cloudinary.com/dd4d1ezxa/image/upload/v1723524629/jrgn5sgwr8d33lyzeazu.png
        altText: Image six
        caption: Image six caption
        elementId: ''
      - type: ImageBlock
        url: >-
          https://res.cloudinary.com/dd4d1ezxa/image/upload/v1723524728/qtgos3x9agnpkug6uh74.png
        altText: Image seven
        caption: Image seven caption
        elementId: ''
      - type: ImageBlock
        url: >-
          https://res.cloudinary.com/dd4d1ezxa/image/upload/v1723523503/q4qjdtef1jsg5z9jkxhv.jpg
        altText: Image eight
        caption: Image eight caption
        elementId: ''
    colors: colors-a
    spacing: 12
    columns: 3
    aspectRatio: '1:1'
    showCaption: false
    enableHover: true
    elementId: ''
    styles:
      self:
        height: auto
        width: full
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
  - type: CtaSection
    title: ''
    text: |2
         
    actions:
      - type: Button
        label: Order a commision
        altText: ''
        url: 'https://tally.so/r/m6xgkY'
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
    colors: colors-a
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-2
          - pb-4
          - pl-2
          - pr-2
        alignItems: center
        justifyContent: flex-end
        flexDirection: col
        borderColor: border-dark
        borderRadius: xx-small
        margin:
          - ml-0
          - mt-0
          - mb-0
          - mr-0
      title:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
---

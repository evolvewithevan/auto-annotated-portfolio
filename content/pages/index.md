---
type: PageLayout
title: Home
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg1.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - type: CtaSection
    title: Let's make something awesome
    text: >+
      We will work together through every step of the process in order to make
      something that truly captures your vision.

    actions:
      - type: Button
        label: Order a commision
        altText: Order a commision button
        url: 'https://tally.so/forms/m6xgkY'
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
      - type: Link
        label: Learn more
        altText: ''
        url: /
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
        width: narrow
        padding:
          - pt-28
          - pb-28
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
  - type: MediaGallerySection
    title: Portfolio
    subtitle: ''
    images:
      - type: ImageBlock
        url: /images/gallery-1.jpg
        altText: Image one
        caption: Image one caption
        elementId: ''
      - type: ImageBlock
        url: /images/gallery-2.jpg
        altText: Image two
        caption: Image two caption
        elementId: ''
      - type: ImageBlock
        url: /images/gallery-3.jpg
        altText: Image three
        caption: Image three caption
        elementId: ''
      - type: ImageBlock
        url: /images/gallery-4.jpg
        altText: Image four
        caption: Image four caption
        elementId: ''
      - type: ImageBlock
        url: >-
          https://assets.stackbit.com/components/images/default/default-image.png
        altText: altText of the image
        caption: Caption of the image
        elementId: ''
      - type: ImageBlock
        url: >-
          https://assets.stackbit.com/components/images/default/default-image.png
        altText: altText of the image
        caption: Caption of the image
        elementId: ''
      - type: ImageBlock
        url: >-
          https://assets.stackbit.com/components/images/default/default-image.png
        altText: altText of the image
        caption: Caption of the image
        elementId: ''
      - type: ImageBlock
        url: >-
          https://assets.stackbit.com/components/images/default/default-image.png
        altText: altText of the image
        caption: Caption of the image
        elementId: ''
    colors: colors-a
    spacing: 76
    columns: 4
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
        label: View more
        altText: ''
        url: ''
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
        width: full
        padding:
          - pt-5
          - pb-5
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
        borderColor: border-dark
      title:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
  - type: FeaturedPostsSection
    elementId: ''
    colors: colors-f
    variant: variant-d
    subtitle: Featured Posts
    showFeaturedImage: false
    actions:
      - type: Link
        label: See all posts
        url: /blog
    posts:
      - content/pages/blog/post-six.md
      - content/pages/blog/post-four.md
      - content/pages/blog/post-three.md
    showDate: true
    showExcerpt: true
    showReadMoreLink: true
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
          - pt-28
          - pb-48
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
      actions:
        justifyContent: flex-end
  - type: ContactSection
    colors: colors-f
    backgroundSize: full
    title: "Got an interesting project? Tell me more...\U0001F4AC"
    form:
      type: FormBlock
      elementId: sign-up-form
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
          width: 1/2
          type: EmailFormControl
        - name: address
          label: Address
          hideLabel: true
          placeholder: Address
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: updatesConsent
          label: Sign me up to recieve updates
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: "Submit \U0001F680"
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
        textAlign: left
      text:
        textAlign: left
---

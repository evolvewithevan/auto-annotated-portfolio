---
type: PageLayout
title: Home
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg4.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - type: CtaSection
    title: ''
    text: |+
      ## Let's make something awesome



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
        width: wide
        padding:
          - pt-12
          - pb-11
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
        width: wide
        padding:
          - pt-4
          - pb-1
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
  - type: MediaGallerySection
    title: Recent Works
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
    spacing: 5
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
        label: View Portfolio
        altText: ''
        url: 'https://www.artstation.com/evolve-with-evan'
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

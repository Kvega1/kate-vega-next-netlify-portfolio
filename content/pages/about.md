---
type: PageLayout
title: About
sections:
  - type: HeroSection
    text: |+
      ## About

    actions:
      - type: Link
        label: Partners
        altText: ''
        url: '#partners_section'
        showIcon: false
        icon: arrowRight
        iconPosition: right
        elementId: ''
    media:
      type: ImageBlock
      url: /images/Kate Vega - Portrait Image - Custom.jpg
      altText: Hero image
    colors: colors-f
    backgroundSize: full
    elementId: ''
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
    subtitle: >-
      Are you looking for someone specialized in UI/UX end-to-end design AND
      development AND digital marketing who can deliver high-quality digital
      solutions for your business? My unique blend of experience paired with a
      diverse, multifaceted skill set make me an excellent candidate for your
      organization.
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
  - type: MediaGallerySection
    subtitle: 'Partners:'
    images:
      - type: ImageBlock
        url: /images/Logo 1.png
        altText: Logo one
        caption: Logo one
      - type: ImageBlock
        url: /images/Logo 2.png
        altText: Logo two
        caption: Logo two
      - type: ImageBlock
        url: /images/Logo 3.png
        altText: Logo three
        caption: Logo three
      - type: ImageBlock
        url: /images/Logo 4.png
        altText: Logo four
        caption: Logo four
      - type: ImageBlock
        url: /images/Logo 5.png
        altText: Logo five
        caption: Logo five
      - type: ImageBlock
        url: /images/Logo 6.png
        altText: Logo six
        caption: Logo 6
        elementId: ''
      - type: ImageBlock
        url: /images/Logo 7.png
        altText: Logo seven
        caption: Caption of the image
        elementId: ''
      - type: ImageBlock
        url: /images/Logo 8.png
        altText: Logo eight
        caption: Logo eight
        elementId: ''
      - type: ImageBlock
        url: /images/Logo 9.png
        altText: Logo nine
        caption: Logo nine
        elementId: ''
      - type: ImageBlock
        url: /images/Logo 10.png
        altText: Logo ten
        caption: Logo ten
        elementId: ''
      - type: ImageBlock
        url: /images/Logo 11.png
        altText: Logo eleven
        caption: Logo eleven
        elementId: ''
      - type: ImageBlock
        url: /images/Logo 12.png
        altText: Logo twelve
        caption: Logo twelve
        elementId: ''
    colors: colors-f
    spacing: 3
    columns: 5
    aspectRatio: auto
    showCaption: false
    enableHover: false
    styles:
      self:
        width: wide
        height: auto
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
    elementId: partners_section
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
    subtitle: 'You can find me here:'
    items:
      - type: FeaturedItem
        actions:
          - type: Link
            label: Behance
            url: 'https://www.behance.net/katherinevega3/project'
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        actions:
          - type: Link
            label: LinkedIn
            url: 'https://www.linkedin.com/'
        styles:
          self:
            textAlign: left
    actions: []
    colors: colors-f
    columns: 3
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
  - type: ContactSection
    title: Drop me a line...
    form:
      type: FormBlock
      fields:
        - type: TextFormControl
          name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          width: 1/2
          isRequired: true
        - type: TextFormControl
          name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          width: 1/2
          isRequired: false
        - type: EmailFormControl
          name: email
          label: Email
          hideLabel: true
          placeholder: Email
          width: full
          isRequired: true
        - type: TextareaFormControl
          name: message
          label: Message
          hideLabel: true
          placeholder: Tell me about your project
          width: full
          isRequired: true
        - type: CheckboxFormControl
          name: updatesConsent
          label: Sign me up to receive updates
          width: full
          isRequired: false
      submitLabel: Contact Me
      elementId: sign-up-form
      styles:
        submitLabel:
          textAlign: center
    colors: colors-f
    backgroundSize: full
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
          - pt-12
          - pb-12
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
    elementId: contact_section
  - type: TestimonialsSection
    testimonials:
      - type: Testimonial
        quote: >
          "I hired Kate for web design and found her work to be outstanding,
          precise, innovative and very professional! I definitely recommend
          her!"
        name: Salvatore D.
        title: Naturopathic Doctor N.D.
        elementId: ''
        styles:
          name:
            fontWeight: 400
          title:
            fontWeight: 400
      - type: Testimonial
        quote: >
          “Kate is beyond your average marketing expert. Her skill, knowledge
          and hard work ethic has helped grow my business through difficult
          times.”
        name: Johnna Doe
        title: Product Marketing Manager at Acme
        image:
          type: ImageBlock
          url: /images/person-3.jpg
          altText: Johnna Doe
          caption: Caption of the image
          elementId: ''
        elementId: ''
        styles:
          name:
            fontWeight: 400
          title:
            fontWeight: 400
    colors: colors-a
    variant: variant-a
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-28
          - pb-28
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
metaTags: []
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/Kate Vega - Background Image - Custom.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
---

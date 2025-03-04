---
type: PageLayout
title: Resume
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/Kate Vega - Background Image - Custom.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - type: LabelsSection
    colors: colors-f
    subtitle: 'Skills:'
    items:
      - type: Label
        label: HTML5
      - type: Label
        label: CSS3
      - type: Label
        label: Adobe Creative Cloud
      - type: Label
        label: Figma
      - type: Label
        label: Next.js
      - type: Label
        label: Webflow
      - type: Label
        label: Shopify
      - type: Label
        label: Hubspot
      - type: Label
        label: React
        url: ''
      - type: Label
        label: Builder.io
        url: ''
      - type: Label
        label: Salesforce Commerce Cloud
        url: ''
      - type: Label
        label: Adobe Experience Manager
        url: ''
      - type: Label
        label: Meta
        url: ''
      - type: Label
        label: Pinterest
        url: ''
      - type: Label
        label: SEO
        url: ''
      - type: Label
        label: Google Analytics
        url: ''
      - type: Label
        label: Personalization
        url: ''
      - type: Label
        label: A/B Testing
        url: ''
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
      design\@katevega.com
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
        subtitle: 'Experience:'
        text: |+
          **Current**

          *   Digital Art Director @ JOANN 

          **2016-2022**

          *   Graphic Design
          *   Web Design & Development
          *   Photography
          *   Digital Marketing

          **2015-2016**

          *   Web Designer @ Mason Companies

          **2013**

          *   intern developer at marketing agency

        styles:
          self:
            textAlign: left
            padding:
              - pt-0
              - pl-0
              - pb-0
              - pr-0
      - type: FeaturedItem
        subtitle: 'Education:'
        text: >+
          **2009-2012**


          *   Graduated Summa Cum Laude

          *   Kent State University

          *   BTAS Bachelor of Technical and Applied Sciences in Computer
          Technology with a Concentration in Web Applications Development


          **2009-2010**


          *   Graduated Summa Cum Laude

          *   Kent State University

          *   A.A.B. Associate and Applied Business in Computer Technology with
          a Concentration in Web Scripting and Multimedia Design


          **2001-2003**


          *   Youngstown State University

          *   Pursued a B.A. Bachelors of Art in graphic design and visual
          communications.

        styles:
          self:
            textAlign: left
            padding:
              - pt-0
              - pl-0
              - pb-0
              - pr-0
    columns: 2
    spacingX: 60
    spacingY: 60
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
    backgroundSize: full
    title: Drop me a line...
    colors: colors-f
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
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Tell me about your project
          isRequired: true
          width: full
          type: TextareaFormControl
        - name: updatesConsent
          label: Sign me up to receive updates
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: Contact Me
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
---

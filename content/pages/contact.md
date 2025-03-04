---
type: PageLayout
title: Contact
sections:
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

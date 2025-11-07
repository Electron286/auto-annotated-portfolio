---
type: PageLayout
title: Sobre mí
colors: colors-a
backgroundImage:
  type: BackgroundImage
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: Tomás Jiménez Lavid
    subtitle: Ingeniero de fabricación
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
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        flexDirection: row-reverse
        textAlign: left
    type: HeroSection
    actions: []
    text: >
      Soy ingeniero de telecomunicaciones con más de 20 años en el sector de la
      electromedicina.


      Actualmente también desarrollo Aventura Digital en Familia, una iniciativa
      educativa para que niños y padres aprendan juntos sobre Inteligencia
      Artificial.
    media:
      type: ImageBlock
      url: /images/Avatar.png
      altText: Tomás Jiménez Lavid
      caption: Tomás Jiménez Lavid
      elementId: ''
  - colors: colors-f
    type: FeaturedProjectsSection
    elementId: ''
    actions:
      - type: Link
        label: Ver todos los proyectos
        url: /proyectos
        altText: Ver todos los proyectos
        icon: ''
        iconPosition: right
        showIcon: false
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
    variant: variant-c
    projects:
      - content/pages/projects/project-two.md
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        textAlign: left
    subtitle: Trayectoria y proyectos
  - type: ContactSection
    colors: colors-f
    backgroundSize: full
    title: Ponte en contacto
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: Nombre
          label: Nombre
          hideLabel: true
          placeholder: Nombre
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: Apellidos
          label: Apellidos
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
        self:
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
        flexDirection: row
        textAlign: left
    text: |
      No dejes de escribirme, responderé en unas horas.
---

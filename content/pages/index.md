---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: Kontor for rådgivning av hørsel
      color: text-light
      type: TitleBlock
    subtitle: ''
    text: >
      Aures tilbyr skreddersydd audiopedagogisk behandling for å hjelpe deg med
      å høre bedre og kommunisere tydeligere – for et rikere og mer meningsfylt
      liv.
    actions:
      - label: Ta kontakt
        altText: ''
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
        type: Button
      - label: Les mer
        altText: ''
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
        type: Link
    media:
      altText: Unblock your team boost your time to production preview
      elementId: ''
      type: ImageBlock
    badge:
      label: Personlig audiopedagogisk behandling
      color: text-light
      type: Badge
    elementId: ''
    colors: bg-neutral-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-14
          - pl-11
          - pb-20
          - pr-11
  - type: FeaturedItemsSection
    title:
      text: Vår behandling
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: ''
    items:
      - type: FeaturedItem
        title: Lytte- og språktrening for hørselshemmede
        subtitle: ''
        text: "Vi tilbyr skreddersydd trening for personer med cochlea-implantat (CI) og høreapparat for å forbedre lytteferdigheter og språkforståelse.\_\n"
        actions: []
        elementId: null
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
            textAlign: left
        image:
          type: ImageBlock
          altText: ''
          elementId: ''
          styles:
            self:
              borderRadius: x-large
      - title: Kartlegging av lytteutvikling og kommunikasjon
        subtitle: ''
        text: "Vi gjennomfører omfattende kartlegging av klientens lytteutvikling og kommunikasjonsevner for å tilpasse treningsoppleggene best mulig.\_\n"
        image:
          altText: Featured icon two
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            textAlign: left
            justifyContent: center
        type: FeaturedItem
      - type: FeaturedItem
        title: Veiledning for brukere og deres nettverk
        subtitle: ''
        text: >
          Dette inkluderer familien, samt ansatte i skoler og barnehager, slik
          at alle forstår hvordan de best kan støtte og tilrettelegge for
          personer med hørselsutfordringer.
        image:
          type: ImageBlock
          altText: Placeholder text
          elementId: ''
          styles:
            self:
              borderRadius: x-large
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
            textAlign: left
      - title: 'Opplæring i hørselsteksniske hjelpemidler '
        subtitle: ''
        text: "Dette inkluderer TV-streamere, samtaleforsterkere og annet hørselsteknisk utstyr.\_Vi\_viser hvordan du kan få mest ut av disse hjelpemidlene.\n\n"
        image:
          altText: Featured icon three
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
        type: FeaturedItem
      - type: FeaturedItem
        title: Søknadshjelp for hørselteknisk utstyr
        subtitle: ''
        text: >+
          Vi hjelper til med søknadsprosessen for å få tilgang til nødvendig
          hørselsteknisk utstyr. Vår veiledning sikrer at du får riktig utstyr
          og støtte.

        image:
          type: ImageBlock
          altText: Placeholder text
          elementId: ''
          styles:
            self:
              borderRadius: x-large
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
            textAlign: left
      - type: FeaturedItem
        title: Tinnitus-behandling og oppfølging
        subtitle: ''
        text: >
          Dette inkluderer TV-streamere, samtaleforsterkere og annet
          hørselsteknisk utstyr. Våre eksperter viser hvordan du kan få mest
          mulig ut av disse hjelpemidlene.
        image:
          type: ImageBlock
          altText: Placeholder text
          elementId: ''
          styles:
            self:
              borderRadius: x-large
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
            textAlign: left
    actions: []
    badge:
      label: Audiopedagogiske tjenester
      color: text-primary
      styles:
        self:
          textAlign: center
      type: Badge
    elementId: ''
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pb-16
          - pt-16
          - pl-10
          - pr-10
        justifyContent: center
      subtitle:
        textAlign: center
  - title:
      text: Fyll ut skjemaet for å komme i kontakt
      color: text-dark
      type: TitleBlock
    subtitle: ''
    text: >
      Vi ønsker å høre fra deg! Hvis du har spørsmål, ønsker mer informasjon,
      eller ønsker å bestille en time, vennligst ta kontakt med oss.
    media:
      fields:
        - name: name
          label: Name
          hideLabel: true
          placeholder: Fullt navn
          isRequired: true
          width: full
          type: TextFormControl
        - name: E-post
          label: E-post
          hideLabel: true
          placeholder: E-post
          isRequired: true
          width: full
          type: EmailFormControl
        - type: TextFormControl
          name: Telefon
          label: Telefon
          hideLabel: true
          placeholder: Telefon
          isRequired: true
          width: full
        - name: message
          label: Message
          hideLabel: true
          placeholder: Hva trenger du hjelp med?
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
        label: Send
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: null
    badge:
      label: Kontakt oss
      color: text-dark
      type: Badge
    colors: bg-light-fg-dark
    type: GenericSection
    styles:
      self:
        padding:
          - pt-10
          - pl-10
          - pb-10
          - pr-10
seo:
  metaTitle: Aures - Rådgivningskontor for hørsel
  metaDescription: ''
  socialImage: /images/Hovedlogo_mbg.png
  type: Seo
type: PageLayout
isDraft: false
---

---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: Greetings from Healthify
      color: text-dark
      type: TitleBlock
    subtitle: >-
      Sri Lanka's ground breaking multi-purpose digital healthcare platform.
      Accessible and hassle free healthcare at your disposal.
    text: |
      Coming Soon !
    actions: []
    badge:
      label: ''
      color: text-primary
      type: Badge
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
  - type: CarouselSection
    items:
      - type: FeaturedItem
        title: Why Healthify ?
        tagline: Feature 1
        subtitle: ''
        text: >
          Tired of long waiting times and costly consultations ?

          Sick of all these hassle to access healthcare ?


          We are here to bridge these gaps. We at healthify aim to give you more
          than just cure to your illnesses.

          Join us to embark on a healthier journey. Let us take care of your
          health.
        image:
          type: ImageBlock
          url: /images/Healthify_icon@2x@2x.png
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
  - type: FeaturedItemsSection
    title:
      type: TitleBlock
      text: Our Services
      color: text-dark
      styles:
        self:
          textAlign: center
    subtitle: ''
    items:
      - type: FeaturedItem
        title: Virtual Consultations
        subtitle: ''
        text: >+
          Connect with your healthcare professional hassle free at the comfort
          of your home

        image:
          type: ImageBlock
          url: /images/icon1.svg
          altText: Lightning bolt symbol on red background
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
        title: ''
        subtitle: Health Counselling
        text: >
          We don't just cure disease, we prevent them. We provide individualised
          disease screening and health counselling. Be it exercise prescription,
          mental health or medical advice, we'd be your go to friend
        image:
          type: ImageBlock
          url: /images/icon2.svg
          altText: Featured icon two
          elementId: ''
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
      - type: FeaturedItem
        title: Health Monitoring
        subtitle: Remote health monitoring and home visits
        text: >
          We care about you more than you do. We keep track of your health and
          we will come to you when you need us.
        image:
          type: ImageBlock
          url: /images/avatar2.svg
          altText: Featured icon three
          elementId: ''
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
    actions:
      - type: Button
        label: Get started
        altText: ''
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
    badge:
      type: Badge
      label: ''
      color: text-primary
      styles:
        self:
          textAlign: center
    elementId: ''
    variant: small-list
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pb-16
          - pt-16
          - pl-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
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
      text: Join Us to Keep You healthy
      color: text-dark
      type: TitleBlock
    subtitle: We'll contact you as soon as we are live
    text: ''
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
          placeholder: Your email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Anything You'd like to hear from us ?
          width: full
          type: TextareaFormControl
          isRequired: false
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
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: null
    badge:
      label: ''
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

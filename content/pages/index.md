---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: Hi, I'm a Web & Mobile Developer
      color: text-dark
      type: TitleBlock
    subtitle: Building digital experiences that matter
    text: >
      I'm an experienced developer specializing in creating modern, responsive web applications and mobile solutions. With expertise in full-stack development, I transform ideas into polished, high-performance products that users love.
    actions:
      - label: View My Work
        altText: View Projects
        url: '#projects'
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Button
      - label: Get In Touch
        altText: Contact Me
        url: '#contact'
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
        type: Link
    media:
      url: /images/main-hero.svg
      altText: Developer illustration
      elementId: ''
      type: ImageBlock
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
  - type: GenericSection
    title:
      text: About Me
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: My journey as a developer
    text: >
      With years of experience in web and mobile development, I've had the privilege of working on diverse projects ranging from startup MVPs to enterprise applications. I'm passionate about clean code, user experience, and staying current with the latest technologies. When I'm not coding, you'll find me exploring new frameworks, contributing to open-source projects, or mentoring aspiring developers.
    actions: []
    elementId: about
    colors: bg-neutral-fg-dark
    styles:
      self:
        flexDirection: col
        justifyContent: center
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
      subtitle:
        textAlign: center
  - type: FeaturedItemsSection
    title:
      text: Technical Skills
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Technologies I work with
    items:
      - type: FeaturedItem
        title: Frontend Development
        subtitle: Building beautiful interfaces
        text: >-
          React, Vue.js, Next.js, TypeScript, Tailwind CSS, HTML5/CSS3. Creating responsive, accessible, and performant user interfaces that delight users.
        actions: []
        elementId: null
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
            justifyContent: flex-start
            textAlign: left
        image:
          type: ImageBlock
          altText: Frontend icon
          elementId: ''
          url: /images/icon1.svg
          styles:
            self:
              borderRadius: x-large
      - title: Mobile Development
        subtitle: Native & cross-platform apps
        text: >-
          React Native, Flutter, iOS, Android. Developing mobile applications that provide seamless experiences across all devices and platforms.
        image:
          url: /images/icon2.svg
          altText: Mobile development icon
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
            textAlign: left
            justifyContent: flex-start
        type: FeaturedItem
      - title: Backend Development
        subtitle: Scalable server solutions
        text: >-
          Node.js, Python, PostgreSQL, MongoDB, REST APIs, GraphQL. Building robust and scalable backend systems that power modern applications.
        image:
          url: /images/icon3.svg
          altText: Backend development icon
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
        type: FeaturedItem
    actions: []
    elementId: skills
    variant: three-col-grid
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
  - type: FeaturedItemsSection
    title:
      text: Featured Projects
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: A selection of my recent work
    items:
      - title: E-Commerce Platform
        tagline: Web Application
        subtitle: Full-stack development
        text: |
          A modern e-commerce platform built with Next.js, featuring real-time inventory management, secure payments, and an intuitive admin dashboard.
        image:
          url: /images/abstract-feature1.svg
          altText: E-Commerce Project
          styles:
            self:
              borderRadius: x-large
          type: ImageBlock
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
        type: FeaturedItem
        actions:
          - label: View Project
            url: '#'
            showIcon: true
            icon: arrowRight
            iconPosition: right
            style: primary
            type: Link
      - title: Fitness Tracking App
        tagline: Mobile Application
        subtitle: React Native
        text: |
          A cross-platform fitness app with workout tracking, progress analytics, and social features. Available on iOS and Android.
        image:
          url: /images/abstract-feature2.svg
          altText: Fitness App Project
          styles:
            self:
              borderRadius: x-large
          type: ImageBlock
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
        type: FeaturedItem
        actions:
          - label: View Project
            url: '#'
            showIcon: true
            icon: arrowRight
            iconPosition: right
            style: primary
            type: Link
      - title: SaaS Dashboard
        tagline: Web Application
        subtitle: TypeScript & React
        text: |
          A comprehensive analytics dashboard for a SaaS product, featuring real-time data visualization, team collaboration, and custom reporting.
        image:
          url: /images/abstract-feature1.svg
          altText: SaaS Dashboard Project
          styles:
            self:
              borderRadius: x-large
          type: ImageBlock
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
        type: FeaturedItem
        actions:
          - label: View Project
            url: '#'
            showIcon: true
            icon: arrowRight
            iconPosition: right
            style: primary
            type: Link
    variant: three-col-grid
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-8
          - pb-16
          - pr-8
        justifyContent: center
      subtitle:
        textAlign: center
    elementId: projects
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
      text: Let's Work Together
      color: text-dark
      type: TitleBlock
    subtitle: Get in touch
    text: |-
      I'm always interested in hearing about new projects and opportunities.
      Whether you have a question or just want to say hi, feel free to reach out!
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
          placeholder: Tell me about your project...
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
        label: Send Message
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: null
    badge:
      label: Contact
      color: text-primary
      type: Badge
    colors: bg-neutral-fg-dark
    type: GenericSection
    elementId: contact
seo:
  metaTitle: Developer Portfolio
  metaDescription: Experienced web and mobile developer specializing in modern, responsive applications. View my portfolio and get in touch.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---

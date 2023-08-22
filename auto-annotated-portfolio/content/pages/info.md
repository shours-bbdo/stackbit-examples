---
type: PageLayout
title: About
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg4.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    text: >
      I’m a graduate student currently pursuing my MS in Computational analytics
      at GeorgiaTech with a focus on Machine Learning and statistical methods.


      I'm currently working as a data scientist at BBDO Atlanta. I have
      previously worked for 5 years in different analytical roles in the field
      of finance.  
    media:
      type: ImageBlock
      url: /images/GT2022_Headshot_Low_Res.jpg
      altText: Hero image
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
    type: HeroSection
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
    colors: colors-f
    subtitle: 'I worked with these folks:'
    images:
      - type: ImageBlock
        url: /images/BBDO.png
        altText: BBDO
        caption: BBDO
      - type: ImageBlock
        url: /images/GoldmanSachs.png
        altText: Goldman Sachs
        caption: Goldman Sachs
        elementId: ''
      - type: ImageBlock
        url: /images/LineData.jpg
        altText: Linedata
        caption: Linedata
      - type: ImageBlock
        url: /images/Delloite.webp
        altText: Deloitte
        caption: Deloitte
    spacing: 50
    columns: 4
    aspectRatio: '3:2'
    showCaption: false
    enableHover: true
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
        actions:
          - type: Link
            label: Mail
            url: 'mailto:shourie.suraj@gmail.com'
            showIcon: true
            icon: mail
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        actions:
          - type: Link
            label: GitHub
            url: 'https://github.com/sshourie'
            showIcon: true
            icon: github
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        actions:
          - type: Link
            label: LinkedIn
            url: 'https://www.linkedin.com/in/suraj-shourie/'
            showIcon: true
            icon: linkedin
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        actions:
          - type: Link
            label: StackOverflow
            url: 'https://stackoverflow.com/users/6385519/suraj-shourie'
            showIcon: true
            iconPosition: right
            elementId: StackOverflow
        styles:
          self:
            textAlign: left
    columns: 4
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
    subtitle: 'You can find me here:'
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
  - type: LabelsSection
    colors: colors-f
    subtitle: 'Skills:'
    items:
      - type: Label
        label: Python
      - type: Label
        label: SQL
      - type: Label
        label: R
      - type: Label
        label: Javascript
      - type: Label
        label: Stackbit
      - type: Label
        label: Pancakes
      - type: Label
        label: C++
      - type: Label
        label: Swift
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

          *   Data scientist (Part-time) at BBDO Atlanta

          **2019-2022**

          *   Associate quantitative strategist at Goldman Sachs

          **2017-2019**

          *   Financial risk analyst at Linedata (previously know as Gravitas)

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
          **2022-2023 (Ongoing)**


          *   MS in Computational Analytics at Georgia Tech


          **2013-2017**


          *   BTech in Material Science at Indian Institute of Technology,
          Bombay

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
---

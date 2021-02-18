---
layout: blocks
title: Homepage
date: 2017-11-22T23:00:00.000+00:00
page_sections:
  - template: navigation-header
    block: header-1
    logo: "Logo.png"
    navigation:
      - link: "/"
        link_text: Home
      - link: "#mission"
        link_text: What we do
      - link: "#services"
        link_text: Services
      - link: "#team"
        link_text: Team


  - template: hero-banner-w-image
    block: hero-2
    slug: features
    headline:  <br><strong>Beat Coaster</strong>
    content:
      Glide through the space roller coaster to the rhythm of the music. A thrilling experience.
    cta:
      enabled: true
      url: https://play.google.com/store/apps/details?id=com.amapama.beatcoasterv3
      button_text: "Get it now!"
    image:
      image:  "/uploads/2018/06/21/beatcoaster.png"
    background_image: "/uploads/2018/06/21/background.png"

  - template: content-feature
    block: feature-1
    media_alignment: Left
    slug: mission
    headline:
      <strong>Games that fit in your pocket<span class="light">&nbsp;</span></strong>
    content:
      We create games that you can bring pretty much play anywhere, anytime on your favorite smart phone and smart watch.
    media:
      image: "/uploads/2018/06/21/product.png"

  - template: 3-column-text
    slug: services
    block: three-column-1
    col_1: 
      headline: Game development outsourcing
      content: Want to create your own PocketSized game with our help? Fear not. We can help you create your own mobile or watch game at a minimal cost.
    col_2: 
      headline: Game design consulatancy
      content: Need some advice on your own game? Fear not, with our years of experience we can prodive you with help you never knew you needed.
    col_3: 
      headline: 2D and 3D game asset outsourcing
      content: Need to create some awesome art for your great next hit? Of course we can help you with that.


  - template: 1-column-text
    slug: team
    block: one-column-1
    headline: Our team
    content: Has worked in the mobile game industry for about 6-7 years now, having worked on dozens of games, ranging from hypercasual up to hardcore games.




  - template: 4-column-footer
    block: footer-2
    image: "icon.png"
    col_2: <a href="mailto:martin.vuminhduc@gmail.com">Contact</a>
    col_3: <a href="privacy_policy.html">Privacy Policy</a>
    col_4: ""
---

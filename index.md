---
title: Home
sections:
  - type: heroblock
    title: Hi, I'm Manoj Khatri. <br> I am UI / UX and Front End Developer
    section_id: hero
    component: hero_block.html
    content: This section can contain a subtitle or tagline. The recommended length
      is one to three sentences, but can be changed as you prefer.
  - view_all_text: View All
    num_projects_displayed: 6
    section_id: latest-projects
    view_all_url: portfolio/index.html
    subtitle: An optional subtitle of the section
    title: Recent Work
    type: portfolioblock
    layout_style: mosaic
    component: portfolio_block.html
  - type: servicesblock
    title: What We Do
    section_id: services
    component: services_block.html
    subtitle: An optional subtitle of the section
    serviceslist:
      - title: Service Title
        content: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec nisl
          ligula, cursus id molestie vel, maximus aliquet risus. Vivamus in nibh
          fringilla, fringilla tortor at, pulvinar orci.
      - title: Service Title
        content: "Donec lobortis velit sed suscipit lobortis. Ut non quam metus. Nullam
          a maximus mi. Quisque justo nunc, sollicitudin euismod euismod at,
          tincidunt ut tellus. Vivamus rhoncus mattis varius. "
      - title: Service title
        content: Vestibulum a nunc ut eros condimentum posuere. Nullam dapibus quis nunc
          non interdum. Pellentesque tortor ligula, gravida ac commodo eu.
      - title: Service title
        content: Aliquam pulvinar, orci ac scelerisque tempus, felis leo sagittis justo,
          sit amet condimentum lorem nibh vel quam. Duis consectetur lorem
          ipsum, non efficitur urna viverra et.
  - type: testimonialsblock
    title: Testimonials
    section_id: testimonials
    component: testimonials_block.html
    subtitle: An optional subtitle of the section
    testimonialslist:
      - author: John Doe
        avatar: images/john_doe.jpg
        content: Vestibulum a nunc ut eros condimentum posuere. Nullam dapibus quis nunc
          non interdum. Pellentesque tortor ligula, gravida ac commodo eu.
      - author: Jane Roe
        avatar: images/jane_roe.jpg
        content: Sed laoreet magna commodo libero euismod sodales. Nunc ac libero
          convallis, interdum ligula vel, pretium diam. Integer commodo sem at
          dui sollicitudin, vel posuere justo laoreet.
  - type: postsblock
    title: Latest from the Blog
    section_id: latest-posts
    component: posts_block.html
    subtitle: An optional subtitle of the section
    num_posts_displayed: 2
    actions:
      - label: View Blog
        url: blog/index.html
  - type: contactblock
    title: Contact Us
    section_id: contact
    component: contact_block.html
    subtitle: An optional subtitle of the section
menus:
  main:
    title: Home
    weight: 1
layout: home
---

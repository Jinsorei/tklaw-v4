---
# Banner
banner:
  title: "TK & Associates giải pháp pháp lý ưu việt"
  content: "TK & Associates là công ty luật có trụ sở chính tại Thành phố Hồ Chí Minh. Kinh nghiệm, sự hiểu biết sâu sắc về luật pháp và văn hóa Việt Nam, cùng với đội ngũ luật sư có trình độ chuyên môn cao, chúng tôi mang đến cho khách hàng sự tin tưởng trong bất kỳ vấn đề pháp lý nào mà họ gặp phải."
  image: "/images/banner.png"
  button:
    enable: true
    label: "Tư vấn miễn phí"
    link: "/contact/"


title: My page
type: landing

sections:
  - block: slider
    content:
      slides:
        - title: 👋 Welcome to the group
          content: Take a look at what we're working on...
          align: center
          background:
            image:
              # Specify an image from `assets/media/`
              # or delete the image section to remove it
              filename: client-logo1.png
              filters:
                brightness: 0.7
            position: right
            color: '#666'
        - title: Lunch & Learn ☕️
          content: 'Share your knowledge with the group and explore exciting new topics together!'
          align: left
          background:
            image:
              # Specify an image from `assets/media/`
              # or delete the image section to remove it
              filename: client-logo2.png
              filters:
                brightness: 0.7
            position: center
            color: '#555'
        - title: World-Class Semiconductor Lab
          content: 'Just opened last month!'
          align: right
          background:
            image:
              # Specify an image from `assets/media/`
              # or delete the image section to remove it
              filename: client-logo3.png
              filters:
                brightness: 0.5
            position: center
            color: '#333'
          link:
            icon: graduation-cap
            icon_pack: fas
            text: Join Us
            url: ../contact/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      # Make the slides full screen within the browser window?
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000


# # Client Logos
# clientLogos:
#   - "/images/client-logo1.png"
#   - "/images/client-logo2.png"
#   - "/images/client-logo3.png"
#   - "/images/client-logo4.png"
#   - "/images/client-logo5.png"
#   - "/images/client-logo6.png"
#   - "/images/client-logo7.png"

# Features
features:
  - title: "What's Included in Hugoplate"
    image: "/images/service-1.png"
    content: "Hugoplate is a comprehensive starter template that includes everything you need to get started with your Hugo project. What's Included in Hugoplate"
    bulletpoints:
      - "10+ Pre-build pages"
      - "95+ Google Pagespeed Score"
      - "Build with Hugo and TailwindCSS for easy and customizable styling"
      - "Fully responsive on all devices"
      - "SEO-optimized for better search engine rankings"
      - "**Open-source and free** for personal and commercial use"
    button:
      enable: false
      label: "Get Started Now"
      link: "#"

  - title: "Discover the Key Features Of Hugo"
    image: "/images/service-2.png"
    content: "Hugo is an all-in-one web framework for building fast, content-focused websites. It offers a range of exciting features for developers and website creators. Some of the key features are:"
    bulletpoints:
      - "Zero JS, by default: No JavaScript runtime overhead to slow you down."
      - "Customizable: Tailwind, MDX, and 100+ other integrations to choose from."
      - "UI-agnostic: Supports React, Preact, Svelte, Vue, Solid, Lit and more."
    button:
      enable: true
      label: "Get Started Now"
      link: "https://github.com/zeon-studio/hugoplate"

  - title: "The Top Reasons to Choose Hugo for Your Hugo Project"
    image: "/images/service-3.png"
    content: "With Hugo, you can build modern and content-focused websites without sacrificing performance or ease of use."
    bulletpoints:
      - "Instantly load static sites for better user experience and SEO."
      - "Intuitive syntax and support for popular frameworks make learning and using Hugo a breeze."
      - "Use any front-end library or framework, or build custom components, for any project size."
      - "Built on cutting-edge technology to keep your projects up-to-date with the latest web standards."
    button:
      enable: false
      label: ""
      link: ""
---

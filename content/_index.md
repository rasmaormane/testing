---
title: 'home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: CoMet
      text: Be certain in your uncertainties!
      primary_action:
        text: Get Started
        url: user-guide/getting-started
        icon: rocket-launch
      # secondary_action:
      #   text: Read the docs
      #   url: https://docs.hugoblox.com
      announcement:
        text: "for the latest updates"
        link:
          text: "click here"
          url: "content/news/"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: background.jpg
          filters:
            brightness: 0.5
  # - block: stats
  #   content:
  #     items:
  #       - statistic: "1M+"
  #         description: |
  #           Websites built  
  #           with Hugo Blox
  #       - statistic: "10k+"
  #         description: |
  #           GitHub stars  
  #           since 2016
  #       - statistic: "3k+"
  #         description: |
  #           Discord community  
  #           for support
    # design:
    #   # Section background color (CSS class)
    #   css_class: "bg-gray-100 dark:bg-gray-900"
    #   # Reduce spacing
    #   spacing:
    #     padding: ["1rem", 0, "1rem", 0]
  - block: cta-image-paragraph
    id: about
    content:
      items:
        - title: Community Metrology Toolkit
          text: An open-source software project for assessing data uncertainties.
          feature_icon: check
          features:
            - "Handle, process & store measurement uncertainties"
          # Upload image to `assets/media/` and reference the filename here
          image: build-website.png
          caption: 'Image credit: [**Unsplash**](https://unsplash.com)'
          button:
            text: Learn More
            url: about/
            icon: rocket-launch
  - block: features
    id: tools
    content:
      title: Tools
      text: A list of tools which abstract away the complexity of dealing with uncertainties.
      items:
        - name: comet_maths
          icon: code-bracket
          description: useful mathematical algorithms, including interpolation with uncertainties
          button:
            text: Learn More
            url: https://www.comet-toolkit.org/tools/comet_maths/
            icon: rocket-launch
        - name: punpy
          icon: star
          description: propagates uncertainties on input quantities through any python function, evaluating the uncertainty on the output
        - name: obsarray
          icon: sparkles
          description: an extension to xarray for defining, storing and interfacing with uncertainty and measurement error-covariance information in NetCDF files using standardised metadata
    design:
    #   # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: cta-image-paragraph
    id: examples
    content:
      items:
        - title: Examples
          text: Exploring the possibilitites of CoMet!
          feature_icon: bolt
          features:
            - "Quantify uncertainties"
            - "Create digital effects tables"
            - "Validate measuriments"
          # Upload image to `assets/media/` and reference the filename here
          image: coffee.jpg
          caption: 'Image credit: [**Unsplash**](https://unsplash.com)'
          button:
            text: More
            url: user-guide/examples/
            icon: rocket-launch
  # - block: testimonials
  #   content:
  #     title: ""
  #     text: ""
  #     items:
  #       - name: "Hugo Smith"
  #         role: "Marketing Executive at X"
  #         # Upload image to `assets/media/` and reference the filename here
  #         image: "testimonial-1.jpg"
  #         text: "Awesome, so easy to use and saved me so much work with the swappable pre-designed sections!"
  #   design:
  #     spacing:
  #       # Reduce bottom spacing so the testimonial appears vertically centered between sections
  #       padding: ["6rem", 0, 0, 0]
  # - block: cta-card
  #   content:
  #     title: Build your future-proof website
  #     text: As easy as 1, 2, 3!
  #     button:
  #       text: Get Started
  #       url: https://www.comet-toolkit.org/
  #   design:
  #     card:
  #       # Card background color (CSS class)
  #       css_class: "bg-primary-700"
  #       css_style: ""
---

---
# An instance of the Pages widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: pages

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 90
title: "Publications"
subtitle: ""

title: Recent Publications
subtitle: ''

content:
  # Page type to display. E.g. post, talk, publication...
  page_type: publication
  # Choose how much pages you would like to display (0 = all pages)
  count: 5
  # Choose how many pages you would like to offset by
  offset: 0

  # Page order. Descending (desc) or ascending (asc) date.
  order: "desc"

  # Filter posts by a taxonomy term.
  filters:
    tag: "An UWB-based Communication Protocol Design for Infra-structure Free Cooperative Navigation"
    category: "11"
    publication_type: "22"
    author: "Jianan Zhu, Solmaz S. Kia"
    exclude_featured: false
  
design:
  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   4 = Citation (publication only)
  view: 2
  
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.
    
  # Background color.
  # color = "navy"
  
  # Background gradient.
  # gradient_start = "DeepSkyBlue"
  # gradient_end = "SkyBlue"
  
  # Background image.
  image: "architecture.png"  # Name of image in `static/img/`.
  image_darken: 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  # text_color_light = true  
  
advanced:
 # Custom CSS. 
 css_style: ""
 
 # CSS class.
 css_class: ""
---

{{% callout note %}}
Quickly discover relevant content by [filtering publications](./publication/).
{{% /callout %}}

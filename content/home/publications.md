---
# An instance of the Pages widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: pages

# This file represents a page section.
headless: true

<<<<<<< HEAD
# Order that this section appears on the page.
weight: 90
=======
title = "Publications"
subtitle = ""
>>>>>>> 7a502d0 (Update publications.md)

title: Recent Publications
subtitle: ''

content:
  # Page type to display. E.g. post, talk, publication...
  page_type: publication
  # Choose how much pages you would like to display (0 = all pages)
<<<<<<< HEAD
  count: 5
=======
  count = 0
  
>>>>>>> fec39d6 (Update publications.md)
  # Choose how many pages you would like to offset by
<<<<<<< HEAD
  offset: 0
  # Page order: descending (desc) or ascending (asc) date.
  order: desc
  # Filter on criteria
  filters:
    tag: ''
    category: ''
    publication_type: ''
    author: ''
    exclude_featured: true
design:
  # Choose a view for the listings:
=======
  offset = 0

  # Page order. Descending (desc) or ascending (asc) date.
  order = "desc"

  # Filter posts by a taxonomy term.
  [content.filters]
    tag = ""
    category = ""
    publication_type = ""
    author = "Jianan Zhu, Solmaz S. Kia"
    exclude_featured = false
  
[design]
  # Toggle between the various page layout types.
>>>>>>> 7a502d0 (Update publications.md)
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   4 = Citation (publication only)
<<<<<<< HEAD
  view: 4
---

{{% callout note %}}
Quickly discover relevant content by [filtering publications](./publication/).
{{% /callout %}}
=======
  view = 2
  
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
  # image = "background.jpg"  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  # text_color_light = true  
  
[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++

<<<<<<< HEAD
{{% alert note %}}
<!-- Quickly discover relevant content by [filtering publications]({{< ref "/publication/_index.md" >}}). -->
{{% /alert %}}
>>>>>>> 89bbbc0 (Update publications.md)
=======
<!-- {{% alert note %}}
Quickly discover relevant content by [filtering publications]({{< ref "/publication/_index.md" >}}).
{{% /alert %}} -->
>>>>>>> ccbf6ca (Update publications.md)

---
title: "Bias Compensation for UWB Ranging for Pedestrian Geolocation Applications"
authors:
- Jianan Zhu
- Solmaz S. Kia
date: "2019-08-13T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-08-13T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Sensors Letters*
#publication_short: In *STC*

abstract: We present an effective bias compensation method to process none-line-of-sight (NLoS) and long distance line-of-sight (LD-LoS) ultra wideband (UWB) range measurement signals used to aid a pedestrian inertial navigation system (INS). The common UWB bias compensation techniques use machine learning methods to identify and remove the bias in the measurements. These techniques are computationally expensive and require extensive prior data. Here, we propose to use an algorithmic compensation technique that accounts for the bias by estimating it using the Schmidt–Kalman filter (SKF). Next, we exploit the positivity of the error in the UWB range measurements to propose a novel constrained sigma point based correction filtering that can be used atop the SKF for further improvement in the positioning accuracy of the UWB-aided pedestrian inertial navigation. Experiments demonstrate the effectiveness of our methods.

# Summary. An optional shortened abstract.
summary: IEEE Sensors Letters

tags:
- Source Themes
featured: false

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8805384
#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
url_video: https://www.youtube.com/watch?time_continue=1&v=XXroFFLtnBI&feature=emb_title

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

<!-- {{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/). -->

---
title: "UWB ranging aided pedestrian geolocation with GPB-based Filtering for LoS and NLoS Measurement processing"
authors:
- Jianan Zhu
- Solmaz S. Kia
date: "2020-06-09T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "22020-06-09T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE/ION Position Location and Navigation Symposium 2020*
#publication_short: In *STC*

abstract: This paper considers the global localization of a pedestrian via an ultra-wideband (UWB) ranging aided inertial navigation system (INS) and aims to address the challenges involved in proper processing of UWB range measurements. Even though UWB offers a decimeter level accuracy in line-of-sight (LoS) ranging, its accuracy degrades significantly in non-line-of-sight (NLoS). This drop in accuracy is due to a significant unknown positive bias in the NLOS range measurements. Therefore, the measurement models used in UWB LoS and NLoS ranging conditions are different, and proper processing of NLoS measurements requires a bias compensation measure. Previous work on bias compensation for UWB ranging that is used to aid an INS based localization assumes that the LoS and NLoS measurements are identified and distinguished from each other with absolute certainty. However, in practice, this assumption is hard to satisfy, and identifiers that determine the type of UWB range measurements deliver their results with only some level of certainty. To take into account the probabilistic nature of the NLoS identifiers, in this paper, we propose an adaptive localization based on the first-order generalized pseudo Bayesian (GPB) method to seamlessly handle the measurement model switching between LoS and NLoS UWB range measurements. The effectiveness of our proposed method is demonstrated via an experiment for pedestrian geolocation using a shoe-mounted INS system aided by UWB range measurements with respect to beacons with known locations.

# Summary. An optional shortened abstract.
summary: Proceedings of the IEEE/ION Position Location and Navigation Symposium 2020

tags:
- Source Themes
featured: false

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9110175
#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
url_video: https://www.youtube.com/watch?v=FtrzGWvA_O8&feature=emb_title

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

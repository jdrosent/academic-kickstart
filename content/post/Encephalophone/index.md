---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Encephalophone"
subtitle: "**An EEG-based musical instrument for clinical therapy and performance art**


The Encephalophone is an EEG-based musical instrument for clinical therapy and performance art. The concept was created by Dr. Thomas Deuel, an M.D./Ph.D.
at from UW DXARTS and Seattle's Swedish Hospital. The device has been used for diverse projects including rehabilitative clinical trials with patients suffering motor impairment,
concerts, and brain-computer interface research.


The Encephalophone is controlled by user connected to an EEG. By modulating how much one thinks about movement (i.e. thinking about making a fist and squeezing), he/she
is able to control the mu rhythem of the motor cortex, an 8-12 Hz wave that is most prominent when a person is not moving nor thinking about moving. The power detected
in the mu rhythm frequency band in the motor cortex is used to select one of eight notes that are played via a SuperCollider engine.


I wrote the Matlab code that interfaced a commercially-available Mitsar EEG headset and amplifier with a laptop via the open-source Lab Streaming Layer (LSL) protocol,
processed the EEG data (e.g. filtering, power extraction, note classification) and transmitted notes to the SuperCollider engine."
summary: "An EEG-based musical instrument for clinical therapy and performance art"
authors: []
tags: []
categories: []
date: 2017-09-01T12:58:19-07:00
lastmod: 2020-03-20T12:58:19-07:00
featured: false
draft: false
reading_time: false  # Show estimated reading time?
share: false  # Show social sharing links?
profile: True  # Show author profile?
commentable: false  # Allow visitors to comment? Supported by the Page, Post, and Docs content types.
editable: false  # Allow visitors to edit the page? Supported by the Page, Post, and Docs content types.

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: "Smart"
  preview_only: True

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
{{< youtube pWdc9hHwRWg >}}

{{< youtube dbRSySv2B3g >}}
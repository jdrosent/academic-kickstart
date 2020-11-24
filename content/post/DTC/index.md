---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Digitally-Tuned Capacitors for Backscatter Communication"
subtitle: "**A wireless backscatter brain-computer interface for electrophysiology experiments**


Digitally-tuned capacitors are an interesting component for RF applications. They are often used to provide dynamic impedance matching for antennas in, e.g. cell phones
where external factors influence the resonant frequency of the antenna. 

High quality, low loss inductors are challenging to implement in small integrated circuits, but inductors are useful to designing the impedance constellation of backscatter modulators.
For this project, I explored how digitally-tuned capacitors could be used to prototype backscatter communication modulators without using inductors. In the paper I developed 
a Bluetooth Low Energy (BLE) compatible single-sideband (SSB) backscatter communication uplink using an inductor-free, digitally-tuned capacitance
modulator. The FPGA-based approach consumed 35.5 mW of total power, of which 34.8 mW (98.2%) was due to digital logic in the FPGA,
and only 600 μW (1.8%) was consumed by the backscatter modulator. 

The measured sideband suppression ratio was 10.7 dB. Over-the-air tests demonstrated compatibility with a completely
unmodified (neither hardware nor software modifications) iPad, iPhone, Samsung Android Smartphone, and an off-the-shelf BLE
chipset from Nordic Semiconductor. 

This all-digital approach points the way toward future single-chip, inductor-free SSB BLE-compatible backscatter sensors and devices."
summary: "Using digitally-tuned capacitors to create inductor-free backscatter modulators"
tags: [wireless communications, RFID, backscatter]
authors: []
categories: []
date: 2020-10-06T19:01:01-07:00 	
lastmod: 2020-10-07T19:01:01-07:00
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
  preview_only: true

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: ["publication/ros-kam-shar-rey-t-bio-c-19/index.md"]
---
![](photo.png)
---
title: "Automated Reports - IMLS, Public Libraries Survey"
tags: [LaTeX, R, ggplot2, education, automated reports]
author: "Michael Lee"
date: 2018-05-09
categories: ["projects"]
comments: true
subtitle: Automate the production of over 50 reports embedded with customized text, tables, and visualizations.
bigimg: [{src: "/img/alReport.png", desc: "IMLS, Public Libraries Survey Report"}]
twitterimg: "https://www.mikelee.co/img/alReport.png"
---


## Background
The Institute of Museum and Library Services' mission is to inspire libraries and museums to advance innovation, lifelong learning, and cultural and civic engagement. Each year it conducts a survey of the nation’s approximately 123,000 libraries and 35,000 museums to provide a snapshot of national and state-level trends.

## Development
The goal for this project was to automate the production of each state and jurisdiction's customized report. I acted as an R and LaTeX developer in creation of the template laying out these summary results. The typesetting was coded in LaTeX and embedded with the Myriad Pro and Museo Slab families for clarity and emphasis. The figures were generated using base R graphics. Finally, an Rmarkdown file was used to seamlessly integrate each state's visualizations into the summary report pdf.

Check out the Alabama version of the report [here](/img/ALReport.pdf).

## Software
- **R**: Data cleaning and data visualization production
- **LaTeX**: Document preparation and typesetting

### Click the image below to check out a sample IMLS Public Library Services report!

<div class="projectBox">
  <a href="/img/ALReport.pdf" target="_blank">
      <img src="/img/alReport.png" alt="Avatar" class="image" style="width:100%">
      <a href="/img/ALReport.pdf">
        <div class="middle">
          <div class="text">Click to view a sample report.</div>
        </div>
      </a>
  </a>
</div>

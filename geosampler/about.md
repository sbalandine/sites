---
title: "About"
output:
  rmarkdown::html_vignette:
    keep_md: yes
bibliography: bibliography.bib
csl: bibliography.csl
link-citations: yes
vignette: >
  %\VignetteIndexEntry{About}
  %\VignetteEncoding{UTF-8}
  %\VignetteEngine{knitr::rmarkdown}
---



# Estimating population size in the early phase of an emergency

Population and demographic figures in the aftermath of rapid-onset disasters or humanitarian emergencies provide relief agencies and humanitarian organisations with critical information to plan resource requirements or to assess health needs [@Brown2001; @sphere_association_sphere_2018; @telford_counting_1997], as well as to measure the impact of the disaster.

While conducting a population census is the best option for providing accurate data, it is, however, rarely feasible soon in the aftermath of a disaster, when a population count is most needed. Depending on the disaster effect, the population may be widely dispersed or may be gathered in refugee camps. Moreover, the movement of people after the event occurred adds an additional layer of complexity, and pre-disaster data may widely vary in quality or may be outdated.

# Population estimates through sampling

The aim of getting population estimates through sampling is to timely provide decision makers with sufficiently reliable information, so that to plan adequate resources.

Methods of estimating population size through sampling require alternative sample frames such as the list of geographical coordinates of the area where the population is located, or the list of tents in a refugee camp or the sample.

When compared with population census, sampling methods are more timely and less costly, but come the disadvantage of providing results with a degree in uncertainty. Moreover, different types and procedures of sampling may be considered in crisis situations. Recent sampling techniques take advantage of the more and more availability, and ease of access, of GIS data and tools, including satellites images, GPS devices and smartphones. Although part of the work can be carried remotely, a good knowledge of the field situation is, nevertheless, of paramount importance for choosing the sampling method that is more appropriate to the context.

## GeoSampler to facilitate the task

**GeoSampler** is a browser-based application that was created to facilitate and standardise procedures for **estimating population sizes using a sample of geographical information**. The application was created and is maintained by [Epicentre](https://epicentre.msf.org){target="_blank"} to support the field activities of [Médecins Sans Frontières](https://www.msf.org){target="_blank"}.

GeoSampler is developed in [R](https://www.r-project.org){target="_blank"} and based on the [Shiny](https://shiny.rstudio.com/){target="_blank"} package, and runs on a server or off-line on a computer.

Sampling and demographic techniques are continually being updated and improved. GeoSampler is flexible to implement new and update old methods.

# References

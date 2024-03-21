---
title: HYPERNETS Science Conference
summary: CoMet poster was presented at the HYPERNETS science conference.
date: 2023-03-20
authors:
  - admin
tags:
  - Uncertainty
  - Error
image:
  caption: 'Image credit: [**hypernets_processor**](https://hypernets-processor.readthedocs.io/)'

---

## ❔ What is HYPERNETS?

The HYPERNETS project has developed a new hyperspectral radiometer integrated in automated networks of water and land bidirectional reflectance measurements for satellite validation. 

## ❕ How is the CoMet Toolkit contributing to HYPERNETS?

A detailed uncertainty budget was measured in the lab for the HYPERNETS instruments. These uncertainties were then propagated from product to product using the CoMet Toolkit within the hypernets_processor. 

All HYPERNETS products are provided as obsarray-compatible digital effects tables. For the HYPERNETS vicarious calibration study, the uncertainties in these files are also propagated to TOA using punpy.


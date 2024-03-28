---
title: Introduction to uncertainties
summary: Walk-through the most important concepts relevant for CoMet Toolkit and its applications. 
date: 2024-03-19
authors:
  - RasmaOrmane
tags:
  - Uncertainty
  - Error
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com)'
---

Navigating the world of uncertainties can be quite tricky, as oftentimes terms such as _errors_ and _uncertainties_ are used interchangeably, even though they do not describe the same thing.

In this brief introduction to uncertainties and their propagation, we will highlight the most important concepts and signpost you to useful resources. 

By providing learning materials covering relevant topics at varying levels of depth, we want to ensure that you can fully understand and therefore implement the capabilities of this toolkit. 

## ❔ Why do we care about uncertainties?

Uncertainties are a vital aspect of the measurement science, as they provide credibility and trust in measured data. 

To ensure thet everyone is on the same page, a great place to start is this [Measurement Good Practice Guide](https://eprintspublications.npl.co.uk/1568/1/MGPG11.pdf#:~:text=Every%20measurement%20is%20subject%20to%20some%20uncertainty.%20A,environment%2C%20from%20the%20operator%2C%20and%20from%20other%20sources.) put together by the National Physical Labpratory (NPL).

It covers all the relevant terminology, best practises, and examples for understanding the uncertainty of measurements. 

As mentioned at the beginning of this article, we can confirm that _uncertainties_ and _errors_ are, in fact, not the same thing: 

  > **Uncertainty** is a quantification of the doubt about the measurement result. 


  > **Error** is the difference between the measured value and the "true value" of the thing being measured. 


## ✔️ Uncertainty in Earth Observations (EO)

Considering the origins of this toolkit, it makes sense to dive a bit deeper into the uncertainties in the context of **Earth Observations**.

A great resource that describes all the various aspects of uncertainty propapagtion for satellite EO data is [**FIDUCEO**](https://research.reading.ac.uk/fiduceo/). 

This project provides a comprehensive guide to understanding and implementing:

  - [Measurement functions](https://research.reading.ac.uk/fiduceo/fcdrs/theoretical-basis-2/1-determining-the-measurement-function/)
  - [Uncertainty effects](https://research.reading.ac.uk/fiduceo/fcdrs/theoretical-basis-2/2-defining-uncertainty-effects/)
  - [Uncertainty trees](https://research.reading.ac.uk/fiduceo/fcdrs/theoretical-basis-2/2-defining-uncertainty-effects/)
  - [Effects tables](https://research.reading.ac.uk/fiduceo/fcdrs/theoretical-basis-2/4-completing-the-effects-table/)
  - [Harmonisation](https://research.reading.ac.uk/fiduceo/fcdrs/harmonisation/)


## 🏆 Best practice framework fo EO



The Quality Assurance framework for Earth Observation (**QA4EO**) was established and endorsed by the Committee on Earth Observation Satellites (**CEOS**). 

QA4EO ensures credible and reliable interpretation of environmental observations from satellites and in-situ measurements by requiring that associated uncertainty information is provided. It is also key to understand error-covariances in the data (e.g., separate handling of random and systematic uncertainties).

The approaches defined within QA4EO enable the Earth observation (EO) community to develop quantitative characterisation of uncertainty in EO data. However, practically implementing these methods is not trivial and can be time consuming. To facilitate this, the CoMet Toolkit was developed to provide a means to store and propagate uncertainty and error-correlation information. These tools allow the user to rely on quality-assured code, rather than having to reinvent the wheel, and lower the barrier to entry for users new to handling uncertainties.




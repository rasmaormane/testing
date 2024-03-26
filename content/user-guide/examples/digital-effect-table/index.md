---
title: Digital Effects Table
summary: How to define a digital effect table?
date: 2024-03-20
authors:
  - admin
tags:
  - CoMet
  - Obsarray
image:
  #caption: 'Image credit: [**Unsplash**](https://unsplash.com)'
---

## 📋 Digital Effects Tables

> **Digital effects table** is 

Bellow, we have compiled a list of relevant examples and linked their corresponding jupyther notebooks with detailed comentary. 

1. A notebook containing examples that define **digital effects tables** is available [here](https://colab.research.google.com/github/comet-toolkit/comet_training/blob/main/defining_digital_effects_table.ipynb). 

It covers the following concepts:

  - How [obsarray]({{< relref "/tools/obsarray" >}}) can be used as a templater for efficiently making **xarray datasets** (both with and without uncertainties)?
  - How, using [obsarray's]({{< relref "/tools/obsarray" >}}) **special variable types** (uncertainties and flags), datasets including detailed uncertainty and covariance information as well as quality flags can be created? 
  - An example for a digital effects table quantifying the uncertainties and error-correlation of the gas temperature, pressure, and the number of moles. Here, the uncertainties can be efficiently and easily propagated through a **measurement function** using [punpy]({{< relref "/tools/punpy" >}}) ([learn more](https://colab.research.google.com/github/comet-toolkit/comet_training/blob/master/training/punpy_digital_effects_table_example.ipynb)).

2. An example, showcasing the application of [obsarray]({{< relref "/tools/obsarray" >}}) can be found [here](https://colab.research.google.com/github/comet-toolkit/comet_training/blob/main/obsarray_example.ipynb).

- An example of using punpy with digital effects tables created with [obsarray]({{< relref "/tools/obsarray" >}}) is explained [here](https://colab.research.google.com/github/comet-toolkit/comet_training/blob/main/defining_digital_effects_table.ipynb).

In this notebook, we have outlined how digital effects tables that are created with [obsarray]({{< relref "/tools/obsarray" >}}), can be propagated through a measurement function using [punpy]({{< relref "/tools/punpy" >}}). 

Here, we calculate the uncertainties in a volume of gas, using the ideal gas law and a digital effects table. 

Consequently, we quantified the uncertainties and error-correlation of the gas temperature, pressure and amount of substance (number of moles).
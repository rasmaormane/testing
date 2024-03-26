---
title: Examples
summary: How to utilise the various tools within the CoMet Toolkit?
date: 2024-03-19

authors:
  - admin
tags:
  - CoMet
  - punpy
  - comet_maths
  - obsarray

image:
    caption: 'Image credit: [**Unsplash**](https://unsplash.com)'
---

Bellow, we have compiled a list of relevant examples and linked their corresponding jupyther notebooks with detailed comentary. 

## 📦 Punpy as a Standalone Package

### 🗸 General Use Cases

Some general use cases can be found [here](https://colab.research.google.com/github/comet-toolkit/comet_training/blob/main/punpy_standalone_example_overview.ipynb).

### 🗸 Validation Examples

We also have compiled some validation examples [here](https://colab.research.google.com/github/comet-toolkit/comet_training/blob/main/NIST_example.ipynb), where the [punpy]({{< relref "/tools/punpy" >}}) results are compared against the NIST uncertainty machine.

## 📋 Digital Effects Tables

**Digital effects table** is 

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

## ☄️ Comet_maths interpolation 

### 🗸 How to interpolate data with uncertainties?

A jupyter notebook for interpolation with uncertainties can be found [here](https://colab.research.google.com/github/comet-toolkit/comet_training/blob/main/interpolation_example.ipynb).


## 🗂️ Project specific examples

Here, we have compiled a list of external projects and examples that have utilised the CoMet Toolkit. 

### 🗸 **HYPERNETS example** 

- 🛰️ LANDHYPERNET flags and uncertainty propagation (through band integration over S2 SRF) is available [here](https://colab.research.google.com/github/comet-toolkit/comet_training/blob/main/hypernets_surface_reflectance.ipynb).
---
title: Getting started with CoMet
date: 2024-03-21

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com)'

authors:
  - RasmaOrmane

# tags:
#   - CoMet
#   - Metrology
#   - Uncertainties
---

Welcome 👋

In this brief guide we will walk you through the basic steps and prerequisists to get started with CoMet. 

1.💡 Get familiar with the toolkit and its capabilitites. 

All the relevant information regarding the aims and functionality of CoMet Tolkit is outlined in the [**About Section**]({{< relref "/about" >}}). 

But, in a nutshell, CoMet stands for **Community Metrology Toolkit** and it a set of software tools that handle, process, and store measurement data uncertainties.

It accounts for case- and source-specific characteristics of the measurements, and can be used to quantify uncertainties and the uncertainty budget, create digital effects tables, and overall validate measurements. 

At this time, there are the following individual tools:

{{< list_children >}}

  1. comet_maths
  2. obsarray
  3. punpy

but more modules are planned to be developed and included in the future. For more detail, refer to the [**Tools Section**]({{< relref "/#tools" >}}). 

2. 🗃️ Characterise the data/measurements that require the uncertainty propagation 

    - data type
    - contributing uncertainty types
    - uncertainty characteristics
    - expected outcome

3. 🧾 Identify similarities between your specific requirements and the available examples.

  Look through the available examples and documentation, and plan out how the toolkit can be applied to the specific case study (which tools, what order etc). 

4. 🖥️ Install the tools

  - pip install comet_maths
  - pip install punpy*
  - pip install obsarray

  _*Installing punpy will automatically install the other two tools._


5. ✔️ Perform the uncertainty estimation and interpret the results (eror correlation, etc)



6. 📈 Advanced use

  - Managing memory and runtime
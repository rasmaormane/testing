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

<!-- {{ < Tools_children > }} -->

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

  <!-- 
  
  Things to include here from Pieter

  One section I would add at the end is on `advanced use' or `managing memory and runtime' or something like that, which could point to https://punpy.readthedocs.io/en/latest/content/punpy_memory_and_speed.html and other resources for how to deal with more complex/large datasets (which tend to be what people really need in practise). 
  
  in step 4, there is not pip install comet, but there is a pip install punpy, pip install obsarray and pip install comet_maths   (note that the punpy install also installs the other two as dependencies). in step 5, I would say uncertainty propagation rather than estimation . Is uncertainty estimation of input quantities (i.e. compiling the actual values from documentation/literature/expert knowledge) part of step 2? Or should that be a separate step after step 2? We should make sure to link this to the QA4EO `steps to an uncertainty budget' (https://qa4eo.org/docs/3_Process_Document.pdf)
  
  Maybe under step 2, there could be a few subsections (e.g. general/defining measurement function/quantifying uncertainties on input quantities/determining error correlations)?
  
  -->
---
title: "Seismology in the cloud: guidance for the individual researcher"
collection: publications
permalink: /publication/2023-08-seismicloud
date: 2023-08-25
---

## Abstract
The commercial cloud offers on-demand computational resources that could be revolutionary for the seismological community, especially as seismic datasets continue to grow. However, there are few educational examples for cloud use that target individual seismological researchers. Here, we present a reproducible earthquake detection and association workflow that runs on Microsoft Azure. The Python-based workflow runs on continuous time-series data using both template matching and pre-trained machine learning models. We provide tutorials for constructing cloud resources (both storage and computing) through a desktop portal and deploying the code both locally and remotely on the cloud resources. We apply the cloud-based workflow to one year of continuous data from a mid-ocean ridge to demonstrate the construction of two earthquake catalogs, one through template matching and one with a pre-trained machine learning model. We report on scaling of compute times and costs to show that CPU-only processing is generally inexpensive, and can be faster and simpler than using GPUs. Overall, we find that the commercial cloud presents a steep learning curve but is cost-effective. This report is intended as an informative starting point for any researcher considering migrating their own processing to the commercial cloud.

Published in *Seismica*. Read the paper here: [https://seismica.library.mcgill.ca/article/view/979](https://seismica.library.mcgill.ca/article/view/979)

Project repository: [https://github.com/Denolle-Lab/seismicloud](https://github.com/Denolle-Lab/seismicloud)

Krauss, Z., Ni, Y., Henderson, S., & Denolle, M. (2023). Seismology in the cloud: guidance for the individual researcher. Seismica, 2(2).
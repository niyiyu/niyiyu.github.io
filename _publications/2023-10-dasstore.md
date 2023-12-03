---
title: "An Object Storage for Distributed Acoustic Sensing"
collection: publications
permalink: /publication/2023-10-dasstore
date: 2023-10-14
---

## Abstracts
Large-scale processing and dissemination of distributed acoustic sensing (DAS) data are among the greatest computational challenges and opportunities of seismological research today. Current data formats and computing infrastructure are not well-adapted or user-friendly for large-scale processing. We propose an innovative, cloud-native solution for DAS seismology using the MinIO open-source object storage framework. We develop data schema for cloud-optimized data formats — Zarr and TileDB, which we deploy on a local object storage service compatible with the Amazon Web Services (AWS) storage system. We benchmark reading and writing performance for various data schema using canonical use cases in seismology. We test our framework on a local server and AWS. We find much-improved performance in compute time and memory throughout when using TileDB and Zarr compared to the conventional HDF5 data format. We demonstrate the platform with a computing heavy use case in seismology: ambient noise seismology of DAS data. We process one month of data, pairing all 2089 channels within 24 hr using AWS Batch autoscaling.

Published in *Seismological Research Letters*. Read the full paper
[here](https://pubs.geoscienceworld.org/ssa/srl/article/doi/10.1785/0220230172/628716/An-Object-Storage-for-Distributed-Acoustic-Sensing)

Project repository: [https://github.com/niyiyu/dasstore](https://github.com/niyiyu/dasstore)

Ni, Y., Denolle M.A., Fatland, R., Alterman, N., Lipovsky, B.P., Knuth F. (2023). An Object Storage for Distributed Acoustic Sensing. Seismological Research Letters
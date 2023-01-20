---
title: " A DICOM Framework for Machine Learning and Processing Pipelines Against Real-time Radiology Images"
collection: publications
permalink: /publication/2021-08-JDI-Niffler
excerpt: 'This paper presents the architecture of [Niffler](https://github.com/Emory-HITI/Niffler/) DICOM framework.'
date: 2021-08-01
venue: 'Journal of Digital Imaging (JDI)'
paperurl: 'https://doi.org/10.1007/s10278-021-00491-w'
citation: '<b>Kathiravelu, P.</b>, Sharma, P., Sharma, A., Banerjee, I., Trivedi, T., Purkayastha, S., Sinha, P., Cadrin-Chenevert, A., Safdar, N., and Gichoya, J. A DICOM Framework for Machine Learning Pipelines against Real-Time Radiology Images. In Journal of Digital Imaging (JDI). 34(4), 1005-1013. August 2021.'
---

[Download paper here](https://doi.org/10.1007/s10278-021-00491-w)

Real-time execution of machine learning (ML) pipelines on radiology images is difficult due to limited computing resources in clinical environments, whereas running them in research clusters requires efficient data transfer capabilities. We developed Niffler, an open-source Digital Imaging and Communications in Medicine (DICOM) framework that enables ML and processing pipelines in research clusters by efficiently retrieving images from the hospitals’ PACS and extracting the metadata from the images. We deployed Niffler at our institution (Emory Healthcare, the largest healthcare network in the state of Georgia) and retrieved data from 715 scanners spanning 12 sites, up to 350 GB/day continuously in real-time as a DICOM data stream over the past 2 years. We also used Niffler to retrieve images bulk on-demand based on user-provided filters to facilitate several research projects. This paper presents the architecture and three such use cases of Niffler. First, we executed an IVC filter detection and segmentation pipeline on abdominal radiographs in real-time, which was able to classify 989 test images with an accuracy of 96.0%. Second, we applied the Niffler Metadata Extractor to understand the operational efficiency of individual MRI systems based on calculated metrics. We benchmarked the accuracy of the calculated exam time windows by comparing Niffler against the Clinical Data Warehouse (CDW). Niffler accurately identified the scanners’ examination timeframes and idling times, whereas CDW falsely depicted several exam overlaps due to human errors. Third, with metadata extracted from the images by Niffler, we identified scanners with misconfigured time and reconfigured five scanners. Our evaluations highlight how Niffler enables real-time ML and processing pipelines in a research cluster.

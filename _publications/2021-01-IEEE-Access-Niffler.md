---
title: "Understanding Scanner Utilization with Real-Time DICOM Metadata Extraction"
collection: publications
permalink: /publication/2021-01-IEEE-Access-Niffler
excerpt: 'This paper presents an approach to understanding MRI scanner utilization using DICOM metadata using the [Niffler](https://github.com/Emory-HITI/Niffler/) framework.'
date: 2021-01-01
venue: 'IEEE Access'
paperurl: 'https://doi.org/10.1109/ACCESS.2021.3050467'
citation: '<b>Kathiravelu, P.</b>, Sharma, A., and Sharma, P. Understanding Scanner Utilization with Real-Time DICOM Metadata Extraction. In IEEE Access. Vol. 9, pp. 10621 – 10633. January 2021.'
---

[Download paper here](https://doi.org/10.1109/ACCESS.2021.3050467)

Understanding system performance metrics ensures better utilization of the radiology resources with more targeted interventions. The images produced by radiology scanners typically follow the DICOM (Digital Imaging and Communications in Medicine) standard format. The DICOM images consist of textual metadata that can be used to calculate key timing parameters, such as the exact study durations and scanner utilization. However, hospital networks lack the resources and capabilities to extract the metadata from the images quickly and automatically compute the scanner utilization properties. Thus, they resort to using data records from the Radiology Information Systems (RIS). However, data acquired from RIS are prone to human errors, rendering many derived key performance metrics inadequate and inaccurate. Hence, there is motivation to establish a real-time image transfer from the Picture Archiving and Communication Systems (PACS) to receive the DICOM images from the scanners to research clusters to conduct such metadata processing to evaluate scanner utilization metrics efficiently and quickly. This paper analyzes the scanners’ utilization by developing a real-time monitoring framework that retrieves radiology images into a research cluster using the DICOM networking protocol and then extracts and processes the metadata from the images. Our proposed approach facilitates a better understanding of scanner utilization across a vast healthcare network by observing properties such as study duration, the interval between the encounters, and the series count of studies. Benchmarks against using the RIS data indicate that our proposed framework based on real-time PACS data estimates the scanner utilization more accurately. Furthermore, our framework has been running stable and performing its computation for more than two years on our extensive healthcare network in pseudo real-time.

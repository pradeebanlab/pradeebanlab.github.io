---
title: "Software-Defined Workflows for Distributed Interoperable Closed-Loop Neuromodulation Control Systems"
collection: publications
permalink: /publication/2021-09-IEEE-Access-NEXUS
excerpt: 'This paper presents the NEXUS workflow framework for closed-loop executions.'
date: 2021-09-01
venue: 'IEEE Access'
paperurl: 'https://doi.org/10.1109/ACCESS.2021.3113892'
citation: '<b>Kathiravelu, P.</b>, Sarikhani, P., Gu, P., and Mahmoudi, B. Software-Defined Workflows for Distributed Interoperable Closed-Loop Neuromodulation Control Systems. In IEEE Access. 9, 131733-131745. September 2021.'
---

[Download paper here](https://doi.org/10.1109/ACCESS.2021.3113892)

Closed-loop neuromodulation control systems facilitate regulating abnormal physiological processes by recording neurophysiological activities and modifying those activities through feedback loops. Designing such systems requires interoperable service composition, consisting of cycles. Workflow frameworks enable standard modular architectures, offering reproducible automated pipelines. However, those frameworks limit their support to executions represented by directed acyclic graphs (DAGs). DAGs need a pre-defined start and end execution step with no cycles, thus preventing the researchers from using the standard workflow languages as-is for closed-loop workflows and pipelines. In this paper, we present NEXUS , a workflow orchestration framework for distributed analytics systems. NEXUS proposes a Software-Defined Workflows approach, inspired by Software-Defined Networking (SDN), which separates the data flows across the service instances from the control flows. NEXUS enables creating interoperable workflows with closed loops by defining the workflows in a logically centralized approach, from microservices representing each execution step. The centralized NEXUS orchestrator facilitates dynamically composing and managing scientific workflows from the services and existing workflows, with minimal restrictions. NEXUS represents complex workflows as directed hypergraphs (DHGs) rather than DAGs. We illustrate a seamless execution of neuromodulation control systems by supporting loops in a workflow as the use case of NEXUS . Our evaluations highlight the feasibility, flexibility, performance, and scalability of NEXUS in modeling and executing closed-loop workflows.

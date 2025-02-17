---
title: "CONTROL-CORE: A Framework for Simulation and Design of Closed-Loop Peripheral Neuromodulation Control Systems"
collection: publications
permalink: /publication/2022-03-IEEE-Access-CONTROL-CORE
excerpt: 'This paper presents the [CONTROL-CORE](https://github.com/ControlCore-Project/) framework for the design and simulation of neuromodulation control systems.'
date: 2022-03-01
venue: 'IEEE Access'
paperurl: 'https://doi.org/10.1109/ACCESS.2022.3161471'
citation: '<b>Kathiravelu, P.</b>, Arnold, M., Fleischer, J., Yao, Y., Awasthi, S., Goel, A. K., Branen, A., Sarikhani, P., Kumar, G., Kothare, M. V., and Mahmoudi, B. <b>CONTROL-CORE: A Framework for Simulation and Design of Closed-Loop Peripheral Neuromodulation Control Systems.</b> In IEEE Access. 10, 36268-36285. March 2022.'
---

[Download paper here](https://doi.org/10.1109/ACCESS.2022.3161471)

Closed-loop Vagus Nerve Stimulation (VNS) based on physiological feedback signals is a promising approach to regulate organ functions and develop therapeutic devices. Designing closed-loop neurostimulation systems requires simulation environments and computing infrastructures that support i) modeling the physiological responses of organs under neuromodulation, also known as physiological models, and ii) the interaction between the physiological models and the neuromodulation control algorithms. However, existing simulation platforms do not support closed-loop VNS control systems modeling without extensive rewriting of computer code and manual deployment and configuration of programs. The CONTROL-CORE project aims to develop a flexible software platform for designing and implementing closed-loop VNS systems. This paper proposes the software architecture and the elements of the CONTROL-CORE platform that allow the interaction between a controller and a physiological model in feedback. CONTROL-CORE facilitates modular simulation and deployment of closed-loop peripheral neuromodulation control systems, spanning multiple organizations securely and concurrently. CONTROL-CORE allows simulations to run on different operating systems, be developed in various programming languages (such as Matlab, Python, C++, and Verilog), and be run locally, in containers, and in a distributed fashion. The CONTROL-CORE platform allows users to create tools and testbenches to facilitate sophisticated simulation experiments. We tested the CONTROL-CORE platform in the context of closed-loop control of cardiac physiological models, including pulsatile and nonpulsatile rat models. These were tested using various controllers such as Model Predictive Control and Long-Short-Term Memory based controllers. Our wide range of use cases and evaluations show the performance, flexibility, and usability of the CONTROL-CORE platform.

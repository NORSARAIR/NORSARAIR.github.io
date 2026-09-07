---
layout: post
title: "Our team has performed the first sucessful tomography excercise from a balloon"
description: "Marouchka Froment released a preprint describing the first ever inversion of seismic velocities from balloon-borne acoustic data"
output: html_document
date: 2025-05-01 10:00:00 -0400
category: inversion
tags: [infrasound, venusquakes, venus, detectability]
comments: false
---

The AIR team just released a new preprint **Balloon seismology enables subsurface imaging without ground stations** {% cite froment2025inversion %}! In this contribution we present, for the first time ever, seismic velocity models built from acoustic data recorded by a balloon network. Marouchka Froment led this impressive study where we examined a unique set of balloon and seismic recordings after the 2021 Flores sea earthquake to investigate the feasibility of seismology techniques to retrieve seismic velocity from the sky.

<br>

Knowledge of the seismic velocity structure provides essential insights into the composition and evolution of planetary interiors. The Earth’s structure is primarily derived from the inversion of seismic signals recorded by seismometers at the ground. However, on Venus, harsh surface conditions prevent the deployment of ground-based instruments. %Installation and maintenance can also be difficult in the polar and oceanic regions on Earth.  Ballon-borne seismology provides an alternative by recording the low-frequency acoustic wave signature of seismic waves, known as infrasound, from the high atmosphere. Here, we show that seismic velocities and earthquake source location can be jointly inverted from such balloon observations. We demonstrate this method using infrasound signals recorded by a network of four stratospheric balloons following a major earthquake in the Flores Sea, Indonesia. We implement a Bayesian inversion using Markov chain Monte Carlo sampling, allowing us to assess trade-offs inherent to the joint location and velocity estimation. The distributions of source location and seismic velocity structure are consistent with results obtained using ground seismometers in terms of mean and uncertainty. Our ability to estimate source and velocity parameters without ground deployments paves the way for the development of future seismo-acoustic missions to Venus, and provides new opportunities for seismic exploration in Earth remote regions.

<iframe src="/presentations/2025_Froment_Joint_seismic_source_location_and_subsurface_inversion.pdf" width="100%" height="600px">
    This browser does not support PDFs. Please download the PDF to view it: 
    <a href="/presentations/2025_Froment_Joint_seismic_source_location_and_subsurface_inversion.pdf">Download PDF</a>.
</iframe>

{% bibliography --cited %}
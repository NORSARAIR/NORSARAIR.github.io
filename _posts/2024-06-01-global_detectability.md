---
layout: post
title: "Assessing the detectability of venusquakes and volcanic eruptions at a global scale"
description: "How likely are we to detect volcanic and seismic events from a balloon platform?"
output: html_document
date: 2024-06-01 10:00:00 -0400
category: detectability
tags: [detectability, infrasound, venusquakes, venus]
comments: false
---

The AIR project ultimate goal is to build an efficient framework to map seismic infrasound to subsurface velocity structures on Venus. However, our abaility to invert infrasound data will very much depend on our ability to detect these signals in a first place. **Can we really detect seismic infrasound from a balloon platform on Venus?**

<br>

Recent balloon experiments on Earth seem to confirm that large or close-by events can, indeed, be detected {% cite nasholm2024exploring %}. Yet, the amplitude of the signals vary widely depending on the event magnitude and distance to the epicenter. Future balloon mission will have to account for this variability in Signal-to-Noise Ratio (SNR) to ensure the detection of seismic infrasound signals.

<br>

Building on a seismic hazard probabilistic framework, also known as PHSA, **we determined the probability of a balloon to observe a signal above a given SNR**. Our model is fed with seismicity scenarios, i.e., estimates on how many venusquake will occur at each location on the planet, an amplitude prediction model based on numerical simulations, and balloon trajectories. **Our results show that a mission about 3 to 4 months long will likely observe signals with SNR above 1**. More details are provided in the presentation below:

<iframe src="/presentations/AIR_workshop_slides.pdf" width="100%" height="600px">
    This browser does not support PDFs. Please download the PDF to view it: 
    <a href="/presentations/AIR_workshop_slides.pdf">Download PDF</a>.
</iframe>

{% bibliography %}
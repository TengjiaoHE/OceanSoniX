---
title: "3D modal theory for underwater acoustic propagation"
permalink: /teaching/research-num-1
excerpt: "Modeling and vistualizing the acoustic interations with the realistic ocean including intricate topography, 3D sound speed distribution, and ocean dynamics <img src='/images/3DUAP2.png'>"

---

Modeling and vistualizing the acoustic interations with the realistic ocean including intricate topography, 3D sound speed distribution, and ocean dynamics!

Order-reduced adiabatic mode model
======

<img src='/images/3DUAP1.png'>

One could argue that 3D modal coupling effects are a secondary factor in underwater acoustic propagation, where horizontal refraction dominates. This suggests that the adiabatic assumption, which only accounts for horizontal refraction, is beneficial for modeling in most realistic scenarios due to its numerical efficiency compared to the fully coupled mode solution. Our aim is to develop a model order reduction technique to solve HREs. This model highlights that only a few seconds are required for longitudinally invariant environments, providing a naturally wide-angle solution. Additionally, it enables efficient and accurate solutions on a coarse grid for fully 3D environments, which will be useful for developing a fully coupled model and for propagation control in future work.

Interactions with ocean dynamics
======

<img src='/images/3DUAP3.gif' width="1000" height="500">

The reduced-order adiabatic mode model allows for rapid predictions of longitudinally invariant simulations, requiring only a few seconds of computational time. This is particularly useful when analyzing acoustic interactions with ocean dynamics, such as internal waves. For example, the model successfully reproduces the experimental conditions of the [SWARM95](https://pubs.aip.org/asa/jasa/article/117/2/613/541579/Measurement-and-modeling-of-three-dimensional) scenario, capturing observable pressure fluctuations modulated by the internal wave train. The bottom panel illustrates the normalized pressure as a function of time at the position of the receiver in the [SWARM95](https://pubs.aip.org/asa/jasa/article/117/2/613/541579/Measurement-and-modeling-of-three-dimensional) experiment. Achieving such results with the reduced-order adiabatic mode model requires only a few minutes of runtime, demonstrating its computational efficiency.

3D directional source
======

<img src='/images/3DUAP4.gif' width="1000" height="500">

<img src='/images/3DUAP5.gif' width="1000" height="500">

One of the key features of the reduced-order adiabatic mode model is its inherent wide-angle capability, which facilitates a detailed and precise description of the complex characteristics of directional sources, such as surface vessels and underwater vehicles. Furthermore, the solution's expression as a double summation provides the foundation for developing an analytical term for a directional source that can be coupled with the reduced-order adiabatic mode. This aspect is still under development and will be addressed in future work.

